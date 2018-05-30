<h2 align="center">☑️<br/>Front-End Design Checklist</h2>

<p align="center">
  <em> The Design Checklist for Front-End Developers and Designers is an exhaustive list of elementsand rules that help ensure the quality of new products.</em>
</p>

## Table of Contents
* **[1. Pre-design phase (Measure Twice, Cut Once)](#1---pre-design-phase-measure-twice-cut-once-)**
  * [1.1 Mobile-first](#11---mobile-first-)
  * [1.2 Prototype with Adobe XD](#12---prototype-with-adobe-xd-)
* **[2. Design requirements](#2---design-requirements)**
  * [2.1 Grid system](#21---grid-system-)
  * [2.2 Colors](#22---colors-)
  * [2.3 Fonts](#23---fonts-)
  * [2.4 Images / Icons](#24---images--icons-)
  * [2.5 Forms and buttons](#25-forms-and-buttons-)
  * [2.6 Responsive Web Design](#26---responsive-web-design-)
  * [2.7 Style Guide and component approach](#27---style-guide-and-component-approach-)

---

## 1. - Pre-design phase (Measure Twice, Cut Once) ✂️

> The overarching goal of preparation is risk reduction: a good project planner clears major risks out of the way as early as possible so that the bulk of the project can proceed as smoothly as possible. By far the most common project risks in software development are poor requirements and poor project planning, thus preparation tends to focus on improving requirements and project plans.

> Building a software system is like any other project that takes people and money. If you’re building a house, you make architectural drawings and blueprints before you begin pounding nails. You’ll have the blueprints reviewed and approved before you pour any concrete. Having a technical plan counts just as much in software.

> You don’t start decorating the Christmas tree until you’ve put it in the stand. You don’t start a fire until you’ve opened the flue. You don’t go on a long trip with an empty tank of gas. You don’t get dressed before you take a shower, and you don’t put your shoes on before your socks. You have to do things in the right order in software, too.
Programmers are at the end of the software food chain. The architect consumes the requirements; the designer consumes the architecture; and the coder consumes the design.

📖 [Code Complete: A Practical Handbook of Software Construction, Second Edition 2nd Edition](https://www.amazon.com/Code-Complete-Practical-Handbook-Construction/dp/0735619670)
by Steve McConnell


### 1.1 - Mobile-first 📱

> If you still have it in your head that mobile web design and application development is a niche industry, you need to change your way of thinking. Mobile isn’t a trend, nor is it even the future, it’s the present. 

* [ ] Think about mobile usage of app first
* [ ] Use Progressive Enhancement

__Resources:__
  * 📖 [Mobile First](https://zurb.com/word/mobile-first)
  * 📖 [Mobile First Design: Why It’s Great and Why It Sucks](https://mayvendev.com/blog/mobilefirst)
  * 📖 [Progressive enhancement explained simply](https://medium.com/@adambsilver/progressive-enhancement-explained-simply-32dd1dc9e064)

**[⬆ back to top](#table-of-contents)**

### 1.2 - Prototype with Adobe XD 🚀

Prototyping is essential to help team create the best product possible. It’s a chance to experiment with ideas and turn them into something tangible that you can test and build upon. When you fail with your prototype, you land softly — there’s always the chance to iterate and improve.

* [ ] All pages and components are prototyped in **Adobe XD** and tested.
* [ ] Prototype should cover all UX issues.
* [ ] Prototype should cover both mobile and desktop version of app

__Resources:__
  * 🛠 [Adobe XD](https://www.adobe.com/products/xd.html)
  * 📖 [How We Use Prototyping, And How It Made Us More Efficient](https://www.smashingmagazine.com/2016/08/prototyping-for-success/)

**[⬆ back to top](#table-of-contents)**

## 2. - Design requirements

Designing a website or a webapp requires following some rules and taking into consideration that the project is not only a graphic project but a web project too. The next sections are crucial for any web project.

### 2.1. - Grid system 📐

* [ ] A **grid** is explicitly provided in the design, and the details of the grid are present in the technical specification (width, gutters, number of columns…). The Web Designer can keep the grid in a transparent layer and use it on all his project.

> ℹ️ On Sketch, you can use the integrated “[Make Grid Tool][7]” to design your desired grid.

__Additional Resources:__

* 🛠 [Bootstrap Grid System][8] (v4)
* 🛠 [Flexbox Grid][9]
* 📖 [Don't Overthink It Grids | CSS-Tricks][10]

**[⬆ back to top](#table-of-contents)**

### 2.2. - Colors 🎨 

* [ ] **All colors used in the creatives are named** ($gray-light, $gray-dark, $green) or accordingly with their use ($body-background, $body-copy, $text-paragraph…). They can be exported in an [ACO file][11] (on a symbol page for Sketch) and shared with the developers.

* [ ] The different **color state** of some elements (like buttons, links, inputs...) are defined and worked in the context of a light or dark background and with a light or a dark text.

* [ ] All or the most important/used **colors are accessible** in the design to allow a fluid navigation on the website/webapp.

**[⬆ back to top](#table-of-contents)**

### 2.3 - Fonts 🈶

Fonts are an essential part of every design, they shouldn’t be chosen without discernment. Choosing the wrong font for a project could have financial and legal impacts.

* [ ] [Fallback font](https://en.wikipedia.org/wiki/Fallback_font) stacks were specified in a document (ideally the Style Guide) to the Front-End Developer.

  __Resources:__
  * 📖 [CSS Basics: Fallback Font Stacks for More Robust Web Typography | CSS-Tricks](https://css-tricks.com/css-basics-fallback-font-stacks-robust-web-typography/)

__Additional Resources:__

* 🛠 [WCAG - Contrast Checker](https://contrastchecker.com/)
* 🛠 [Color Safe - accessible web color combinations](http://colorsafe.co/)
* 🛠 [Coolors.co - The super fast color schemes generator](https://coolors.co/)

**[⬆ back to top](#table-of-contents)**

### 2.4 - Images / Icons 🖼

* [ ] A **favicon image** with at least 512px X 512px is provided in PNG format. The generation of all the others Favicons can be easily done with online tools.

  __Resources:__
  * [Favicon Generator for all platforms: iOS, Android, PC/Mac...](https://realfavicongenerator.net/)

* [ ] All icons are provided in **SVG format**, each in the same square dimension, in black and in a separated folder.

  __Resources:__
  * 🛠 [SVGOMG - SVGO's Missing GUI](https://jakearchibald.github.io/svgomg/)

* [ ] The **name of each icon** starts with `icon-` and is entirely in lowercase (without any space and using dashes to separate each word).

__Additional Resources:__
* 📖 [Essential Image Optimization](https://images.guide/)

### 2.5 Forms and buttons 📬

* [ ] All forms possess a title that can be used as a legend
* [ ] An example of the **different states of all input fields** were provided (at least focus and inactive/disabled state).
* [ ] **All error messages** were provided, the text (eventually in a separated document) the position and the color are clearly identifiable in the creatives and consistent. Some messages should be different according to the error.
  __Resources:__
  * 📖 [Forms Need Validation – UX Collective](https://uxdesign.cc/forms-need-validation-2ecbccbacea1)
* [ ] **Indicators of required/optional** fields are provided.
* [ ] The **primary and secondary buttons** are clearly identifiable and are used following common practices.
  __Resources:__
  * 📖 [Primary & Secondary Action Buttons – UX Planet](https://uxplanet.org/primary-secondary-action-buttons-c16df9b36150)
* [ ] An example of the **different states of a button** were provided (Normal, hover, focused, pressed and inactive state).
* [ ] Buttons with built-in **loading indicators** are provided and can be applied to any button.

__Additional Resources:__

* 📖 [Design Better Forms – UX Collective](https://uxdesign.cc/design-better-forms-96fadca0f49c)
* 📖 [Design Better Input Fields – UX Collective](https://uxdesign.cc/design-better-input-fields-3d02985a8e24)
* 📖 [Designing Perfect Text Field: Clarity, Accessibility and User Effort](https://uxplanet.org/designing-perfect-text-field-clarity-accessibility-and-user-effort-d03c1e26004b)
* 📖 [Button UX Design: Best Practices, Types and States – UX Planet](https://uxplanet.org/button-ux-design-best-practices-types-and-states-647cf4ae0fc6)
* 📖 [How To Design Better Buttons — Smashing Magazine](https://www.smashingmagazine.com/2016/11/a-quick-guide-for-designing-better-buttons/)
* 📖 [Buttons in Design Systems – EightShapes – Medium](https://medium.com/eightshapes-llc/buttons-in-design-systems-eac3acf7e23)

**[⬆ back to top](#table-of-contents)**

### 2.6 - Responsive Web Design 📲

* [ ] The **mobile version** of the design is provided before or at the same time of the desktop version.

	> If the “**mobile first**” thinking was not followed by the creative team, some irregularities and inconsistencies may appear between the mobile and the desktop version. Check and flag these issues before starting the development of the project.
* [ ] The **tablet version** of the design in certain cases should be provide too.

⚠️ *The **pixel perfect** notion is today in a certain way deprecated. Today, it’s impossible to have a design that worked the same facing the multitude of the screen sizes.*

__Additional Resources:__

* 📖 [Official Google Webmaster Central Blog: Mobile-first Indexing](https://webmasters.googleblog.com/2016/11/mobile-first-indexing.html)

**[⬆ back to top](#table-of-contents)**

### 2.7 - Style Guide and component approach 📋

* [ ] All components designed on each page were created with the **component based approach**  (Atomic Design). If not, issues can occur in terms of performance, maintainability of the project...

  __Resources:__
  * 📖 [Atomic design][16]
  * 📖 [6 Reasons for Component-Based UI Development](https://www.tandemseven.com/technology/6-reasons-component-based-ui-development/)

* [ ] A **Style Guide** needs to be provided listing all elements, components, styles, dimensions. Some boilerplates like [UX Power Tools](https://www.uxpower.tools/) can help saving time and keep consistency in the designs.

__Additional Resources:__

* 📖 [Style Guides – Design + Sketch – Medium](https://medium.com/sketch-app-sources/tagged/style-guides)
* 📖 [The CodePen Design Patterns and Style Guide](https://codepen.io/guide)
* 📖 [Lonely Planet Travel Guides and Travel Information](http://rizzo.lonelyplanet.com/styleguide/design-elements/colours)
* 📖 [Styleguide](https://www.yelp.com/styleguide)

#### In the case of an existing project:

Sometimes, the creative team needs to add new pages or modules in an existing project. They should have or create a list of all existing elements and try to use what is already there. Having a Style Guide already created can save hours and ensure consistency of the project.


**[⬆ back to top](#table-of-contents)**

[6]:	https://guideguide.me/
[7]:	https://www.sketchapp.com/docs/canvas/rulers-guides-grids/
[8]:	https://getbootstrap.com/docs/4.0/layout/grid/
[9]:	http://flexboxgrid.com/
[10]: https://css-tricks.com/dont-overthink-it-grids/
[11]:	https://www.lifewire.com/aco-file-2619477
[16]:	http://bradfrost.com/blog/post/atomic-web-design/
[22]:	https://js.libhunt.com/
[23]:	https://bestof.js.org/
[28]:	https://gitter.im/Front-End-Checklist/Front-End-Design-Checklist
