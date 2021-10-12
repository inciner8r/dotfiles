fix hibernate, suspend to disk-
<br>point to swap file in /etc/default/grub - <i>GRUB_CMDLINE_LINUX_DEFAULT="resume=UUID=swapUUID"</i>
And add resume hook to mkinitcpio before filesystems

<br>Wifi driver- Available in AUR as rtw89-dkms-git... https://github.com/lwfinger/rtw89
