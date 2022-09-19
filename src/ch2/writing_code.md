# Writing Code

Now that we've got our project setup and open, let's write our first line of code. We'll print out a message saying hello to the world, a revolutionary action never-before-seen in mankind's existence.

```java
System.out.println("Hello, world!");
```

Woah! There's a lot here. What's System? What's out? What's their *connection?* We can guess that `println` might print something, but what exactly does it print? Surely just the text we gave it - right? Some of these questions and others might arise upon seeing this code. Throughout this book, we'll answer all of them, and more.

So - where to put this line of code? You might think the line that says `// TODO code application logic here` looks promising. And you'd be right.

Great! So now let's put the line of code in the line after the comment:

```java,editable
public class Main {
    public static void main(String[] args) {
       // TODO code application logic here
       System.out.println("Hello, world!");
    }
}
```

Awesome! We can try experimenting with the text inside the double quotes, replace it with your name, whatever text you want to try printing out. Next, let's see how to run our application!
