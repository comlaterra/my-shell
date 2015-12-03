# my-shell

Just a way to keep all my shell code organized and shared

## How to use it

### Ubuntu

If you didn't change your terminal source before, your source file should be:

    ~/.bashrc.sh

#### Copy & paste

The easiest way is to copy the commands in every of the files in this repo in that file and just reassign the source of your terminal running:

    source ~/.bashrc.sh

If the system doesn't complain the colors should be applied and you should be able to run the commands included on your .bashrc file.

#### Using the repository

In the case you want to keep the files organized you should 'include' the new files in your .bashrc file. To do that you should add:

    source absolutePathToYourFile/profile_dev
    source absolutePathToYourFile/profile_util
    source ...
    ...

> This option is recommended because it allows you to maintain organized the files, and use the files you can find in the repository (keeping them up to date, or not).
You can use system links or setting up the full path to them.

### OSX

The only difference between Ubuntu and iOS version is the location of the source file. In OSX usually is `/etc/profile`.
