# My-Portfolio
## Description
This project is to build a portfolio describing about me, my project and my contact information using HTML and Advanced CSS.
## Technology Used 
| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| HTML    | [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) | 
| CSS     | [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)      |   
| Git | [https://git-scm.com/](https://git-scm.com/)     |    
## Code snippets:
The HTML page is divided into multiple sections to display links to sections, introduction, projects and contact information.
Every project is loacted in a project-container for styling purpose.
```html
<section><h3>PROJECTS</h3></section>
            <section id="projects" class="container">
                <section class="project1 project-container">
                    <header class="title">Refactor site</header>
                    <div class="info">
                        
                        <p>
                         Refactor the exisiting website to meet accessibility standard using semantic HTML and CSS.
                        </p>
                        <a href="https://github.com/srinithi19/refactor-site" target="_blank">Github</a>
                        <a href="https://srinithi19.github.io/refactor-site/" target="_blank">Demo</a>
                    </div>
                    
                </section>
                <section class="project2 project-container">
                    <header class="title">Placeholder 2</header>
                    <div class="info">
                        
                        <p>
                         Coming soon
                        </p>
                        <!-- <a href="https://github.com/srinithi19/" target="_blank">Github</a>
                        <a href="#" target="_blank">Demo</a> -->
                    </div>
                    
                </section>
                <section class="project3 project-container">
                    <header class="title">Placeholder 3</header>
                    <div class="info">
                        
                        <p>
                         Coming soon
                        </p>
                        <!-- <a href="https://github.com/srinithi19/" target="_blank">Github</a>
                        <a href="#" target="_blank">Demo</a> -->
                    </div>
                    
                </section>
```
corresponding CSS styling as below
```css
.container {
    display: flex;
    position: relative;
    align-items: center;
    flex-wrap: wrap;
    /* background-image: linear-gradient(lightgrey,lightblue); */

}

.project-container {
    /* display: flex;
    position: relative; */
    padding: 10px;
    text-align: center;
    border-style: dashed;
    border-width: 1px;
    width: 100%;
    margin: 20px;
    justify-content: center;
    display: inline-block;
    background-size: cover;
    width: 40vw;
    height: 60vh;
    border-radius: 1.5rem;
    background-position: inherit;
    background-size: 100% 100%;
    background-repeat: no-repeat;
    align-items: center;

}

/* setting backgrounf image for all projects */
.project1 {
    background: url("https://www.netsolutions.com/insights/wp-content/uploads/2021/05/code-refactoring-kpis.jpg");
    background-repeat: no-repeat;
    background-size: 100% 100%;
    width: 75%;
    align-items: center;
    justify-content: center;
    margin-left: auto;
    margin-right: auto;

}
```

Some of the CSS pseudo class are implemented to display project on hover over the Project section
```CSS
.project-container:hover,
.project-container:focus-within,
.project-container:active {
  transform: scale(1.1);
}

.project-container:hover .info,
.project-container:focus-within .info,
.project-container:active .info {
  opacity: 1;
}
```

For Responsive layout on resize the page, media query is used as follows
```CSS
@media screen and (max-width: 992px) {
    .project-container {
      width: 50%;
    }
}
@media screen and (max-width: 768px) {
    .project-container {
      width: 100%;
    }
}


```

## Outcome
Through this project i learnt the advanced properties of CSS such as flexbox, pseudo classes by building a webpage.
## Links
Github repo: https://github.com/srinithi19/My-Portfolio            
Application URL : https://srinithi19.github.io/My-Portfolio/
