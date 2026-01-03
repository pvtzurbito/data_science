## Welcome to My Data Science Repository!
Here, you can see a short summary of the datasets that I have examined.

### Python
<table>
  <tr>
    <th>Title</th>
    <th>Tools used</th>
    <th>Results Description</th>
  </tr>
  <tr>
    <td><a href = "https://github.com/pvtzurbito/data_science/tree/main/Learning%20Pandas">JPMorgan Balance Sheet</a></td>
    <td>Pandas, Jupyter</td>
    <td><ul>
      <li>Data Cleaning - Removed the 2020 columns due to the lack of data present in the columns, and filling NaNs with 0s.</li>
      <li>Data Reshaping - Shifted the data from a long format (metrics-based) with a wide format (time-based).</li>
      <li>Feature Engineering - Addition of two metrics, namely the debt-to-asset ratio and equity ratio.</li>
      <li>Documentation - Used the markdown options inside Jupyter notebooks to make the steps readable.</li>
    </ul>
    </td>
  </tr>
</table>

#### Key Insights and Lessons Learned
<ul>
  <li>Learned how to implement DataFrame renaming, filling and dropping columns and cells, and reshaping using <code>set_index('column_name').T</code>. </li>
  <li>Learned the definition of debt-to-assets ratio and equity ratio.</li>
  <li>Based on the balance sheet, the debt-to-assets and equity ratios are steadily increasing from 2021 to 2024, indicating that the bank is likely on their expansion phase.</li>
</ul>
