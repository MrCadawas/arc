# arc
Educational libaray for students learning Java for the first time

This library provides 3 classes:
1. "Console" window that will allow keyboard inputs, mouse input, and screen output
2. Text File Input class
3. Text File Output class

The Javadocs for this libaray can be found here:
http://staugustinechs.ca/arc

macOS users.  The currentKey/currentChar methods might cause your inputs in the Console to become unresponsive.  This is due to the macOS "feature" that pops up an accent menu for certain keys when you hold them down.   Unfortunately, there is no way to deal with this "feature" using Java code so if you want realtime input, disable the accent menu using this terminal command:

defaults write -g ApplePressAndHoldEnabled -bool false
