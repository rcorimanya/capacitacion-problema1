## **Que es integracion continua?**

La integración continua es un modelo informático propuesto inicialmente por 
Martin Fowler que consiste en hacer integraciones automáticas de un proyecto lo más a menudo posible para así poder detectar fallos 
cuanto antes. Entendemos por integración la compilación y ejecución de pruebas de todo un proyecto


## **Para que  sirve DevOps?**

DevOps nos dio ventaja. ... DevOps es un conjunto de prácticas que automatizan los procesos entre los equipos de desarrollo de software y TI 
para que puedan compilar, probar y publicar software con mayor rapidez y fiabilidad

# ** PREGUNTAS PARTE 2 **

## **1. ¿Para qué ayuda el `git stash`?**
Este comando de guardado rápido (stashing) toma el estado del espacio de trabajo, con todas las modificaciones en los archivos bajo control de cambios, 
y lo guarda en una pila provisional. 
Desde allí, se podrán recuperar posteriormente y volverlas a aplicar de nuevo sobre el espacio de trabajo.

## **2. ¿Cuál es la diferencia entre `git stash pop` y `git stash apply`?**
git stash popaplica el elemento escondido superior y lo elimina de la pila. git stash applyhace lo mismo, pero lo deja en la pila de alijo.

## **3. ¿Qué significa el modo interactivo del `git rebase`?**

git rebase -i HEAD~2
-i significa "modo interactivo", por lo que va a abrir tu editor de texto configurado (vim o nano) y va a editar todos los commits hasta HEAD~2 (HEAD es "el último", HEAD~2 es "el último menos 2", por lo que en el dibujo sería el commit 2).

Cuando hacés esto, vas a ver algo así:

## **4. ¿Cual es la diferencia entre la shell y la terminal?**

La Shell, la terminal y la consola - ¿En qué se diferencian?
Cualquier usuario que haya tratado de realizar configuraciones avanzadas a su computadora con Windows u OS X, ha tenido contacto con la interfaz de línea de 
comandos. ¿Cómo se llama esto? ¿Shell?, ¿Consola?, ¿Terminal? ¿A quién le importa? Al final significan lo mismo, ¿Verdad? La respuesta es sí y no. 
Al igual que el router inalámbrico, estos términos solían (y técnicamente lo siguen siendo) ser diferentes, a pesar de que las palabras pueden compartir su significado.

¿Qué es una terminal?
Para entender lo que es un terminal, tenemos que volver a los días de los mainframe. Las computadoras centrales eran ordenadores con muchos usuarios. Eran comunes en las grandes empresas y en los campus universitarios. Pero cuando se tiene decenas de personas que desean utilizar un ordenador al mismo tiempo, ¿cómo hacer para compartirlo? En palabras actuales, queremos dar a cada usuario un monitor, un teclado y un mouse. En la era de las mainframe se utilizaron terminales. Un “terminal”, según la definición de los diccionarios, es o bien el final de algo o un punto de contacto, a veces ambos. Las computadoras centrales tenían estaciones terminales equipadas con una pantalla y un teclado. Esto para que los usuario pudieran acceder a las mainframe.

¿Qué es una consola?
Hoy en día, las consolas pueden ser completamente en software, pero no siempre fue el caso. Las consolas van de la mano con las terminales. Con respecto a un mainframe, una consola era a la vez el puerto y la conexión digital a la unidad central del sistema operativo de la terminal. Una definición más amplia de una consola es un escritorio o la interfaz desde la que un sistema se controla y/o monitorea. La terminal se conecta físicamente al puerto de la consola en la unidad central de manera que el usuario puede controlar la mainframe. En un sistema Linux puedes pulsar <ctrl> + <alt> + <F1 | F2 | F3 | ...> Para acceder a las diferentes consolas. Muchos sistemas todavía tienen puertos de consola basada en administración, tales como equipos de red profesional.

¿Qué es una Shell?
El nombre Shell puede sonar divertido, pero “Kernel” puede ser aún más divertido. La Shell es la pieza que envuelve al kernel. En las computadoras no hay diferencia. La shell es la interfaz de línea de comandos con la que interactúas. Los ejemplos de Shell son BASH, CSH, y ZSH. La cáscara toma comandos escritos a mano y le dice al sistema operativo que debe ejecutarlos, o puede tomar secuencias de comandos e interpretar la lógica dentro de ellos, además da instrucciones al sistema operativo para ejecutar los comandos contenidos en el script.

Shell vs Console vs Terminal
Así que, ¿cuál es la diferencia real entre la Shell, la consola y la terminal? La terminal se conecta a la consola en donde se puede utilizar la Shell. Es bastante simple, ¿no crees?
Con el tiempo, muchas palabras en la tecnología han sido víctimas de generalización, que tiende a ocultar una rica y aventurera historia de innovación y evolución.

## **5. ¿Que hace estos comandos? **
### **git clone:** Clona un repositorio dentro la carpeta actual  local.
### **git status:** Muestra el estado del árbol de trabajo
### **git add:** Agrega contenido de archivos al índice
### **git commit:** Registra los cambios en el repositorio
### **git push:**	Actualizar referencias remotas junto con objetos asociados
### **git checkout:**	Cambiar ramas o restaurar archivos de árbol de trabajo
### **git stash:**	 oculta los cambios en un directorio de trabajo sucio
### **git rebase:**	vuelva a aplicar confirmaciones en la parte superior de otro consejo básico
### **git merge:**	 une dos o más historiales de desarrollo juntos
### **git branch:**	Listar, crear o borrar ramas

	
	


