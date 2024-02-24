# pylintrc
My system-wide pylint configuration file.


## Usage
There are [many options](https://pylint.pycqa.org/en/latest/user_guide/usage/run.html)
where pylint searches for a configuration file. On Windows I've tried the following two from the list of options:

10. The file named by environment variable `PYLINTRC` (this is what I'm currently using)
11. if you have a home directory which isn't `/root`:
     1. `.pylintrc` in your home directory

*Note: Run pylint with the `-v` switch to see the path of the configuration file used.*


## References:
- [Example pylintrc file](https://github.com/pylint-dev/pylint/blob/main/pylintrc)
- [Running Pylint](https://pylint.pycqa.org/en/latest/user_guide/usage/run.html)





