# OS Tools
A bunch of cyber / disk tools useful for a developer.

I use this scripts as XFCE4/nemo right click filemanager accellerators.

# Preconditions
You must install the below packages for your distribution.
```
sudo apt install genisoimage dvdisaster zenity imagemagick qpdf
```

# Install in Thunar
```
cp ./os-tools /var/lib
```
Go to Thunar>Edit>Configure Custom Actions
Open a separate terminal.
```
bash /var/lib/os-tools/image-magick --help
```
Configure Thunar to whatever action you want in the script.

# Install in Nemo
```
cp os-tools /var/lib
cp /var/lib/os-tools/nemo-actions/ed-* /usr/share/nemo/actions
```
Right click nemo actions are now installed.
