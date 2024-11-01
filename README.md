# The Odin Project: Landing Page

![Screenshot of my project](image.jpg)
A screenshot of my version of Landing Page Project.

## Introduction

This is my attempt at [The Odin Project's](https://www.theodinproject.com/) final project in the Flexbox Chapter of their Foundations Course. We were given a lot of freedom for this one, just a reference image and an image with the relevant colours and font styles, so it should be an interesting project to complete with my budding knowledge of HTML and CSS.

## Aims

There are a few objectives that I'd like to complete over the course of this project:
1. Make the HTML as semantic as possible.
    - While I have a better understanding now of why so many `<div>` wrappers are important for positioning elements on a webpage, I personally think it's confusing and convoluted when you have nothing but `<div>`s within the HTML, doesn't make it super readable. Instead I'm aiming to use as much of the semantic HTML elements, like `<section>`, baked into HTML already, and use `<div>`s where necessary but with semantic class names as well.
2. Make it responsive, and looking good, with Flexbox at all screen sizes.
    - While I only really know how to position elements with Flexbox at the moment, I've seen enough static websites to know how subpar they look compared to websites that adapt to the sizes they are. It's not enough to simply shrink down appropriately, but should also look good when on a wider screen. There have been too many company websites I've see where it doesn't adapt and only fills half the space available, it just looks like a half-finished product and doesn't leave a good impression.
3. Minimise the number of individual selectors in CSS
    - This is probably just my inexperience in the process, but I found that when comparing my previous solutions in the [css-exercises](https://github.com/TheOdinProject/css-exercises) to the *model* solutions, I missed out on a lot of the optimisations and had a few declarations repeating themselves. This time I want to be more aware of this and try to group selectors where I can and try to reduce the filesize of the CSS stylesheet just a little bit.
4. Use git effectively
    - I am going to try and use git as it is suggested to, by recording each *significant* step forward in the process. I might not be as diligent on this as it's a new idea to me, it's not just about saving my work but getting snapshots that I, or others, can refer back to at any given time. There's also the commit message etiquette that I will try to adhere to, that way I can leave behind a git log that is easy for people to look through, and maybe learn from, in the future.

## Reflections

### HTML

While writing out the HTML portion of the project, I used emmet to lay out all the elements. I tried to use it all in one line but it got a little bit much to try and keep track of everything. I think that next time, I'll just use it in portions to lay out meaningful chunks as I come across them. For instance, using it to layout one section of the page at a time. That's probably as much information as I could hold in my head at one time. 

I also like the idea of having each portion of the page being within a `<section>` element, even if that means I need to give each one a different class name anyway, I think that makes a lot more sense than having lots of `<div>`s everywhere. I reserved the use of `<div>`s for when it was merely for placement purposes rather layout. For example, the portion of the webpage with the image carousel, I had the overall section be within a `<section>` element. However, I wanted the heading to be laid out differently to the figures, so I wrapped the figures within a `<div>`. When looking at the overall structure I can clearly see that these elements all belong within one section and the `<div>` portion is just there to help with the aesthetics.

I originally had the `<nav>` portion wrapped within a `<header>` but that honestly seemed superfluous. If the only semantic element I am going to have within the header is the navigation portion, then why not just leave it as just `<nav>`. That means less indentation, makes it easier to write, and it won't affect how I style it at all when it comes to CSS. I can still style it exactly as I would have done if it was the header. Keeping it simple makes it easier to read, at least to me, so I went ahead and tried to identify any other superfuous elements. I decided I didn't need any `<p>` elements within the `<blockquote>` as it was just one paragraph, I also decided I didn't need the `<p>` element within  the `<footer>` as that was going to be the only element in there. I might find more later, or I might find styling it difficult later but let's see. 

Overall, I think I achieved my objective of making it as semantic as possible. At least to me it reads quite nicely and by simplifying it a little I think it's become even better. I'm hoping I've added enough classes and IDs to make it straightforward to style with CSS though that may change as I go through with the next portion of the project. Bring on the CSS!
