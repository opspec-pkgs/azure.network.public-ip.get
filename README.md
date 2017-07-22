# Problem statement
gets the public ip of an azure network resource

# Example usage

> note: in examples, VERSION represents a version of the azure.network.public-ip.get pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/azure.network.public-ip.get.get#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/azure.network.public-ip.get.get#VERSION
```

## compose

```yaml
op:
  pkg: { ref: github.com/opspec-pkgs/azure.network.public-ip.get#VERSION }
  inputs:
    subscriptionId:
    loginId:
    loginSecret:
    name:
    resourceGroup:
    # end optional args
    loginTenantId:
    loginType:
    # end optional args
  outputs:
    value:
```

# Support

join us on [![Slack](https://opspec-slackin.herokuapp.com/badge.svg)](https://opspec-slackin.herokuapp.com/)
or [open an issue](https://github.com/opspec-pkgs/azure.network.public-ip.get/issues)
