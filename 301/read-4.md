# css Grid
is a two-dimensional grid-based layout system that aims to do nothing less than completely change the way we design grid-based user interfaces.
![#](https://camo.githubusercontent.com/b8d898e9ae60fcc04f27d4e5d25217be2d0d9f4d12e5741776d3da9d053a6db0/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f3836302f312a4669665a55477a39374f6e6d623752554f61697262672e706e67)

`display: grid` : define a container element as a grid
`grid-template-columns` and `grid-template-rows` : set the column and row sizes.
`grid-column and grid-row` : place its child elements into the grid
`grid-column-start` : specify the start point of grid column.
.container {
  display: grid;
  grid-template-columns: 50px 50px 50px 50px;
  grid-template-rows: auto;
  grid-template-areas: 
    "header header header header"
    "main main . sidebar"
    "footer footer footer footer";
}
.item-a {
  grid-area: header;
}
.item-b {
  grid-area: main;
}
.item-c {
  grid-area: sidebar;
}
.item-d {
  grid-area: footer;
}

## Regular Expression = RegEx
is a sequence of characters that specifies a search pattern. Usually such patterns are used by string-searching algorithms

`^the` : matches any string that starts with **the**.
`endword$` : matches a string that ends with endword .
`^word endword$` : exact string match (starts and ends). 
`roar` : matches any string that has the text **roar** in it
`()` : Capturing group.
`[]` : match any character in set.
`A-Z` : match a charcter from A to Z
`\w` : Matches any word character (alphanumeric & underscore)
 Matches 1 or more of the preceding token.



