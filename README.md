# T(erraform) A(ws) C(onfig) S(sh)
============

**tacs** is a command line program that generates a ssh config
entry that is specific to a PPF Terraform AWS environment.

## Features

Generate ssh config entry

* using given AWS credentials and 
* Terraform environment


## Installation

#### OSX
```sh
brew tap ruijzndl/tasc
brew install tasc
```

#### Other systems

Clone this repo, or download and unzip the [tarball](https://github.com/ruijzndl/tasc/archive/0.0.1.tar.gz). Either add the `bin` directory to your `$PATH`, or create a symlink in your `$PATH` that points to the **tasc** executable in the `bin` directory.

If you execute **tasc** via symlink, *make sure that the name of the target file (the symlink) is also tasc*. Otherwise, tab completions won't work.



## Usage

```sh
tasc -m
```

## License
This code is licensed under the [MIT License](https://opensource.org/licenses/MIT).