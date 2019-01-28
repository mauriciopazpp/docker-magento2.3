![Magento 2](https://cdn-images-1.medium.com/max/1400/1*bUVzeE00N3BgQO9qJNQdPw.jpeg)
## Docker php7.2 + Magento 2 + phpmyadmin + Installer magento 2 script

### How to use

Clone this repository
```
git clone git@github.com:mauriciopazpp/docker-magento2.git
```

Avaliable comands to use this Docker Image:
```js
./docker-up //Run the docker
./docker-kill //Kill all the instances of docker
./docker-bash //Access the Image
./docker-install-magento //Install magento 2 on Image. Tip: You can type the version after the command, ex: 2.2
```

If you want, enter your vhost configuration in the file `magento.conf`

Open in the browser
``` 
http://localhost
```
Credentials to access:
```
User: admin
Pass: admin123
```
You can access phpmyadmin with this link:
```
http://localhost:8080
```
See ya!
