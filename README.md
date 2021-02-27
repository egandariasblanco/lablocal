# lablocal

¿Verificaciones?
Encontrar forma de recoger la salida de kubeadm en paso 04 para añadir los workers al cluster


Hay que forzar la creación del lv o crearlo con shrink=no, si no, si ya existe, da error.


El fichero /etc/kubernetes/admin.conf no se puede copiar sin más. Hay que cambiarle los permisos antes de copiarlo a la home de root