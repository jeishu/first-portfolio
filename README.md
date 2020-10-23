# Jeremy Zhu's First Portfolio Website // Jeishu

This was our first homework assigned where we had to start from scratch. By using our lectures, activities, and outside resources, we had to create a website with HTML and CSS (maybe Javascript, if we are feeling comfortable with it.)

## Motivation

Besides this project being a homework, I was actually extremely excited to make my own website from scratch. Prior to this class, I had no knowledge in HTML and CSS. Just a little bit of Javascript, but barely any Javascript was used in this project.

## Table of Contents

* [Features](#Features)
* [Screenshots](#Screenshots)
* [Code-Example](#Code-Example)
* [Reference](#Reference)
* [Tests/Issues](#Test/Issues)
* [Contribute](#Contribute)
* [Credits](#Credits)
* [License](#License)

## Features

This portfolio was mostly done with HTML and CSS, just one Javascript for the "scroll to top" action. No Bootstrap was used, we did not learn that in class. 
Throughout the entire website, I used a lot of pseudo elements (hover, focus, after, etc), and used transition/transform styles to make the motion look as clean as possible when resized to different screen size. In which, I utilized a good amount of media queries to fixed any issue with responsiveness.

## Screenshots

These are desktop views:

![landing](./images/README-pics/landingpage.jpg)
![skills](./images/README-pics/skillspage.jpg)

These are iPhone X view:

![landing](./images/README-pics/landing.png)
![skills](./images/README-pics/skills.png)

## Code-Example

I utilized spaces and comments in HTML and CSS to organize and divide the sections up.
```
  <!-- ===== Landing Page ===== -->
        <header id="mountain">
            <div class="content">
                <h1>Jeremy Zhu</h1>
                <p>
                    Web Developer in Training.
                </p>
                <a href="#nav" class="button"><i class="fa fa-angle-down"></i></a>
            </div>
        </header>
        
    <!-- ===== Navigation Bar ===== -->
        <section class="navigationBar" id="nav">
            <nav>
                <ul class="navContainer" id="navbar"> 
                    <li>
                        <a href="#aboutBtn">About</a>
                    </li>
                
```
Spaces used for dividing up the styles in CSS || Comments used to help indicate the Flexbox Parent
```
   /* flexbox parent :: img div.aboutInfo */
.aboutCard {
    display: flex;
    justify-content: center;
    align-items: center;
}
    /* flexbox parent  :: p.name p.title p.info */
.aboutInfo {
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
}
.about img {
    width: 20rem;
    height: auto;

    margin: 1rem;
    padding: 2rem;

    float: left;
    border-radius: 3rem;
    transition: all .5s;
}
```

## Reference

These are websites I used to aid me in learning different techniques within HTML and CSS (and a dash of Javascript).
> - [CSS-Tricks](https://css-tricks.com/) || Learn most of my CSS from this website.
> - [Developer Mozilla](https://developer.mozilla.org/en-US/) || Learn most of my tag definitions here.
> - [W3School](https://www.w3schools.com/) || Learn many tricks (creating a form, hover effect, buttons, etc) here.
> - [GitHub Docs](https://docs.github.com/en/free-pro-team@latest/github/writing-on-github/basic-writing-and-formatting-syntax) || Learn most of my README syntax here.
> - [Akash Nimare](https://medium.com/@meakaakka/a-beginners-guide-to-writing-a-kickass-readme-7ac01da88ab3) || Based my README from his person.
> - [Traversy Media](https://www.youtube.com/channel/UC29ju8bIPH5as8OGnQzwJyA) || Watched his basics to HTML and CSS and other video to help create this website.

## Tests/Issues

> OVERFLOW-X: HIDDEN;
- I had issues margin, and padding that would flow outside of the viewport, which lead to a horizontal scrollbar.
- I initally used this to hid the horizontal bar, this lead to more issues than helping.
- This also conflicted with my single Javascript, thus instead of using the OVERFLOW-X: HIDDEN, I fixed the issue with Media Queries.
> Layout problems 
- I initially used CSS Grids for my website, but the CSS grids got more and more complicated, so switch to Flexbox
> POSITION: STICKY;
- While initially attempting to stick my NAVBAR to the top of the screen, it would roll pass it.
- Did more research and realized, they you need the -web-sticky for compatibility for the Chrome Browser to work.
> Chrome Dev Tool
- I did about 90% of my troubleshooting on here to test screen size and CSS codes.
- Used to help identify limits for my Media Queries.

## Contribute

- My class instructor, Calvin
- My tutor, Sangeetha
- My classmates and study groups

## Credits

> [DevFolio](https://bootstrapmade.com/demo/themes/DevFolio/)
- A good amount of inspirations came from this portfolio (Thanks Dora for linking this.)

> [Pixel Perfect](https://www.flaticon.com/authors/pixel-perfect), [icon54](https://icon54.com/)
- My skill section icons are all from this author.
- Also, they have an excellent website to receive inspirations from.

> [Wallpaper Flare](https://www.wallpaperflare.com/)
- This is where I got my background image from, also used for my temporary Project's Image.

## License

MIT © [Jeremy Zhu](2020)

