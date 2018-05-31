

1. variable nextplayer is declared. and is equal to boolean true. 

2. variable boardstate is initialized. nine nulls exist. the variable is an array. 

purpose: to keep track of the board outside of the DOM. 

3. Function play is declared.
args: 1

variable row is declared. box parent element returns the parent element of an specified element.
get attribute is row. DOM interacts with a value get from row. 

variable column is declared. box get attribute connects with column value. DOM. 

if else statement. 

user case: when a player clicks, X comes visible, when the nextplayer clicks, it shows O. Then Xs and then Os. 

same player cannot play twice in a row. because nextplayer does not equal nextplayer. 

if all the boxes have been clicked, then system alerts that "grow up...".

4. function populateBoard is declared. 
variable board equals DOM element document. get element by id. which taks information from tic tac board. 
variable row and column is declared.

for loop inside a for loop.
var i and j is set to 0. i and j increases once per loop, until 3. 

row equals board [i]. children is a DOM related. column is set to equal row j. 

column.innerHTML equals boardstate i and j. 

user case: it makes sure that the game is played following rules. 

5. function buildboard is declared. 

variable board is set to equal DOM element document get element id. which relates to the board. 
var row and cell is defined. 

two for loops. within inside. 
i starts from 0, goes up by 1 each time and stops at 3. 
row equals board. insert row. DOM. 
row. set attribute, row and i. 

another for loop: var j set to zero, j up to 3. goes up once per loop.

cell equals to row. insertcell, DOM. j. 

cell. innerHTML equals to boardstate i and j. 

cell.setAttribute. DOM. connects to column and j.

another cell attr. connects to onclick and play this. DOM.

6. windows eventlistener DOM. 

user case: DOM related. when the user click anywhere. something happens. 

