sch:
https://www.google.com/search?q=qubes+os+dual+boot

# FAQ:
- https://www.qubes-os.org/faq/#can-i-install-qubes-os-together-with-other-operating-system-dual-bootmulti-boot

# Relation: Grub Chainloading
sch: https://www.google.com/search?q=ubuntu+grub+chainloading+partition

Guide:
- https://wiki.gentoo.org/wiki/GRUB/Chainloading

# Guide:
## Multibooting Qubes - Community Guides
https://forum.qubes-os.org/t/multibooting-qubes/18988

>Qubes by default does not include other systems in the generated grub menu, because handling of other systems has been disabled. This means that you will have to manually add grub entries for any other OS.
>
>The general approach is:
>
>- Enable legacy boot mode
>- Ensure current OS boots in legacy mode
>- Install Qubes
>- Manually add boot stanzas to /etc/grub.d/40_custom
>- Update grub


## Blog:
https://micahflee.com/2014/04/dual-booting-qubes-and-ubuntu-with-encrypted-disks/
- ark: https://web.archive.org/web/20231106011610/https://micahflee.com/2014/04/dual-booting-qubes-and-ubuntu-with-encrypted-disks/
