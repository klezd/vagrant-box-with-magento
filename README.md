###### Download Magento 2.2 


From [Magento offical download page](https://magento.com/tech-resources/download), download with the .tar.gz extension

And save in the root folder, named it 'MagentoCE-22.tar.gz'

---
###### Download Magento before run 
```
$ vagrant up
$ vagrant ssh
```
---

After that

```

$ vagrant up
$ vagrant ssh

```

You now have your database and magento set. 

And your account to mysql is magento/magento

```

$ mysql -u magento -pmagento

```

---

Now you can come to http://127.0.0.1:1180 to start setup 

---
###### Note

If the frontend is messy, run

```
cd /var/www/magento2ce
php bin/magento setup:static-content:deploy -f
```

