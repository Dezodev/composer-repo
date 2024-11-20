# Dezodev/composer-repo by Satis

This is a private Composer repository.

[View the repository](https://github.com/dezodev/composer-repo)

## Setting up this repository in your projects

To use it, you have to add this repository to your project's `composer.json` file, then you can require these private packages just like you would with one from [Packagist](https://packagist.org).

```json
{
  "repositories": [{
    "type": "composer",
    "url": "https://dezodev.github.io/composer-repo"
  }]
}
```