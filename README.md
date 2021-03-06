[![Build Status](https://travis-ci.org/smravi/docco-plus.svg)](https://travis-ci.org/smravi/docco-plus)
[![Code Climate](https://codeclimate.com/github/smravi/docco-plus/badges/gpa.svg)](https://codeclimate.com/github/smravi/docco-plus)

[![Dependency Status](https://david-dm.org/smravi/docco-plus.svg)](https://david-dm.org/smravi/docco-plus)
[![devDependency Status](https://david-dm.org/smravi/docco-plus/dev-status.svg)](https://david-dm.org/smravi/docco-plus#info=devDependencies)
[![peerDependency Status](https://david-dm.org/smravi/docco-plus/peer-status.svg)](https://david-dm.org/smravi/docco-plus#info=peerDependencies)


# docco-plus

> docco-plus is an extension to [docco](http://jashkenas.github.io/docco/) with support for multiple folders and same file name with different extensions


## How to use

### Installation and Setup

Install docco-plus globally using the command

```

sudo npm install -g docco-plus

```

### Usage

```

docco-plus [options] FILES

```

`FILES` can be a list of files or a glob pattern. **When passing glob pattern make sure that they are enclosed by quotes.**

#### Options:

Options available for docco-plus are listed below, These options do the same thing as docco options. In fact, they are
passed as-is to the docco processor. Refer the Docco documentation on more details about these options.

 - `-h` or `--help` output usage information

 - `-V` or `--version` output the version number

 - `-c [file]` or `--css [file]` use a custom css file

 - `-o [path]` or `--output [path]` use a custom output path

 - `-e [ext]` or `--extension [ext]` use the given file extension for all inputs

 - `-L [file]` or `--languages [file]` use a custom languages.json

 - `-m [file]` or `--marked [file]` use custom marked options