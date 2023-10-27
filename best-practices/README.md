# ![Responsive Design - Best Practices](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to utilize testing tools to evaluate the responsiveness of a website on different devices and understand the principles of progressive enhancement to create websites that are accessible to a broad range of users.

## Test your website on different devices

Ensuring your website's responsiveness on multiple devices is crucial for user experience. While testing on the actual devices your audience uses is ideal, it's often not feasible. Tools like the  [Device Toolbar in Chrome](https://developer.chrome.com/docs/devtools/device-mode/#viewport) provide a viable alternative.


### Key Areas to Focus On

When conducting tests, zero in on:

 - **Layout:** Does it align with your design objectives?
 - **Content:** Is all your content visible and easily accessible?
 - **Navigation:** How effortless is it to move around the website?
 - **Forms:** Are they fully functional?
 - **Interactivity:** Do clickable items behave as expected?

 > ❓ Which of these would "testing the animation of a hamburger menu" fall under? 

## Using Chrome's Device Toolbar for Testing

The Device Toolbar in Chrome DevTools simulates various screen sizes and resolutions, including Retina screens. To activate it:

1. Open Developer Tools (`Cmd+Option+I` on Mac or `F12` on Windows)
2. Click on the Device Toolbar icon next to the Elements tab
3. Select a device from the drop-down or input custom dimensions
4. Refresh the page to see how your website behaves under different conditions.

### You Do 

Chrome's browser simulation for mobile devices has come a long way, but it isn't perfect. Find a mobile device in the drop down that most closely matches your own personal device.

1. Navigate to one of your favorite websites using the simulator. Take a look at the UI.
2. Now navigate to that same site from your personal device.

Are there any differences in how the page displays? 


## Progressive enhancement

Progressive enhancement is a way to design websites that work for everyone, regardless of their device or browser. It starts with creating a basic version of the website with all the essential content and features. Then adding more features and enhancements for users with more powerful devices and browsers.


### Benefits of Progressive Enhancement
 - **Universal Accessibility**: All users receive the essential content and basic functionalities.
 - **Reduced Load Times**: Users with older hardware or slower internet connections benefit from faster load times for essential features.
 - **Easier Maintenance**: Since the basic version needs to be maintained, it simplifies long-term site upkeep.

  > ❓ Can you think of a feature that might not be useful on a mobile device, but could greatly enhance a desktop experience?  