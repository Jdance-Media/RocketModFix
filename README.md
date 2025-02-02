# RocketModFix

The **RocketModFix** is a fork of RocketMod for Unturned maintained by the Unturned plugin devs, this fork don't have plans for any major changes to the RocketMod, only fixes and new features that doesn't break any backward compatibility with API, etc.

## Our plan

- [x] Create Discord Server Community.
- [x] UnityEngine NuGet Package redist.
- [x] Unturned NuGet Package redist.
- [ ] RocketMod NuGet Package containing all required libraries for RockeMod API usage.
- [ ] CI/CD and nightly builds with RocketMod .dlls.
- [ ] RocketMod Fixes:
	- [ ] Fix UnturnedPlayer.SteamProfile (cause so many lags). 
	- [ ] Assembly Resolve fixes (don't spam with not found library or make a option to disable it, load all libraries at rocketmod start instead of searching for them only on OnAssemblyResolve)
	- [ ] Commands fixes:
		- [ ] Fix /vanish.
		- [ ] Fix /god.
		- [ ] Fix /p (not readable at all). 
- [ ] Keep backward compatibility.
- [ ] Collect a Team with a direct access to the repo edit without admins help.

After plan is finished -> Add new plans, keep coding, and don't forget to accept PR or issues.

## Installation

The dedicated server includes the latest version, so an external download is not necessary:
1. Copy the Rocket.Unturned module from the game's Extras directory.
2. Paste it into the game's Modules directory.

## Discord

Feel free to join our [Discord Server](https://discord.gg/z6VM7taWeG).

## Contributing

PR and issues are feel free to be made and approved.

We don't commit right into `master` branch, make a branch from `dev`, and then PR inside `dev`. We keep `master` branch stable as possible, the `dev` branch is for development and its allowed to be unstable.

## Resources

fr34kyn01535 has listed all of the original plugins in a post to the /r/RocketMod subreddit: [List of plugins from the old repository](https://www.reddit.com/r/rocketmod/comments/ek4i7b/)

Following closure of the original forum the recommended sites for developer discussion are the [/r/UnturnedLDM](https://www.reddit.com/r/UnturnedLDM/) subreddit, [SDG Forum](https://forum.smartlydressedgames.com/c/modding/ldm), or the [Steam Discussions](https://steamcommunity.com/app/304930/discussions/17/).

The RocketMod organization on GitHub hosts several related archived projects: [RocketMod (Abandoned)](https://github.com/RocketMod)

## History

On the 20th of December 2019 Sven Mawby "fr34kyn01535" and Enes Sadık Özbek "Trojaner" officially ceased maintenance of Rocket. They kindly released the source code under the MIT license. [Read their full farewell statement here.](https://github.com/RocketMod/Rocket/blob/master/Farewell.md)

Following their resignation SDG forked the repository to continue maintenance in sync with the game.

On the 2nd of June 2020 fr34kyn01535 requested the fork be rebranded to help distance himself from the project.