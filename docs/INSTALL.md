# EdgarEzBundleGeneratorBundle

## Installation

### Get the bundle using composer

Add EdgarEzBundleGeneratorBundle by running this command from the terminal at the root of
your symfony project:

```bash
composer require edgar/ez-bundlegenerator-bundle
```

## Enable the bundle

To start using the bundle, register the bundle in your application's kernel class:

```php
// app/AppKernel.php
public function registerBundles()
{
    $bundles = array(
        // ...
        new Edgar\EzBundleGeneratorBundle\EdgarEzBundleGeneratorBundle(),
        // ...
    );
}
```
