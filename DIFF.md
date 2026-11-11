# How this package differs from upstream

`@qadeer-xtech/whatsapp-rust-bridge` 1.0.0 is a **faithful republish**
of the official **whatsapp-rust-bridge 0.5.4** by João Lucas (npm),
renamed so the StableBail dependency tree carries a single publisher
scope.

## Changed
- `package.json` — package name, version (1.0.0) and branding fields.
- `README.md` — title and install instructions.

## NOT changed — verified
All shipped code is **byte-identical** to the official
`whatsapp-rust-bridge@0.5.4` npm tarball: the whole `dist/` folder and
the whole `pkg/` folder, **including the compiled WebAssembly
binaries**. Verified with a full recursive diff and per-folder `cmp`
against the official tarball on 2026-11-11. There are no code
modifications of any kind in this republish.

If a future version of this package ever modifies code, the change
will be listed here file by file.
