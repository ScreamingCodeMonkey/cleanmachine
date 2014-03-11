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

## Things it does

1. Installs the XCode command-line tools
2. Changes the default shell to zsh
3. Installs oh-my-zsh
4. Installs homebrew and the following packages:
	1. ack
	2. git
	3. moreutils
5. Installs homebrew casks, and installs the following applications:
	1. Adium (IM client)
	2. Airfoil (for playing music on an Airport Express)
	3. Alfred (launcher app)
	4. Charles (excellent debugging HTTP proxy)
	5. Dropbox (file syncing)
	6. Firefox (web browser)
	7. Google Chrome (web browser)
	8. iTerm2 (much better than Terminal.app)
	9. MAMP Pro (Apache, mySQL, PHP)
	10. Opera (web browser)
	11. 1Password (password storage and syncing)
	12. Sequel Pro (amazing GUI mySQL client)
	13. Skype (chat and IM)
	14. Spotify (music)
	15. Sublime Text (the standard text editor for cowards)
	16. The Unarchiver (decompresses any archive you can throw at it)
	17. VLC (plays any video file you can throw at it)
6. Uses a decent gitconfig file as a starting config
7. Installs RVM and the latest version of Ruby, plus the following Gems:
	1. Compass
	2. Jekyll + Kramdown
	3. Capistrano
8. Installs Pip and HTTPie, a great HTTP debugging tool
9. Takes the huge amount of default crapware (Launchpad? Photo Booth?!)
   out of the dock, and adds Chrome, Sublime, and iTerm

## Usage

Download the script to the machine and run it; alternatively, you can
run directly from the web:

	curl https://raw.github.com/bigfishdesign/cleanmachine/master/cleanmachine | zsh

It's been tested on OS X 10.9 "Mavericks", but there shouldn't be any
reason why it wouldn't work on earlier versions; the only requirement is
zsh, which is installed by default.
