# Llanfair

##  **[> Hey! English Version here](https://github.com/rudahee/Llanfair/blob/master/readme-eng.MD)**


<br>

# Indice 📋
1. Descarga y Ejecucion
2. Registro de cambios
3. ¡Forkeame!
4. Mejoras y sugerencias
5. Nota final


---

## **Descarga y Ejecucion🔧📦**

> **Es compatible para todos los sistemas operativos y equipos que puedan instalar Java 8 o superior**

### **Descarga**
Para realizar la descarga dirigete a [la pagina de releases](https://github.com/rudahee/Llanfair/releases) y en la seccion de assets de la ultima version disponible veras un archivo llamado `llanfair-v.XXXX.jar`.

Cuando le hagas click se descargara automaticamente.

_Si no quieres ir a ver cada vez a la pagina de releases, hay un pequeño atajo a la derecha con la ultima version disponible_

### **Ejecucion**

Para ejecutar la aplicacion solo debes hacerle doble click o ejecutar desde un terminal lo siguiente:
```java
java -jar llanfair-XXXX
```

Si en plataformas *nix no funciona con doble click debeis darle permisos de ejecucion. _[esto quizas ayude](https://wiki.debian.org/Permissions)_

_Es importante entender que esto es una aplicacion JAVA, por tanto no existe una forma de instalarlo, solo ponlo donde lo quieras tener_

---

## **Registro de cambios ✒️**

- ## Version 1.5.5:
  - **Se ha cambiado el funcionamiento del Split.** 
    - Cuando ahora tenemeos una run con distintos splits, y pulsamos la tecla de cambio de split, el timer no se pausa, como solia pasar en la anterior version.
  - **Se ha arreglado un bug con la carga de runs.**
    - Ahora los milisegundos del delay no se vuelven a 0 despues de cada run o al cargar un nuevo run.
  - **Se ha arreglado una serie de bugs con la seleccion del World Record**
    - Las peticiones a Speedrun.com ya funcionan bien, aunque la interfaz sigue siendo deficiente.
  - **Se han actualizado las dependencias**
    - Se evita provocar ciertas vulnerabilidades.

- ## Version 1.5.4.1
  - **Todo el proyecto se ha portado a Maven**
  - **Se han agregado una cantidad importante de fallos en el codigo**

- ## Version 1.5.4
  - **Se ha forkeado el proyecto de gered**

---
## **¡Forkeame! 🛠️**

Te animo a seguir desarrollando este proyecto por tu cuenta.

Necesitas:
- Java 8 o superior
- Eclipse o cualquier otro editor
- Maven
- Git

Para realizar tus propias builds sigue estos pasos:
```
$ mvn clean
$ mvn build
$ mvn package
```

Se genera un archivo en `llanfair/target` llamado: 
- llanfair-XXXX-jar-with-dependencies.jar
----

## **Mejoras y sugerencias :arrow_up:**

- **Por ahora está vacia**

_En algun momento futuro, tocare la interfaz de usuario_

---
## **Nota Final**

El proyecto no es mio, yo hice el [fork de aqui](https://github.com/gered/Llanfair), pero gered tiene el proyecto inactivo y no lo esta manteniendo.

Pero sorpresa, el autor original es Xavier "Xunkar" Sencert.

Podeis encontrar el[repositorio de gered aqui](https://github.com/gered/Llanfair), o su [antiguo readme aqui.](https://github.com/rudahee/Llanfair/blob/master/old_README.md)

