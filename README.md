#Description
A modern IRCd written in Python 3.10. Support for lower versions has officially been dropped.
Massive code overhaul, so there might still be some issues.

#Installation
Install the required packages: pip3 install -r requirements.txt

Edit conf/examples/ircd.example.conf and save it to conf/ircd.conf.
When you are done editting the configuration files, you can start ProvisionIRCd by running python3 ircd.py

#Features
Very modular, all modules can be reloaded on the fly (not always recommended)
IRCv3 features
Full TLS support
Extended channel and server bans
Linking capabilities
Flexible oper permissions system
#Services
To use Anope with ProvisionIRCd, load the unreal4 protocol module in Anope services.conf.

#Issue
If you find a bug or have a feature request, you can submit an issue
or you can contact me on IRC @ irc.provisionweb.org when I'm not afk.
