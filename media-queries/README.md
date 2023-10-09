# Responsive Design - Media Queries

![Hero image](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to use media queries and breakpoints to create responsive web pages.

Media queries are a CSS feature that allow us to apply different CSS rules to a page depending on the characteristics of the device or environment in which the page is being displayed. For example, we can use media queries to change the layout of our page for different screen sizes, or to hide or show certain elements on printouts.

## Using media queries to apply different CSS rules to a page

To use a media query, we wrap the CSS rules that we want to apply conditionally in a @media block. The @media block specifies the conditions that must be met for the CSS rules to be applied.

tktk example

```css
@media (max-width: 600px) {
  /* CSS rules for small screens */
}

```


We can also combine multiple media queries to create more complex conditions. For example, the following media query will apply the CSS rules inside the block to all desktop devices with a screen width of less than 1200 pixels and a screen ratio of 16:9:

```css
@media (min-width: 768px) and (max-width: 1199px) and (aspect-ratio: 16/9) {
  /* CSS rules for desktop devices with a screen width of less than 1200 pixels and a screen ratio of 16:9 */
}

```

## Breakpoints

Breakpoints are the specific screen sizes or other conditions that we use to create media queries. Common breakpoints include:

Mobile: 320px - 480px
Tablet: 481px - 767px
Desktop: 768px - 1199px
Large desktop: 1200px+

Of course, we can use any breakpoints that make sense for our website or web application, and we should always choose our breakpoints based on our content. 


## Order may matter

The order of our media queries can matter, depending on the conditions that we are checking for. For example, if we have two media queries that both apply to the same device, the browser will apply the first media query that matches.

To avoid this, we should put our media queries in order of most specific to least specific. For example, if we have a media query for mobile devices and a media query for tablet devices, we should put the media query for mobile devices first.

## 🧠 You do

Add another media query for a breakpoint at `(min-width: 1024px)` - a common breakpoint width for desktop displays.

Within the query, add some CSS to change the colors of the backgrounds and text.

Next up is a lab that will give you some practice working with **Media Queries**, **CSS Grid**, and **Flexbox**.

However, here are a few quick review questions for you:

## Review Questions ❓

1. **In your own words, describe Responsive Design.**
2. **When coding an app that we want to make responsive, is it more common to write the “base” CSS for mobile screens or desktops?**
3. **What key CSS feature did we learn about that’s fundamental to the implementation of responsive design?**

