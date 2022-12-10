### Hi  👋
# Cool!! Welcome to my Readme profile items :tada::tada::tada:


<div style="display: flex">
  
<img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white"/>
   
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>

<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>

<img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E"/>

<img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=linux&logoColor=white"/>
  
</div>


<br>
<br>
<br>

## logos:
<p align="center">
  <img src="https://media3.giphy.com/media/ln7z2eWriiQAllfVcn/200w.webp" width="100"><img src="https://i.giphy.com/media/LMt9638dO8dftAjtco/200.webp" width="100"><img src="https://i.giphy.com/media/eNAsjO55tPbgaor7ma/200w.webp" width="100"><img src="https://i.giphy.com/media/VgGthkhUvGgOit7Y9i/200.webp" width="100"><img src="https://media3.giphy.com/media/kdFc8fubgS31b8DsVu/giphy.webp" width="100"><img src="https://i.giphy.com/media/KzJkzjggfGN5Py6nkT/200.webp" width="100"><img src="https://i.giphy.com/media/IdyAQJVN2kVPNUrojM/200.webp" width="100">
</p>
<br>
<br>   

# Python :tada:

<summary>:eyes: Python Example </summary>
<br>


``` 
import datetime

def name():
    name = input("What is your name?")  #ask the user for his name
    surname = input("What is your surname?") #ask the user for his surname
    print ("My name is" + " " + name + " " + surname) #print the name and surname
    
def address():
    address = input("Where do you live?") #ask the user for his address
    print ("I live in" + " " + address) #print the address

def college():
    college = input("Where do you study?") #ask the user for his college
    print ("I study in" + " " + college) #print the college
    
def course():
    course = input("What course are you doing?") #ask the user for his course
    print ("I am doing a" + " " + course) #print the course

def date_time():
    print(datetime.datetime.now()) #print the date and time

if __name__ == '__main__':
    name()
    address()
    college()
    course()
    date_time()
```
<br>
<br>   

![Dam2998 GitHub stats](https://github-readme-stats.vercel.app/api?username=Dm2998&theme=radical&show_icons=true)

<br>
<br>   

![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=Dm2998&repo=github-readme-stats)

<br>
<br>

# JavaScript :tada:


<summary>:eyes: Example of JavaScript. </summary>
<br>
<br>   

```
function add(a, b) {                   // add() function adds two numbers and returns the sum.
    console.log(a + b);
    print("the sum is: " + a + b + "!");
  return a + b;
}

function subtract(a, b) {                // subtract() function subtracts two numbers and returns the difference.
    console.log(a - b);
    print("the difference is: " + a - b + "!");
    return a - b;
    }

function multiply(a, b) {                  // multiply() function multiplies two numbers and returns the product.
    console.log(a * b);
    print("the product is: " + a * b + "!");
  return a * b;
}   

function divide(a, b) {                      // divide() function divides two numbers and returns the quotient.                                             
    console.log(a / b);
    print("the quotient is: " + a / b + "!");
    return a / b;
    }

function increment(n) {                       // increment() function increments a number by 1.
    console.log(n += 1);
    print("the number is: " + n += 1 + "!");
    return n += 1;
    }

function decrement(n) {                       // decrement() function decrements a number by 1.
    console.log(n -= 1);
    print("the number is: " + n -= 1 + "!");
    return n -= 1;
    }

function makeInt(n) {                       // makeInt() function parses a string and returns an integer.
    console.log(parseInt(n, 10));
    print("the number is: " + parseInt(n, 10) + "!");
    return parseInt(n, 10);
    }

function preserveDecimal(n) {                 // preserveDecimal() function parses a string and returns a floating point number.
    print("the number is: " + parseFloat(n) + "!");
    return parseFloat(n);
    }



```





<br>
<br>


## dino gif:
 <img align="center" src="https://github.com/saadeghi/saadeghi/blob/master/dino.gif" />
<br>
<br> 

<br>
<br>   


# Turtle Python :tada:

<summary>:eyes: Example of Trigonometry with Turtle Python. </summary>

<br>
<br>  

```
import turtle

def draw_circle(turtle, color, size, x, y): #draw circle
    turtle.color(color)
    turtle.pensize(size)
    turtle.penup()
    turtle.goto(x, y)
    turtle.pendown()
    turtle.circle(size)
    turtle.end_fill()
    
def draw_triangle(turtle, color, size, x, y): #draw triangle
    turtle.color(color)
    turtle.pensize(size)
    turtle.penup()
    turtle.goto(x, y)      #x and y are the coordinates
    turtle.pendown()
    turtle.begin_fill()
    for i in range(3):        
        turtle.forward(100)
        turtle.right(120)
    turtle.end_fill()
    turtle.setheading(0)
    
def draw_square(turtle, color, size, x, y): #draw square
    turtle.color(color)
    turtle.pensize(size)
    turtle.penup()
    turtle.goto(x, y)
    turtle.pendown()
    turtle.begin_fill()
    for i in range(4):      #for loop to draw square
        turtle.forward(size * 2)   # size * 2 to make it bigger
        turtle.forward(100)     # 100 to make it bigger
        turtle.right(90)         # right 90 degrees
    turtle.end_fill()      #end fill
    turtle.setheading(0)

def draw_star(turtle, color, size, x, y): #draw star
    turtle.color(color)
    turtle.pensize(size)
    turtle.penup()
    turtle.goto(x, y)
    turtle.pendown()
    turtle.begin_fill()
    for i in range(5):          # for loop to draw star
        turtle.forward(size * 2)    
        turtle.forward(100)
        turtle.forward(size * 2)   # size * 2 to make it bigger
        turtle.right(144)
    turtle.end_fill()
    turtle.setheading(0)

def draw_spiral(turtle, color, size, x, y): #draw spiral
    turtle.color(color)
    turtle.pensize(size)
    turtle.penup()
    turtle.goto(x, y)
    turtle.pendown()
    turtle.begin_fill()
    for i in range(50):         # for loop to draw spiral
        turtle.forward(size * 2)
        turtle.forward(100)
        turtle.forward(size * 2)
        turtle.right(144)
    turtle.end_fill()
    turtle.setheading(0)

def draw_art(): #draw art final
    window = turtle.Screen()
    window.bgcolor("red")
    tri = turtle.Turtle()
    tri.shape("arrow")
    tri.color("green")
    draw_triangle(tri, "green", 100, 0, 0)  #draw triangle
    draw_square(tri, "green", 100, 0, 0)    #draw square
    draw_circle(tri, "green", 100, 0, 0)     #draw circle
    draw_star(tri, "green", 100, 0, 0)       #draw star
    draw_spiral(tri, "green", 100, 0, 0)     #draw spiral
    window.exitonclick()             #exit on click
```


<br>
<br>   


## :sparkling_heart: Contributions are welcome!



<br>
<br>   

<!--
**Dm2998/Dm2998** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
