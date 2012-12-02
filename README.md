My configuration files:
=======================

###Set up from distro linuxmint 14 configuration.
(which is based on ubuntu 12.10 "quantal")

After installation, There's no ~/.bashrc in user's home directory.
But the ~/.profile contains :

	# if running bash
	if [ -n "$BASH_VERSION" ]; then
	    # include .bashrc if it exists
	    if [ -f "$HOME/.bashrc" ]; then
			. "$HOME/.bashrc"
	    fi
	fi

so i created the ~/.bashrc .

il replaced dots by underscores.

The dotfiles concern the following softwares:

* Bash,
* conky,
* Vim,
* Gnome-Pie
* ...
