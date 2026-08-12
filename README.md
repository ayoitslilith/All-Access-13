## Bubberstation (TG Downstream)

[![CI Suite](https://github.com/Bubberstation/Bubberstation/actions/workflows/ci_suite.yml/badge.svg)](https://github.com/Bubberstation/Bubberstation/actions/workflows/ci_suite.yml)

[![resentment](.github/images/badges/built-with-resentment.svg)](.github/images/comics/131-bug-free.png) [![technical debt](.github/images/badges/contains-technical-debt.svg)](.github/images/comics/106-tech-debt-modified.png) [![forinfinityandbyond](.github/images/badges/made-in-byond.gif)](https://www.reddit.com/r/SS13/comments/5oplxp/what_is_the_main_problem_with_byond_as_an_engine/dclbu1a)

| Website                 | Link                                                              |
| ----------------------- | ----------------------------------------------------------------- |
| Git / GitHub cheatsheet | https://www.notion.so/Git-GitHub-61bc81766b2e4c7d9a346db3078ce833 |
| Website                 | Todo                                                              |
| Wiki                    | Todo                                                              |
| Codedocs                | Todo                                                              |
| Socials                 | Todo                                                              |

Aaaaaand now it's All Access. Yay!

**Please note that this repository contains sexually explicit content and horrible, horrible acts of violence. Viewer discretion is advised.**

Space Station 13 is a paranoia-laden round-based roleplaying game set against the backdrop of a nonsensical, metal death trap masquerading as a space station, with charming spritework designed to represent the sci-fi setting and its dangerous undertones. Have fun, and survive!

## Contribution Rules and Guidelines

**1. do whateverrrrrr if i like it i'll add it**
You already know how to contact me if you're here. Just hmu and we'll talk.

## Modularization and codedocs note

### Modularization

New modularized code should be put in the modular_zubbers folder. This is to keep our unique code seperate, easier to maintain, and helps future contributors find things. It is expected that you call into the override functions to reduce the amount of code we overwrite and edit from our upstream source.

### Spriting

For the sake of consistency, we typically ask that sprites be drawn such that it aligns with the look and feel of other sprites. We understand that some items may not be perfect and that's okay, but sprites ideally should do their best to match others for the sake of consistency.

Also consider that when doing clothing sprites, teshari themselves use different sprites (requiring a bit more effort) as well as digitigrades legs. Otherwise, these sprites will either be entirely broken or look heavily off if not done properly.

### Configuration

Most of our [config files](https://github.com/Bubberstation/config/tree/master) are open source, and therefore can be edited (though you should have good reason to do so)

## Important note - TEST YOUR PULL REQUESTS

You are responsible for the testing of your content. You should not mark a pull request ready for review until you have actually tested it. If you require a separate client for testing, you can use a guest account by logging out of BYOND and connecting to your test server.

Testing your changes is super critical for multiple reasons.

1. It makes sure your features/changes actually work.
2. It helps reduce the chance that something else has broken
3. Provides a first peek at the changes before its actually in the game

This is why we require notes on testing, and in most instances, videos or screenshots to help support that.

Test notes can be a step-by-step set of instructions. But for visual content, we require either screenshots of how something renders, a video of the content being interacted with/used, or a video with sound to show audio changes.

Ideally, test notes are you providing people with confidence that your change works and has not interfered with other bits of code.

## DOWNLOADING

[Downloading](.github/guides/DOWNLOADING.md)

[Running on the server](.github/guides/RUNNING_A_SERVER.md)

[Maps and Away Missions](.github/guides/MAPS_AND_AWAY_MISSIONS.md)
[Maps and Away Missions](.github/guides/MAPS_AND_AWAY_MISSIONS.md)

## Compilation

Find `BUILD.bat` here in the root folder of tgstation, and double click it to initiate the build. It consists of multiple steps and might take around 1-5 minutes to compile.

**The long way**. Find `bin/build.cmd` in this folder, and double click it to initiate the build. It consists of multiple steps and might take around 1-5 minutes to compile. If it closes, it means it has finished its job. You can then [setup the server](.github/guides/RUNNING_A_SERVER.md) normally by opening `tgstation.dmb` in DreamDaemon.

**Building tgstation in DreamMaker directly is deprecated and might produce errors**, such as `'tgui.bundle.js': cannot find file`.

**[How to compile in VSCode and other build options](tools/build/README.md).**

## Getting started

<!-- For contribution guidelines refer to the [Guides for Contributors](.github/CONTRIBUTING.md). -->

For getting started (dev env, compilation) see the HackMD document [here](https://hackmd.io/@tgstation/HJ8OdjNBc#tgstation-Development-Guide).

For overall design documentation see [HackMD](https://hackmd.io/@tgstation).

## Code Reviews

Please include a changelog if you're extra nice :^)

## LICENSE

All code after [commit 333c566b88108de218d882840e61928a9b759d8f on 2014/12/31 at 4:38 PM PST](https://github.com/tgstation/tgstation/commit/333c566b88108de218d882840e61928a9b759d8f) is licensed under [GNU AGPL v3](https://www.gnu.org/licenses/agpl-3.0.html).

All code before [commit 333c566b88108de218d882840e61928a9b759d8f on 2014/12/31 at 4:38 PM PST](https://github.com/tgstation/tgstation/commit/333c566b88108de218d882840e61928a9b759d8f) is licensed under [GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.html).
(Including tools unless their readme specifies otherwise.)

See LICENSE and GPLv3.txt for more details.

The TGS DMAPI is licensed as a subproject under the MIT license.
The TGS DMAPI is licensed as a subproject under the MIT license.

See the footer of [code/\_\_DEFINES/tgs.dm](./code/__DEFINES/tgs.dm) and [code/modules/tgs/LICENSE](./code/modules/tgs/LICENSE) for the MIT license.

All assets including icons and sound are under a [Creative Commons 3.0 BY-SA license](https://creativecommons.org/licenses/by-sa/3.0/) unless otherwise indicated.
