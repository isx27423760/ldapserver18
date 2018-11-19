# ldapserver:18group

## @edt ASIX M06-AS = curs 2018-2019

Servidor ldap amb edt.org totes les dades per uid i es
conectara amb el client que configurem amb pam


#### Execució

```
$ docker run --rm --name ldap -h ldap --net ldapnet -d edtasixm06/ldapserver:18group
```

