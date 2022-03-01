<!--
```{eval-rst}
:orphan:
```
-->

# Typescript Jupyter Book Template

![Jupyter Book Badge](https://jupyterbook.org/badge.svg)

I'm an avid Typescript developer, so much so that I wrote and published [typescript-jupyter-kernel](https://github.com/simplyhexagonal/typescript-jupyter-kernel)
to use with [Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable/) and [Jupyter Lab](https://jupyter.org/).

As my research has grown in size and complexity, I've put together this [Jupyter Book](https://jupyterbook.org/) template,
making sure to adhere to well-known industry standards (such as [APA](https://apastyle.apa.org/style-grammar-guidelines/references/examples/webpage-website-references) style citations/bibliography),
to help organize and publish my work in an efficient and conscientious manner.

![](https://raw.githubusercontent.com/jeanlescure/typescript-jupyter-book-template/main/book/assets/snapshot.png)

View the [live example](https://jeanlescure.io/books/typescript-jupyter-book-template/).

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

Clone this repository and navigate to the root directory:

```sh
git clone https://github.com/jeanlescure/typescript-jupyter-book-template.git

cd typescript-jupyter-book-template
```

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

Open this repository on VS Code.

Alternatively, you can run the following command to run Jupyter Lab inside the book's directory:

```sh
pnpm dev
```

**NOTE:** `CTRL-C` does not stop Jupyter Lab, to stop the server, click `File -> Shut Down` on Jupyter Lab's UI.

## Building Book (HTML)

```sh
pnpm build
```

## Other build options

You can find more information on how to build your book in the [Jupyter Book documentation](https://jupyterbook.org/basics/build.html).

## Customization

Place your logo image at the root of this repository then change the logo file name, title, and
author in the `_config.yml` file to match yours.
