# MultiAuth
**"AuthmeReloaded with Multipaper support"**

## Description

Add multipaper support for AuthmeReloaded<br>
Prevent username stealing on your server!<br>
Use it to secure your Offline mode server or to increase your Online mode server's protection!

AuthMeReloaded disallows players who aren't authenticated to do actions like placing blocks, moving,<br>
typing commands or using the inventory. It can also kick players with uncommonly long or short player names or kick players from banned countries.

With the Session Login feature you don't have to execute the authentication command every time you connect to the server! 
Each command and every feature can be enabled or disabled from our well structured configuration file.

With multipaper support. You and install this in every multipaper node and sharing database between server using MySQL
or with realtimesync(recommend MySQL over files sync and recommend MariaDB over MySQL)

#### Features:
<ul>
  <li><strong>Multipaper support</strong></li>
  <li><strong>All authme reloaded feature support!</strong></li>
</ul>

#### Configuration
<ul>
  <li><strong>Install this plugin on every node or just put inside masternode/synce-server-file/plugins/</strong></li>
  <li><strong>Recommend using database and set poolsize to 1-2 on every node</strong></li>
  <li><strong>You can use reltime sync in multipaper.yml config if you want</strong></li>
</ul>

#### Commands
[Command list same as Authme](https://github.com/AuthMe/AuthMeReloaded/blob/master/docs/commands.md)
#### Permissions
- authme.player.* - for all user commands
- authme.admin.* - for all admin commands
- [List of all permission nodes](http://github.com/AuthMe/AuthMeReloaded/blob/master/docs/permission_nodes.md)

#### How To
- Migrade from Authme to MultiAuth -> you can copy every files in AuthMe folder to MultiAuth folder and its work fine
- [How to use the converter](https://github.com/AuthMe/AuthMeReloaded/wiki/Converters)
- [How to import database from xAuth](https://dev.bukkit.org/projects/authme-reloaded/pages/how-to-import-database-from-xauth)
- [Website integration](https://github.com/AuthMe/AuthMeReloaded/tree/master/samples/website_integration)
- [How to convert from Rakamak](https://dev.bukkit.org/projects/authme-reloaded/pages/how-to-import-database-from-rakamak)
- Convert between database types (e.g. SQLite to MySQL): /authme converter


## Links and Contacts

 - **Support:**
   - [Discord](https://www.rainbowcreation.net/discord)


## Requirements

##### Running requirements:
>- Java 17
>- Multipaper, Purpur, Paper or Spigot (java 17+)<br>
>- ProtocolLib (optional, required by some features)

## Credits

##### Contributors:
Thank a lot for all AuthMe developer teams.
Team members: <a href="https://github.com/AuthMe/AuthMeReloaded/wiki/Development-team">developers</a>, <a href="https://github.com/AuthMe/AuthMeReloaded/wiki/Translators">translators</a>

Credits for the old version of the plugin: d4rkwarriors, fabe1337, Whoami2 and pomo4ka

Thanks also to: AS1LV3RN1NJA, Hoeze and eprimex

##### GeoIP License:
This product uses data from the GeoLite API created by MaxMind, available at https://www.maxmind.com
