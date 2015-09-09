# aws
project to learn aws, using go

AWS page: http://54.213.126.59

# tricky
>. use sudo to run on port 80
```bash
sudo ./hello
```
>. file upload via SCP
```bash
scp -i ~/user.pem source_file user@server:/target/path
```
>. memcached
```bash
sudo apt-get install memcached
memcached -d -m 128 -p 11111 -u root
```
