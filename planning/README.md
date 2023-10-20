# Responsive Design - Planning

![Hero image](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to plan responsive web pages using mobile first design and the viewport meta tag.

## Mobile first design philosophy

Two approaches can be followed:

1. Write the starting CSS for a large desktop screen, then apply “new” CSS (using media queries) as the screen width decreases, or
   
2. Write the starting CSS for a mobile screen, then apply additional CSS as the width increases.

The experts tell us that it's better to use a **mobile-first** approach for the following reasons:

- Translating the design from mobile to desktop is more straighforward than vice-versa; thus, it should require less time to build.
- Mobile-first encourages you to think about what content is the most important - and prioritize them.
- It's easier to detect performance-related issues, such as the slow loading of large image files on mobile devices. It's better to deal with performance issues early on.
- A design based on small screen width, although not ideal, is usable on larger screens; however, the reverse is often not the case.

### First step to enabling a better experience on mobile

For those who remember using smartphones when they first came out to browse the web, we often saw screens with tiny, unreadable content.

Unlike desktop browsers that render pixel-by-pixel, mobile browsers render to a virtual **viewport**. This virtual viewport concept is what enables pinching to zoom in and out.

By default, mobile browsers scale down the content to fit it in the browser window, resulting in tiny text that's hard to read.


## Viewport `meta` tag

The viewport `<meta name="viewport" ...>` enables us to inform the browser not to scale the page as seen above. With this HTML present, mobile devices instead display the content based upon the physical number of pixels available - just like desktop browsers do.

The following should look familiar:

```html
<meta name="viewport" content="width=device-width, initial-scale=1">
```

This viewport `meta` tag is so essential that VS Code adds it automatically in the HTML boilerplate.

Every app you write will have this meta tag.




