# Jerrin Varghese — X-Sim RV (CFD + FEA simulation)

Website: **https://jerrin-v.github.io/xsim-rv/**

X-Sim RV is a browser app for CFD and FEA simulation of 3D models. It runs on the computer's own processor cores.

## Latest updates

The last 3 updates pushed here, newest first.

<!-- latest-updates:start -->
| Updated | Change | Version | Commit |
| --- | --- | --- | --- |
| Sat 21 Nov 2026, 11:23:05 AM UAE<br><sub>Sat 21 Nov 2026, 7:23:05 AM UTC</sub> | wall model on the model's faces, large deflection, yielding, smooth surfaces, trust labels and mesh check, a fuller PDF report, automatic server route for heavy runs, tests on GitHub | v1.0.97 | [`54035d7`](https://github.com/jerrin-v/xsim-rv/commit/54035d7230b029d8df99f581794b79ae70f71c51) |
| Sat 21 Nov 2026, 12:11:36 AM UAE<br><sub>Fri 20 Nov 2026, 8:11:36 PM UTC</sub> | renamed to X-Sim RV with the new X logo and black / white primary colour; simulation files are .xrv (old files still open) | v1.0.92 | [`14268e5`](https://github.com/jerrin-v/xsim-rv/commit/14268e5f1d8ebf236aa34007bb89102ecbdb16a8) |
| Fri 20 Nov 2026, 10:33:29 PM UAE<br><sub>Fri 20 Nov 2026, 6:33:29 PM UTC</sub> | flow physics (thin parts, curved walls, wall model on the ground, true Reynolds number), air pressure as a Strength load, manual wind tunnel, model rotation, undo, fluid temperature and humidity, number box icons | v1.0.90 | [`0c111e9`](https://github.com/jerrin-v/xsim-rv/commit/0c111e9ec252c07a556e4d7086c105741807c948) |
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
