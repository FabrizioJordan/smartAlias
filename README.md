# Smart Alias Script

A script to see your most used commands (from Bash and Zsh history files).


## Requirements

All you need is a `bash` shell and the usual Linux command-line tools.  
`root` or `sudo` access required only for the installation.

## Installation

Clone the repo and set up the script:

```
git clone https://github.com/FabrizioJordan/smartAlias.git && cd smartAlias
```

If you want a command to execute quickly copy and paste this code:

```
chmod +x smartAlias && sudo cp smartAlias /usr/local/bin
```


## How to update

Update is so easy

Now you have only one option

From the terminal ->
Only run this two commands:

```
git clone https://github.com/FabrizioJordan/smartAlias.git && cd smartAlias
```

To update the script used for the command:
```
sudo cp smartAlias /usr/local/bin/smartAlias && cd .. && rm -f smartAlias
```


## Usage


### How this script works?

Its easy.

First, execute the script with `./smartScript` or `bash smartScript`.

Then, select your best option.

Now, you are free to create your new aliases.

## Uninstallation

During installation, the script is copied to /usr/local/bin. If you wish to uninstall it, follow these steps:

To remove the script:

```
find /home/ -type f -name "smartAlias" -exec rm {} \; && sudo find /usr/ -type f -name "smartAlias" -exec rm {} \;
```
