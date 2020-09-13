# Read:04 - Responsive Web Design and Regular Expressions

### Regex
RegExr – is a way to find and edit the text. 

The between brackets is what you place regex in.   /  / 

Refer to Regex Cheat-sheet.



### CSS Grids

1.	Define the grid container: 
Display: grid;
Grid-template-columns: col1 col2 col3 col4 etc. they are defined by sizes. 
Grid-template-rows:  row1 row2 row3 row4 etc. They are defined by sizes. 


Then define the object you are placing into the location specified by the column and row.
.item {
	grid-column: ¼;
	Grid-row: 2/3;
}

There are a lot of variations and work arounds for certain instances. For example, repeat, auto-repeat, auto-fill, auto-fit etc. Refer to Grid-Reference.


Using grids is a great way to accomplish a responsive web design from different screen sizes. 

Instead of using percentages ( fr ) is a way to define the measurements to equal the percentage value. 1fr out of 4fr’s, is equal to 25%. 

Column-gap: 20px;    - is a way to create spaces between each specified grid. 


The Holy Grail layout: 

body {
display: grid;
grid-template-columns: 200px 1fr 200px;
grid-template-rows: auto 1fr auto;
height: 100vh;
}
