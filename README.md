Download Link: https://assignmentchef.com/product/solved-comp1007-assignment5-fundamental-operations-of-matplotlib
<br>
This assignment helps you review the fundamental operations of Matplotlib (covered by our labs) and self-learn some new features (not covered by our labs). Please store all your solutions in a single Python file. Use a separate cell for each question.

<ol>

 <li>Write a Python program that generates the following figure with 4 subplots, each with a differentmarker style.</li>

</ol>

Hint: when you call the <strong>scatter()</strong> function, set the <strong>marker</strong> parameter to ‘+’, ‘x’, 4, and 5 respectively, for the four different marker style. E.g., <strong>axes.scatter(x, y, marker=’+’)</strong>.

<strong><u>Marker reference</u></strong>: https://matplotlib.org/api/markers_api.html#module-matplotlib.markers

<ol start="2">

 <li>Assume a dictionary <strong>books = {‘Tom’:10, ‘Dick’:11, ‘Harry’:9, ‘Slim’:7, ‘Jim’:12}</strong> stores the number of books of five students. Write a Python program that generates the following figure.</li>

</ol>

Hint:

<ul>

 <li>to get the list of dictionary values, you can use <strong>list(books.values())</strong>;</li>

 <li>to get the list of dictionary keys (as the y-axis labels), you can use <strong>list(books)</strong>;</li>

 <li>to set the y-axis ticks and labels, use function <strong>set_yticks()</strong> and <strong>set_yticklabels()</strong>. You can learn from the following online example to set the y-axis labels correctly:</li>

</ul>

https://matplotlib.org/gallery/lines_bars_and_markers/barh.html

<ol start="3">

 <li>Study the example at https://matplotlib.org/gallery/lines_bars_and_markers/simple_plot.html. Then write a Python program that generates the following figure with 2 subplots.</li>

</ol>

Hint: you may need to use the <strong>tight_layout()</strong> function to set a tight layout.