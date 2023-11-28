# CS2 Knife Selector
Lets you chose a knife in game with !knife command.

## Requirments
[CounterStrikeSharp](https://github.com/roflmuffin/CounterStrikeSharp)

## Features
- Saves user knife preferences to a DB (via SQLite)
- Checks if user member of specified steam group, if not user can't use !knife (this feature can be disabled in config)
- Easy to add new knifes after new knife being introduced to game.
- Multiple languages

## Known Issues
- Plugin is not working on Windows servers.

Add me on discord to get the plugin: Discord @ **huesebio**

**Please note that this is a private plugin.**
```json {
{
  "server_prefix": "[Server/Clan Name]",
  "server_language": "en",
  "check_steam_group": true,
  "steam_group_id": "xxxxxxxxxxxxxxxxx",
  "knife_command": "knife",
  "knifelist_command": "knifelist",
}
```
