<!--
```{eval-rst}
:orphan:
```
-->

# Typescript Jupyter Book Template

I'm an avid Typescript developer, so much so that I wrote and published [typescript-jupyter-kernel](https://github.com/simplyhexagonal/typescript-jupyter-kernel)
to use with [Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable/) and [Jupyter Lab](https://jupyter.org/).

As my research has grown in size and complexity, I've put together this Jupyter Book template,
making sure to adhere to well-known industry standards (such as [APA](https://apastyle.apa.org/style-grammar-guidelines/references/examples/webpage-website-references) style citations/bibliography),
to help organize and publish my work in an efficient and conscientious manner.

![](https://raw.githubusercontent.com/jeanlescure/typescript-jupyter-book-template/main/book/assets/snapshot.png)

If you find it useful, please consider supporting my work by:

- [Buying me a coffee](https://www.buymeacoffee.com/jeanlescure) ☕
- Donating to my open source project Simply Hexagonal on [Open Collective](https://opencollective.com/simplyhexagonal) 🏆
- Starring this repo on [Github](https://github.com/simplyhexagonal/package) 🌟

## Getting Started

Install Python 3 and pip:

- [How to Install on Debian / Ubuntu / Linux Mint](https://realpython.com/installing-python/#how-to-install-on-ubuntu-and-linux-mint)
- [How to Install on openSUSE](https://realpython.com/installing-python/#how-to-install-on-opensuse)
- [How to Install on CentOS and Fedora](https://realpython.com/installing-python/#how-to-install-on-centos-and-fedora)
- [How to Install on Arch Linux](https://realpython.com/installing-python/#how-to-install-on-arch-linux)
- [How to Install on MacOS](https://realpython.com/installing-python/#how-to-install-from-homebrew)
- [How to Install on Windows](https://realpython.com/installing-python/#how-to-install-from-the-full-installer)

Install pip dependencies:

```sh
pip install -r requirements.txt
```

Install [nvm](https://github.com/nvm-sh/nvm#install--update-script).

Install Node long-term support (LTS) using nvm:

```sh
nvm install --lts
```

Install [pnpm](https://pnpm.io/installation#using-npm):

```sh
npm install -g pnpm
```

Install [Typescript Jupyter Kernel](https://github.com/simplyhexagonal/typescript-jupyter-kernel#readme) and `package.json` dependencies:

```sh
pnpm setup-ts-kernel

pnpm i
```

## Usage

```sh
pnpm dev
```

**NOTE:** `CTRL-C` does not stop the Jupyter Lab server, to stop the server, click `File -> Shut Down` on Jupyter Lab's UI.

## Building Book (HTML)

```sh
pnpm build
```

## Other build options

You can find more information on how to build your book in the [Jupyter Book documentation](https://jupyterbook.org/basics/build.html).

## Customization

Place your logo image at the root of this repository then change the logo file name, title, and
author in the `_config.yml` file to match yours.
