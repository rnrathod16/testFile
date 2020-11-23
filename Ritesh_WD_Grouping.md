# ***Hello Everyone , Welcome*** 

:smile:

# **I am ***Ritesh Rathod*****
## My Social Handel 

<br>

## Topic :- So Here we will be taking an overview of ***Grouping*** and ***Universal Selector***

<br>

# ***Grouping*** 

- So we use Grouping when we have to set same style for different elements
- we can group all the selectors and can write styling code for all at once
- It can be grouping of different classes or Tags or all together
- It reduces time requried to set the style 
- It reduces the Code redundancy
- With the use of grouping the code becomes Concise
- With grouping it is easy to debug the code in case of Error

<br>

**For ex :-**

If we have code like this

```css
h1{
    color:green;
}

.text{
    color:green;
}

h2{
    color:green;
}
```
In this we can see that we have to change the color of 3 different elements to green so why to write the code for all the elements seperately simply we can do this by Grouping

To group them together we have to write all of them seperated by Comma

This is simplified code

```css
h1, .text, h2{
    color:green;
}
```
It will work as  same as written above just to reduce the code we can write it in this format also

There is no condition for how the elements should be grouped we can group all the classes , ID's and tags all together


**[Ritesh_Code](D:\Open_Source\Ritesh_WD_Grouping_code.md)
You can check the code in here**


<br>
<br>
<br>

# ***Universal Selector*** 

- Universal Selector is used to select all the type of elements
- Universal Selector can be used to set same value to the elements 
- An Asterisk **(*)** is used to denote the Universal Selector
- The Universal Selctor is Capable of Selecting all the elements inside another elements also
- It is like an Wildcard which matches all the elements

<br>

**For ex :-**

If we want to set the color for all the elements to blue so writing code for all elements will not be an good idea so in this case we can make use of Universal Selector.

we can write it like this

```css
* {
    color:blue;
}
```

It will Select all the elements and will change their text color to blue.

<br>

**[Ritesh_Code](D:\Open_Source\Ritesh_WD_Grouping_code.md)
You can check the code in here**

<br>

We can also select all the div tags and color all the elements inside it using the Universal Selector 

**For ex :-**

```css
div *{
    color:white;
    background-color:black;
}
```
This will change all the elements of div and color them as mentioned

<br>

**[Ritesh_Code](D:\Open_Source\Ritesh_WD_Grouping_code.md)
You can check the code in here**


<br>
<br>
<br>



## ***Thank You For Reading***
## ***Hope You Enjoyed it !!!***
