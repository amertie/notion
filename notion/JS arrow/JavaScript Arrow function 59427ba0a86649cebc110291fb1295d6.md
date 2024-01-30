# JavaScript Arrow function

The syntax of the *function declaration* and *function expression* looks very similar, but they differ in the way they are evaluated, check out the following example:

**Example**

```jsx
declaration(); // Outputs: Hi, I'm a function declaration!
function declaration() {
    alert("Hi, I'm a function declaration!");
}

expression(); // Uncaught TypeError: undefined is not a function
let expression = function() {
    alert("Hi, I'm a function expression!");
};
```

It gets shorter! If the function has only one statement, and the statement returns a value, you can remove the brackets *and* the `return` keyword:

# Arrow Functions Return Value by Default

```html
hello = () => "Hello World!";
```

If you have parameters, you pass them inside the parentheses:

# Arrow Function With Parameters:

```html
hello = (val) => "Hello " + val;
```

# What About this?

The handling of `this` is also different in arrow functions compared to regular functions.

In short, with arrow functions there are no binding of `this`.

In regular functions the `this` keyword represented the object that called the function, which could be the window, the document, a button or whatever.

With arrow functions the `this` keyword *always* represents the object that defined the arrow function.

Let us take a look at two examples to understand the difference.

Both examples call a method twice, first when the page loads, and once again when the user clicks a button.

The first example uses a regular function, and the second example uses an arrow function.

The result shows that the first example returns two different objects (window and button), and the second example returns the window object twice, because the window object is the "owner" of the function.

# Example

With a regular function `this` represents the object that *calls* the function:

```html
// Regular Function:hello = function() {  document.getElementById("demo").innerHTML += this;}
// The window object calls the function:window.addEventListener("load", hello);
// A button object calls the function:document.getElementById("btn").addEventListener("click", hello);
```

# Example

With an arrow function `this` represents the *owner* of the function:

```html
// Arrow Function:
hello = () => {
  document.getElementById("demo").innerHTML += this;
}

// The window object calls the function:
window.addEventListener("load", hello);

// A button object calls the function:
document.getElementById("btn").addEventListener("click", hello);
```

The syntax of the *function declaration* and *function expression* looks very similar, but they differ in the way they are evaluated, check out the following example:

**Example**

```jsx
declaration(); // Outputs: Hi, I'm a function declaration!
function declaration() {
    alert("Hi, I'm a function declaration!");
}

expression(); // Uncaught TypeError: undefined is not a function
let expression = function() {
    alert("Hi, I'm a function expression!");
};
```

It gets shorter! If the function has only one statement, and the statement returns a value, you can remove the brackets *and* the `return` keyword:

# Arrow Functions Return Value by Default

```html
hello = () => "Hello World!";
```

If you have parameters, you pass them inside the parentheses:

# Arrow Function With Parameters:

```html
hello = (val) => "Hello " + val;
```

# What About this?

The handling of `this` is also different in arrow functions compared to regular functions.

In short, with arrow functions there are no binding of `this`.

In regular functions the `this` keyword represented the object that called the function, which could be the window, the document, a button or whatever.

With arrow functions the `this` keyword *always* represents the object that defined the arrow function.

Let us take a look at two examples to understand the difference.

Both examples call a method twice, first when the page loads, and once again when the user clicks a button.

The first example uses a regular function, and the second example uses an arrow function.

The result shows that the first example returns two different objects (window and button), and the second example returns the window object twice, because the window object is the "owner" of the function.

# Example

With a regular function `this` represents the object that *calls* the function:

```html
// Regular Function:hello = function() {  document.getElementById("demo").innerHTML += this;}
// The window object calls the function:window.addEventListener("load", hello);
// A button object calls the function:document.getElementById("btn").addEventListener("click", hello);
```

# Example

With an arrow function `this` represents the *owner* of the function:

```html
// Arrow Function:
hello = () => {
  document.getElementById("demo").innerHTML += this;
}

// The window object calls the function:
window.addEventListener("load", hello);

// A button object calls the function:
document.getElementById("btn").addEventListener("click", hello);
```

```python

def greet():
    print('hello')
      
def greet_with_name(name, age, last_name = 'kebede'):
    print(f'hello {name} age:{age} last name:{last_name}')
   
greet()
greet_with_name('hanna') 

greet()
greet_with_name('hanna', age = 56)

# assignment 1. data scrapping (that uses local websites)  
# 2. telegram bot (that fetches data/ qoutes from an api and and send it through the bot)
# positional argument 
# keyword arguments
# default arguments
#string formatting using f string 

greet()
greet_with_name('hanna', 'kebede')

greet()
greet_with_name('numbers')
```

###