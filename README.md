# ***Carousel***

https://mlama007.github.io/a11yTabs/

### [Accessible Carousel](https://codepen.io/mlama007/pen/JBKbdZ) 
* Carousels use the same concept as Tabs


### _Functionality_
* Navigate to the carousel with the `Tab` key and naviagte to each section with the arrow keys ( `<` and `>` ).
* You can jump to the first section with the `Home` key
* You can jump to the last section with the `End` key

HTML
```html
<!-- Create element with class="tabs" -->
<div class="tabs">
    <div>
        <!-- Create elements with role="tabpanel" -->
        <div role="tabpanel">
            <!-- There MUST be a h3 heading -->
            <h3>Title goes here</h3>
            <p> Circle back strategic high-level 30,000 ft view so golden goose, yet today shall be a cloudy day, thanks to blue sky thinking. </p>
            <img src="http://via.placeholder.com/450x250" alt="Placeholder image- gray box">
        </div>
        <div role="tabpanel">
            <h3>Title 2 goes here</h3>
            <p> We've got to manage that low hanging fruit UX powerPointless, yet baseline the procedure and samepage your department..</p>
            <img src="http://via.placeholder.com/550x250" alt="Placeholder image- gray box">
        </div>
        <div role="tabpanel">
            <h3>Title 3 goes here</h3>
            <p> Circle back value-added UI, or globalize, for we need to harvest synergy effects. Design thinking.</p>
            <img src="http://via.placeholder.com/450x250" alt="Placeholder image- gray box">
        </div>
        <div role="tabpanel">
            <h3>Title 4 goes here</h3>
            <p> Bake in it. Translating our vision of having a market leading platfrom digital literacy for thought shower cannibalize.</p>
            <img src="http://via.placeholder.com/250x250" alt="Placeholder image- gray box">
        </div>
    </div>

    <!-- Create element with role="tablist" -->
    <div role="tablist" aria-label="Carousel- Use arrow keys to navigate">
        <!-- Create element with role="tab" -->
        <button role="tab"> </button>
        <button role="tab"> </button>
        <button role="tab"> </button>
        <button role="tab"> </button>
    </div>
</div>
```