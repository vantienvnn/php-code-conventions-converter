Automatic correct code conventions with PHP_CodeSniffer
=====================

Install PHP_CodeSniffer via PEAR

```php
pear install PHP_CodeSniffer
```

if have error for pear path

```php
pear config-set doc_dir C:\xampp\php\pear\docs
pear config-set cfg_dir C:\xampp\php\pear\cfg
pear config-set data_dir C:\xampp\php\pear\data
pear config-set cache_dir C:\xampp\php\pear\cache
pear config-set download_dir C:\xampp\php\pear\download
pear config-set temp_dir C:\xampp\php\pear\temp
pear config-set test_dir C:\xampp\php\pear\tests
pear config-set www_dir C:\xampp\php\pear\www
```

How to use:

- Convert all files in a path
```php
   // follow custom rule
   phpcbf --standard=phpcs.xml /path/to/you/project
   
   // follow PSR2
   phpcbf --standard=PSR2 /path/to/you/project
```

- Convert a file
```php
   phpcbf --standard=phpcs.xml /path/to/you/file.txt
```
