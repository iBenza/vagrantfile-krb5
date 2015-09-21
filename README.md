Start auth server with vagrant
==============================

```
$ vagrant up
```

Kerberos authentication test
============================

```
$ KRB5_CONFIG=krb5.conf kinit dog@TG2KRB5.COM
$ klist   # Show kerberos cache
```
