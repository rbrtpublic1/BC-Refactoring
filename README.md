# BC-Refactoring

## Intro

The criteria for this job ticket example was to refactor an existing website to solve some SEO and accessibility issues from within the html and css.  There are numerous improvements with the changes indicated by comments within the html and css files and in the summary below. There are also general upgrades to the code in terms of a cleaner, more logical hierarchy of html elements and an included css reset file to improve browser compatibility.

---

## Site Picture

![Refactoring Site Picture](./assets/images/BC-Refactoring-Site-Picture.png)

---

## Deployed Link

[https://rbrtpublic1.github.io/BC-Refactoring/](https://rbrtpublic1.github.io/BC-Refactoring/)

---

## Technologies Used

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [Git](https://git-scm.com/)
- [GitHub](https://github.com/)

---

## Summary

- Accessibility Enhancements: Clear titling and liberal use of alt tags in image and semantic elements have been added to satisfy the web's growing emphasis on accessibiity.
- Semantics Enhancements: The prior code version relied almost exclusively on div tags when it is more beneficial in the case of this website to incorporate semantic tags to improve SEO as well as accessibility.
- Hierarchy: Within the html, the hierarchy has been cleaned up to more coherently reflect the relationships between the site's elements and allow better indication of the enhancement comments.
- CSS consolidations: Redundant css classes were consolidated into multiple argument classes.
- CSS reset: Not part of the criteria but as part of best practices, a public domain css reset sheet was included and linked for better browser compatibility. [Attribution Link](http://meyerweb.com/eric/tools/css/reset/)

## Code Snippets

- Within HTML the commenting indicates enhancements made - example below:

```html
<!-- Semantics Enhancement: div to section -->
<!-- Accessibility Enhancement: alt="Online Reputation Management Pitch"> -->
<section id="online-reputation-management" class="online-reputation-management" alt="Online Reputation Management Pitch">
    <!-- Accessibility Enhancement: alt="Online Reputation Managment" -->
    <img src="./assets/images/online-reputation-management.jpg" alt="Client sees dramatic increase in online reputation" class="float-right" />
        <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. 
                Social media allows anyone with an internet connection to say 
                whatever they want about your business. 
                Online Reputation Management gives you the control over what 
                potential customers see when they search for your business.
            </p>
</section>
```

- Within CSS the commenting also indicates enhancements made - example below:

```css
/* Consolidated .search-engine-optimization, .online-reputation-management, .social-media-marketing css entries */
.search-engine-optimization, .online-reputation-management, .social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}
```

---

## README Author Links

Robert Schramm

- https://github.com/rbrtpublic1/BC-Refactoring

- [LinkedIn](https://www.linkedin.com/in/robertwschramm/)

## Website Owner

&copy; 2019 Horiseon Social Solution Services, Inc. / 
UC Berkeley Coding Bootcamp
