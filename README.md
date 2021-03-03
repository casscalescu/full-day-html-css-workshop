# Welcome to the Intro to HTML & CSS Workshop! :sparkles:

## Let's get familiar with HTML + CSS and build a landing page.

Here are the slides with examples: https://drive.google.com/file/d/1eIPN9CN0BkFGPqfmucLIzg53cbJV-K0-/view?usp=sharing

Here is an example landing page you can inspect (you also have access to the full code base in the `example-bulk-store folder`: https://competent-montalcini-cc9174.netlify.app/

Make sure you have a text editor like [Sublime](https://www.sublimetext.com/) or [VS Code](https://code.visualstudio.com/download)

Remember, to open your file on the web browser: right click your file & Open With: Chrome.

### Challenge 1 | HTML

1. Clone or download this repository (you can use your command line or download it directly to your desktop).
2. Now that you have the file structure, drag the folder into your text editor to open, and make sure you have the following code to start your document:

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  
</body>
</html>
```

3. Update the `<title>` of your webpage a title.
4. Let's start by creating a page banner:

- In between your `<body>` tags, let's add some HTML structure. Use a `<h1>` tag and give your site a heading.
- Now use a `<p>` for some text in your site.
- Let's use a link in your HTML with an `<a>` tag.
- Lets put a `<div>` tag around all of the content we've created so far within the `<body>`.
- Give the `<div>` a class with: `class="your-class-here"`.
- Feel free to include other HTML tags below the `<div>` you've created + be creative!

5. Let's now build the structure of your footer that will be styled later. You can follow the structure below or make your own:

- Create a `<div>` and give it a `class`.
- Inside the `<div>` add a `<h2>` with some text and a contact/signup `<form>`
- Optional: add social links using an `<img>` within an `<a>` tag. Inside the `images` folder there are 3 social media logos you can use.


### Challenge 2 | CSS
1. First, navigate to your `style.css` file. Make sure it is linked in your `index.html` file.
2. For the `class` you have given to your `banner section` in the previous challenge, let's now give it some styling:

- Find a background image on [Unsplash](www.unsplash.com) or [Pexels](https://www.pexels.com/). Download and drag the image into the `images` folder.
- Give the `class` a `background-image: url();` and use the image you found. 
- Next, give it a `height` and some `padding`.
- If the `background-image` isn't aligned nicely, try adding `background-size: cover;` and `background-position: center;` to ensure it takes up the entire space and is centered.
- Next, change the `color` and `text alignment` of the `text` (if you want).
- Don't forget your `<a>` link! Try adding some `background-color`, `padding`, a `hover` effect etc.
- Add any extra styling you'd like. Check out more examples of CSS styling here: [W3Schools | CSS](https://www.w3schools.com/css/).

### Challenge 3 | Google Fonts
1. Want to add different fonts? Head to [Google Fonts](https://fonts.google.com/).
2. Find a font you like.
3. Copy the `link` tag & put it in your `<head>`.
4. Update your `font-family` css attribute.

### Challenge 3 | CSS Advanced
1. Use Boostrap to customise your page! https://getbootstrap.com/.
2. Remember to import Bootstrap in the head of your html:

```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
```

3. To use the Javascript Bootstrap components, put the following lines right above your closing `</body>` tag in your html file:

```
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/js/bootstrap.bundle.min.js" integrity="sha384-b5kHyXgcpbZJO/tY9Ul7kGkf1S0CWuKcCD38l8YkeH8z8QjE0GmW1gYU5S9FOnJ0" crossorigin="anonymous"></script>
<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
```


 


