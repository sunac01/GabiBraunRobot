<p align="center">
  <img src="https://telegra.ph/file/0ed48df18f4175d61b5d8.jpg">
</p>

## Gabi Braun Robot 

### Telegram Group
<p align="left">
<a href="https://t.me/GabiHelpSupport" alt="Telegram!"> <img src="https://aleen42.github.io/badges/src/telegram.svg" /> </a>

### Bot And Channel 
* Bot Link:  <a href="http://t.me/Gabi_Braun_Robot" alt="GabiBraun"> <img src="https://img.shields.io/badge/%F0%9F%A4%96%20-GabiBraun-blue" /> </a>
* Log Channel: <a  href="https://t.me/Gabi_Support_Log" alt="Bot Logs"> <img  src="https://img.shields.io/badge/%F0%9F%92%A1-gabibraun%20Log%20Channel-9cf" /> </a>

### Creating your own modules.

Creating a module has been simplified as much as possible - but do not hesitate to suggest further simplification.

All that is needed is that your .py file is in the modules folder.

To add commands, make sure to import the dispatcher via

from GabiBraun  import dispatcher.

You can then add commands using the usual

dispatcher.add_handler().

Assigning the help variable to a string describing this modules' available
commands will allow the bot to load it and add the documentation for
your module to the /help command. Setting the mod_name variable will also allow you to use a nicer, user-friendly name for a module.

The migrate() function is used for migrating chats - when a chat is upgraded to a supergroup, the ID changes, so 
it is necessary to migrate it in the DB.

The stats() function is for retrieving module statistics, eg number of users, number of chats. This is accessed 
through the /stats command, which is only available to the bot owner.

## Starting the bot.

Once you've set up your database and your configuration is complete, simply run the bat file(if on windows) or run (Linux):

python3 -m GabiBraunRobot

You can use nssm to install the bot as service on windows and set it to restart on /gitpull 
Make sure to edit the start and restart bats to your needs. 
Note: the restart bat requires that User account control be disabled.

For queries or any issues regarding the bot please open an issue ticket or visit us at <p align="left">
<a href="https://t.me/GabiHelpSupport" alt="Telegram!"> <img src="https://aleen42.github.io/badges/src/telegram.svg" /> </a>

## How to setup on Heroku 
For starters click on this button 

<p align="center"><a href="https://heroku.com/deploy?template=https://github.com/sunac01/GabiBraunRobot"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-black?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>


## Our Telegram Channel and Group

* [Support](https://telegram.dog/GabiHelpSupport)
* [Discussion](https://telegram.dog/helpcenterbot1)
* [Second Group](https://telegram.dog/Ast_Official_Channel)

## Credits,  
*   [The Ghost Hunter](https://telegram.dog/The_Ghost_Hunter)

## Bot Owner
*  [Falco Grice](https://telegram.dog/Official_Flying_Titan)
