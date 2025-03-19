# Amg-Sec
Un programa que escoge entre una lista de nombres a uno de manera aleatoria 

Aquí está la traducción al español:

<page>
readme Último commit Historia readme Metadatos y controles del archivo
</page>

# Amigo Secreto - Proyecto en JavaScript

## **Descripción del Proyecto**
Este proyecto es un sorteo de amigo secreto desarrollado en JavaScript. El objetivo principal es aplicar conceptos de lógica de programación, como el uso de variables, arrays, funciones y manipulación del DOM, para crear una aplicación interactiva donde los usuarios puedan:

1. Agregar nombres de los participantes.
2. Sortear un amigo secreto al azar entre los participantes.
3. Mostrar el resultado del sorteo en la interfaz.

El HTML y el CSS ya están preparados, lo que permite que el enfoque esté en la lógica en JavaScript.

---

## **Funcionalidades**

1. **Agregar Participantes:** Los nombres se agregan a un array a través de un campo de entrada.
2. **Sorteo del Amigo Secreto:** Un participante se sortea al azar.
3. **Mostrar el Resultado:** El nombre del participante sorteado se muestra en la interfaz.

---

## **Cómo Usar el Proyecto**

### **Paso 1:** Abrir el archivo HTML en el navegador
Abre el archivo `index.html` en el navegador para ver la interfaz de la aplicación.

### **Paso 2:** Agregar participantes
Escribe los nombres de los participantes en el campo de entrada y haz clic en el botón "Agregar". Cada nombre se almacenará en la lista interna del programa.

### **Paso 3:** Realizar el sorteo
Haz clic en el botón "Sortear" para sortear aleatoriamente a uno de los participantes. El nombre sorteado se mostrará en la pantalla.

---

## **Explicación Técnica**

El código JavaScript tiene las siguientes funciones principales:

### **Funciones Principales**
1. `adicionarAmigo()`
   - Agrega el nombre del participante al array `participantes`.
   - Incrementa el contador de nombres registrados.

2. `limparCampo()`
   - Limpia el campo de entrada de texto después de agregar un nombre.

3. `sortearAmigo()`
   - Realiza la lógica del sorteo y llama a la función `finJuego()` para mostrar el resultado.

4. `finJuego()`
   - Sortea aleatoriamente a un participante del array y muestra el resultado en la interfaz.
