# nus-info
This repository contains a set of json files with all of the information available from the Nintendo eShop for every language that their server supports.

**All filenames are lowercase.**

The base URL for all files is [https://dantheman827.github.io/nus-info/](https://dantheman827.github.io/nus-info/)

## File descriptions
- [**titles.json**](https://dantheman827.github.io/nus-info/titles.json) - Contains a list of title ids and product codes for every system.
- [**publishers.json**](https://dantheman827.github.io/nus-info/publishers.json) - Contains a list of publishers with localized names for each language if available.
- [**title-names.json**](https://dantheman827.github.io/nus-info/title-names.json) - Contains a list of title ids with localized names for each language if available.
- [**platforms.json**](https://dantheman827.github.io/nus-info/platforms.json) - Contains a list of platform codes, ids, and localized system names.
- **complete-\*\*.json** - Contains a list of all games for every system for the two letter language code. e.g. [**complete-us.json**](https://dantheman827.github.io/nus-info/complete-us.json)
- **complete-\*\*\*-\*\*.json** - Contains a list of all games for the system code for the two letter language code. e.g. [**complete-wup-us.json**](https://dantheman827.github.io/nus-info/complete-wup-us.json)
- **complete-\*\*\*.json** - Contains a list of all games for the system code for all of the supported languages. e.g. [**complete-wup.json**](https://dantheman827.github.io/nus-info/complete-wup.json)
- **complete-\*\*\*-regionprimaries.json** - Contains a list of all games for the system code for the primary languages for each region (US, GB, JP, HK, KR). e.g. [**complete-wup-regionprimaries.json**](https://dantheman827.github.io/nus-info/complete-wup-regionprimaries.json)
- **titles/** - This directory contains json files with all the information for every game for every language listed in [**titles.json**](https://dantheman827.github.io/nus-info/titles.json) for the title ID.
  - The filename format is "(16 character title ID)-(language code).json" e.g. [**000500001010ec00-us.json**](https://dantheman827.github.io/nus-info/titles/000500001010ec00-us.json)
  - You can also omit the language code for a file containing the information for the game with the information for each language that is available. e.g. [**000500001010ec00.json**](https://dantheman827.github.io/nus-info/titles/000500001010ec00.json)

## Known platform codes
- **CTR** - Nintendo 3DS
- **WUP** - Nintendo Wii U

## Projects currently using this data
- [HomebrewTitleIDGenerator - Unused TitleID's & TitleID Check](https://gbatemp.net/threads/homebrewtitleidgenerator-unused-titleids-titleid-check.456064/)

## A note about forking
This repository is updated automatically and is force-pushed so any forks will become orphaned very quickly.

## License
[![Creative Commons License](https://i.creativecommons.org/l/by-nc/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/).

I would also appreciate it if you could send me a message with the name of your project.