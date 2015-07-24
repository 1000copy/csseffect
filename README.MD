Sticky notes with CSS3 - http://robsobers.com/sticky-notes-with-css/

搞定bootstrap栅格(grid)系统 - http://boke.io/gao-ding-bootstrap-yuan-ma-zhi-zha-ge-gridxi-tong/

Create a Sticky Note Effect in 5 Easy Steps with CSS3 and HTML5 - Tuts+ Code Tutorial - http://code.tutsplus.com/tutorials/create-a-sticky-note-effect-in-5-easy-steps-with-css3-and-html5--net-13934


### What's the difference between an element and a node in XML

Stack Overflow - http://stackoverflow.com/questions/132564/whats-the-difference-between-an-element-and-a-node-in-xml

The Node object is the primary data type for the entire DOM.

A node can be an element node, an attribute node, a text node, or any other of the node types explained in the "Node types" chapter.

An XML element is everything from (including) the element's start tag to (including) the element's end tag.

	// it's OK
	var t = document.getElementById("div1")
    var t = t.getElementsByTagName("UL")[0]
    // it's Error
    // var t = document.getElementById("div1").childNodes[0]