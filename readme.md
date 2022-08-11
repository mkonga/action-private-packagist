# Mkonga / action-private-packagist

Installs your Private Packagist token globally for further use.

## Example configuration

```
steps:
  - uses: mkonga/action-private-packagist
    with:
      private-packagist-token: ${{ secrets.PACKAGIST_TOKEN }}
```

## Arguments

The argument is optional.

### private-packagist-token

This argument is optional.

If you need to install packages via Private Packagist, you can configure the parameter `private-packagist-token`, which will then be configured for Composer.
If you leave this out, nothing will be done.
