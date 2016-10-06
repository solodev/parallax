# parallax
In this article, [Solodev](https://www.solodev.com/) will teach you how to add Parallax Images with multiple backgrounds to your website. Parallax creates a depth and transition effect when scrolling down and creates smooth scrolling throughout your website.

## Tutorial

For detailed insutrctions, view Solodev's [Using Parallax with Multiple Background Images](https://www.solodev.com/blog/web-design/using-parallax-with-multiple-backgrounds.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/33ao8hsv/).

## HTML

The parallax example has the following HTML markup.

```
<div id="intro">
   <div class="story">
      <div class="float-left">
         <h2>(Almost) Static Background</h2>
         <p>This section has a background that moves slightly slower than the user scrolls. This is achieved by changing the top position of the background for every pixel the page is scrolled.</p>
      </div>
   </div>
   <!--.story-->
</div>
<!--#intro-->
<div id="second">
   <div class="story">
      <div class="bg"></div>
      <div class="float-right">
         <h2>Multiple Backgrounds</h2>
         <p>The multiple backgrounds applied to this section are moved in a similar way to the first section -- every time the user scrolls down the page by a pixel, the positions of the backgrounds are changed.</p>
         <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean nibh erat, sagittis sit amet congue at, aliquam eu libero. Integer molestie, turpis vel ultrices facilisis, nisi mauris sollicitudin mauris, volutpat elementum enim urna eget odio. Donec egestas aliquet facilisis. Nunc eu nunc eget neque ornare fringilla. Nam vel sodales lectus. Nulla in pellentesque eros. Donec ultricies, enim vitae varius cursus, risus mauris iaculis neque, euismod sollicitudin metus erat vitae sapien. Sed pulvinar.</p>
      </div>
   </div>
   <!--.story-->
</div>
<!--#second-->
<div id="third">
   <div class="story">
      <div class="float-left">
         <h2>What Happens When JavaScript is Disabled?</h2>
         <p>The user gets a slap! Actually, all that jQuery does is moves the backgrounds relative to the position of the scrollbar. Without it, the backgrounds simply stay put and the user would never know they are missing out on the awesome! CSS2 does a good enough job to still make the effect look cool.</p>
      </div>
   </div>
   <!--.story-->
</div>
<!--#third-->
```

## CSS

All necessary CSS is included in parallax.css

## External Includes

This tutorial includes the following third party resources.

```
<link href="https://fonts.googleapis.com/css?family=Open+Sans+Condensed:300" rel="stylesheet">
<link href="parallax.css" rel="stylesheet">

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://www.solodev.com/assets/parallax/jquery.localscroll-1.2.7-min.js"></script>
<script src="https://www.solodev.com/assets/parallax/jquery.parallax-1.1.3.js"></script>
<script src="https://www.solodev.com/assets/parallax/jquery.scrollTo-1.4.2-min.js"></script>
```
