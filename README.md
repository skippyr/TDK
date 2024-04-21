<p align="center">
	<img alt="" src="assets/ornament.webp" />
</p>
<h1 align="center">≥v≥v&ensp;libtdk&ensp;≥v≥v</h1>
<p align="center">
	<img alt="" src="https://img.shields.io/github/license/skippyr/libtdk?style=plastic&label=%E2%89%A5%20license&labelColor=%2324130e&color=%23b8150d" />
	&nbsp;
	<img alt="" src="https://img.shields.io/github/v/tag/skippyr/libtdk?style=plastic&label=%E2%89%A5%20tag&labelColor=%2324130e&color=%23b8150d" />
	&nbsp;
	<img alt="" src="https://img.shields.io/github/commit-activity/t/skippyr/libtdk?style=plastic&label=%E2%89%A5%20commits&labelColor=%2324130e&color=%23b8150d" />
	&nbsp;
	<img alt="" src="https://img.shields.io/github/stars/skippyr/libtdk?style=plastic&label=%E2%89%A5%20stars&labelColor=%2324130e&color=%23b8150d" />
</p>

## ❡ About

A simple C99 terminal manipulation library for Linux that can be used to create general purpose terminal applications.

It includes features to manipulate terminal properties, styles and key readings with UTF-8 encoding.

## ❡ Install

### Dependencies

The following dependencies must be installed before installing it:

- **git**: it will be used to clone this repository.
- **gcc**, **make**: they will be used to compile this software.

### Procedures

To install this software, using a terminal, follow these steps:

- Clone this repository using `git`:

```sh
git clone --depth 1 https://github.com/skippyr/libtdk;
```

- Access the directory of the repository you cloned using `cd`:

```sh
cd libtdk;
```

- Use `make` to compile and install this software:

```sh
make install;
```

- Add the following environment variables to your shell startup file in order to include the installed files that are at the directories under `~/.local/share`:

```zsh
export LD_LIBRARY_PATH=${LD_LIBRARY_PATH}:~/.local/share/lib;
export LIBRARY_PATH=${LD_LIBRARY_PATH}:~/.local/share/lib;
export MANPATH=${MANPATH}:~/.local/share/man;
export CPATH=${CPATH}:~/.local/share/include;
```

- Open a new shell session.

## ❡ Uninstall

To uninstall this software, using a terminal, follow these steps:

- Go back to the directory of the repository you cloned.
- Use `make` to uninstall it:

```sh
make uninstall;
```

## ❡ Documentation

After installed, you can access its documentation using `man`:

```sh
man tdk.3;
```

## ❡ Help

If you need help related to this project, open a new issue in its [issues pages](https://github.com/skippyr/libtdk/issues) or send me an [e-mail](mailto:skippyr.developer@gmail.com) describing what is going on.

## ❡ Contributing

This project is open to review and possibly accept contributions, specially fixes and suggestions. If you are interested, send your contribution to its [pull requests page](https://github.com/skippyr/libtdk/pulls) or to my [e-mail](mailto:skippyr.developer@gmail.com).

By contributing to this project, you agree to license your work under the same license that the project uses.

## ❡ License

This is free software licensed under the BSD-3-Clause License that comes WITH NO WARRANTY. Refer to the `LICENSE` file that comes in its source code for license and copyright details.

&ensp;
<p align="center"><sup><strong>≥v≥v&ensp;Here Be Dragons!&ensp;≥v≥</strong><br />Made with love by skippyr <3</sup></p>
