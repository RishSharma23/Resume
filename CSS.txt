/* You can poke around this CSS if you want to customize your formatting / styling further */
/* You can even import custom fonts! */




/* fonts */
@import url('https://fonts.googleapis.com/css2?family=Tinos:wght@400;700&display=swap');




/* meta */
body {
  font-family: Tinos, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", sans-serif;
  font-size:  13.1px; /*change this to change body font size, does not change the sections headers or Rish sharma name */
  font-weight: 400;
}




.spacer {
  margin: 0px auto;
}




.vertical-spacer {
  height: 5.7px; /*change this to condese page vertically*/
}




/* ordering of content */
h1 {
  order: 0;
}




.headerInfo {
  order: 1;
}




/* styling content */
h1, h2, h3, p, a, li {
  color: black, lightgray;
}
h5{/* use for light comments*/
  color: rgb(0, 0, 0);
  margin: 0px 0px ;
  font-weight: lighter;
  padding-left: 24px;
}
h2 {
  margin: 8.0px 0px; /* use for section headers*/
}




h3 {
  margin: 4.49px 0px; /*use for slant comments*/
}




h1 {
  color: black;
  text-transform: uppercase;
  text-align: left;
  font-size: 29.0px; /*rish Sharma size*/
  margin: 0;
  padding: 0;
}




h2 {
  border-bottom: 1px solid #000000; /*line size*/
  text-transform: uppercase;
  font-size: 15.0px; /* section header size */
  padding: 0;
}




h3 {
  display: flex;
  font-size: 14.0px; /* position title size*/
  padding: 0;
  justify-content: space-between;
}




p {
  margin: 0;
  margin-top: 1.5px;
  margin-bottom: 1.5px;
  padding: 0;
  display: flex;
}




li > p {
  display: inline;
}




a {
  color: black;
}




ul {
  margin: 4px 0;
  padding-left: 24px;
  padding-right: 24px;
}




strong, em, a {
  padding-left: 1px;
  padding-right: 2px;
}




/* header info content */
.headerInfo > ul {
  display: flex;
  text-align: center;
  justify-content: center;
  margin: 6px auto 0px !important;
  padding: 0;
}




.headerInfo > ul > li {
  display: inline;
  white-space: pre;
  list-style-type: none;
}




.headerInfo > ul >li:not(:last-child) {
  margin-right: 8px;
}




.headerInfo > ul > li:not(:last-child):after {
  content: "•";
  margin-left: 8px;
}
@media print {
   body {margin-top: 0px; margin-bottom: 0px;
         margin-left: 0px; margin-right: 0px}
}







