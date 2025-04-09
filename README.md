# Iris

Iris is a tiny bit of shared message and file convention that pretends to be forum software.

It is a fully usable message system, designed for use between different users on a single server.

Iris is strictly text-based, requiring no GUI, database, or web servers.

## How to use this Makejail

Because Iris is a completely offline forum software, so you can avoid network configuration. Just keep in mind that you will have to create a user manually and how your users can access is up to you.

```sh
appjail makejail \
    -j iris \
    -f gh+AppJail-makejails/iris \
    -o alias \
    -o ip4_disable \
    -o ip6_disable
```

### Arguments

* `iris_ajspec` (default: `gh+AppJail-makejails/iris`): Entry point where the `appjail-ajspec(5)` file is located.
* `iris_tag` (default: `13.5`): see [#tags](#tags).

## Tags

| Tag           | Arch    | Version            | Type   |
| ------------- | --------| ------------------ | ------ |
| `13.5`    | `amd64` | `13.5-RELEASE` | `thin` |
| `14.2`    | `amd64` | `14.2-RELEASE` | `thin` |
