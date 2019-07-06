Simple and clean treetable in vanilla js. 



How it works
-----

My goal was to dump hierarchical table data from a script to an html file and be able to expand and collapse the sub rows. 

Each row needs a unique ```id``` and to have the ```id``` of its parent added to its class list. Top level lows must be of class ```treeroot```.

```html
<table id="treetable">
 <tbody>
  <tr id="id1" class="treeroot"> <td>Item 1</td><td>123</td></tr>
  <tr id="id2" class="id1">      <td>Item 2</td><td>123</td></tr>
 </tbody>
</table>
```



