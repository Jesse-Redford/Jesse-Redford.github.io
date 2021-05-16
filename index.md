## Biography

<img src="Headshot_Italy.jpg" alt="Headshot" style="height: 10px; width:10px;"/>

Hello my name is Jesse, I am PhD Student at the Univeristy of North Caronlina at Charlotte and Research Assistant for Center for Precision Metrology. I am also Vice-President of the American Society of Precision Engineers Graduate Student Chapter. 


### Portfolio

Image - Link - Description
  
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Full Screen Slider</title>
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="slider">
    <div class="slide current">
      <div class="content">
        <h1>Slide One</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit quidem, architecto eos adipisci maxime aperiam!</p>
      </div>
    </div>
    <div class="slide">
      <div class="content">
        <h1>Slide Two</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit quidem, architecto eos adipisci maxime aperiam!</p>
      </div>
    </div>
    <div class="slide">
      <div class="content">
        <h1>Slide Three</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit quidem, architecto eos adipisci maxime aperiam!</p>
      </div>
    </div>
    <div class="slide">
      <div class="content">
        <h1>Slide Four</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit quidem, architecto eos adipisci maxime aperiam!</p>
      </div>
    </div>
    <div class="slide">
      <div class="content">
        <h1>Slide Five</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit quidem, architecto eos adipisci maxime aperiam!</p>
      </div>
    </div>
    <div class="slide">
      <div class="content">
        <h1>Slide Six</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit quidem, architecto eos adipisci maxime aperiam!</p>
      </div>
    </div>
  </div>
  <div class="buttons">
    <button id="prev"><i class="fas fa-arrow-left"></i></button>
    <button id="next"><i class="fas fa-arrow-right"></i></button>
  </div>

  <script src="main.js"></script>
</body>
</html>


<!--
A div with an id of 'slideshow' contains five images, the first of which is shown and the others are hidden using a display style of none. Using Javascript, create a simple slideshow that cycles through the images, displaying each image for three seconds at a time, looping back to the first image when the end is reached. You cannot use jQuery or any other library.
-->
<html>
<body>
<div id="slideshow">
	<img src="Headshot.PNG"  alt="Headshot One"   style="display: none">
	<img src="Headshot_Italy.jpg" alt="Headshot Two" style="display: none">
	<img src="Headshot_Italy.jpg" style="display: none">
	<img src="Headshot_Italy.jpg" style="display: none">
	<img src="Headshot_Italy.jpg" style="display: none">
</div>
<script>
var slideshow = document.getElementById('slideshow');
var slides = slideshow.getElementsByTagName('img');
var idx = 0;
function changeSlide() {
	slides[idx].style.display = 'none';
	idx = (idx + 1) % slides.length;
	slides[idx].style.display = 'block';
}
setInterval(changeSlide, 3000);
</script>
</body>
</html>









































<!--

ALL OF THIS IS COMMENTED OUT!!!


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)

```


For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Jesse-Redford/Jesse-Redford.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

-->
