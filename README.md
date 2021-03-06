# Gang Framework
gang-core is a roleplay framework for FiveM. It is developed on top of [EssentialMode](https://essentialmode.com/) (aka ES).

### Links & Read more
- [ES Documentation](https://docs.essentialmode.com/)
- [FiveM Native Reference](https://runtime.fivem.net/doc/reference.html)

### Features
- Accounts (bank / black money). You can add further accounts
- Advanced inventory system (press `F2` ingame)
- Job system
- Loadouts and position synced in database
- The best framework out there for RP servers
- i18n (locale) system
- Plenty of plugins available

### Requirements
This order also applies in the startup order.

- [mysql-async](https://github.com/brouznouf/fivem-mysql-async)
- [essentialmode](https://github.com/kanersps/essentialmode)
- [esplugin_mysql](https://github.com/kanersps/esplugin_mysql)
- [async](https://github.com/ESX-Org/async)

### Manually
- Download https://github.com/ESX-Org/es_extended/releases/latest
- Put it in the `resource/[essential]` directory
- Download https://github.com/ESX-Org/esx_menu_default/releases/latest
- Put it in the `resource/[esx]/[ui]` directory
- Download https://github.com/ESX-Org/esx_menu_dialog/releases/latest
- Put it in the `resource/[esx]/[ui]` directory
- Download https://github.com/ESX-Org/esx_menu_list/releases/latest
- Put it in the `resource/[esx]/[ui]` directory

## Installation
- Import `gangcore.sql` in your database
- Configure your `server.cfg` to look like this

```
start mysql-async
start essentialmode
start esplugin_mysql

start gang-core

start gang_menu_default
start gang_menu_list
start gang_menu_dialog
```


## Credtis
[esx-framework](https://github.com/esx-framework)
