
## to install

see https://github.com/despiegk/gridstarter

follow the instructions there, it will also install this repo

## to develop


## generating docs

```bash
#cd in this directory
## with also private methods
v doc -all -m zstor -o /tmp/crystallib -f html -readme

## public methods only
rm -rf /tmp/crystallib && v doc -m zstor -o /tmp/crystallib -f html -readme
open /tmp/crystallib/_docs/builder.html
```


