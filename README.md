# StormSewer Scoop bucket

[Scoop](https://scoop.sh) manifests for
[StormSewer](https://github.com/mf4633/stormsewer), a free and open-source
program for gravity storm-drain design and analysis.

```powershell
scoop bucket add stormsewer https://github.com/mf4633/scoop-bucket
scoop install stormsewer
```

## Status

The manifest installs from `StormSewer-windows-x64.zip`, the portable build,
which contains `StormSewer.exe` at its root. Nothing here has to guess at an
installer's internal layout, so there is no untested path left in it: the
archive was unpacked and its contents checked against the manifest before this
was published.

An earlier version of this manifest unpacked the Inno Setup installer instead
and could not be verified without a third-party extractor. The portable zip
exists partly to remove that problem.

## Other ways to install

StormSewer is also on winget, Homebrew, crates.io and PyPI, and there are
installers for Windows, macOS and Linux plus a browser build on the
[releases page](https://github.com/mf4633/stormsewer/releases).

## License

The manifests here are MIT. StormSewer itself is GPL-3.0-or-later.
