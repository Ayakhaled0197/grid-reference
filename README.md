# grid-reference
##CSS grid Property
to use the grid property we do<br>
`display : grid;` <br>
then our web page is in grid system . <br>
> there is some properties to setup more
<hr>

`grid-column-start` <br>
this property change the starting order of the defined style box in columns 
```
.system{
 display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}
.item{
grid-column-start:3;
}
```
<hr>

`grid-column-end` <br>
this property change the ending order of the defined style box in columns 
```
.system{
 display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}
.item{
grid-column-end:3;
}
```
<hr>

