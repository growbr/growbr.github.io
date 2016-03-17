<h1 id="colvis">ColVis</h1>

<p>ColVis adds a button to the toolbars around DataTables which gives the end user of the table the ability to dynamically change the visibility of the columns in the table:</p>

<ul>
<li>Dynamically show and hide columns in a table</li>
<li>Very easy integration with DataTables</li>
<li>Ability to exclude columns from being either hidden or shown</li>
<li>Save saving integration with DataTables</li>
</ul>

<h1 id="installation">Installation</h1>

<p>To use ColVis, first download DataTables ( http://datatables.net/download ) and place the unzipped ColVis package into a <code>extensions</code> directory in the DataTables package. This will allow the pages in the examples to operate correctly. To see the examples running, open the <code>examples</code> directory in your web-browser.</p>

<h1 id="basic-usage">Basic usage</h1>

<p>ColVis is initialised using the <code>C</code> option that it adds to DataTables' <code>dom</code> option. For example:</p>

<pre><code class="js">$(document).ready( function () {
    $('#example').dataTable( {
        "dom": 'C&lt;"clear"&gt;lfrtip'
    } );
} );
</code></pre>

<h1 id="documentation-%2F-support">Documentation / support</h1>

<ul>
<li>Documentation: http://datatables.net/extensions/colvis/</li>
<li>DataTables support forums: http://datatables.net/forums</li>
</ul>

<h1 id="github">GitHub</h1>

<p>If you fancy getting involved with the development of ColVis and help make it better, please refer to its GitHub repo: https://github.com/DataTables/ColVis</p>
