# Jerrin Varghese — SimBench (CFD + FEA simulation)

Website: **https://jerrin-v.github.io/simbench/**

SimBench is a browser app for CFD and FEA simulation of 3D models. It runs on the computer's own processor cores.

## Latest updates

The last 3 updates pushed here, newest first.

<!-- latest-updates:start -->
| Updated | Change | Version | Commit |
| --- | --- | --- | --- |
| Wed 18 Nov 2026, 10:37:39 PM UAE<br><sub>Wed 18 Nov 2026, 6:37:39 PM UTC</sub> | view cube, particle lines, own dropdowns, closed accordions, phone fixes (Frost, Full view, icons, messages) | v1.0.80 | [`9b00e4a`](https://github.com/jerrin-v/simbench/commit/9b00e4a30289cf22cd84c47f6569d222a41d9b18) |
| Wed 18 Nov 2026, 11:11:47 AM UAE<br><sub>Wed 18 Nov 2026, 7:11:47 AM UTC</sub> | the name pill's arrow sits 12 px from its right edge | v1.0.71 | [`ea6113f`](https://github.com/jerrin-v/simbench/commit/ea6113fb3bce02ac19485004d3bdd7e1dad79deb) |
| Wed 18 Nov 2026, 11:01:00 AM UAE<br><sub>Wed 18 Nov 2026, 7:01:00 AM UTC</sub> | tooltips after 2 s with a Settings switch, full-details PDF report, equal result buttons, glass popups, notification cards | v1.0.70 | [`6f495d4`](https://github.com/jerrin-v/simbench/commit/6f495d46b682e41127f4f3caa4068a11f61fa699) |
<!-- latest-updates:end -->

## Open it

1. **Open the website** above in Chrome, Edge, Firefox or Safari.
2. **Pick a simulation**, add a model, set the parameters and run. The examples on the first screen fill everything in.
3. **Save your work** as a `.sb` file from the File menu (click the logo).

## Update it

1. **Ask Claude for the change.** The version goes up by 1 in the last place (v1.0.1 → v1.0.2 → …).
2. **Say "Push".** Nothing is pushed here before that.
3. The update shows in the table above, and on the website a minute or two later.

## What's in this repo

- `backup/` — the app, sealed with [age](https://age-encryption.org), and the version it holds.
- `keys/backup-recipient.txt` — the public key the backup is sealed with.
- `tools/` — seals a new version and keeps the table above up to date.
- `.github/workflows/` — publish the website and update the table after every push.

**If the website is ever gone, see [RESTORE.md](RESTORE.md).**

Note: the results are for comparing designs, not certified values.

---

© 2026 Jerrin Varghese. All rights reserved — see [LICENSE](LICENSE).
