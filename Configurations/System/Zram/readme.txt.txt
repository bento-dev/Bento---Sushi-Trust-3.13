English:
zram is a kernel module from the compcache project:
http://code.google.com/p/compcache

initramfs.conf goes to /etc/initramfs-tools from the initramfs-tools package:
it contains "25%" instead of "nothing", which means it overrides the default which is 50%
of the available RAM to get the size of the block devices created.

compcache.patch is to be used for the compcache file located under 
/usr/share/initramfs-tools/conf.d which belongs to the casper package.

The patch for the compcache file (which is an executable script) goes under 
/usr/share/initramfs-tools/hooks and belongs to initramfs-tools.


Fran?ais:
zram est un module du kernel qui fait partie du projet compcache:
http://code.google.com/p/compcache

initramfs.conf va dans /etc/initramfs-tools du paquet initramfs-tools: 
il comporte "25%" pour compcache au lieu de "rien", ce qui signifie qu'il r??crit 
la valeur par d?faut qui est de 50% de la RAM disponible pour obtenir la taille des
p?riph?riques block cr??s.

compcache.patch est destin? au fichier compcache situ? sous 
/usr/share/initramfs-tools/conf.d qui appartient au paquet casper.

le patch pour le fichier compcache (qui est un script ex?cutable) va
sous /usr/share/initramfs-tools/hooks et appartient ? initramfs-tools.

