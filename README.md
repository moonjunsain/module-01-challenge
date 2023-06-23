# Module-01-Challenge 

## Technology Used 

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| HTML    | [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) | 
| CSS     | [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)      |   
| Git | [https://git-scm.com/](https://git-scm.com/)     |    

## Description 
This project is to refactor the horizeon website code to the following guide line
GIVEN a webpage meets accessibility standards
1. WHEN I view the source code
 THEN I find semantic HTML elements
2. WHEN I view the structure of the HTML elements
 THEN I find that the elements follow a logical structure independent of styling and positioning
3. WHEN I view the image elements
 THEN I find accessible alt attributes
4. WHEN I view the heading attributes
 THEN they fall in sequential order
5. WHEN I view the title element
 THEN I find a concise, descriptive title

[Visit the Deployed Site](https://youtu.be/BFyeuLhjcPY)


## Table of Contents (Optional)

If your README is very long, add a table of contents to make it easy for users to find what they need.

* [Code Refactor Example](#code-refactor-example)
* [Usage](#usage)
* [Learning Points](#learning-points)
* [Author Info](#author-info)
* [Credits](#credits)
* [License](#license)


## Code Refactor Example


```html
<div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
    </div>
```

Converting the above non-semantic div with the class of 'header' to an appropriate 

```html
<header class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <!-- Make it semantic: div => section -->
        <section>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </section>
    </header>

```


## Expected Look
Please email me any error you encounter. Below is the image you should be looking at when you open this project.
![screenshot](./expected_look/hori_sc.png)


## Learning Points 


I Learned some of the difference between semantic and non semantic html.
I also got accustomed to pushing and commiting my work to github using commandline.


## Author Info
June Moon
* Email: [moonjunsain@gmail.com](moonjunsain@gmail.com)

### Farley Wittles 

* [Github](https://github.com/moonjunsain)


## Credits
June Moon (ME)


## License
MIT License


---

© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
