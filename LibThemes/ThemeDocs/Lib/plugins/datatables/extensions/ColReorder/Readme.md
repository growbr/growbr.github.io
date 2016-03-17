<h1 id="colreorder">ColReorder</h1>

<p>ColReorder adds the ability for the end user to click and drag column headers to reorder a table as they see fit, to DataTables. Key features include:</p>

<ul>
<li>Very easy integration with DataTables</li>
<li>Tight integration with all other DataTables plug-ins</li>
<li>The ability to exclude the first (or more) column from being movable</li>
<li>Predefine a column order</li>
<li>Save staving integration with DataTables</li>
</ul>

<h1 id="installation">Installation</h1>

<p>To use ColReorder, first download DataTables ( http://datatables.net/download ) and place the unzipped ColReorder package into a <code>extensions</code> directory in the DataTables package. This will allow the pages in the examples to operate correctly. To see the examples running, open the <code>examples</code> directory in your web-browser.</p>

<h1 id="basic-usage">Basic usage</h1>

<p>ColReorder is initialised using the <code>$.fn.dataTable.ColReorder</code> constructor. For example:</p>

<pre><code class="js">$(document).ready( function () {
    $('#example').DataTable();

    new $.fn.dataTable.ColReorder( table );
} );
</code></pre>

<h1 id="documentation-%2F-support">Documentation / support</h1>

<ul>
<li>Documentation: http://datatables.net/extensions/colreorder/</li>
<li>DataTables support forums: http://datatables.net/forums</li>
</ul>

<h1 id="github">GitHub</h1>

<p>If you fancy getting involved with the development of ColReorder and help make it better, please refer to its GitHub repo: https://github.com/DataTables/ColReorder</p>
