# Raspberry pi manifest

This repo is made to be used by the Repo Google's tool.

## Install Repo
See the documentation here: https://gerrit.googlesource.com/git-repo

Run this command if you are on ubuntu or debian:
```bash
sudo apt-get install repo
```


## Pull the sources
To check out the repository listed in the default.xml file please run the following steps.

* Create a directory and run this command once:
    ```bash
    repo init https://github.com/lucas-vallery/raspberrypi-zero-manifest
    ```

* Download the sources with this command:
    ```bash
    repo sync
    ```
