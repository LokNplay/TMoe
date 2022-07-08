# TMoe

[![license](https://img.shields.io/github/license/cinit/TMoe.svg)](https://www.gnu.org/licenses/gpl-3.0.html)
[![GitHub release](https://img.shields.io/github/release/cinit/TMoe.svg)](https://github.com/cinit/TMoe/releases/latest)

TMoe is an open source Xposed module compatible with several third party open source Telegram clients

## Instructions

After activating this module, click "TMoe Settings" in the settings of the Telegram client to switch the corresponding functions.

## This project is for learning, please do not use for illegal purposes

- This project is guaranteed to be permanently open source. You are welcome to submit Issues or Pull Requests, but please do not submit functions for illegal purposes.
- If a feature is heavily used for illegal purposes, the feature will be removed.
- Developers may **stop updating** or **delete projects** at any time

## Features

1. Debug mode
2. Remove the restriction on copying and saving messages (and many more)

## Supported clients

- For a complete list, please refer to [HookEntry.java](app/src/main/java/cc/ioctl/tmoe/startup/HookEntry.java)
  and [module scope](app/src/main/res/values/arrays.xml)

- If your client meets the compatibility requirements but is not in the list, please add it in [HookEntry.java](app/src/main/java/cc/ioctl/tmoe/startup/HookEntry.java)
  and [module scope](app/src/main/res/values/arrays.xml) add the corresponding value

## License

- [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.html)

````
Copyright (C) 2021-2022 xenonhydride@gmail.com

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as
published by the Free Software Foundation, either version 3 of the
License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>.
````
