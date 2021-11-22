now we need the two divs, the header and the div underneath, to float on top we need the cards with their background white 50%.
and we jsut throw that away underneath 600px, normal div, main section with blogs, and a cool footer, good names for the codeeee, clean sections in the CSS, NAV  MAIN  FOOTER   NAV  MAIN  FOOTER   NAV  MAIN  FOOTER




the page crypto uses a nav container, a container underneath, and then a flex container that just floats on top of both, giving it the ability to float on top of the background image, jsut that it moves when you compress the page, moves into normal, underneath the background-image

this is the code that makes the individual boxes stay above the background.image:::

.post-card {
    -ms-flex: 1 1 300px;
    flex: 1 1 300px;
    -ms-flex-direction: column;
    flex-direction: column;
    overflow: hidden;
    margin: 0 20px 40px;
    min-height: 300px;
    background: white 50%;  //this does it
    background-size: cover;
    border-radius: 5px;
    box-shadow: 8px 14px 38px #272c310f,1px 3px 8px #272c3108;
    transition: all .5s ease;
}


further c omment:: 

they are in multiple divs, jsut that these cards are the contents of the div, so they
actually:: it is the div class="post-feed" that decides where the div begins, it's just that to have the white around the card you must look at the individual card, and there is the white that makes the textt live inside a card so that it clearly lives on top without distruoption on top of the background image,

a flex div that goes on top of the header background-image, then the text must have a background: white 50%; this does itttttt