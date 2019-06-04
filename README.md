![alt text](https://img.shields.io/badge/PHP%20Version-7.2.11-blue.svg) ![alt text](https://img.shields.io/badge/Phalcon%20Version-3.4.3-green.svg) ![alt text](https://img.shields.io/badge/Ubuntu%20Version-14.04.5%20LTS-red.svg)

![phalcon](http://www.comnez.com/images/php-phalcon.png)

How to install Phalcon on DreamHost VPS 

### Step 1

Set your site to use PHP 7.2

![alt text](https://i.ibb.co/8rcxxrf/Screenshot-from-2019-06-04-11-07-33.png)


### Step 2

>Edit .php/7.2/phprc

```
extension=/home/{YOUR_USER_NAME}/.php/7.2/extensions/phalcon.so
```


### Step 3

create extensions folder and upload provided phalcon.so file to new extensions folder:

`.php/7.2/extensions/`


### Step 4
`killall -9 php72.cgi -u YOUR_USER_NAME`


If this helped you please star this repo so other people can find it.
