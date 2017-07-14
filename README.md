# vm-docker
Oltre a contenere un Vagrant per tirare su una macchina virtuale per testare il progetto puppet-desktop, la sezione di provision
contiene degli utili comandi per avere sulla macchina una configurazioni iniziale con Desktop Gnome.
Per aggiungere applicazioni nella dock si puo' seguire anche questa guida
https://developer.gnome.org/integration-guide/stable/desktop-files.html.en

Caratteristiche:

 - Ubuntu 16.04 (shell Gnome 3.3)
 - 4 Gb di Ram
 - 2 cpu
 - 128MB Ram video
 - Accellerazione Hardware 3D



Alcuni plugin Vangrant utili:
 - vagrant plugin install vagrant-vbguest
 - vagrant plugin install cacher
