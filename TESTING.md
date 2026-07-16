# Testing

> [!NOTE]  
> Return back to the [README.md](README.md) file.
---
## Code Validation

### HTML

| Test | Before | After |
| ----------- | ----------- | ----------- |
| HTML W3C validation using URL | ![screenshot showing html validation errors](testing/html/html-validation-errors.png) | ![validation after fixing code no erros](testing/html/w3c-html-validation-url.png) |
| HTML W3C validation using Source code | ![screenshot showing html validation errors](testing/html/html-validation-errors.png) | ![validation after fixing code no erros](testing/html/w3c-html-validation-src-code.png) |

### CSS

| Test | Result | Warnings |
| ----------- | ----------- | ----------- |
| CSS Jigsaw validator | ![CSS validation no errors](testing/css/css-validation.png) | ![warnings](testing/css/css-validation-warning.png) |

Warnings are due to using root variables to organise colour schemes. They have no effect on the code.

---
## Responsiveness

The screenshots below show the site at common viewport sizes used in browser responsive mode. Each screenshot includes a visible viewport label in the top-right corner showing the device type and screen size.

| Device | Viewport | Evidence |
| ----------- | ----------- | ----------- |
| Mobile | 320x667 | ![mobile screenshot 1](testing/responsivness/mobiles.png) <br> ![mobile screenshot 2](testing/responsivness/mobiles-2.png) <br> ![mobile screenshot 3](testing/responsivness/mobiles-3.png) <br> ![mobile screenshot 4](testing/responsivness/mobiles-4.png) <br> ![mobile screenshot 5](testing/responsivness/mobiles-5.png) |
| Tablet | 768x1024 | ![tablet screenshot 1](testing/responsivness/tablet.png) <br> ![tablet screenshot 2](testing/responsivness/tablet-1.png) <br> ![tablet screenshot 3](testing/responsivness/tablet-2.png) <br> ![tablet screenshot 4](testing/responsivness/tablet-3.png) <br> ![tablet screenshot 5](testing/responsivness/tablet-4.png) |
| Desktop | 1440x1100 | ![desktop screenshot 1](testing/responsivness/desktop.png) <br> ![desktop screenshot 2](testing/responsivness/desktop-1.png) <br> ![desktop screenshot 3](testing/responsivness/desktop-2.png) <br> ![desktop screenshot 4](testing/responsivness/desktop-3.png) |

---
## Browser Compatibility

| Chrome | Firefox | Edge |
| ----------- | ----------- | ----------- |
| ![Chrome compatibility screenshot](testing/browser-comp/chrome/chrome-desktop.png) | ![Firefox browser compatibility](testing/browser-comp/firefox/firefox-desktop.png) | ![Microsoft Edge compatibility](testing/browser-comp/edge/edge-desktop.png) |
---
## Lighthouse Audit

| Mobile | Desktop |
| ----------- | ----------- |
| ![Mobile lighthouse test result, 86/100 for performance, 100/100 for accessibility, 100/100 for best practices](testing/lighthouse/mobile-lighthouse-test.png) | ![Desktop lighthouse result, 97/100 for performance, 100/100 for accessibility and 100/100 for best practices](testing/lighthouse/desktop-lighthouse-test.png)

---
## User Story Testing
Refer to user stories for full details in README.md

| User Story | Evidence | 
| ----------- | ----------- |
| As a visitor, I want a clear navigation menu so that I can quickly access different sections of the webpage. | ![navigation evidence](testing/user-stories/navbar.png) |
| As a first-time visitor, I want an engaging introduction so that I immediately understand the purpose of the website. | ![hero section with header, subheading and Call to action button](testing/user-stories/hero-cta.png) |
| As a visitor, I want easy-to-understand information about mental health so that I can develop a basic understanding of the topic. | ![What is mental health section](testing/user-stories/about.png) |
| As a visitor, I want information about common mental health challenges so that I can recognise some common experiences. | ![Common challenges section](testing/user-stories/challenges.png) |
| As a visitor, I want practical wellbeing tips so that I can learn simple ways to support my mental health. | ![Practical tips for mental wellbeing](testing/user-stories/tips.png) |
| As a user, I want the website to be accessible so that I can easily read and navigate the content. | ![Lighthouse accessibility score](testing/accessibility/accessibilty-test.png) |
| As a visitor using different devices, I want the website to display correctly on any screen size. | refer to responsivness section |
| As a visitor, I want links to trusted organisations so that I can access further support if needed. | ![links to resources](testing/user-stories/resources.png) |
| As a visitor, I want to provide feedback so that I can suggest improvements to the webpage. A confirmation message should show once I have provided feedback. | ![Contact form section](testing/user-stories/contact-form.png) ![Contact form success message modal](testing/user-stories/success-page.png) |
| As a visitor, I want to read an encouraging message so that I leave the website feeling supported. | ![affirmations](testing/user-stories/affirmations.png) |
---
## Bugs
| Bugs | Picture | Fixed | Comment |
| ----------- | ----------- | ----------- | ----------- |
| On mobile devices the layout beyond the About section was asymmetrical, forming a larger gap on the right side of the screen. | ![bug on mobile gap on right of screen](testing/bugs/mobile-320px.png) | ![bug fixed](testing/bugs/mobile-bug-fixed.png) | Media queries were clashing with the Bootstrap responsiveness. Deleted the media query. |

### Unfixed Bugs

| Bugs | Picture | Comment |
| ----------- | ----------- | ----------- |
| Contact form does not clear once the Send Message button is clicked. | ![contact form filled not clearing](testing/bugs/contact-form-bug.png) | As there is no back end or JavaScript functionality, this bug cannot be fixed. It is out of the scope of this project. |