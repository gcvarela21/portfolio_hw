# Responsive Portfolio
Unit 02 CSS and Bootstrap Homework: Responsive Portfolio

This project is an exercise in using Bootstrap's grid system to replicate sample images for a responsive portfolio web site.
​
![Sample Page](https://gcvarela21.github.io/varela_portfolio/img/992-index.png)
​
## **Built With**
* [HTML](https"//w3schools.com)
* [CSS](https"//w3schools.com)
* [Bootstrap](https://getbootstrap.com/)
* [gitBash](https://git-scm.com/downloads)
* [gitHub](https"//gitHub.com)
* [Atom](https://atom.io/)
______________________________________________________________________________

### **Summary**
Using Bootstrap's grid I was able to use the utility items such as flex, layout gutters and columns, break points, and nav bars to build this site. Using reference images and specified break points I was able to recreate the sample on a live web setting hosted on git hub, using git commands from gitBash to add, commit, and push code from my personal computer onto gitHub's server for version control.  
​

​
______________________________________________________________________________
​
#### **Code Snippet**
​
Nested Rows and Columns created the spacing and layout for the responsive elements:
​
```
<div class="row">
  <div id="whiteOut" class="col-12 col-md-7 col-lg-7">
        <div  class="col-12 col-md-12 col-lg-12">
          <div class="page-header">
            <h1>About Me</h1>
          </div>
        </div>
        <div id="lineIt" class="col-12 col-md-12 col-lg-12">
          </div>
        <div class="col-12 col-md-12 col-lg-12  gy-3">
          <img src="http://placehold.it/350x350" alt="Placeholder" />
            <p> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque dignissim, felis ut dictum tristique, nibh erat feugiat libero, sit amet fringilla mauris velit in mi. Duis tempus felis vitae felis vulputate pretium. Nullam commodo, est ac auctor ornare, eros nisi fringilla sem, non pulvinar tortor lorem sit amet sem. Aenean quis erat facilisis, porttitor ex cursus, luctus enim. Curabitur et metus in lacus tristique sagittis et in lorem. Nunc id nisi et neque fringilla ultricies. Aenean at feugiat elit, a posuere justo. Pellentesque egesta dolor et nisi venenatis, nec fermentum urna fringilla. Etiam efficitur porta purus, id posuere sem congue a.
            </p>
            <p> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque dignissim, felis ut dictum tristique, nibh erat feugiat libero, sit amet fringilla mauris velit in mi. Duis tempus felis vitae felis vulputate pretium. Nullam commodo, est ac auctor ornare, eros nisi fringilla sem, non pulvinar tortor lorem sit amet sem. Aenean quis erat facilisis, porttitor ex cursus, luctus enim. Curabitur et metus in lacus tristique sagittis et in lorem. Nunc id nisi et neque fringilla ultricies. Aenean at feugiat elit, a posuere justo. Pellentesque egesta dolor et nisi venenatis, nec fermentum urna fringilla. Etiam efficitur porta purus, id posuere sem congue a.
            </p>
        </div>
    </div>
  </div>
  <div class="col-12 col-md-5 col-lg-5 ">
  </div>
</div>
```
______________________________________________________________________________
​

​**Code Snippet**

​For the about page finding a reference for getting the text to wrap around an image was a challege. I opted for an image float and text justification to do the trick.
​
```
    <title>About Gloria Varela</title>

    <style>

    img {
        float: left;
        margin: 5px;
        padding-right: 10px;
        padding-top: 10px;

    }
    p {
        text-align: justify;
        font-size: 25px;
    }
    </style>
```
______________________________________________________________________________
​
​
#### **Deployed Link**
​
* [See Live Site on Git Hub](https://gcvarela21.github.io/varela_portfolio/)
​
### **The Author Links**
​
* **Gloria C Varela**

- [Link to Portfolio Site](https://www.glo.digital)
- [Link to Github](https://github.com/gcvarela21)
- [Link to LinkedIn](https://www.linkedin.com/in/glovarela)
​
​
​
______________________________________________________________________________
​
#### **License**
​
This project is licensed under the MIT License
​
​
