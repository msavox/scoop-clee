# scoop-clee

The [Scoop](https://scoop.sh) bucket for [CleeCode](https://cleecode.marunja.com) —
your terminal IDE. The Windows twin of the `homebrew-clee` tap: one manifest, pointing
at the same release the other platforms install.

```powershell
scoop bucket add clee https://github.com/msavox/scoop-clee
scoop install clee
```

Updating is `scoop update clee`. The manifest carries `checkver`/`autoupdate` against the
GitHub releases, and every release ships its own `.sha256` beside the archive, so a bump is
one `checkver -u` away.
