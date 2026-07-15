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

Warnings are due to using root variables to organise color schemese. They have not effect on the code.

---
## Responsiveness

The screenshots below show the site at common viewport sizes used in browser responsive mode. Each screenshot includes a visible viewport label in the top-right corner showing the device type and screen size.

| Device | Viewport | Evidence |
| ----------- | ----------- | ----------- |
| Mobile | 320x667 | ![mobile screenshot 1](testing/responsivness/mobiles.png)  ![mobile screenshot 2](testing/responsivness/mobiles-2.png)  ![mobile screenshot 3](testing/responsivness/mobiles-3.png)  ![mobile screenshot 4](testing/responsivness/mobiles-4.png)  ![mobile screenshot 5](testing/responsivness/mobiles-5.png) |
| Tablet | 768x1024 | ![tablet screenshot 1](testing/responsivness/tablet.png)  ![tablet screenshot 2](testing/responsivness/tablet-1.png)  ![tablet screenshot 3](testing/responsivness/tablet-2.png)  ![tablet screenshot 4](testing/responsivness/tablet-3.png)  ![tablet screenshot 5](testing/responsivness/tablet-4.png) |
| Desktop | 1440x1100 | ![desktop screenshot 1](testing/responsivness/desktop.png)  ![desktop screenshot 2](testing/responsivness/desktop-1.png)  ![desktop screenshot 3](testing/responsivness/desktop-2.png)  ![desktop screenshot 4](testing/responsivness/desktop-3.png)  ![desktop screenshot 5](testing/responsivness/desktop-4.png) |


---
## Browser Compatibility

| Chrome | FireFox | Edge |
| ----------- | ----------- | ----------- |
| ![chrome compatiblity scrrenshot](testing/browser-comp/chrome/chrome-desktop.png) | ![firefox browser compatibility](testing/browser-comp/firefox/firefox-desktop.png) | ![microsoft edge compatbility](testing/browser-comp/edge/edge-desktop.png) |
---
## Lighthouse Audit

| Mobile | Desktop |
| ----------- | ----------- |
| ![mobile lighthouse test result, 86/100 for performance, 100/100 for Accessbility, 100/100 fo Best practices](testing/lighthouse/mobile-lighthouse-test.png) | ![Desktop lighthouse result, 97/00 for perfomrance, 100/100 for Accessibility and 100/100 for Best pracices](testing/lighthouse/desktop-lighthouse-test.png)

---
## User Story Testing
Refer to user stories for full details in README.md

| User Story | Evidence | 
| ----------- | ----------- |
| As a visitor, I want a clear navigation menu so that I can quickly access different sections of the webpage. | ![navigation evidence](testing/user-stories/navbar.png) |
| As a first-time visitor, I want an engaging introduction so that I immediately understand the purpose of the website. | ![hero section with header, subheading and Call to action button](testing/user-stories/hero-cta.png) |
| As a visitor, I want easy-to-understand information about mental health so that I can develop a basic understanding of the topic | ![what is mental health section](testing/user-stories/about.png) |
| As a visitor, I want information about common mental health challenges so that I can recognise some common experiences. | ![common challenges section](testing/user-stories/challenges.png) |
| As a visitor, I want practical wellbeing tips so that I can learn simple ways to support my mental health. | ![practical tips formental wellbeing](testing/user-stories/tips.png) |
| As a user, I want the website to be accessible so that I can easily read and navigate the content. | ![light house accesibility score](testing/accessibility/accessibilty-test.png) |
| As a visitor using different devices, I want the website to display correctly on any screen size. | refer to responsivness section |
| As a visitor, I want links to trusted organisations so that I can access further support if needed. | ![links to resources](testing/user-stories/resources.png) |
| As a visitor, I want to provide feedback so that I can suggest improvements to the webpage. | ![contact form section](testing/user-stories/contact-form.png) |
| As a visitor, I want to read an encouraging message so that I leave the website feeling supported. | ![affirmations](testing/user-stories/affirmations.png) |
---
## Bugs
| Bugs | Picture | Fixed | Comment
| ----------- | ----------- | ----------- | ----------- |
| On mobile devices the layout beyond about section was assymetrical forming a larger gap on the right of the screen | ![bug on mobile gap on right of screen](testing/bugs/mobile-320px.png) | ![bug fixed](testing/bugs/mobile-bug-fixed.png) | Media queries was clashing witht he bootstrap repsonsivness. Deleted media query |

### Unfixed Bugs