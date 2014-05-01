# vagrant-php55-apache

Vagrant files to install PHP5.5 and Apache for CentOS6.4

php packages are installed via remi repository.

CentOS6.4にPHP5.5とApacheをインストールするためのVagrantfile一式です。

PHPはremiレポジトリ経由でインストールされます。

## How to use

## add box

you have to get a CentOS6.4 box
see http://www.vagrantbox.es/

事前に CentOS6.4 or 6.5のboxを追加しておいてください。

```
vagrant box add centos6.4 URL
```



## vagrant up

```
git clone https://github.com/DQNEO/vagrant-php55-apache
cd vagrant-php55-apache
vagrant up
```

## See if it is installed

access the URL below by your browser on the host machine.
ホストマシンから下記のアドレスにブラウザでアクセスしてください。

http://10.10.10.10/

or simply `php -v` on the guest machine

または`php -v`などしてもバージョンを確認できます。

