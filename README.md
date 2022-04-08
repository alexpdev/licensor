# OSSlicenser

<!--- These are examples. See https://shields.io for others or to customize this set of shields. You might want to include dependencies, project status and licence info here --->

[!OSSlicenser](https://github.com/alexpdev/osslicenser/blob/master/osslicenser.png?raw=true)
-------

![GitHub repo size](https://img.shields.io/github/repo-size/alexpdev/osslicenser)

OSSlicenser is a tiny CLI tool that allows generates various OSS `LICENSE` on demand.

## Prerequisites

- Python 3
- pip

## Installing osslicenser

`pip install osslicenser`

## Using osslicenser

To use osslicenser, follow these steps:

- Use the `-l` or `--list` command line option to list available licenses.

- Use the `get` subcommand followed by the abbreviated license code found entering the `-l` option.

- Use the `choose` subcommand to select a particular license from a list of choices

Examples:

```bash
> osslicenser --list

> osslicenser get bsd1

> osslicenser choose
```

## Contact

If you want to contact me you can reach me through the issues tab on github
