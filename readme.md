# npm-iss11894

> Reproducing [issue 11894](https://github.com/npm/npm/issues/11894) in the npm issue tracker


## Usage

### Install

First, install this package globally

```
$ npm install -g npm-iss11894
```

This command will list the installed files as a `postinstall` hook.

## Uninstall

After that, uninstall the package again.

```
$ npm uninstall -g npm-iss11984
```

The uninstall command will run `ls` as a `preuninstall` hook.  Spot the difference!


## License

MIT © [Sam Verschueren](https://github.com/SamVerschueren)
