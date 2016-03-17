<h1 id="tabletools">TableTools</h1>

<p>TableTools is a plug-in for the DataTables HTML table enhancer, which adds a highly customisable button toolbar to a DataTable. Key features include:</p>

<ul>
<li>Copy to clipboard</li>
<li>Save table data as CSV, XLS or PDF files</li>
<li>Print view for clean printing</li>
<li>Row selection options</li>
<li>Easy use predefined buttons</li>
<li>Simple customisation of buttons</li>
<li>Well defined API for advanced control</li>
</ul>

<h1 id="installation">Installation</h1>

<p>To use TableTools, first download DataTables ( http://datatables.net/download ) and place the unzipped TableTools package into a <code>extensions</code> directory in the DataTables package (in DataTables 1.9- use the <code>extras</code> directory). This will allow the pages in the examples to operate correctly. To see the examples running, open the <code>examples</code> directory in your web-browser.</p>

<h1 id="basic-usage">Basic usage</h1>

<p>TableTools is initialised using the <code>T</code> option that it adds to DataTables' <code>dom</code> option. For example:</p>

<pre><code class="js">$(document).ready( function () {
    $('#example').DataTable( {
        dom: 'T&lt;"clear"&gt;lfrtip'
    } );
} );
</code></pre>

<h1 id="documentation-%2F-support">Documentation / support</h1>

<ul>
<li>Documentation: http://datatables.net/extensions/tabletools/</li>
<li>DataTables support forums: http://datatables.net/forums</li>
</ul>

<h1 id="github">GitHub</h1>

<p>If you fancy getting involved with the development of TableTools and help make it better, please refer to its GitHub repo: https://github.com/DataTables/TableTools</p>
