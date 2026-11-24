# US Packs for Nuclear Option

Two standalone BepInEx mod packs that add US jets and helicopters to Nuclear Option. Install either one, or both. They share no files, so they won't conflict.

**Latest release: [v8.6](https://github.com/ILA-Logistics/nuclear-option-vehicle-packs/releases/tag/v8.6)**

> **Beta, untested in game.** Back up your `BepInEx/plugins` and `BepInEx/config` folders before installing.

## What's new in v8.6
- **Added the F-14B Tomcat** to the jets pack.
- **F-35C and F-35E updated:** the weapon bay doors now work.
- Plugin IDs are now `ila.nuclearoption.<unit>`, so delete your old `US_*.cfg` files before installing (see Install).

## Downloads

| File | Size | Contents |
|---|---|---|
| `us-jets-pack-v8.6.zip` | 61 MB | 11 jets, install guide, licences |
| `us-helos-pack-v8.6.zip` | 29.5 MB | 6 helicopters, install guide, licences |
| `SHA256SUMS.txt` | 177 B | Checksums for both zips |

## Aircraft

### Jets pack
| Aircraft | Liveries |
|---|---|
| **F-14B Tomcat** (new in v8.6) | — |
| **F-35C Lightning II** (updated in v8.6: working bay doors) | — |
| **F-35E Lightning II** (updated in v8.6: working bay doors) | — |
| F-15C Eagle | — |
| F-16C Fighting Falcon | USAF Hill Gray · Arizona ANG |
| YF-23 Black Widow II | Prototype · Pale Grey · Production Stealth Charcoal |
| F/A-18E Super Hornet | — |
| F/A-18F Super Hornet | VMFA(AW)-224 Bengals · VMFA(AW)-225 Vikings |
| EA-18G Growler | — |
| A-10C Thunderbolt II | USAF Two-Tone Grey · FlightGear Grey (legacy) |
| E-2D Hawkeye | — |

The F-14B is a new aircraft built on the stock Alkyon, so it shows up in hangars that have the Alkyon (Medium Hangar). It uses the Alkyon's flight model and hitbox.

### Helos pack
| Aircraft | Liveries |
|---|---|
| UH-60M Black Hawk | 7 liveries, ESSS pylons |
| UH-60J Rescue | — |
| MH-60R Seahawk | — |
| CH-46E Sea Knight | — |
| AH-64D Apache Longbow | US Army |
| AH-1Z Viper | USMC Light Grey · Sharkmouth Squadron |

## Install
1. Close the game. You need **BepInEx 5** installed.
2. If you had an older version, delete the old `US_*.dll` files from `Nuclear Option/BepInEx/plugins/` and the old `US_*.cfg` files from `Nuclear Option/BepInEx/config/`.
3. Unzip the pack and copy every `.dll` from its `plugins/` folder into `Nuclear Option/BepInEx/plugins/`.
4. Start the game. Everyone in a multiplayer session needs the same DLLs.

Unit details, liveries and settings are in `README.md` inside each zip.

## Changelog
- **v8.6:** Added the F-14B Tomcat. F-35C and F-35E weapon bay doors fixed. Plugin IDs cleaned up. Jets and helos each ship as one zip.
- **v8.5:** Liveries in the in-game picker, UH-60M ESSS pylons, UH-60J Rescue, and retextures for the AH-64D, AH-1Z, F-16C, YF-23, F/A-18F and A-10C.

---

## Credits
Models are open-licensed community models. Each zip includes the licence texts in `licenses/<unit>/`. GPL sources are at the linked repositories.
- **F-14B:** FlightGear Grumman F-14 Tomcat by Alexis Bory (original model), Richard Harrison (primary author), Enrique Laso, Nikolai V. Chr. and contributors ([Zaretto/f-14b](https://github.com/Zaretto/f-14b)), GPL v3
- **F-35C / F-35E:** FlightGear F-35A Lightning II by VooDoo and the FGUK team, Petar Jedvaj, Detlef Faber, F-GTUX, Paolo Amoroso ([PaoloAmoroso/F-35A](https://github.com/PaoloAmoroso/F-35A)), GPL-2.0
- **F-15C:** Zaretto (Richard Harrison), FlightGear F-15 ([Zaretto/F-15](https://github.com/Zaretto/F-15)), GPL-2.0
- **F-16C:** NikolaiVChr / OPRF, FlightGear F-16 ([NikolaiVChr/f16](https://github.com/NikolaiVChr/f16)), GPL-2.0
- **YF-23:** Lee Elliott, FlightGear YF-23 ([FGMEMBERS/YF-23](https://github.com/FGMEMBERS/YF-23)), GPL-2.0
- **F/A-18E, F/A-18F, EA-18G:** FGUK F/A-18C and F/A-18D Hornet for FlightGear, Mathias Froehlich, StuartC / FGUK ([FGMEMBERS/F-18C](https://github.com/FGMEMBERS/F-18C), [F-18D](https://github.com/FGMEMBERS/F-18D)), GPL-2.0
- **A-10C:** Lee Elliott, Alexis Bory and contributors, FlightGear A-10 ([l0k1/A-10](https://github.com/l0k1/A-10)), GPL-2.0
- **E-2D:** Alexis Bory, FlightGear E-2C Hawkeye (based on Emmanuel Baranger's C-2A), GPL-2.0
- **AH-64D:** FGUK AH-64/WAH-64 Apache for FlightGear ([FGMEMBERS/AH-64_Apache](https://github.com/FGMEMBERS/AH-64_Apache)), GPL-2.0
- **UH-60M:** FGUK Sikorsky UH-60 Black Hawk for FlightGear, GPL-2.0
- **UH-60J, MH-60R:** Uchi craft room / Hitoshi Uchida, FlightGear UH-60J and SH-60J ([Uchi-craft-room](https://github.com/Uchi-craft-room)), GPL-2.0+
- **AH-1Z:** AH-1W SuperCobra, Savage X3D Examples Archive (Naval Postgraduate School / Web3D Consortium), Web3D open-source licence
- **CH-46E:** "CH46e" by William Clapham (Delta3D), free use and distribution
- **Lettering:** Barlow (SIL OFL 1.1)

*Fan mod. Not affiliated with the US military, any unit shown, Shockfront Studios, or the Nuclear Option developers.*
