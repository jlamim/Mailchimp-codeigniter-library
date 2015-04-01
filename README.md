# Mailchimp library to CodeIgniter

This library use the Mailchimp API 2.0, and have compatibility with CodeIgniter 2.x and 3.x.

##Installing

Copy the files to their respective directories, as listed below:

>config/mailchimp.php
>
>libraries/Mailchimp.php
>
>libraries/Mailchimp (copy the directory)

After copy files, get the API KEY in your Mailchimp Panel, and paste in mailchimp config file, set also if debug option is true or false.

```php
$config['mc_apikey'] = "xxxxxxxxxxx";
```

To load Mailchimp library automatically, add the library name in config/autoload file:

```php
$autoload['libraries'] = array("Mailchimp");
```

Set also the autoload to the mailchimp config file:

```php
$autoload['config'] = array('mailchimp');
```

##Examples

Comming soon
