# A black OS X Leopard Terminal theme that is actually readable

This Terminal theme was created by Todd Werth (http://blog.infinitered.com/).<br/>
Read his original blog post [here](http://blog.infinitered.com/entries/show/6).

This repository contains all the necessary files to get it working under Mac OS 10.6+; conveniently in one place.

# Lion

The OS X Lion Terminal.app has support for ANSI color without SIMBL/TerminalColours.bundle. Simply install the
IR_Black terminal file (inside the 10.7 folder) and set it as default.

# Snow Leopard

## Installation 

1. Install the SIMBL plugin package for Snow Leopard by double clicking it or running the following:

		sudo install -pkg SIMBL-0.9.7.pkg -target "/"

2. Copy the TerminalColours.bundle:
	
		# For all users
		
		mkdir -p /Library/Application\ Support/SIMBL/Plugins
		cp -r TerminalColours.bundle /Library/Application\ Support/SIMBL/Plugins

		# For just you
		
		mkdir -p ~/Library/Application\ Support/SIMBL/Plugins
		cp -r TerminalColours.bundle ~/Library/Application\ Support/SIMBL/Plugins
		
3. Double click the **IR\_Black.terminal** file. Go to Terminal -> Preferences -> Setting and set IR\_Black as the default theme.

4. That's it. Optionally you could add [Todd's bash scripts](http://github.com/twerth/dotfiles).

## Misc

If you're experiencing a font difference when connecting an external monitor try [OS X hints - 10.6: Re-enable LCD font smoothing for some monitors](http://hints.macworld.com/article.php?story=20090828224632809&query=mar)

> [...] OS X incorrectly detects many third party LCD monitors as CRTs, and consequently, disables LCD font smoothing.

## Credits

**SIMBL**

	Mike Solomon - http://www.culater.net/software/SIMBL/SIMBL.php

**TerminalColours.bundle**

	Ciarán Walsh - http://ciaranwal.sh/2007/11/01/customising-colours-in-leopard-terminal
	Evan Phoenix - http://github.com/evanphx/terminalcolours/

**IR_Black.terminal**
**Bash scripts**

	Todd Werth   - http://blog.infinitered.com/entries/show/6
	@fyrabanks   - http://twitter.com/#!/fyrabanks

And everyone else!