# cinf301-spr18-demo
Foundation is a family of responsive front-end frameworks that make it easy for design work.
#feature
Semantic:Everything is semantic. You can have the cleanest markup without sacrificing the utility and speed of Foundation.

Mobile First:You can build for small devices first. Then, as devices get larger and larger, layer in more complexity for a complete responsive design.

#Used in Demo
layout: Grid. The grid is based on row and column. Default max width is 12 columns. Specify the widths of each column with the .small-#, .medium-#, and .large-# classes. Since Foundation is mobile-first, code for small screens first, and larger devices will inherit those styles.

    XY grid:It is present by default in foundation.css. The structure of XY grid uses .grid-x, .grid-y, and .cell as its base.

Callout：Callouts combine panels and alerts from Foundationinto one generic container component. It can be put any kind of content inside.

    Coloring:Callouts can be colored using the .secondary, .primary, .success, .warning, or .alert classes. 

    Making Closable:Pair the callout with the close button component and data-closable attribute to create a dismissable alert box.Adding the attribute data-close to any element within the callout will turn it into a close trigger.When using the data-closable attribute, you can optionally add Motion UI classes to the attribute to change the closing animation.
    
#JS/Animation
Orbit:An image and content carousel with animation support.

    Slide Container:The slide container houses each individual slide. 
    Next/Previous Arrows:Orbit controls use the class .orbit-previous and .orbit-next
    Bullets:The bullets serve two purposes: they mark the current slide, and can be clicked on to navigate to another slide.
    Using Animation:Orbit uses Motion UI CSS classes to animate slides around.
        data-anim-in-from-left: transition to play when a slide comes in from the left.
        data-anim-in-from-right: transition to play when a slide comes in from the right.
        data-anim-out-to-left: transition to play when a slide comes out to the left.
        data-anim-out-to-right: transition to play when a slide comes out to the right.

Dropdown Menu:Change a basic Menu into an expandable dropdown menu with the Dropdown Menu plugin.Add the class .dropdown and the attribute data-dropdown-menu to the menu container to set up the dropdown.

Reveal:Modal dialogs, or pop-up windows, are handy for prototyping and production. A modal is just an empty container, so you can put any kind of content inside it.

Animations：To use animations from the Motion UI library, include the data-animation-in="someAnimationIn" and data-animation-out="someAnimationOut" attributes.
