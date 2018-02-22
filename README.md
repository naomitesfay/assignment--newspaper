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

The `code` folder containers a boilerplate html file and a starting CSS-file. We suggest you start by making the mobile version and then work your way up. Mobile first! You will be reviewed on your code for mobile, tablet and desktop, so make sure all look good before submitting your pull request.

To complete this assignment, you need to fork this repository, add your code to your repository, and then submit a pull request on GitHub (from your repository into the Technigo one) for review. [Read the guide on GitHub](https://guides.github.com/activities/forking/) for more info on how to do this.

### :books: Reading List

* [W3Schools - Responsive Web Design](https://www.w3schools.com/html/html_responsive.asp)
* [CSS-tricks – Media Queries](https://css-tricks.com/css-media-queries/)
* [MDN – Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)

---

### :sos: How to get help
Learning how to think as a web developer is learning how to be an expert in problem solving. So whenever you get stuck start with step 1 and continue until problem solved.

1. Google! In English, type in the error message if there is one, search within the language you're using (ie CSS, JavaScript etc).
2. Ask your code buddies in your Company.
3. Ask your fellow students in Slack.
4. Ask Damien or David. Please note: we are part of a sharing community - share the answer with your fellows.

---

### :boom: Success!

After completing this assignment, you should be comfortable using media queries and know how to build responsive webpages. You should also have knowledge about how to think about cascading styles (To change as little as possible between the screen sizes) and how overrides work in CSS.

---

### :runner: Stretch Goals

Done with the main task? Here's some ideas for things to continue with:

1. Make it so the tag line of an article shows above the title on mobile screens. One approach to this is to have two copies of the tag line in the html and then show/hide them in CSS based on screen size. (You can use `display: none` to hide something in CSS, and then `display: block` or `display: inline` to show it again depending on whether you want it to behave as a block or inline element)
1. Implement the background color of the headlines as on kit.se. This is a little tricky but [here's a great guide](https://css-tricks.com/multi-line-padded-text/) to multiple approaches. We have faith in you!
1. Try to implement the same hover effect as kit.se has.
