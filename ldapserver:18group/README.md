# ldapserver:18group

## @edt ASIX M06-AS = curs 2018-2019

Servidor ldap amb edt.org totes les dades per uid i es
conectara amb el client que configurem amb pam


#### Execució

* Si fem servir per muntar els homes samba , fem servir la xarxa sambanet

```
$ docker run --rm --name ldap -h ldap --net sambanet -d francs2/ldapserver:18group
```

* o 

```
$ docker run --rm --name ldap -h ldap --net ldapnet -d francs2/ldapserver:18group
```


