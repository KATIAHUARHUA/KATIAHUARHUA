- 👋 Hi, I’m @KATIAHUARHUA
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
KATIAHUARHUA/KATIAHUARHUA is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import turtle

# Configuración de la pantalla
screen = turtle.Screen()
screen.bgcolor("white")

# Configuración de la tortuga
t = turtle.Turtle()
t.color("red")
t.speed(3)

# Función para dibujar el corazón
def draw_heart():
    t.begin_fill()
    t.left(50)
    t.forward(133)
    t.circle(50, 200)
    t.right(140)
    t.circle(50, 200)
    t.forward(133)
    t.end_fill()

# Llamada a la función
draw_heart()

# Mantener la ventana abierta hasta que se cierre
turtle.done()
