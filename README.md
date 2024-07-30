# Shell Colors

Give colored output to your python programs or print simple formatted text in into the shell.

### Usage

There are several available methods to be called in order to format your texts.

if you print a string:

    print("Hello World!")

Output will be: 

    Hello World!


you can make the text bold, italic or underlined with the corresponding method

    import ShellColors

    print(bold("This is bold"))
    print(italic("This is italic"))

Output:

**This is bold**

_This is Italic_


or you can make a text colored

    print(cyan("Hello World!"))
    print(red("Hello World!"))

Output:

<span style="color:lightblue">Hello World!</span>.

<span style="color:red">Hello World!</span>.

### Available methods

    bold(string)
    underline(string)
    yellow(string)
    red(string)
    cyan(string)
    magenta(string)
    blue(string)
    gray(string)
    italic(string)
    pink(string)
