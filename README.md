# toggle-xdebug-linux
A very very simple script to toggle XDebug on Linux machines. You may have to adjust it to your specific needs, paths and Linux distribution.

## Installation
1. Place xdebug-toggle script at /usr/local/bin
2. Place xdbug.ini at /var or some other path (then you'll have to adjust the path in /usr/local/bin/xdebug-toggle) and make sure to adjust it to your PHP installation
3. Create a keybinding for /usr/local/bin/xdebug-toggle. You may run it through pkexec or through sudo and create a sudoers config like:
  ```bash
# Allow me to enable or disable xdebug without entering my password.

YOUR_USERNAME ALL = NOPASSWD:/usr/local/bin/xdebug-toggle
```
(adjust YOUR_USERNAME to your username)
4. If you need any help, create an issue and I'll try to help you.
