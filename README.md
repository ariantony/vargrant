# vagrant
1. Install vagrant
https://www.vagrantup.com/downloads.html
2. Cari Vagrant Box yang sesuai
https://app.vagrantup.com/boxes/search
3. CMD
> vagrant init
> edit Vagrantfile.
> Tambahkan baris ini, untuk mengaktifkan bridge
> config.vm.network "public_network", type: "dhcp", bridge: "eth0"
