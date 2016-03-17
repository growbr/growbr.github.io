<h1 id="fixedcolumns">FixedColumns</h1>

<p>When making use of DataTables' x-axis scrolling feature (<code>scrollX</code>), you may wish to fix the left or right most columns in place. This plug-in for DataTables provides exactly this option (for non-scrolling tables, please use the FixedHeader plug-in, which can fix headers, footers and columns). Key features include:</p>

<ul>
<li>Freezes the left most column to the side of the table</li>
<li>Option to freeze two or more columns</li>
<li>Full integration with DataTables' scrolling options</li>
</ul>

<h1 id="installation">Installation</h1>

<p>To use FixedColumns, first download DataTables ( http://datatables.net/download ) and place the unzipped FixedColumns package into a <code>extensions</code> directory in the DataTables package. This will allow the pages in the examples to operate correctly. To see the examples running, open the <code>examples</code> directory in your web-browser.</p>

<h1 id="basic-usage">Basic usage</h1>

<p>FixedColumns is initialised using the <code>$.fn.dataTable.FixedColumns()</code> constructor. For example:</p>

<pre><code class="js">$(document).ready(function() {
    var table = $('#example').DataTable( {
        scrollY:        "300px",
        scrollX:        true,
        scrollCollapse: true,
        paging:         false
    } );

    new $.fn.dataTable.FixedColumns( table );
} );
</code></pre>

<h1 id="documentation-%2F-support">Documentation / support</h1>

<ul>
<li>Documentation: http://datatables.net/extensions/FixedColumns/</li>
<li>DataTables support forums: http://datatables.net/forums</li>
</ul>

<h1 id="github">GitHub</h1>

<p>If you fancy getting involved with the development of FixedColumns and help make it better, please refer to its GitHub repo: https://github.com/DataTables/FixedColumns</p>
