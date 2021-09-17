# flexbox-minesweeper

## The goal

The goal of this project is to create a web page that reproduces the graphical interface of the minesweeper game.

## The technologies used are:

1. HTML
2. CSS
  * Specifically the FlexBox module

## Page construction logic

### With html

  * I created a main block () which served as a reference surface to center the game interface in the page.
  >     <div class = "main_container">

  * And I created a second block to contain the game items.
  >     <div class = "items_container">

  * And I created 64 small boxes which are the elements of the game (containing either a bomb or a number or just nothing)
  >     <div class = "item_box">

### With css

  * I resized and modified the appearance of each block according to its use (according to the instructions related to the challenge)
I applied the flexbox properties to organize the block layout


    ** In items_container **

        display: flex;
        flex-wrap: wrap;
        align-content: flex-start;
   
    ** In item_box **

        flex-grow: 1;

### Deployment method

  * GitHub page


[Please click here to view the page](https://logmodia.github.io/flexbox-minesweeper/)