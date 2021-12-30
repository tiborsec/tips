### Instaling .deb package:

While dpkg -i indeed installs the package, it doesn't do any automatic dependency resolution, mean while there are two other alternatives, using gdebi, or the apt-get tool. To use the later just use:

sudo apt-get install ./package.deb
