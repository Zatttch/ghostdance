# ghostdance

Ghost Dance theme for HubPress

it also can be transformed in a Ghost theme with little or no efforts.

## Due Credits

This is a variation of **Purple Slimer** Ghost template which is itself a variation of **GhostScroll** template for Ghost.

[GhostScroll](https://github.com/zebheone/GhostScroll)

[Purple Slimer](https://github.com/zebheone/GhostScroll)

## Installation

1. HubPress runs on a GitHub repo, right? After you have your copy of HubPress up and running at GitHub, clone your fork of it to your local computer.
2. Enter the `themes/` directory which exists on the HubPress repository root, and
3. Clone the `ghostdance` template in there, so that the root of the `ghostdance` clone is inside themes (*ie*., `themes/ghostdance`):
    `git clone https://github.com/iacchus/ghostdance.git`
4. Enter `ghostdance` subdirectory and remove the hidden `.git` repository. This makes it easier to commit changes to hubpress after editing the theme's template.

```sh
cd ghostdance/
rm -rf .git/
```

5. Go back to the root your fork of your HubPress repository, commit the changes and push:
```sh
git add .
git commit -a -m 'ghostdance Theme added to my HupPress repo'
git pull --rebase
git push
```
6. Go to admin panel of your blog *username*.github.io**/hubpress**, go to `Settings` -> `Site` and set ghostdance as your template.

And you are all ready. :)

## License

This is released under MIT License.

See [LICENSE](https://github.com/iacchus/ghostdance/blob/master/LICENSE)
