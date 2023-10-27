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
grid-column-start:1;
grid-column-end:3;
}
```
<hr>

`grid-column` <br>
this property is a shorthand of `grid-column-start` & `grid-column-end` <br>
```
.system{
 display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}
.item{
grid-column:4/6;
}
```
<hr>

`grid-row-start` <br>
this property change the starting order of the defined style box in rows
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

`grid-row-end` <br>
this property change the ending order of the defined style box in rows
```
.system{
 display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}
.item{
grid-column-start:3;
grid-column-end:3;
}
```
<hr>

`grid-row` <br>
this property is a shorthand of `grid-row-start` & `grid-row-end` <br>
```
.system{
 display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}
.item{
grid-row:4/6;
}
```
<hr>

`grid-area` <br> 
this property is a shorthand  `grid-row-start` , `grid-column-start` , `grid-row-end` , `grid-column-end` respectively.
```
.system{
 display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}
.item{
grid-area:1/1/3/6;
}
```
<hr>

`order` <br>
this property controls the order of the style boxes , its similar tp `z-index` property .

```
.system{
 display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}
.item{
order: 2;
}
```
<hr>
