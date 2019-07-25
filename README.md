# watch for vimeo

Script to watch a filepath and upload what is put there to vimeo once it
exists.

Requires: 
- [watchexec](https://github.com/watchexec/watchexec)
- Python and [vimeo.py](https://github.com/vimeo/vimeo.py)

## Config
1. Get an Oauth2 token for your vimeo account from [the developer site](https://developer.vimeo.com/apps)
2. Put it as 'config.json' in this directory

## Run
```
./watchit path/to/file
```
