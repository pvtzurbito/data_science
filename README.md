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
      <li>Feature Engineering - Addition of three metrics, namely the debt-to-asset ratio, equity ratio, and asset growth.</li>
      <li>Documentation - Used the markdown options inside Jupyter notebooks to make the steps readable.</li>
    </ul>
    </td>
  </tr>
  <tr>
    <td><a href = "https://github.com/pvtzurbito/data_science/tree/main/Learning%20Pandas/jupyter%20notebooks/final%20reports/Google%20Advanced%20Data%20Analytics">Google Advanced Data Analytics</td>
    <td>Pandas</td>
    <td><ul>
      <li>Data Aggregation - Computed for the mean of the dataset.</li>
      <li>Data Grouping - Used the <code>groupby()</code> function for grouping the data</li>
      <li>Data Filtering - Filtered the data in multiple conditions.</li>
    </ul>
  </tr>
</table>

#### Key Insights and Lessons Learned
##### JPMorgan Chase Balance Sheet
<ul>
  <li>Learned how to implement DataFrame renaming, filling and dropping columns and cells, and reshaping using <code>set_index('column_name').T</code>. </li>
  <li>Learned the definition of debt-to-assets ratio and equity ratio.</li>
  <li>Based on the balance sheet, the debt-to-assets and equity ratios are steadily increasing from 2021 to 2024, indicating that the bank is likely on their expansion phase.</li>
  <li>In the addition of the Asset Growth using <code>balance_t['Asset Growth'] = balance_t['Total Assets'].pct_change()</code>, I have seen that the bank has shrunk its assets from 2021 - 2022 (-2.08) and expanded from the years 2022 - 2024(5.72, and 3.29 respectively). It is also important to arrange the dates in a chronological ascending order.</li>
  <li>Further, upon inspecting the liquidity to debt ratio, it was seen that it has continuously shrunk from 2.83 (2021) to 1.68 (2024).</li>
</ul>
