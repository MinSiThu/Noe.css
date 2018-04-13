# Noe.css
I haven't finished the framework yet. Contribution is warmly welcomed.

Welcome everyone from *Noe.css*!

I would like to contribute this css framework.
I have built some of the main portions of the framework but I still have a lot of features to finish.
Grid Systems,Buttons,Colors and other features like tags,alerts,cards have finshed.

### Download
For front-end developer who would use **Noe.css** will have to download only Noe.css.
Other Scss files are meant for contributors and those who wolud like to give feedbacks upon codes.

**Hope for some feedbacks after using the framework**

# Documentation

I use OOCSS methodology for this framework. Thus, content and container, skin and structure are separated.

## Colors

There are 8 basic colors in Noe.css.
* Primary
* Secondary
* Success
* Info
* Warning
* Danger
* Dark
* Light

For *Responsive*, Noe.css has grids system.
Like Bootstrap, `lcol` is for screen with **min-width:993px**,
                `mcol` is for screen with **min-width:601px**
                `col` is for screen with **max-width:559px**
And `noe-mobile` is for 100% width in **mobile - max-width:559px**.
Example;
`
  <div class='container'>
      <div class='row'>
        <div class='noe-mobile mcol6 lcol6'>Col 1</div>
        <div class='noe-mobile mcol6 lcol6'>Col 2</div>
      </div>
  </div>
`

For *background-color* , you have to use `noe-danger` class.
eg; `noe-danger , noe-warning`
Moreover, *changing background-color on hovering text* , you have to use `noe-hover-text-success` class.
eg; `noe-hover-danger , noe-hover-secondary`


For *text color* , you have to use `noe-text-info` class.
eg; `noe-text-success , noe-text-primary`
Moreover, *changing color on hovering text* , you have to use `noe-hover-text-success` class.
eg; `noe-hover-text-danger , noe-hover-text-secondary`

Just like background-colors and text-colors,
*border style* can be set with `noe-border-info` and `noe-hover-border-success`.

For *code-style* on Noe.css , you can use `<code>` for single-line code.
`<pre>` for multiple lines code. `<kbd>` for keyboards inputs.
`<samp>` for output of a program.

For *button* , `noe-btn, noe-btn-lg, noe-btn-sm` class are available.
`noe-btn-block` is for block-level button.
There is also `noe-btn-group, noe-btn-group-lg, noe-btn-group-sm` for button-groups.
`
<div class='noe-btn-group noe-info'>
  <button class='noe-btn'>JavaScript</button>
  <button class='noe-btn'>Perl</button>
  <button class='noe-btn'>XML</button>
</div>
`
Since *Padding and Margin* are not set in Noe.css, there are setting classes in Noe.css.
`noe-padding,noe-padding-small` are for padding.
`noe-text-center,noe-text-left` and `noe-text-right` for text-align.
`noe-topleft,noe-topright,noe-topmiddle`and `noe-bottomleft,noe-bottomright,noe-bottommiddle` 
are setting position of elements.

For **form**, check the example below;
`<form>
    <div class="noe-form-group">
      <label for="name">Name</label>
      <input type="text" id="name" class="noe-text-input">
    </div>
    
    <div class="noe-form-group">
      <label for="password">Name</label>
      <input type="password" id="password" class="noe-text-input">
    </div>
    
    <input type="submit" class="noe-btn noe-info" value="submit">
</form>`

# **Components**

# *tag*
`<span class="noe-tag>css</span>"` is tag component.

# *Card*
`<div class='noe-card noe-success'>
  <div class='noe-card-header'>Header</div>
  <div class='moe-card-body'>
      <p>This is card body</p>
      <button class='noe-btn noe-primary'>Like</button>
  </div>
</div>
`
# *Alert*
`
  <p class='noe-alert noe-warning'>This is warning for security</p>
`

# Since I built this framework for educational purpose, any bug-fixing and contribution is warmly welcome.
## Have fun! :smile:


![Noe.css logo](https://github.com/MinSiThu/Noe.css/blob/NoeCSS/Noe%20logo.jpg)
