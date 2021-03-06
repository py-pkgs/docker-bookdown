# py-pkgs Bookdown Docker support

Docker image to support PDF building of the open-source [Python Packages book](https://py-pkgs.org).

## Usage

If you'd like develop and build the Python Packages book to PDF:

1. Install [Docker](https://docs.docker.com/get-docker/).
2. Pull the `pypkgs/bookdown` images: `docker pull pypkgs/bookdown`.
3. Clone the [py-pkgs repository](https://github.com/py-pkgs/py-pkgs) from GitHub: `git clone https://github.com/py-pkgs/py-pkgs.git`.
4. Make any desired changes to source files.
5. Build the book using the `build_bookdown.sh` script.

  ```bash
  $ cd py-pkgs
  $ sh build_bookdown.sh
  ```

A fully-rendered PDF version of the book will be built in `py-pkgs/bookdown/_book/`.
