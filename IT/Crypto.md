# Crypto
## Livres
## Library
* https://github.com/jedisct1/libsodium  A modern and easy-to-use crypto library. https://libsodium.org
## Use
* Comprendre les grands principes de la cryptologie et du chiffrement https://www.cnil.fr/fr/comprendre-les-grands-principes-de-la-cryptologie-et-du-chiffrement
* decrypt a password with an external key (usb)
```
password=$(gpg --batch --quiet --no-default-keyring --secret-keyring /media/usb/key.priv --decrypt <<EOF 
-----BEGIN PGP MESSAGE-----

hQEMA0CjbyauRLJ8AQgAkZT5gK8TrdH6cZEy+Ufl0PObGZJ1YEbshacZb88RlRB9
h2z+s/Bso5HQxNd5tzkwulvhmoGu6K6hpMXM3mbYl07jHF4qr+oWijDkdjHBVcn5
0mkpYO1riUf0HXIYnvCZq/4k/ajGZRm8EdDy2JIWuwiidQ18irp07UUNO+AB9mq8
5VXUjUN3tLTexg4sLZDKFYGRi4fyVrYKGsi0i5AEHKwn5SmTb3f1pa5yXbv68eYE
lCVfy51rBbG87UTycZ3gFQjf1UkNVbp0WV+RPEM9JR7dgR+9I8bKCuKLFLnGaqvc
beA3A6eMpzXQqsAg6GGo3PW6fMHqe1ZCvidi6e4a/dJDAbHq0XWp93qcwygnWeQW
Ozr1hr5mCa+QkUSymxiUrRncRhyqSP0ok5j4rjwSJu9vmHTEUapiyQMQaEIF2e2S
/NIWGg==
=uriR
-----END PGP MESSAGE-----
EOF)
```
* RTFM: 
A database of common, interesting or useful commands, in one handy referable form https://necurity.co.uk/osprog/2017-02-27-RTFM-Pythonized/ - https://github.com/leostat/rtfm
## Decryption / encryption algorithms
* Principles and practice of x-raying, great and maybe the first article about this, by Peter Ferrie. https://vallejocc.files.wordpress.com/2017/08/x-raying.pdf
* XorSearch, by Didier Stevens. https://blog.didierstevens.com/programs/xorsearch/
* Decoding XOR shellcode without a Key, by Chris Jordan. https://playingwithothers.com/2012/12/20/decoding-xor-shellcode-without-a-key/
* UnXor, by Tomchop. https://github.com/tomchop/unxor
* Deobfuscating Embedded Malware using Probable-Plaintext Attacks (KANDI tool), by Christian Wressnegger, Frank Boldewin, and Konrad Rieck. https://www.tu-braunschweig.de/Medien-DB/sec/pubs/2013-raid.pdf
## Hide my Shell
*  Encrypted exploit delivery for the masses https://github.com/Mrgeffitas/Ironsquirrel
## Stegano
* Stego in TCP/IP made easy (Part-1): https://www.exploit-db.com/docs/40891.pdf  (pdf) 
* Part 2 - The Phantom Shell : https://www.exploit-db.com/docs/40897.pdf  (pdf)
* Python Steganography Tool: Matroschka https://github.com/fbngrm/Matroschka