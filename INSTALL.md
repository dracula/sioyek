### [Sioyek](https://sioyek.info)

#### Install using Git

1. Compile latest development version of sioyek
2. Clone this repo

	```
	git clone https://github.com/dracula/sioyek
	```
3. Copy theme file to sioyek config directory

	```
	cp ./dracula.config ~/.config/sioyek
	```
4. Source the theme file

	```
	echo "source dracula.config" >> ~/.config/sioyek/prefs_user.config
	```
5. Make sure there is a `toggle_custom_color` option in `startup_commands` of `~/.config/sioyek/prefs_user.config`.
	
	If you don't have  `startup_commands`, add it:
	
	```
	echo "startup_commands toggle_custom_color" >> ~/.config/sioyek/prefs_user.config
	```

