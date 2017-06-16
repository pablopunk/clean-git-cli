# clean-git-cli

<p align="center">
  <i>Find all git repos that are not 'clean' from your command line</i>
</p>
<p align="center">
  <a href="https://www.npmjs.com/package/clean-git-cli"><img src="https://img.shields.io/npm/dt/clean-git-cli.svg" /></a>
</p>

## Install

```bash
npm install --global clean-git-cli
```

## Usage

Use `clean-git -h` to display the following help:

```bash
  Commands:
    help  Display help
  
  Options:
    -h, --help            Show help
    -H, --help            Output usage information
    -i, --ignores <list>  Paths to ignore (defaults to ["node_modules"])
    -m, --maxdepth <n>    How deep the search gets (defaults to 3)
    -v, --version         Output the version number
  
  Examples:
    - Find all repos starting from the current directory
    $ clean-git

    - Find all repos starting from your home folder
    $ clean-git ~

    - Find all repos starting from "repos", ignoring paths containing *dist* or *node_modules*, and looking only 2 levels deep
    $ clean-git repos/ -m 2 -i dist -i node_modules
```

## Contribute

Feel free to open an [issue](https://github.com/pablopunk/clean-git-cli/issues/new) or a [PR](https://github.com/pablopunk/clean-git-cli/compare).

## Related

The API for this module => [clean-git](https://github.com/pablopunk/clean-git)

## Author

| ![me](https://www.gravatar.com/avatar/fa50aeff0ddd6e63273a068b04353d9d?s=100) |
| ----------------------------------------------------------------------------- |
| © 2017 [Pablo Varela](http://pablo.life)                                      |
