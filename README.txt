Python server to ease local developement of packaged apps for Firefox OS.

This script serves the packaged app mini-manifest and does request-time
zipping of the files.

If project directory will be the same as GitHub's repository name it will serve
the file in exactly the same way as github pages.

To use:

Change directory to the root of your packaged app directory and execute this
script. For example:

    $ cd ~/myapp
    $ python ~/serve_packaged_apps.py
