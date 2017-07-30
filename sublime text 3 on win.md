sublime text 3 on win10:

1. the essential plug-ins to make the st a better text editor to use
	+ basic
		- Package Control
		It is easy to install it with `Ctrl+shift+p`
	+ Markdown
		- Markdown extend + Monokai extended
			* description: this is  a highlight color scheme for markdown writing
			* setting: Preference --> ColorScheme --> MonokaiExtended
		- Markdown preview
	    		* description: this is to preview your markdown file as html
	    		* setting: add a short cut if you want
	    			example:`{ "keys": ["alt+m"], "command": "markdown_preview", "args": {"target": "browser", "parser":"markdown"} }`
	+ Python
	[blog][]---really a nice blog.
		-  plugin Sublime Repel
			`Solve the problem that we can not input with python`
			*  python3
				`make sure the environment path is okay`
			* shortcut
				Preferences---->Keybindings---->create your own shortcut
				`You name your keys and copy the command from the Default.sublime-commands file`
3. build c/c++ files in sublime text3
	+ download MinGW and set the environmentual path right `MinGW/bin`
	+ build your own build system for c and c++
		- Tools--->Build System--->New Build System
		-  [more detail][]


4. Backup and  regain the configuration with git
`here you just back up the configuration but not the packages itself, so you have to install them again from scratch `
[Backup guide blog][]




[blog]:http://www.cnblogs.com/unflynaomi/p/5704293.html
[Backup guide blog]:http://zuyunfei.com/2015/05/21/backup-sublime-settings/
[more detail]:http://blog.163.com/liping_xy/blog/static/212537308201511271123917/
