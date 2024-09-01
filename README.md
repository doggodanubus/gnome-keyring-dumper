# Keyring Crack PoC
This is a fork that has build instructions. I changed the repository name to reflect it is for gnome secrets.

#
Keyring-crack is a PoC code for cracking gnome-keyring that is widely used in Gnome based Linux.
Currently, google-chrome employs the keyring as a default password-manager and then some packages including network-manager and gnome-online-accounts.

#Note:
This does not extract all data. It only pulls URL and password. I am not real competent at coding. I might fumble up at least username. The output format will need help. I'd like a gnome secret CSV format and keepassxc csv format if possible. I won't be able to do that. 

# How to build updated
You require the following to build keyring-crack:

gcc `pkg-config -cflags libsecret-1` `pkg-config -libs libsecret-1` keyring_crack.c -o keycrack

Video removed. It does not belong to me. 

Thanks to sungjungk for this. If you have the power spin them up a dungeon full of fabulous treasures please do so. 
