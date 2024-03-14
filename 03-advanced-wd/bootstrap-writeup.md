# Process Writeup

## Name: Hao
## Course: SEP 10
## Period: 5
## Concept: Bootstrap

### Context
    Bootstrap is currently what we are learning for unit 3 and it basically makes coding and advanced web design extremely easy and simple as all bootstrap does most of the code for us since it has been built upon for almost 13 years and has most of the code is already written for us for example the html and the css has already been written and all we need to do is pick a template already given and complete the code.

### What I've learned
    What I've learned in bootstrap so far, so far we've learned about the grid system that bootstrap uses which is the template which is split into 12 and since 12 is devisable by 1, 2, 3, 4, and 6 which is very useful for making websites responsive and so the grid for the website can be split in multiple ways and in multiple designs for unqiue and also responsive websites. Next we learned about containers and container fluid and breakpoints. To start breakpoints are more or less how your screen size affects the website which makes the website responsive for example a phone will have a small screen size and can have a pixel range between extra small to medium, and the pixel ranges for extra small, small, and medium are >576, 576-767, and 768 - 991 respectively although there are a few more pixel sizes above medium. Next as the name states the container for all of the code in your website design. For example (Insert code lol) however there is a difference between normal containers and container fluid's. Containers will at certain breakpoints if stated in the code will take up sections of the screen with the only expection being the extra small breakpoint which at its breakpoint will take up 100% of the screen, then with container fluid it will no matter what breakpoint it is wether it is 500 pixels or 1000 pixels will always be at 100% size. Finally we learned about components which are basically add on to which you can add on to a website to make it more appealing or more customer friendly for example if I added ``` html <div class="dropdown">
  <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton1" data-bs-toggle="dropdown" aria-expanded="false">
    Dropdown button
  </button>
  <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
    <li><a class="dropdown-item" href="#">Action</a></li>
    <li><a class="dropdown-item" href="#">Another action</a></li>
    <li><a class="dropdown-item" href="#">Something else here</a></li>
  </ul>
</div>

```
So if I were to add this code to my website I could add customizable dropdown buttons that viewers of my website could click on and hit whatever customized button I chose.

### Challenge 1
A challenge I had was when we were first learning about containers and its counter part container fluid as I didn't realize they were quite different even though they were at the same time quite similar. However after a little bit of tinkering and seeing the results of tiny changed I realized there was indeed a major different between container and container fluid as if I had used code like this ```html  <div class="container-fluid"  >
            <div class="row">
              <div class="col-lg-4" id= "col1">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lorem donec massa sapien faucibus. Aliquet lectus proin nibh nisl condimentum id. Ac turpis egestas maecenas pharetra convallis. Volutpat consequat mauris nunc congue nisi vitae suscipit tellus mauris. Convallis a cras semper auctor neque. Tempor nec feugiat nisl pretium fusce id velit ut. Hendrerit gravida rutrum quisque non tellus orci. Vel elit scelerisque mauris pellentesque pulvinar. Vitae proin sagittis nisl rhoncus mattis rhoncus urna neque viverra. Fringilla urna porttitor rhoncus dolor purus non enim praesent. Sit amet aliquam id diam maecenas ultricies.
              </div>
              <div class="col-lg-4" id= "col2">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lorem donec massa sapien faucibus. Aliquet lectus proin nibh nisl condimentum id. Ac turpis egestas maecenas pharetra convallis. Volutpat consequat mauris nunc congue nisi vitae suscipit tellus mauris. Convallis a cras semper auctor neque. Tempor nec feugiat nisl pretium fusce id velit ut. Hendrerit gravida rutrum quisque non tellus orci. Vel elit scelerisque mauris pellentesque pulvinar. Vitae proin sagittis nisl rhoncus mattis rhoncus urna neque viverra. Fringilla urna porttitor rhoncus dolor purus non enim praesent. Sit amet aliquam id diam maecenas ultricies.
              </div>
              <div class="col-lg-4" id= "col3">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lorem donec massa sapien faucibus. Aliquet lectus proin nibh nisl condimentum id. Ac turpis egestas maecenas pharetra convallis. Volutpat consequat mauris nunc congue nisi vitae suscipit tellus mauris. Convallis a cras semper auctor neque. Tempor nec feugiat nisl pretium fusce id velit ut. Hendrerit gravida rutrum quisque non tellus orci. Vel elit scelerisque mauris pellentesque pulvinar. Vitae proin sagittis nisl rhoncus mattis rhoncus urna neque viverra. Fringilla urna porttitor rhoncus dolor purus non enim praesent. Sit amet aliquam id diam maecenas ultricies.
              </div>
            </div>
          </div>

```
Though this code I would have had three pieces of of text that would have reached THE ENTIRE span of the screen and that is the biggest difference HOWEVER if I had changed it to a regular container I would have had three pieces of text that DIDNT reach the whole span of the screen.










### Challenge 2
A second challenge I had was that I had a hard time figuring out how to get the bootstrap components to work properly while tinkering as when I copy pasted this code into jsbin 
```html 
<div class="accordion" id="accordionExample">
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingOne">
      <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
        Accordion Item #1
      </button>
    </h2>
    <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the first item's accordion body.</strong> It is shown by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingTwo">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
        Accordion Item #2
      </button>
    </h2>
    <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingThree">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
        Accordion Item #3
      </button>
    </h2>
    <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
</div>


```
And although this code should have worked as it was directly from the bootstrap website it didn't and after a little while I decided to ask one of my friends and they had helped me realized that it wasnt the code that was wrong it was the required meta tags as I didn't have the required meta tags to properly utilize bootstrap.


Take aways
* Tinker
* Ask for help
* Use what is available to you






































