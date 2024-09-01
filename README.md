# Keyring Crack PoC
This is a fork that has build instructions. I changed the repository name to reflect it is for gnome secrets.

Previous coder:
Keyring-crack is a PoC code for cracking gnome-keyring that is widely used in Gnome based Linux.
Currently, google-chrome employs the keyring as a default password-manager and then some packages including network-manager and gnome-online-accounts.


# How to build updated
You require the following to build keyring-crack:

gcc `pkg-config -cflags libsecret-1` `pkg-config -libs libsecret-1` keyring_crack.c -o keycrack

Video removed. It does not belong to me. 
