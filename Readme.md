# Ucenter PHP7

[![Total Downloads](https://poser.pugx.org/laravel/framework/d/total.svg)](https://github.com/jinsoft/UcenterPro)
[![License](https://poser.pugx.org/laravel/framework/license.svg)](https://github.com/jinsoft/UcenterPro)


## 改动

### /install/index.php

 *  12    ```ini_set('set_magic_quotes_runtime',0);```
 
 *  43   删除 短标签判断
 
 
 
###   更改所有的mysql 成mysqli

*  ```/api/dbbak.php```
*   
 
 
 
 
 
 
 
 
 
 
 
 ### /install/var.inc.php
 
 * 72 
```
 $func_items = array('mysqli_connect', 'gethostbyname', 'file_get_contents', 'xml_parser_create');

```


### /model/base.php

* 95  ``` require_once UC_ROOT.'lib/dbi.class.php'; ```