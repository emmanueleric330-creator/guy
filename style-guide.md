# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

> 💡 These are just the design sizes. Ensure content is responsive and meets WCAG requirements by testing the full range of screen sizes from 320px to large screens.

## Colors

### Primary

- Blue 950: hsl(233, 26%, 24%)
- Green 500: hsl(136, 64%, 51%)
- Cyan 400: hsl(192, 69%, 51%)

### Neutral

- Gray 600: hsl(233, 8%, 62%)
- Gray 100: hsl(220, 16%, 96%)
- Gray 50: hsl(0, 0%, 98%)
- White: hsl(0, 100%, 100%)

## Typography

### Body Copy

- Font size: 18px

### Font

- Family: [Public Sans](https://fonts.google.com/specimen/Public+Sans)
- Weights: 300, 400, 700

> 💎 [Upgrade to Pro](https://www.frontendmentor.io/pro?ref=style-guide) for design file access to see all design details and get hands-on experience using a professional workflow with tools like Figma.



#dd-content {
    position: absolute;
    display: none;
    width: 100%;
    height: 0px;
    box-shadow: 0 18px 36px rgba(0, 0, 0, 0.30), 0, 14px 11px rgba(0, 0, 0, 0.22);
}
#dd-btn:focus-within>#dd-content {
    display: relative;
    transition: 10s ease;
    height: 40pc;
}

#dd-content>a {
    display: block;
    padding: 15px;
    text-decoration: none;
    color: black;
}

#dd-content {
    text-align: center;
    border: none;
    display: none;
}




















<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=b, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="./style.css">
    <style>
        .dd{
            position: relative;
            display:inline-block;
            margin: 15pc 15pc 15pc ;
        }

        .dd-content{
            position: absolute;
            display: none;
            width: 100%;
            box-shadow: 0 18px 36px rgba(0, 0, 0, 0.30), 0, 14px 11px rgba(0, 0, 0, 0.22);
        }
        .dd:focus-within > .dd-content{
            display: block;
            transition: 10s ease;
        }
        .dd-content > a{
            display: block;
            padding: 15px;
            text-decoration: none;
            color: black;
        }
        .dd-content{
            text-align: center;
            border: none;
        }
    </style>
</head>

<body>
    <section class="dd">
        <button class="dd-btn"><img src="../assets/images/icon-hamburger.svg" alt=""></button>
        <div class="dd-content" id="">
            <a href="" class="">menu</a>
            <a href="" class="">text</a>
            <a href="" class="">about</a>
            <a href="" class="">faq</a>
        </div>
    </section>
</body>

</html>