# Rion Studio Third-Party Software Notices

Notice version: 2026-09-13

Rion Studio incorporates third-party open-source software. Copyright remains with the respective authors. The applicable license texts, copyright notices, and attribution requirements remain in force and are not replaced by the Rion Studio Terms of Use.

## Principal runtime components

- Electron — MIT License.
- Chromium and its bundled components — BSD-style and other open-source licenses supplied by Electron.
- `@ramboxapp/electron-chrome-extensions` 4.10.3, audited commit `026cea78b6d743a81e2aa0e84d236081fccf4c72`, with Rion modifications — GNU GPL v3. The full corresponding upstream source is retained under `third_party/electron-chrome-extensions`; product builds use only the audited entry points documented in `RION-PROVENANCE.md`.
- rusqlite — MIT License; SQLite is dedicated to the public domain.
- React and React DOM — MIT License.
- React Router — MIT License.
- Lucide React — ISC License.
- class-variance-authority — Apache License 2.0.
- clsx — MIT License.
- tailwind-merge — MIT License.

The packaged application can contain additional transitive Rust and JavaScript runtime components. Their license texts and notices remain applicable where supplied. Development-only tools are used to build Rion Studio but are not represented as application features.

## Trademarks

Apple, Microsoft, Electron, Chromium, GitHub, Google, Chrome, Facebook, game names, service names, and related marks belong to their respective owners. Listing a product or mark describes compatibility or a dependency and does not imply affiliation, sponsorship, or endorsement.

## Rion Studio code

Rion Studio program code is licensed under GPL-3.0-only. The GPL does not grant trademark rights in the Rion Studio name, logos, or product artwork. Third-party notices do not replace the GPL or any component's own license. Public desktop releases include `Rion.Studio-source.tar.gz`; its digest is part of `SHA256SUMS.txt`.
