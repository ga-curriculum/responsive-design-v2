# Responsive Design - Accounting for Mobile Devices

![Hero image](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to plan responsive web pages using mobile first design and the viewport meta tag.

## Mobile first design philosophy

Two approaches can be followed:

1. Write the starting CSS for a large desktop screen, then apply styling targeting smaller screens as the screen width decreases.
   
2. Write the starting CSS for a mobile screen, then apply styling as the width increases. This is referred to as mobile-first design.

Enginners typically prefer a mobile-first approach for a few reasons:

- Translating the design from mobile to desktop is more straighforward than from desktop to mobile.
- Mobile-first helps encourage thought about what content is the most important - and ensures we know to prioritize that content.
- A design based on small screen width, although not ideal, is usable on larger screens; however, the reverse is often not the case.

## First step to enabling a better experience on mobile

For those who remember using smartphones when they first came out to browse the web, we often saw screens with tiny, unreadable content.

Unlike desktop browsers that render pixel-by-pixel, mobile browsers render to a virtual viewport. The virtual viewport is what enables pinch-to-zoom on mobile browsers.

By default, mobile browsers scale down the content to fit it in the browser window, resulting in tiny text that's hard to read.

### Viewport `meta` tag

The viewport `<meta name="viewport" ...>` enables us to inform the browser not to scale the page as seen above. With this HTML present, mobile devices instead display the content based upon the physical number of pixels available - just like desktop browsers do.

The following should look familiar:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

This viewport `meta` tag is so essential that VS Code adds it automatically in the HTML boilerplate.

Every app you write will have this meta tag.
