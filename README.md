# Stuff

### Little_helper_table_lists.ipynb

If you want to quickly create a table or to process a list, this jupyter notebook in combination with a spreadsheet software can help. 
You can enter the column names and values into the spreadsheet, copy it, and then the respective script can process the content in the clipboard and paste the new version to the clipboard.

This Jupyter Notebook lets you
* create a LaTeX table
* create an HTML table
* sort values separated by an inner cell delimiter in a column, e.g.

<center>
	<table>
	    <th>Column</th><th><div align=center>&rarr;</div></th><th>Column</th>
	    <tr><td><div align=center>bla</div></td><td><div align=center>&rarr;</div></td><td><div align=center>bla</div></td></tr>
	    <tr><td>blo, ble</td><td><div align=center>&rarr;</div></td><td>ble, blo</td></tr>
	</table>
</center>

* Sort columns of a table individually
* Sort 2-dimensional row-array based on unique values in one column, e.g.

<center>
	<table>
	    <thead>
	        <th>Before</th>
	        <th>&rarr;</th>
	        <th>After</th>
	    </thead>
	    <tbody>
	        <tr>
	            <td>[[1, "def", ...],</td>
	            <td>&rarr;</td>
	            <td>[[1, "def", ...],</td>
	        </tr>
	        <tr>
	            <td>[1, "def", ...],</td>
	            <td>&mdash;</td>
	            <td>[2, "def", ...],</td>
	        </tr>
	        <tr>
	            <td>[2, "def", ...],</td>
	            <td>&#8599;</td>
	            <td>[3, "def", ...],</td>
	        </tr>
	        <tr>
	            <td>[3, "def", ...],</td>
	            <td>&#8599;</td>
	            <td>[4, "def", ...],</td>
	        </tr>
	        <tr>
	            <td>[4, "def", ...],</td>
	            <td>&#8599;</td>
	            <td>...]</td>
	        </tr>
	        <tr>
	            <td>...]</td>
	            <td>&#8599;</td>
	            <td></td>
	        </tr>
	    </tbody>
	</table>
</center>

* Count unique values
* convert a MySQL dump to a CSV file
* list TODOs from a LaTeX document

