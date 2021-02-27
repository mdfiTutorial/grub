# grub
Change GRUB2 Themes

Conditions:
- Kali Linux 2020 with GRUB 2

1) Download GRUB Themes from https://www.gnome-look.org/
2) Extract themes.tar.xz on your folder

There are two ways to install
1) Run install.sh from the themes folder
2) Use Grub Customizer and add your new themes (Use subfolder withour "install.sh")

Unfortunately both are not working
1) Navigate with root to /boot/grub/themes/theme_name/
2) Backup first kali folder "mv kali kali_bak"
3) Change the new theme name with "mv theme_name kali"
4) sudo update-grub
5) DONE. REBOOT. IT WORKS
