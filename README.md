## Purpose

It's difficult to keep direct builds from SRPM's that are handled
through [Koji]() synchronized with a git repository. This tool downloads
each SRPM in a given tag, extracts the .spec file, and adds the files to
a git repo for easier consumption.

## Usage

`sfk` must be run from inside an existing git repository.

`sfk -h <kojihub endpoint> -t <tag to retrieve specs from>`

## License

See LICENSE in this repo.
