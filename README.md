# cleanmachine

I really hate setting up new machines for developers. There's so much to
do; installing web browsers, text editors, web servers, changing to
a sensible shell, installing a newer version of Ruby, installing Git;
the list goes on and on.

I always end up forgetting something, too, and before you know it you've
lost a morning.

This is an attempt to automate the process, so we can get from fresh
install of OS X to a sensible configuration in a few minutes rather than
a few hours.

It's definitely geared around what we do here at Big Fish, but with
a bit of effort it could be a bit more configurable.

Enjoy!

## Usage

Download the script to the machine and run it; alternatively, you can
run directly from the web:

	curl https://raw.github.com/bigfishdesign/cleanmachine/master/cleanmachine | zsh

It's been tested on OS X 10.9 "Mavericks", but there shouldn't be any
reason why it wouldn't work on earlier versions; the only requirement is
zsh, which is installed by default.
