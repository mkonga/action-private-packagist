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

All arguments are optional

### private-packagist-token

This argument is optional.

If you need to install packages via Private Packagist, you can configure the parameter `private-packagist-token`, which will then be configured for Composer.
If you leave this out, nothing will be done.

### private-packagist-username

This argument is optional and should usually not be needed.

The default value is "token".

Most of the time the username you need to authenticate with will be "token", but in some cases you might need a specific username.
For these cases you can set a different username.