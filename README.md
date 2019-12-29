# vagrant
1. Install vagrant
https://www.vagrantup.com/downloads.html
2. Cari Vagrant Box yang sesuai
https://app.vagrantup.com/boxes/search
3. CMD
> vagrant init ubuntu/bionic64
4. Edit Vagrantfile > Tambahkan baris ini, untuk mengaktifkan bridge
> https://github.com/ariantony/vargrant/blob/master/Vagrantfile
5. start
> vagrant up
6. ssh
> vagrant ssh
7. destroy
> vagrant destroy
8. vagrant stop
> vagrant halt


## copy ssh key
1. ssh-keygen
2. copy ssh key
- ssh-copy-id username@remote_host > jika bisa akses ssh
- cat ~/.ssh/id_rsa.pub
3. echo public_key_string >> ~/.ssh/authorized_keys ke host yang akan diremote.

https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys-on-ubuntu-1804

## Install Kubernetes
1. Install Docker dimasing2 host, lihat versi yang disupport rancher
> https://docs.docker.com/install/linux/docker-ce/ubuntu/
2. 
