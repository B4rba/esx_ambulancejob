# esx_ambulancejob

## Original

- [esx_ambulancejob](https://github.com/ESX-Org/esx_ambulancejob)

## Added
* Mission
* Death Screen

## Requirements

* Auto mode
   - [esx_skin](https://github.com/ESX-Org/esx_skin)

* Player management (boss actions **There is no way to earn money for now**)
   - [esx_society](https://github.com/ESX-Org/esx_society)

## Installation
- Import `esx_ambulancejob.sql` in your database
- If you want player management you have to set `Config.EnablePlayerManagement` to `true` in `config.lua`
- Add this in your `server.cfg`:

```
start esx_ambulancejob
```

