ko-crypto is a directory file listing program,supports any schema of site deployment,without any database, support html5,supports many kinds of streaming media,you can use aria2 to download or upload files to the server. 
![index](https://user-images.githubusercontent.com/82877945/154240941-f6533825-1132-4ae9-8e22-b581b4085567.png)

```diff
- This project works fine on PHP7.4, but php8.1.5 is not compatible!
```
BUG FIX:

	$this->notdir=array("ag","phpmyadmin",".gitignore","CSS");//Folders that are not allowed to be displayed, A new .gitignore and CSS directory has been added.
Replace 3 broken CSS links.

broken:

~~https://cdn.bootcss.com/bootstrap/3.3.0/css/bootstrap.min.css~~

~~https://cdn.bootcss.com/jquery/1.11.1/jquery.min.js~~

~~https://cdn.bootcss.com/bootstrap/3.3.0/js/bootstrap.min.js~~

~~https://cdn.staticfile.org/twitter-bootstrap/3.3.7/css/bootstrap.min.css~~

~~https://cdn.staticfile.org/jquery/2.1.1/jquery.min.js~~

~~https://cdn.staticfile.org/twitter-bootstrap/3.3.7/js/bootstrap.min.js~~

new:

https://cdn.staticfile.org/twitter-bootstrap/3.3.7/css/bootstrap.min.css

https://cdn.staticfile.org/jquery/2.1.1/jquery.min.js

https://cdn.staticfile.org/twitter-bootstrap/3.3.7/js/bootstrap.min.js
