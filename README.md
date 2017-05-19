# problem statement
copies a dir from s3 to s3

# example usage

> note: in examples, VERSION represents a version of the aws.s3.cp-dir pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/aws.s3.cp-dir#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/aws.s3.cp-dir#VERSION
```

## compose

```yaml
run:
  op:
    pkg: { ref: github.com/opspec-pkgs/aws.s3.cp-dir#VERSION }
    inputs: { srcS3URI, dstS3URI, AWS_ACCESS_KEY_ID, AWS_SECRET_ACCESS_KEY, AWS_DEFAULT_REGION }
```

