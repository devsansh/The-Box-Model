<h1 align=“center”>Box Model</h1>

<p align=“center”> <img src=“boxdim.png” alt=“Box model diagram” width=“200px”> </p>

<p align=“center”>The box model is a concept that describes how HTML elements are styled and laid out on a web page. It consists of four parts: content, padding, border, and margin.</p>

<h2>Content</h2>

<p>The content is the innermost part of the box model, where the actual text and images appear. The width and height properties of an element specify the size of the content area.</p>

<h2>Padding</h2>

<p>The padding is the space between the content and the border. It can have different values for each side (top, right, bottom, left) or one value for all sides. The padding is transparent and does not affect the background color or image of the element.</p>

<h2>Border</h2>

<p>The border is the line that surrounds the padding and content. It can have different styles (solid, dashed, dotted, etc.), colors, and widths. The border also affects the overall size of the element.</p>

<h2>Margin</h2>

<p>The margin is the space outside the border. It creates a gap between adjacent elements and pushes them away from each other. The margin is transparent and does not affect the background color or image of the element.</p>

<h2>Box Sizing</h2>

<p>By default, when you set the width and height properties of an element, you only set the size of its content area. To calculate its total size, you need to add up its padding, border, and margin as well.</p>

<p>However, you can change this behavior by using the <code>box-sizing</code> property. This property allows you to specify whether you want to include or exclude padding and border in your width and height calculations.</p>

<p>There are two possible values for <code>box-sizing</code>:</p>

<ul> <li><code>content-box</code>: This is the default value. It means that only content is included in width and height calculations.</li> <li><code>border-box</code>: This means that both content and border (but not margin) are included in width and height calculations.</li> </ul>

<p>For example:</p>

<pre><code class=“language-css”>div { width: 300px; height: 200px; padding: 20px; border: 10px solid black; margin: 10px; }

div.content-box { /* This div will have a total width of 360px (300 + 20 + 20 + 10 + 10) and a total height of 260px (200 + 20 + 20 + 10 + 10) */ }

div.border-box { /* This div will have a total width of 300px (width includes padding and border) and a total height of 200px (height includes padding and border) */ } </code></pre>

<h2>Resources</h2>

<p>To learn more about box model concepts such as block vs inline elements, how to use display property, how browsers render boxes, etc., please refer to these resources:</p>

<ul> <li><a href=“#1”>The box model - Learn web development | MDN - Mozilla</a></li> <li><a href=“#2”>CSS Box Model - W3Schools</a></li> <li><a href=“#3”>CSS box model - Wikipedia</a></li> <li><a href=“#4”>Basic writing and formatting syntax - GitHub Docs </a></li> </ul>
