# UNIX Shell [^1]
[^1]: Actual code is private due to the assignment constraints. When starting this project, I was given a brief outline by my professor, however the vast majority of the program is written by me (Wylie Mickelson).

### Steps to demo
1. Clone this repo to your local machine
2. Using a Linux terminal (i.e bash and WSL will work), navigate to the folder you cloned this repository to
3. Type './ush' (without quotations) to start the program
4. Type any of the commands listed below and press enter

## List of current working commands
### Basic UNIX commands
Most commands listed [here](https://mally.stanford.edu/~sr/computing/basic-unix.html)
 
### Special identifiers (denoted by text starting with '$' char):
When typing these identifiers, the text will be replaced
| Syntax | Replacement |
| ----------- | ----------- |
| $$ | current Unix PID (process identifier) |
| ${var} | the value of the corresponding environment variable inside of ${}, or an empty string if none found |

### Builtin commands (processed by the shell program itself):
| Command | Description |
| ----------- | ----------- |
| exit [value] | Exit the shell with the value. If value is not given, exit with value 0 |
| envset NAME value | Sets the environment variable of the same name to the given value |
| envunset NAME | Removes the variable NAME from the current environment |
| cd [directory] | Changes the current working directory of the shell. If the directory is not given, uses the env variable HOME |

