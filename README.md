# WEC WeeChat External Config loader
_WEC_ is a script for WeeChat which gives you a possibility to use WeeChat with external **irc.conf**.

Author: **V7**
Current version: 1.0

To use external irc.conf file you should cipher it and upload to external path.

To **cipher** original irc.conf file:

  1. Execute script with "-e" or "--encrypt" argument ( $ ./weechat_config -e ).
  2. Type password for encryption.
    * Ciphered irc.conf ( irc.conf.crypted ) will be created in folder where you have executed script.
  3. Upload encrypted irc.conf ( irc.conf.crypted ) to external path.
  
To **use ciphered irc.conf** ( irc.conf.crypted ) file from external resource.

  1. Open script in your favorite text editor to edit external path or other values
  2. Execute script ( $ ./weechat_config )
  3. Type encryption password
  
_If at first you don't succeed; call it version 1.0_
