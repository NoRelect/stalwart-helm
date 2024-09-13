# Stalwart Helm Chart

A helm chart to deploy the stalwart mail server.

## Admin credential hash

To create the admin credential hash, use the following command:

```sh
openssl passwd -6
```

> Important: Be sure to escape any `$` with `$$` if you use it in a yaml file!
