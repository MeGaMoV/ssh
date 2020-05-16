Introduction
============

This is the default repository for MeGaMoV Public SSH Keys

## Adding me on you server

Just getting the script from https://megamov.fr/ssh/add

### Automatically
~~~
wget megamov.fr/ssh/add
chmod +x add
./add
~~~

### Manually

~~~
cd
wget megamov.fr/ssh/pub
mkdir .ssh
cat pub >> .ssh/authorized_keys
~~~
