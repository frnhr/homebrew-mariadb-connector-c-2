# homebrew-mariadb-connector-c-2
Version 2.2.2 of `mariadb-connector-c` formula which works with Python 2.7 and MySQL-Python

## Why

Seems that MariaDB 10.2.x is not compatible with `MySQL-Python` (and possibly other older Python connectors as well). See 
https://stackoverflow.com/questions/44239393/installing-mysqlclient-for-mariadb-on-mac-os-for-python3

## Why 2.2.2

Found this formula in `homebrew-core` repo, last one before `3.x`.

## But the URL is different

Wow, you checked :+1:

The URL in the formula gives a 404. This URL should work, and is taken from the official site: https://downloads.mariadb.com/Connectors/c/connector-c-2.2.2

Other 2.x versions might work. Or they might not ¯\\\_(ツ)\_/¯

Here is the original formula: https://github.com/Homebrew/homebrew-core/blob/1ea62184de8410f2c8b3fb89ea1cc573fc9c4f92/Formula/mariadb-connector-c.rb

## I don't ever run other people's code like that!

:thinking: A strange thing to say if you running brew... But ok, you can [download the formula](https://raw.githubusercontent.com/frnhr/homebrew-mariadb-connector-c-2/master/Formula/mariadb-connector-c.rb), and build it locally:
```
$ brew install --build-from-source path/to/donwloaded/mariadb-connector-c.rb
```
Don't rename the file, though, brew seems to not like that.
