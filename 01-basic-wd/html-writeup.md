# Process Writeup

## Name: Hao
## Course: Sep 10
## Period: 6
## Concept: HTML


### Context 
HTML is the shorted way of saying hyper text markup language and in sense it is the skeleton for text in a browser or whatever you will use it for. The goal in html was just to set a base for our code and what we will use fot our freedom project through out the year. 
I.E
HTML = What shows up be it images, texts, or links

### What ive learned in HTML
So far in the first unit we've strictly been learning HTML and its code for example using `<img>` to insert images to the page or using `<li>` for lists so on and so forth. However to learn all to this we've mainly using a couple things like freecodecamp or just paying attention during the class.


### Challenges 
The challenges ive faced so far were mainly funny ones as the solutions were generally right infront of my face the whole time and I wouldn't have struggled if I had paid attention and read the instructions on FCC. For example one challenge I had orignally was adding values to the Radio Buttons and Checkboxes. For example in FCC it would give you this line of code to add a value too each button or checkbox.

```html
    <label for="indoor" > <input id="indoor" type="radio" name="indoor-outdoor" > Indoor</label>

    <label for="outdoor"><input id="outdoor" type="radio" name="indoor-outdoor" > Outdoor</label><br>

    <label for="loving"><input id="loving" type="checkbox" name="personality"> Loving</label>

    <label for="lazy"><input id="lazy" type="checkbox" name="personality"> Lazy</label>

    <label for="energetic"><input id="energetic" type="checkbox" name="personality"> Energetic</label>
```
So then I skimmed through the insturctions and had changed the code to 
` <label for="indoor" value = "indoor"> <input id="indoor" type="radio" name="indoor-outdoor"> Indoor</label>`
puttting  `value = "indoor` inside the `<label>` tag.

However after seeing if it would work or not the code didnt end up working I did some tinkering for a bit and when that ended up not working I decided to go through the instructions one more time a little bit more carefully I thought to my self why would a value input be put inside a label tag when it really should be with the input tag with all of the other code that was giving another value to the code. So I then changed the code to this code which ended up working. 



```html
    <label for="indoor" > <input id="indoor" type="radio" name="indoor-outdoor" value= indoor> Indoor</label>

    <label for="outdoor"><input id="outdoor" type="radio" name="indoor-outdoor" value= outdoor> Outdoor</label><br>

    <label for="loving"><input id="loving" type="checkbox" name="personality" value= loving> Loving</label>

    <label for="lazy"><input id="lazy" type="checkbox" name="personality" value= lazy> Lazy</label>

   <label for="energetic"><input id="energetic" type="checkbox" name="personality" value= energetic > Energetic</label>
```
[Freecodecamp Lesson](https://www.freecodecamp.org/learn/responsive-web-design/basic-html-and-html5/use-the-value-attribute-with-radio-buttons-and-checkboxes)

### Challenge 2
A more technical challenge was using `<div>` and figuring out how that worked as when I had gotten the challenge in FCC I was originally confused as the code had done nothing to the outcome so I went and tested it on replit which also ended up with nothing but I kept trying which leading to nowhere. But after the lesson on divs and span it was more apparent that div wasnt meant for the HTMl code but instead was grouping parts of the code to be influenced but the CSS. For example in this piece of code you can see that it is surrounded by a div tag with the named "similarites" this basically tells the CSS code that it should be treated differently 

### Div Code
```html
<div class="similarities">
  <h2>Similarities</h2>
  <ul>
    <li>they are both <span class="blue"> containers </span> that hold content</li>
    <li>they are invisible by default</li>
    <li>they are styled with <code>&lt;style&gt;</code> and <code>&lt;class&gt;</code></li>
  </ul>
   </div>
```
### CSS Code

```css
.similarities {
    background-color: #EAFFF5;
    padding: 50px;
}
```



Some takeaways
* Read the instructions carfully
* Tinkering is very helpful
* Pay attention to the lesson 
*

