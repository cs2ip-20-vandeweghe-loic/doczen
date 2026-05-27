---
icon: lucide/heading-1
title: Code
---

# Code

## Online code

**Online code** is defined by a simple backstick : `

=== "Code"

    ```markdown
    In linux the command line `ls -la` show what inside a dir.
    ```

=== ":right_arrow: Result"

    In linux the command line `ls -la` show what inside a dir.

## Code listing

Code source listing are created with a triple backsticks

=== "Code"

    ````
    ```Javascript
    function hello(){
        console.log("Hello World!");
    }
    ```

    ```C#
    void hello(string who) {
        Console.WriteLine("Hello " + who);
    }
    ```

    ````

=== ":right_arrow: Result"

    ```Javascript
    function hello(){
        console.log("Hello World!");
    }
    ```
    ``` C#
    void hello(string who) {
        Console.WriteLine("Hello " + who);
    }
    ```
