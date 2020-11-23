# ***Grouping Code***

## Case 1  Without Grouping

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grouping</title>
    <style>

        h1{
            color:green;
        }

        h2{
            color:green;
        }

        .text{
            color:green;
        }
        
    </style>
</head>

<body>

    <h1>This is Without </h1>
    <h2>Grouping</h2>
    <div>
        <p class="text"> Hello Everyone , I am Ritesh Rathod </p>
    </div>

</body>

</html>
```

## OUTPUT

<br>

<img src="grouping_1.png" width="500px" height="150px">

<br>
<br>
<br>


## Case 2 With Grouping

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grouping</title>
    <style>
        h1,
        h2,
        .text {
            color: green;
        }
    </style>
</head>

<body>

    <h1>This is With</h1>
    <h2>Grouping</h2>
    <div>
        <p class="text"> Hello Everyone , I am Ritesh Rathod </p>
    </div>

</body>

</html>
```

## OUTPUT

<br>

<img src="grouping_2.png" width="500px" height="150px">

<br>
<br>
<br>
<br>


# ***Universal Selector Code***

<br>

## Case 1  Selecting All Elements

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grouping</title>
    <style>
        * {
            color: blue;
        }
    </style>
</head>

<body>

    <h1>Color Using Universal Selector</h1>
    <h2>This is for Open Source</h2>
    <div>
        <p> Hello Everyone , I am Ritesh Rathod </p>
    </div>

</body>

</html>
```
<br>

## OUTPUT


<br>

<img src="universal_1.png" width="500px" height="150px">

<br>
<br>
<br>
<br>

<br>

## Case 2  Selecting All DIV Elements

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grouping</title>
    <style>
        div * {
            color: white;
            background-color: green;
        }
    </style>
</head>

<body>

    <h1>Selecting DIV Universal Selector</h1>
    <h2>This is for Open Source</h2>
    <div>
        <p class="red"> Hello Everyone , I am Ritesh Rathod </p>
    </div>

    <span class="red">This is not Under div</span>

    <div>
        <span>This is inside the div</span>
    </div>
</body>

</html>
```
<br>

## OUTPUT

<br>

<img src="universal_2.png" width="500px" height="150px">

<br>
<br>
<br>

<br>

## ***Thank You For Reading***
## ***Hope You Enjoyed it !!!***
