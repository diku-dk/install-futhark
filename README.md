# Install Futhark compiler

This action installs the Futhark compiler in a Linux-based GitHub
Actions runner.  The compiler is installed in `$HOME/.local`, which
means it will be on the `$PATH` of a standard setup.

## Inputs

`version`

The full version to install as a string (e.g. `'0.22.3'`), or the
string `'latest'`.

## Example usages

```
      - uses: diku-dk/install-futhark@v1.0.0
        with:
          version: '0.22.3'
```

```
      - uses: diku-dk/install-futhark@v1.0.0
```

```
      - uses: diku-dk/install-futhark@v1.0.0
        with:
          version: 'latest'
```
