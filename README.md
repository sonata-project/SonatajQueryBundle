
Add the jQuery framework inside the Symfony2 framework.



### Installation

Use composer to install SonatajQueryBundle:

```bash
php composer.phar require sonata-project/jquery-bundle
```

If asked for a version, type in 'dev-master' (unless you want another version):

```bash
Please provide a version constraint for the sonata-project/jquery-bundle requirement: dev-master
```

After, just register the bundle in your app/AppKernel.php file:

``` php
<?php
// app/AppKernel.php

public function registerBundles()
{
    $bundles = array(
        // ...
        new Sonata\jQueryBundle\SonatajQueryBundle(),
    );
    // ...
}
```


### Usage

``` html
<script src="{{ asset('bundles/sonatajquery/jquery-1.8.3.js') }}" type="text/javascript"></script>
```