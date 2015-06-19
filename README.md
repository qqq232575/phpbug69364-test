# php-bug-69364-test
CVE 2015-4024 , bug #69364 PHP Multipart/form-data remote dos Vulnerability
WARNING: USE THIS TOOL AT YOUR OWN RISK 
注意：此工具造成的任何后果由使用者自行承担

原理:http://drops.wooyun.org/papers/6077
官方：https://bugs.php.net/bug.php?id=69364

Usage: python xxx.py -t "http://TARGET_URL" -x "THREAD" -r "REQUEST_LENGTH"

Example: python xxx.py -t "http://your.site.using.php/" -x "100" -r "350000"
