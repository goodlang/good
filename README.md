# The Good Programming Language

Good is an open source programming language based on Golang that makes it easy to build simple,
reliable, and efficient software.

![Gopher image](doc/gopher/fiveyears.jpg)

For documentation about how to install and use Good,
visit https://golang.org/ or load doc/install-source.html
in your web browser.

Our repository located at https://github.com/goodlang/good.

Good is the work of hundreds of contributors including Golang contributors. We appreciate your help!

To contribute, please read the contribution guidelines:
	https://golang.org/doc/contribute.html

Unlike Golang, we accept pull requests on github.

Unless otherwise noted, the Good source files are distributed
under the BSD-style license found in the LICENSE file.

--

## Binary Distribution Notes

If you have just untarred a binary Good distribution, you need to set
the environment variable $GOROOT to the full path of the go
directory (the one containing this file).  You can omit the
variable if you unpack it into /usr/local/go, or if you rebuild
from sources by running all.bash (see doc/install-source.html).
You should also add the Good binary directory $GOROOT/bin
to your shell's path.

For example, if you extracted the tar file into $HOME/good, you might
put the following in your .profile:

	export GOROOT=$HOME/good
	export PATH=$PATH:$GOROOT/bin

See https://golang.org/doc/install or doc/install.html for more details.
