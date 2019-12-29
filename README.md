# vagrant
1. Install vagrant
https://www.vagrantup.com/downloads.html
2. Cari Vagrant Box yang sesuai
https://app.vagrantup.com/boxes/search
3. CMD
> vagrant init
4. Edit Vagrantfile > Tambahkan baris ini, untuk mengaktifkan bridge
> config.vm.network "public_network",
> use_dhcp_assigned_default_route: true
5. start
> vagrant up
6. ssh
> vagrant ssh
7. destroy
> vagrant destroy
8. vagrant stop
> vagrant halt




https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys-on-ubuntu-1804
