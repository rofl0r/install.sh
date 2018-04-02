simple public domain install script for use in Makefiles across platform,
written in portable POSIX sh.

why ? because BSD and Mac's install program doesn't support the usage of

    install -Dm 755 myprog /bin/myprog

additionally, this version is atomic and supports symlinks.
