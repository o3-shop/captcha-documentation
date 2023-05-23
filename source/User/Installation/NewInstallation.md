# New installation

Open a terminal window and navigate to the main store directory.

Install the module executing the Composer command:

```
composer require o3-shop/simple-captcha:^1.0
```

```{note}
Dependent on your server configuration you have to adjust the composer command. Please check your hosting support for details.
```

Activate the module executing the command:

```
vendor/bin/oe-console oe:module:activate o3-captcha
```

Alternatively you can activate the module in the Shop Admin at *Extensions -> Modules*. Select the module and activate it in the tab *Overview*.

```{note}
Every time the module is activated or deactivated the module does empty the files in the shop's tmp directory.
```
