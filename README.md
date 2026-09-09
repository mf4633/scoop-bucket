# StormSewer Scoop bucket

[Scoop](https://scoop.sh) manifests for
[StormSewer](https://github.com/mf4633/stormsewer), a free and open-source
program for gravity storm-drain design and analysis.

```powershell
scoop bucket add stormsewer https://github.com/mf4633/scoop-bucket
scoop install stormsewer
```

## Status

**The manifest has not yet been run on a clean machine.** It was written against
the installer that ships with each release, which is Inno Setup, and Scoop
unpacks those with `innounp`. The one value that cannot be checked without
actually running it is `extract_dir`, which has to match the directory name
`innounp` produces. The installer writes to `{app}`, so that is what the
manifest says.

If `scoop install stormsewer` fails with a missing directory, that is the value
to change, and an issue here with the error text is welcome.

This bucket exists so that mistake costs one person a minute rather than
wasting a maintainer's afternoon. Once someone confirms a clean install, the
manifest is worth submitting to
[ScoopInstaller/Extras](https://github.com/ScoopInstaller/Extras), which is
where people actually find things.

## Other ways to install

StormSewer is also on winget, Homebrew, crates.io and PyPI, and there are
installers for Windows, macOS and Linux plus a browser build on the
[releases page](https://github.com/mf4633/stormsewer/releases).

## License

The manifests here are MIT. StormSewer itself is GPL-3.0-or-later.
