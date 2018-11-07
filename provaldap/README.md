# provaldap

##### Franlin colque : 

## @edt ASIX M06-ASO Curs 2018-2019

Servidor ldap amb mipractica.com, totes les dades de users per uid
Schema de dades propi on definim atributs i objectes

## schemas de indepeOrgPerson i llarenaAccount

Usant el concepte 'stand alone' creem el nostre propi schema 
indepeOrgPerson.schema i llarenaAccount.schema i per modificar dades modsocis.ldif

Attibuts de indeOrgPerson:

 * idcat(numeric)
 * sardenes( bolea)
 * foto
 * lema (text)
 * twiter (text)

Objecte:

 * indepeOrgPerson
El objecte no sera derivat de cap altre, bueno si de top.


Attibuts de llarenaAccount:

 * delictes (text)
 * anyscomdemma( numeric)
 * galeres (bolea)

Objecte:

 * llaurenaAccount

El objecte es de tipus auxiliar


