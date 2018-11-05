# Sprint 1: Newspaper Assignment

Today's assignment is to create a classic magazine or newspaper style grid of images which could link to articles. Using [kit.se](https://kit.se/) as inspiration you should create a grid of images with a title and tagline. On desktop sized screens, there should be 3 images on a row. On Tablets, there should be 2 images, and on mobile, there should just be 1 image on each row.

The part of kit we're focussing on is this:

![Kit.se grid](https://github.com/Technigo/assignment-news-paper/blob/master/kit-grid.png)

Some important things about the design on kit and what this assignment is about:

* **The important thing is to make a grid which uses percentages to modify the width of items based on screen size**
* The white background on the titles should be left to the end (it's a stretch goal!)
* If you'd like to use a different site, or design something yourself, that's ok!

**Remember: The focus of this assignment is responsive CSS, not copying the kit.se design verbatim.** So don't get caught up on the design too much!

## How to complete this assignment

From the lecture in the morning, you should be familiar with the media query syntax in CSS. For example, to make an `h1` green on phones, you could write a media query like this:

```css
@media (max-width: 600px) {
  h1 {
    color: green;
  }
}
```

What sizes should match phones, tablets and desktops is a heavily debated topic, but a good starting point is something like this:

* Mobile < 600px
* Tablets > 600px and < 900px
* Desktop > 900px
