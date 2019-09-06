# DisableWare

DisableWare changes system configurations in way which should make it hard to impossible to use any command line tools by breaking the access to those tools. Possible ways range from harmless (adding aliases to .bashrc, easily revertible) to more obscure and harmlful (replacing binaries and similar permanent changes).

The intended use is to allow a fast way of making a computer unusable intentionally from the terminal (and possibly from the desktop enviroment). 

To install run
```bash
# RUN AT YOUR OWN RISK! This potentially will damage your computer.
curl -sSL https://raw.githubusercontent.com/How-do-I-enter-vim/DisableWare/master/install.sh | bash 
```


## Command collection
Some interesting command which can be itegrated.

```bash
# Reverse ls
ls | rev
```
