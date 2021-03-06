# Dotbot apt-get Plugin

For use with [dotbot](https://github.com/anishathalye/dotbot),
this plugin allows one to easily
install or upgrade a list of apt-get packages.

## Usage

It's easiest to track this plugin in your dotfiles repo:

```bash
git submodule add https://github.com/rubenvereecken/dotbot-apt-get
```

I also recommend having your apt-get list in a separate file
since dotbot will need root privileges
in order to use the plugin.
Using the plugin will look something like this:

```bash
./install -p dotbot-apt-get/aptget.py -c packages.conf.yaml
```
