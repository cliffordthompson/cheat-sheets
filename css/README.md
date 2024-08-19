|Selector	|Example	|Description|
|---|---|---|
|element	|p	|Select all \<p\> elements|
|.class	|.myclass	|Select all elements with the class="myclass"|
|.class1 .class2	|.myclass1 .myclass2	|Select all elements with class="myclass2" that are descendants of elements with class="myclass1"|
|.class1.class2	|.myclass1.myclass2	|Select all elements with the class="myclass1 myclass2"|
|#id	|.myid	|Select all elements with id="myid"|
|*	|	|Select all elements|
|element.class	|p.myclass	|Select all \<p\> elements with class="myclass"|
|element1 element2	|div p	|Select all \<p\> inside of \<div\>|
|element , element	|div, p	|Select all \<div\> elements and all \<p\> elements|
|element1 > element2	|div > p	|Select all \<p\> elements that are children of \<div\>|
|element1 + element2	|div + p 	|Selects all \<p\> elements that are placed immediately after \<div\> elements|
|element1 ~ element2	|p ~ ul	|Select every \<ul\> element that is preceded by a \<p\> element|
|[attribute]	|[attr]	|Select all elements that have the "attr" attribute|
|[attribute=value]	|[attr=val]	|Select all elements with attr="val"|
|[attribute~=value]	|[attr~=val]	|Select all elements with an "attr" attribute that contain "val"|
|[attribute^=value]	|[attr^=val]	|Select all elements with an "attr" attribute value that start with "val"|
|[attribute$=value]	|[attr$=val]	|Select all elements with an "attr" attribute value that end with "val"|
|[attribute*=value]	|[attr~=val]	|Select all elements with an "attr" attribute value that contains "val"|
|:first-child	|p:first-child	|Select all \<p\> elements that are the first child of their parent|
|:last-child	|p:last-child	|Select all \<p\> elements that are the last child of their parent|
|:first-of-type	|p:first-of-type	|Select all \<p\> elements that are the first \<p\> element of their parent|
|:last-of-type	|p:last-of-type	|Select all\<p\> elements that are the last \<p\> element of their parent|
|:focus	|a:focus	|Selects the \<a\> element that has focus|
|:hover	|a:hover	|Selects the \<a\> element on mouse over|
|:visited	|a:visited	|Select the \<a\> elements that have been visited|
|:enabled	|input:enabled	|Select all \<input\> elements that are enabled|
|:disabled	|input:disabled	|Select all \<input\> elements that are disabled|
