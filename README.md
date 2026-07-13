# distribution-nightly

This repository hosts nightly-related automation and metadata. For anything about the forked distribution itself—bugs, device support, emulators, or code changes—please use **[AveyondFly/distribution_rocknix](https://github.com/AveyondFly/distribution_rocknix)**:

- [Open an issue](https://github.com/AveyondFly/distribution_rocknix/issues)
- [Open a pull request](https://github.com/AveyondFly/distribution_rocknix/pulls)

## About This Fork

This unofficial community fork is branded **Aurknix**—short for **another unofficial ROCKNIX**. It is maintained by **lcdyk** and **AveyondFly** (kk). The project extends [upstream ROCKNIX](https://github.com/ROCKNIX/distribution) with emulators and **devices that ROCKNIX does not officially support** in its main releases.

The work centres on **Rockchip** platforms, especially **RK3326** and **RK3566** handhelds. Kernel updates are **not** merged aggressively on every upstream ROCKNIX bump: the goal is to avoid chasing mainline kernel churn so day-to-day images stay stable on the hardware this fork cares about.

### For manufacturers

If you are a vendor and want **other Rockchip** devices supported in this fork, please contact us about **donation / sponsorship**: [mask_m@qq.com](mailto:mask_m@qq.com).

### Additional Emulators

- **BBK 4980** (gam4980-lr): Electronic dictionary game emulator
- **HBMAME** (hbmame-lr): Homebrew MAME libretro core
- **ONScripter** (onscripter-lr): Visual novel engine
- **PyMO/cpymo**: PyMO AVG game engine in C
- **free-j2me**: J2ME SDL2 frontend standalone
- **OpenBOR-ff**: OpenBOR-ff variant
- **drastic_adv-sa**: Advanced Drastic NDS emulator
- **fbneoplus-lr**: FBNeo Plus libretro core

### Additional Supported Devices

#### RK3326 Devices (image-b)
| Brand | Models |
|-------|--------|
| Anbernic | RG351M, RG351V |
| BatleXP | G350 |
| Clone R36s | Type 2 (with/without amplifier), Type 3, Type 4, Sauce V03/V04 |
| Diium | D007, D-R28S |
| GameConsole | HG36, K36, K36S, R33S, R36S, R36S Plus, R36T, R36TMax, R36Ultra, R36XXProMax, R40XX, R40XX ProMax, R45H, R46H, R50S, RX6H, T16Max, U8, U8-V2, XGB36 |
| Gameforce | CHI |
| GameMT | E6 |
| Generic | EE Clone |
| MagicX | XU10, XU Mini M |
| ODROID-GO | Advance, Advance Black Edition, Super |
| PortableGame | A10Mini, A10Mini-V2 |
| Powkiddy | RGB10, RGB10X, RGB20S |
| XiFan | DC35V, DC40V, Mini40, MyMini, R36Max, R36Max2, R36Pro, XF28, XF35H, XF40H, XF40V |

#### RK3566 Devices (Specific image)
| Brand | Models |
|-------|--------|
| GameMT | E5P, E6P |
| MiniLong | Pocket1 |
| Powkiddy | x35H, x35S |

#### S905L3A Android TV Boxes
| Brand | Models |
|-------|--------|
| CM311 | CM311 |
| E900V | E900V22C |
| M401 | M401A |

#### RK3562 Devices (WIP)
| Brand | Models |
|-------|--------|
| RO520C | LP3X-V10 |

#### RK3326S Devices (5.1 BSP Kernel)
| Brand | Models |
|-------|--------|
| GameKiddy | GKD Pixel 2 |
| GameMT | E6 |

## Contributing

Do **not** open issues or pull requests here for distribution firmware, packages, or device support—those belong in the source project:

| | Link |
|---|------|
| Repository | [github.com/AveyondFly/distribution_rocknix](https://github.com/AveyondFly/distribution_rocknix) |
| Issues | [github.com/AveyondFly/distribution_rocknix/issues](https://github.com/AveyondFly/distribution_rocknix/issues) |
| Pull requests | [github.com/AveyondFly/distribution_rocknix/pulls](https://github.com/AveyondFly/distribution_rocknix/pulls) |

Use **Issues** for bug reports and feature requests, and **Pull requests** for patches and improvements to the build.

## Support

If you would like to support maintainer **lcdyk**, you can use Ko-fi: [https://ko-fi.com/lcdyk](https://ko-fi.com/lcdyk).
