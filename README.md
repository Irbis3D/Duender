# Duender

Duender is a conversion project that allows you to turn two old Creality Ender-3 printers into a single CoreXY printer.

The original goal was to reuse as many original components as possible and minimize the number of additional parts that need to be purchased.

![Duender](Images/Duender_Image.png)

---

## Project history

If you want to see how the project started and what the early versions looked like, I recommend watching the video series on my YouTube channel.

[![Duender Part 1](https://img.youtube.com/vi/zOplNhr5SfA/maxresdefault.jpg)](https://youtu.be/zOplNhr5SfA)

[![Duender Part 2](https://img.youtube.com/vi/TUS3gvFQUAM/maxresdefault.jpg)](https://youtu.be/TUS3gvFQUAM)

Please note that the current versions already differ significantly from what is shown in those early videos.

---

## Community

A large and active community has formed around Duender. Many experienced and talented users are ready to help newcomers.

Main discussions take place on my Discord server:

**Discord server:**  
https://discord.gg/ae44FHv786

---

## Support the project

If you have the ability and desire to support the project, you can do it in several ways:

- **Patreon** — monthly support: https://patreon.com/Irbis3D  
- **Ko-fi / Buy Me a Coffee** — one-time donations: https://buymeacoffee.com/Irbis3D  
- **YouTube Super Thanks** — under any video: https://youtube.com/@Irbis3D  

Your support helps me create more content, upgrade equipment, and continue experimenting.

---

## Credits

This project uses the following open-source work:

- **Dragon Burner** by chirpy2605  
  https://github.com/chirpy2605/voron/tree/main/V0/Dragon_Burner  

- **Sherpa Mini Extruder** by Annex Engineering  
  https://github.com/Annex-Engineering/Sherpa_Mini-Extruder  

---

## Current status

After many versions and experiments, Duender has partially moved away from its original idea of being the most budget-friendly Ender-3 to CoreXY conversion.

Today it is essentially a modular CoreXY printer project with multiple versions — both budget and advanced.

However, the foundation of almost every Duender is still two old bed-slinger printers.

Duender has existed for more than a year and has multiple official versions and many community modifications. The project continues to evolve.

Although originally created from Creality Ender-3 V1 printers, it has now been confirmed that many other bed-slinger models can be converted to CoreXY in a similar way. In many cases, most parts can be reused without modification.

---

## Available versions

This repository contains files for three base versions of Duender: the wheel version, the MGN9H version, and the MGN12H version.

Unlike older published versions, these versions use M3 pins for all kinematic idlers. Previously, standard screws were used.

Testing has shown that pin-based versions work more reliably and eliminate the common Duender issue (as well as many other CoreXY printers) — belt drift.

---

### MGN9H version

After many tests and experiments, I concluded that the most optimal configuration is the MGN9H version on the XY axes.

In this configuration, I achieved the best Input Shaping results — around real 18K acceleration, assuming everything is assembled properly, rigidly, and without play or binding anywhere.

---

### MGN12H version

The MGN12H version works reliably, but test results show slightly lower acceleration values — around 15K, again assuming high-quality assembly.

---

### Wheel version

The wheel version works, but I recommend considering it as a temporary solution.

It can achieve around 12K stable acceleration, but wheels have obvious disadvantages: they are difficult to align precisely, they wear over time, and they require re-adjustment or replacement.

Unlike the earliest Duender wheel versions, this version requires printing the MGN9H parts and manufacturing carriages with wheel adapters.

The Y and Z axis carriages should ideally be cut from 3 mm aluminum. They can be printed, but this significantly reduces the rigidity of the entire kinematics.

Later, when upgrading to MGN9H, you will not need to reprint all the parts.

This wheel version has not yet been fully tested.

---

## Documentation

Until recently, the only instructions for Duender were YouTube videos.

Thanks to the community — especially a user named **TallothEndill** — a detailed and structured full manual now exists.

The manual includes:

- Step-by-step assembly instructions  
- Complete BOM  
- Required parts list  
- Useful links  
- Practical recommendations  

Huge thanks to TallothEndill and everyone who contributed.

At the moment, the manual is still in progress:

*[(Duender Manual)](https://drive.google.com/file/d/1r_e_1Pna0u54sdXipSJhN7h276Pe2rJI/view)*

Once finalized, it will be permanently integrated into this repository.

---

## Final notes

Duender is fully open source.

You are free to use it, modify it, and build your own derivatives.

If you find the project useful, any kind of support helps. It allows me to spend more time on development, testing, and experiments.

The project will continue to evolve as new ideas appear and as time allows.

Most discussions and development happen on my Discord server:

https://discord.gg/ae44FHv786

---

## License

This project is licensed under the **GNU General Public License v2.0**.  
See the `LICENSE` file for details.

---

## Author

Duender is an open-source project developed by **Sergei Irbenek (Irbis3D)**.

Attribution is not required by the license, but is highly appreciated.
