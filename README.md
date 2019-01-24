## Docker Magento 2

Clone this repository

```
docker-compose up
```

To install magento, run:
```
docker-compose exec --user www-data server bash -c 'mkdir magento; cd magento; install-magento2'
```

If you want, enter your vhost configuration in the file `magento.conf`

Open in the browser
``` 
http://localhost
```

User: admin
Pass: admin123