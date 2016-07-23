# ghostdance

Ghost Dance theme for [HubPress](https://github.com/HubPress/hubpress.io) blogging engine.

It also can be transformed in a [Ghost](https://github.com/TryGhost/Ghost) [blogging engine] theme with little or no efforts.

## Due Credits

This is a variation of **Purple Slimer** Ghost template which is itself a variation of **GhostScroll** template also for Ghost.

[GhostScroll](https://github.com/grmmph/GhostScroll)

[Purple Slimer](https://github.com/zebheone/GhostScroll)


## Installation

1. HubPress runs on a GitHub repo, right? After you have your copy of HubPress up and running at GitHub, clone your fork of it to your local computer.
2. Enter the `themes/` directory which exists on the HubPress repository root, and
3. Clone the `ghostdance` template in there, so that the root of the `ghostdance` clone is inside themes (*ie*., `themes/ghostdance`):

    ```sh
    cd themes/
    git clone https://github.com/iacchus/ghostdance.git
    ```
4. Enter `ghostdance` subdirectory and remove the hidden `.git` repository. This makes it easier to commit changes to hubpress after editing the theme's template. Because you will be inside your HubPress repository and not inside a `ghostdance` repository.

    ```sh
    cd ghostdance/
    rm -rf .git/
    ```
5. Go back to the root your fork of your HubPress repository, commit the changes and push:

    ```sh
    git add . # note that this command has a dot at the end meaning 'track everything in current directory'
    git commit -a -m 'ghostdance Theme added to my HupPress repo'
    git pull --rebase
    git push
    ```
6. Go to the admin panel of your blog at https://*username*.github.io**/hubpress**, go to `Settings` -> `Site` and set ghostdance as your template; save the changes.

And you are all ready. :)

### Alternative Install

Alternatively you can [download the zip tarball](https://github.com/iacchus/ghostdance/archive/master.zip) from GitHub and unzip it inside themes, (following from point 3. above)

## How to Change the Cover Image of your Blog

1. Put the image you want to set as cover inside your **HubPress** `images/` directory, which exists on the root directory of it. 
2. Commit the changes and push to your GitHub repo

    ```sh
    cp ~/cover_filename.png images/
    git add . # note that this command has a dot at the end meaning 'track everything in current directory'
    git commit -a -m 'Added cover_filename.png added to my HupPress repo'
    git pull --rebase
    git push
    ```
3. Go to the admin panel of your blog at https://*username*.github.io**/hubpress**, go to `Settings` -> `Site` and set `Cover Image` as in the example to `images/cover_filename.png` as your template; save the changes. 

## How to Edit this Theme

The HupPress themes are developed alike [Ghost](https://github.com/TryGhost/Ghost) themes, and Ghost Themes documentation should be enough to get you started. Also it uses Handlebars markup to render templates.

[Ghost Themes documentation](http://themes.ghost.org/) is here.

Why don't you also give a look at [Handlebars website](http://handlebarsjs.com/)...

## Philosophy

When I made this I had in mind an clear and simple template for showing articles, with very little or none egotrip.

## License

This is released under MIT License.

See [LICENSE](https://github.com/iacchus/ghostdance/blob/master/LICENSE).
