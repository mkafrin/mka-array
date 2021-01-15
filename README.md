# mka-array
A FiveM wrapper for ArrayForLua (https://github.com/HuotChu/ArrayForLua).

## How to use
In order to use mka-array in your script, you must include Array.lua directly in your __resource.lua or fxmanifest.lua. You can do that by using FiveM's @ syntax for importing resource files:
```lua
client_scripts {
    '@mka-array/Array.lua',
    'your_scripts_client.lua',
}
```
Note: Array.lua should always be listed before your scripts, so that it loads first. Also, this resource works server-side as well.

See https://github.com/HuotChu/ArrayForLua for further documentation on how to use Array.
