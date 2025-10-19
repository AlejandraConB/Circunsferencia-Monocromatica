## 🖥️ Tecnologías Utilizadas:

- Python.
- Turtle.
- Visual Studio Code.
</br></br>
Este proyecto utiliza el módulo turtle de Python para crear un patrón visual de espiral circular. Turtle dibuja una serie de círculos cada vez más grandes, girando ligeramente en cada paso, lo que genera un efecto de espiral helicoidal.
<img align="center" src="https://github.com/AlejandraConB/Images/blob/main/Circunsferencia_monocrom%C3%A1tica.png" height="200" alt="Circunsferencia monocromática">
</br>

## 📦 Requisitos:

- Tener instalado la versión más actualizada de Python.
- Tener instalado Visual Studio Code.
</br></br>

## ▶️ Cómo ejecutar el código

- Guarda el código en un archivo, por ejemplo: spiral_turtle.py.
- Abre una terminal o consola.
- Navega hasta la carpeta donde guardaste el archivo.
- Ejecuta el programa con el siguiente comando: python spiral_turtle.py
Al hacer clic en la ventana del dibujo, esta se cerrará.
</br></br>

## 📝 Explicación del código

- import turtle: Importa el módulo Turtle para gráficos.
- t = turtle.Pen(): Crea una tortuga lista para dibujar.
- for x in range(100): Repite el dibujo 100 veces, con x aumentando de 0 a 99.
- t.circle(x): Dibuja un círculo cuyo radio es el valor actual de x.
- t.left(91): Gira la tortuga 91 grados a la izquierda (el ángulo impar crea el efecto de espiral).
- turtle.exitonclick(): Cierra la ventana al hacer clic dentro de ella.
</br></br>

💙 <strong>Alejandra Contreras</strong></br></br>
<a href="https://www.linkedin.com/in/alejandraconb-dev/" target="_blank">
<img img align="left" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
<img img align="center" src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Relieved%20Face.png" target="_blank" height="40"></a>

<!-- 
- Cambiar el color de fondo: turtle.bgcolor("black")
- Cambiar el color de la pluma: t.pencolor("blue")
- Ajustar la velocidad: t.speed(0) (0 = más rápido) -->
