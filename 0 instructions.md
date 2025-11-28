# Thanksgiving Poster
Do your best to make a web version of the flyer in the images folder, using best-match web-based font substitutions.   

This is in Replit Teams under Thanksgiving Poster.  All CSS should be in an external sheet, using tags, classes and IDs to select. Here's how I'd do it (but there are other ways):

## Stage 1: Basic CSS 
1. View the image in a tab to get poster dimensions via Inspector.
1. Create a parent poster id div and give it those dimensions.
1. Center the poster div and give it a background color FFF7F4
1. Center-align all text inside the poster div
1. Create a headings div for the headings
1. Create a h4 tag for Murphy's 2nd Annual   
1. Create a h1 tag for Thanksgiving
1. Color the text inside headings c94a13
1. Create a div for the ribbon inside headings, 400 pixels wide, 100 pixels high
1. **Display the headings divs as inline-block.**
1. Set ribbon.gif as the background, no repeat, top aligned.
1. Auto-center the ribbon div horizontally.
1. Color any inside text FFF7F4. 
1. Put an H2 for FOOD DRIVE inside that div.
1. Give the ribbon padding so FOOD DRIVE is vert centered (eyeball it)
1. Create a bottom div below ribbon with 270 px height and full width.
1. Color the bottom div B33D0B
   
## Stage 2: Positioning

1. Give the bottom div absolute positioning, with left 0 and bottom 0
1. Give the poster div relative positioning, so bottom is inside it.
1. Create a div for the turkey, under the ribbon div.
1. Give the turkey div absolute positioning, left and right set to 0
1. Give the turkey auto margins to center it horizontally
1. Give the turkey image enough top margin to match the poster.
1. Give the bottom div a z-index of 1.
1. Give the turkey div a z-index of 2. It should be on top now.

## Stage 3: Bottom Boxes
1. Create a div with id of three-box
1. Absolutely position div left 0 bottom 0, 100% width
1. Include a date div floated left, 33% width
1. Include a details div floated left, 67% width
1. Inside details, put accepting and more divs
1. Put in the text, with H4, H3 (date) and P tags
1. Link the more details URL with an a tag
1. Color the a tag link text FFF7F4
1. Set text decoration to none on the link text
1. Give backgrounds of c94a13 to date and accepting
1. Add box sizing to include padding in percentage widths
1. Give three-box a padding of 25 pixels - you might change that later
1. Give details a left-padding of 20px - you might change that later

## Stage 4: Fine Tuning
1. Use top margins to position items above the turkey
1. Use padding with the Accepting div
1. Select different fonts and font sizes to match poster
1. Adjust what you can adjust. Maybe the turkey top margin?
1. Set line heights in em fractions when there are spaces between lines
1. Keep tweaking until you feel comfortable clicking back and forth

## Stage 5: Fancy Fonts
1. You can install Google Fonts that look like what's in the poster:
1. Use fonts.google.com to find a font if you can
1. Download the font, unzip it, and upload the folder into your Repl.
1. Import it using @font-facein your .css file:
@font-face {
    font-family: "CUSTOM FONT FAMILY";
    src: url("PATH/TO/FONT-FILE");
}
1.The Typewriter font for Thanksgiving was: https://fonts.google.com/specimen/Special+Elite
@font-face {
    font-family: "Special_Elite";
    src: url("Special_Elite/SpecialElite-Regular.ttf");
}
