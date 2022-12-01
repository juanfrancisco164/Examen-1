# Examen-1

<H1> Parte 1 </H1>
Paso 1: Iniciamos con el comando git init. En mi caso, aparece que estoy reiniciandolo por los varios intentos que realicé anteriormente

![image](https://user-images.githubusercontent.com/114684233/205116521-2dbc358e-4bf0-4017-8f28-98359f5f07fe.png)


Paso 2: Seguimos con el comando status para comprobar el estado del repositorio local.
![image](https://user-images.githubusercontent.com/114684233/205108438-13e0f1b5-4b31-4831-8007-3c7edba323e8.png)

Paso 3: Ahora vamos a añadir un archivo al área de ensayo.
![image](https://user-images.githubusercontent.com/114684233/205109423-bb78d37a-d31d-4141-926a-c3c67cfd7056.png)

Paso 4: El archivo ahora estará en el área de ensayo, ahora vamos a hacer un commit.
![image](https://user-images.githubusercontent.com/114684233/205110342-16c84bf5-13cb-46a9-beff-f1d6669c1269.png)

Paso 5: Vamos a confirmar los cambios del ultimo commit y guardarlo en el repositorio main. En mi caso, no me funciona porque no ubica el main.
![image](https://user-images.githubusercontent.com/114684233/205117932-5bd02d1a-0ae5-4f53-a578-42783bc84042.png)

Paso 6:Para traer los cambios realizados en main o master a tu copia local. En mi caso, no me funciona porque no ubica el main.
![image](https://user-images.githubusercontent.com/114684233/205118349-090414e3-7d26-4ae7-b613-1f5a0d335647.png)

Paso 7: Si quiero volver al estado original de un archivo cuando todavia no se ha hecho add.
![image](https://user-images.githubusercontent.com/114684233/205116123-069845c4-28e7-4db4-a752-760a56e2ef02.png)

Paso 8: Si ya se ha hecho el add y quiero volver a una versión anterior.
![image](https://user-images.githubusercontent.com/114684233/205115750-306853f4-c0e6-41b0-a111-c14bf21d5e45.png)

Paso 9: El comando "git checkout hash-de-la-revisión -- nombre-de-archivo nombre-de-archivo" sirve para volver a una versión en concreta. Pero en mi caso no aparecen los hashes de revisión.


<H1> Parte 2 </H1>
Paso 1: Con este comando podemos mirar los distintos commits que hemos hecho.
![image](https://user-images.githubusercontent.com/114684233/205121738-f2277d7f-adae-4a00-8b40-5e6ee13b5ae2.png)


Paso 2: Ahora movemos el commit:
![image](https://user-images.githubusercontent.com/114684233/205122218-068d9d8d-decf-4587-aa17-90d130fb1a8d.png)

Paso 3:Ahora la movemos a la rama master.
![image](https://user-images.githubusercontent.com/114684233/205122434-cb540ae3-c794-497f-a2a3-eebbd0f6537f.png)


<H1> Parte 3 </H1>
<H2>Directorio de trabajo (Working directory)</H2>
El directorio de trabajo es la copia del proyecto ya existente. Esta copia del archivo se saca de la base de datos en el directorio Git y se mueve al equipo local.
<H2>Área de preparación (Staging area)</H2>
El área de preparación es un archivo que tiene la información para tu próxima confirmación.
<H2>Repositorio local (Directorio .git)</H2>
El repositorio local donde se almacena la información en el equipo local, no en GIT.
