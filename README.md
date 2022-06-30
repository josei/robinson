# Robinson

Identifies isolated contributors in a git project.

```
usage: robinson [-h] [-a [ALIASES [ALIASES ...]]] [-c] [-t THRESHOLD] [-p PERCENTAGE] [-s]

identifies isolated contributors in a git project

optional arguments:
  -h, --help            show this help message and exit
  -a [ALIASES [ALIASES ...]], --aliases [ALIASES [ALIASES ...]]
                        include a list of alias emails pairs (default: [])
  -c, --cost            show COCOMO-estimated cost instead of edits (default: False)
  -t THRESHOLD, --threshold THRESHOLD
                        minimum edits required to be relevant (default: 800)
  -p PERCENTAGE, --percentage PERCENTAGE
                        minumum percentage required to top contributor (default: 85)
  -s, --show-contributors
                        show all contributors (default: False)
```
