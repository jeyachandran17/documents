### Difference between documents and windows objects ?

|`Documents`|`Windowa`|
|-----------|---------|
|It represents any HTML documents or web page that is loaded in the browser|It represents a browser window or frame that displays the contents of the webpage|
|Each HTML document that gets loaded into a window becomes a document object|It is the top most object and outermost of the object.|
|It is loaded inside the window|It is the very first object that is loaded in the browser|
|It is the object of window property|It is the object of the browser|
|All the tags,elements with attributes in HTML are part of the document |Global objects, functions & variables of JS  are members of the window object|
|We can access the document from a window using the `window.docments`|We can access the window from the window only `i.e ) window.window` |
|The document is part of BOM and DOM|The window is part of BOM, not DOM|
|The document object is property of window object that points to the DOM|The window object represents a windows/tab containing a DOM document|
|Properties  of document objects such as title, body, cookies,.etc, can also be accessed by a window `i.e) window.document.title`|Properties of the window object cannot be accessed by the document object|
|``` Syntex: document.property_name; ( or ) document.method_name; ```|``` Syntex:window.property_name; ( or ) window.method_name; ```|
|``` Example : Var a = document.body; → property name Var b = document.close(); → method name ```|``` Example : Var a = windows.toolbar; → property name Var b = windowt.alert(); → method name ```|


```
Keywords : 

	HTML → Hypertext Markup Language
	DOM   → Document Object Model
	BOM	→ Browser Object Model
	JS	→ JavaScript

```