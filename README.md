# stndp

> A command line tool for doing daily stand-ups.


## Install

__Dependencies:__

- [jq](https://stedolan.github.io/jq) - Used to parse the JSON responses.

```
$ curl https://raw.githubusercontent.com/kjbrum/stndp/master/stndp > ~/bin/stndp
$ chmod +x ~/bin/stndp
```


## Usage

```
stndp - v0.0.1

A command line tool for doing daily stand-ups.

Usage:
    stndp <command> <options>

Commands:
    add        Add a new record to the database
        users
        questions
        answers
    cleanup    Remove all config files
    help       Display this help text
    init       Initialize necessary config files
    list       List records from the database
        users
        questions
        answers
    update     Download the latest version of stndp
    version    Display the current version
```


## Config

#### STNDP_API_KEY

Your Airtable API key. [Find it here](https://airtable.com/account)

#### STNDP_USERNAME

Your Airtable username.


## To-Do


## License

Copyright © [Kyle Brumm](http://kylebrumm.com). Free to use on whatever and may be redistributed under the terms specified in the [license](LICENSE.md).
