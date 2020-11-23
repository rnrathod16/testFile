# ID Selector Code

- ## Case 1
use of Id Selector

``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ID Selector</title>
    <style>

            #green{
                color:green;
            }

    </style>
</head>
<body>

    <div>
        <p id="green"> Hello I am Ritesh </p>
    </div>
    
</body>
</html>
```
## OUTPUT
<br>

<img src="id_selector_1.png" width="500px" height="150px">

<br>
<br>
<br>

- ## Case 2

Code when same ID is given to Different Tags

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ID Selector -2 </title>

</head>

<body>

    <div>
        <p id="change"> Hello Everyone </p>
        <p id="change"> My name is </p>
    </div>

    <script>
        document.getElementById('change').innerHTML = "Ritesh";
    </script>

    <!-- This Script will change the First Id not the Second One -->
</body>

</html>
```

## OUTPUT
<br>

<img src="id_selector_2.png" width="500px" height="150px">

<br>
<br>
<br>
<br>
<br>

# Class Selector

- ## Case 1

Code to Show how to use class

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class Selector -1 </title>
    <style>
        .red {
            color: red;
        }
    </style>
</head>

<body>

    <div>
        <p class="red"> Hello my name is Ritesh </p>
    </div>

</body>

</html>
```

## OUTPUT
<br>

<img src="class_selector_1.png" width="500px" height="150px">

<br>
<br>
<br>
<br>
<br>

- ## Case 2

Code to make Changes to Specific element using class

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class Selector -2 </title>
    <style>
        p.blue {
            color: blue;
        }
    </style>
</head>

<body>

    <div>
        <p class="blue"> Hello </p>
        <span class="blue"> Everyone , I am Ritesh </span>
    </div>

</body>

</html>
```

## OUTPUT

<br>

<img src="class_selector_2.png" width="500px" height="150px">

<br>
<br>
<br>
<br>
<br>

- ## Case 3

Use of 2 different class for same tag

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class Selector -3 </title>
    <style>
        .red {
            color: red;
        }
        
        .size {
            font-size: 20px;
        }
    </style>
</head>

<body>

    <div>
        <p class="red size"> Hello Everyone , I am new to Open Source </p>
    </div>

</body>

</html>
```

## OUTPUT

<br>

<img src="class_selector_3.png" width="500px" height="150px">

<br>
<br>
<br>
<br>


## ***Thank You For Reading***
## ***Hope You Enjoyed it !!!***
