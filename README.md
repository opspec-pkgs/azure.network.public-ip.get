# problem statement
gets a public ip from azure network resource

# example usage

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
run:
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
