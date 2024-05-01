# HTML + CSS Activity

## Assignment

Using the included mockup.jpg and the content on the last page of this document, recreate the image as a web design:

![1714577658208](image/README/1714577658208.png)

### Acceptance Criteria

* [X] Write appropriate HTML markup for the provided content.
* [X] Add CSS to style the HTML appropriately to create the design in the mockup.

### Constraints

* [X] HTML is well formed and organized.
* [X] Implemented using modern technique and best practices.
* [X] Final site followd WCAG 2.2 standards where possible/applicable.
* [X] Use of Frameworks/libraries is acceptable but not required.
* [X] Interactive elements and hover states are recommended.
* [X] OPTIONAL: Implement a responsive layout with support for multiple screen sizes.
* [X] Final site is published in an online platform to be shared.

### Resources

* Publishing platform: **[Codepen](https://codepen.io.)**
* Logo: [ASU Logo](https://www.angelo.edu/live/resource/image/_i/themes/global/assets/images/asu-logo-white-gold.svg)
* Main background photo: **[BG-Image](https://www.angelo.edu/live/image/gid/315/width/2000/45797_Mall_Between_Archer__CHP.jpg)**
* Academics: [Lecture Hall Photo](https://www.angelo.edu/live/image/gid/315/width/600/height/400/crop/1/41765_COM_3949.jpg)
* Student Life: [Sporting Event Photo](https://www.angelo.edu/live/image/gid/315/width/600/height/400/crop/1/55387_SCT_0033.jpg)
* Atheltics: [Baseball Team Photo](https://www.angelo.edu/live/image/gid/315/width/600/height/400/crop/1/49730_20220528_Rams_vs_CMU_Game_3_South_Central_Super_Regional_0039.JPG)
* Font: [Barlow](https://fonts.googleapis.com/css2?family=Barlow:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap)

### Colors

Gold: hex #ffc423, rgba(255, 196, 35, 1)

Light Blue: hex #c1edfb, rgba(193, 237, 251, 1)

Text: hex #002554, rgba(0, 37, 84, 1)

Background Overlay:  hex #003fb0, rgba(0, 37, 84, 1), background-blend-mode: multiply

## Implementation Notes

**[Final Implementation is available here](https://jrastetterpm.github.io/ASU/#)**.

Some minor deviations from the mockup were made to enhace accessibility and performance. Details listed below.

* Main link text size and hit zone: Increased text size and padding to make it easier to read and interact with on mobile devices.
* Padding and background color on cards: Increased card size and contrast between the text and background to make it easier to read and interact with.
* Responsive Layout: Added breakpoints so that links and cards adjust to viewport size to make it easier to use from a variety of devices.

### Performance Optimization

* Minified all styles and javascipt resources.
* Preloaded all critical resource to optimize initial load time.
* Converted all images for moder webp format to reduce load.

### Accessibility and SEO Testing

* Ran a Lighthouse report and did some manual testing of tab order to ensure a high degree of accessibility.
* Added keywords, and metadata headers to improve SEO and discoverability.

[Full lighthouse report is available here.](./Lighthouse_report.html)
