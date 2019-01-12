# ldapserver:18samba

## @edt ASIX M06-AS  curs 2018-2019

Servidor ldap de la dase de dades edt , que es conectara amb el servidor samba de 
altre continidor que fa servir un backend  **ldapsam** , i un hostpam que 
sera per veure que munta els homes de usuaris ldap y es conecta per via samba.

**sambanet** Una xarxa propia per als containers implicats.

### Configuració del server ldap

Per tal de que el servei ldap es comunique amb el server samba inclourem un esquema
de samba al ficher de configuració principal de ldap.

 * El esquema de samba.schema te una estructura global de la documentacio SAMBA. 

slapd.conf
```
include		/opt/docker/samba.schema

```

#### Execució

```
$ docker run --rm --name ldap -h ldap --net sambanet -d ldapserver:18samba
```


