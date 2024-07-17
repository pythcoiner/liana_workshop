# Build Liana from sources on Windows 10

## Rust toolchain

If  you visit [rust website](https://www.rust-lang.org/tools/install) you will find
the method for install rust on your system:

![rust](./assets/0.png)

Download rust installer for your platform, its likely 64-bits one.

![rust](./assets/1.png)

Execute it and choose the first option.

![rust](./assets/2.png)

You'll be asked to install visual studio installer, do it and follow its install process.

![rust](./assets/3.png)

At this step, close visual studio.

![rust](./assets/4.png)

Choose the first option.

![rust](./assets/5.png)

At this step in enter to close terminal.

## Install Git

![rust](./assets/6.png)

Go to [git website](https://git-scm.con/download) in order to download its installer.

![rust](./assets/7.png)

Then start installer.

![rust](./assets/8.png)

and follow the installer step w/ defaults options.

![rust](./assets/9.png)

right click + open git gui

![rust](./assets/10.png)

select "Clone Existing Repository"

![rust](./assets/11.png)

Enter my liana repository address (https://github.com/pythcoiner/liana.git) and your target directory
Note: this is not the 'official' [Liana](https://github.com/wizardsardine/liana) repository but my 
own 'fork' tha i've modified for workshop purpose.

then click `Clone`.

![rust](./assets/12.png)

After download has finnish close Git Gui

open liana/gui folder

![rust](./assets/13.png)

right click + open Git Bash

![rust](./assets/14.png)

Type `git fetch origin liana_demo && git checkout liana_demo && cargo build --release` and hit enter.

![rust](./assets/15.png)

If you get this at the end of the build you are good, and can close the terminal!

![rust](./assets/16.png)

Then go to target/release directory and execute liana-gui

![rust](./assets/17.png)


