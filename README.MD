# Birthday BOT

Birthday BOT is a Discord bot that allow members on a server to register their birthday for being announced by the bot when it is. It also include other features like define a special role for member birthday etc.

If you want to add this bot to your server, go to [official website](http://birthdaybot.pawz.xyz/).
If you want to learn more about bot features or how the bot work, check the [documentation](http://birthdaybot.pawz.xyz/guide.html).


**Bot source code is closed sources, you will not find any bot source code on this repository.**


### Support

If you ever encouter a bug with the bot, feel free to open an issue. Label it like a bug and be sure to add date and time of survenances, explaining at best how the bug occur and include your Discord server id. Without all of that we will not able to help you well.


### Localization and languages

Current supported languages:

Language | Status | Contributor(s)
--- | --- | ---
**english** | Up to date | [Eryux](https://github.com/Eryux)
**french** | Up to date | [Eryux](https://github.com/Eryux)
**german** | Up to date | [TreeZenDE](https://github.com/TreeZenDE)

You can help us to translate the bot in differents languages. 
For bot translation we use GNU gettext utilities with .po files. All bot translation are availables inside `i18n` folder.

If you want to contribute, please follow this procedure :

- Make a grammar fix :

    * Edit directly file where grammar mistake is (never edit `msgid` line)

- Add new language :

    * Create new folder with same hierarchy of others inside `i18n` folder and name it with two letters language code corresponding to your new language
    * Copy file `locale.pot` inside your new `LC_MESSAGES` folder and rename it to `locale.po`
    * Make your translation in the `locale.po` file, you can also fill po headers (never edit `msgid` line)


If you are familiar with git, make your modification inside a fork and ask for a pull request. 
If you aren't, send us a zip of your modification at mail address contact@pawz.xyz.
