# Tables
In HTML, tables are used to display tabular data in rows and columns. They provide a structured way to present data in a grid-like format. Here's how you can create tables in HTML:

```html
<table>
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
    <th>Header 3</th>
  </tr>
  <tr>
    <td>Data 1</td>
    <td>Data 2</td>
    <td>Data 3</td>
  </tr>
  <tr>
    <td>Data 4</td>
    <td>Data 5</td>
    <td>Data 6</td>
  </tr>
</table>
```

In this example, we have a simple table with three columns and two rows. The `<table>` tag is used to define the table. Inside the table, we use the `<tr>` (table row) tag to define each row. Within each row, we use the `<th>` (table header) tag to define the table headers in the first row, and the `<td>` (table data) tag to define the data cells in subsequent rows.

The table headers are typically displayed in bold and centered by default, while the data cells are aligned left by default. You can use CSS to customize the table's appearance, such as applying styles to the table headers, alternating row colors, adding borders, etc.

You can add more rows to the table by including additional `<tr>` tags, and more columns by adding more `<th>` or `<td>` tags within the respective rows.

To merge cells horizontally or vertically, you can use the `colspan` and `rowspan` attributes on the appropriate `<th>` or `<td>` tags. These attributes define the number of columns or rows the cell should span.

Tables are commonly used for displaying data, creating forms, and organizing information in a structured manner. However, it's important to use tables appropriately and consider the accessibility implications, as tables can be challenging for screen readers and users with disabilities.