# ![Responsive Design - Accounting for Mobile Devices](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to plan responsive web pages using mobile-first design and the viewport meta tag.

## Mobile-first design philosophy

Two approaches can be followed:

1. Write the starting CSS for a large desktop screen, then apply styling targeting smaller screens as the screen width decreases.
   
2. Write the starting CSS for a mobile screen, then apply styling as the width increases. This is referred to as mobile-first design.

Engineers typically prefer a mobile-first approach for a few reasons:

- Translating the design from mobile to desktop is more straightforward than translating it from desktop to mobile.
- Mobile-first helps encourage thought about what content is the most important - and ensures we know to prioritize that content.
- Although not ideal, a design based on small screen width is usable on larger screens. However, the reverse is often not the case.

## The first step to enabling a better experience on mobile

Unlike desktop browsers that render pixel-by-pixel, mobile browsers render to a virtual viewport. The virtual viewport is what enables pinch-to-zoom on mobile browsers. Mobile browsers scale down page content to fit it into the viewport by default. 

This default results in tiny text that may be hard to read but does at least make older sites usable with pinch-to-zoom. This was necessary when mobile devices with fully-featured browsers were first released since websites weren't built to work on mobile devices. 

So, how do you get a website to feel native to a mobile device?

### Viewport `meta` tag

The following should look familiar:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

This HTML informs the browser not to scale the page on a mobile device. With this HTML present, mobile devices instead display page content based on the device's width (as specified by `width=device-width`) and do not zoom out `initial-scale=1.0`.

This viewport `meta` tag is so essential that it is one of the few items automatically included in VS Code's HTML boilerplate. Every app you write will have this meta tag.

tktk Hunter, can you combine these into a single widescreen graphic? (I'm not worried about the text in the no meta viewport tag image being readable, but it would be nice if the text in the meta viewport tag image was.)

![No meta viewport tag](./assets/no-meta.png)
![Meta viewport tag](./assets/meta.png)
