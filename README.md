# use - a simple way to use modules in your shell scripts

## Example

```sh
#!/bin/sh

. "(command -v use)"

use 'tayadev/ShellStuff:textstyle.sh'

echo "${green}If this text is colored is works :)$reset"
```

## Installation
`$ git clone https://github.com/tayadev/use`
`$ cd use`
`$ [sudo] make install`
