# virtualhost-script-for-MacOS
A shell script for creating virtualhosts with command line

## Installation
`sudo mv virtualhost /usr/local/bin && chmod a+x /usr/local/bin/virtualhost`

**In Apache config add:**
`Include /private/etc/apache2/virtualhosts/*`

## Usage
`virtualhost`

```
Usage: virtualhost <name> [<optional path>]
       virtualhost list
       virtualhost edit <name>
       virtualhost delete <name>
   where <name> is the one-word name you'd like to use. (e.g. mysite.dev)
```
