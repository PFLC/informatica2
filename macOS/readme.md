# Instalando Flowgorithm en la MAC (versión Catalina 2020)

# PREPARACIÓN DE DEPENDIENCIAS GENERALES "FREETYPE"
```
$ curl -L http://download.savannah.gnu.org/releases/freetype/freetype-2.7.tar.gz -o freetype-2.7.tar.gz
$ tar xf freetype-2.7.tar.gz
$ cd freetype-2.7
$ ./configure --prefix=$TARGET/usr
$ make install
$ cd ..
```

# PREPARACIÓN DE HomeBrew GRATIS (https://brew.sh/index_es)
```
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

$ brew unlink bison
(MENSAJE) Unlinking /usr/local/Cellar/bison/3.4... 0 symlinks removed
$ brew install bison
$ brew link bison --force
(MENSAJE) Linking /usr/local/Cellar/bison/3.4... 9 symlinks created
$ echo 'export PATH="/usr/local/opt/bison/bin:$PATH"' >> ~/.bash_profile
$ export LDFLAGS="-L/usr/local/opt/bison/lib"
$ source ~/.bash_profile
$ bison -V
(MENSAJE)  bison (GNU Bison) 3.x
```
# INSTALACION
I was able to build Wine 64 bit from source on macOS Catalina and successfully run Notepad++ 64 bit on it.

My steps were more or less something like that:

Download Wine 4.20 from https://dl.winehq.org/wine/source/4.x/wine-4.20.tar.xz
Extract it
In terminal go to extracted directory
Run: ./configure --enable-win64
It showed that it couldn't find bison, so I installed it with macports (sudo port install bison).
After I was able to run ./configure --enable-win64 successfully without errors in terminal run: make
It compiled after more than 30 minutes.
I run it with: ./wine start
It opened windows console and here I was able to cd to Notepad++ 64 bit directory (downloaded from https://notepad-plus-plus.org/repository/7.x/7.0/npp.7.bin.x64.zip note that newest version did not work and threw some errors about some dll's)
I typed notepad++ to run exe file
It showed some errors about freetype fonts so I installed them with macports and I had to copy them from /opt/X11/lib to /usr/local/lib before wine detected them
After fixing freetype fonts problem I was able to run notepad++
Also you might want to run: sudo spctl --master-disable to disable gatekeeper if you will see some system alerts about loading app from unknown developer.
Also note that instead of ./wine start you can run ./wine explorer for graphical file manager instead of console



REFERENCIAS: https://mybyways.com/blog/compiling-wine-from-scratch-on-macos-with-retina-mode
