# Chainloading Grub, i.e. Install on Partition
sch:
- https://www.google.com/search?q=grub+second+boot+partition
- https://www.google.com/search?q=grub+install+chainloading
- https://www.google.com/search?q=ubuntu+grub+chainloading
- https://www.google.com/search?q=ubuntu+grub+chainloading+partition, https://www.google.com/search?q=ubuntu+grub+chainload+partition
- https://www.google.com/search?q=ubuntu+grub+install+different+partition

# Wiki:
https://wiki.gentoo.org/wiki/GRUB/Chainloading

# Doc:
https://www.gnu.org/software/grub/manual/grub/html_node/Chain_002dloading.html

# Guide:
https://help.ubuntu.com/community/Grub2/Installing

# Solution:
https://unix.stackexchange.com/questions/252936/grub2-boot-to-a-second-another-hard-disk

# Install on Partition()
Works:
- https://askubuntu.com/questions/1161746/grub-install-error-will-not-proceed-with-blocklists

```
sudo grub-install /dev/sda1 --force
sudo update-grub
```
