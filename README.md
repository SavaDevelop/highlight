# highlight
Text higlighting is part of DynaCloud – where tags/keywords are automatically highlighted once they’re clicked – so I took that code and made it a stand-alone JavaScript text highlighting jQuery plugin.

Usage
Add highlight

h2 Style the highlight class
=====================
Create an entry in your style sheet for the highlight class.

.highlight { background-color: yellow }

h2 Highlight terms
=====================
Call the highlight function with the text to highlight. To highlight all occurrances of “bla” (case insensitive) in all li elements, use the following code:

$('li').highlight('bla');


h2 Remove highlighting
=====================
The highlight can be removed from any element with the removeHighlight function. In this example, all highlights under the element with the ID highlight-plugin are removed.

$('#highlight-plugin').removeHighlight();
