# Code test decision table
To decide whether a test should be written, a risk analysis should be done according to the decision table below.

<table style="text-align: center">
  <tr>
    <th rowspan=5>Impact</th>
    <th nowrap>Very large</th>
    <td style="background-color: orange">5</td>
    <td style="background-color: orange">10</td>
    <td style="background-color: green">15</td>
    <td style="background-color: green">20</td>
    <td style="background-color: green">25</td>
  </tr> 
  <tr>
    <th nowrap>Large</th>
    <td style="background-color: orange">4</td>
    <td style="background-color: orange">8</td>
    <td style="background-color: orange">12</td>
    <td style="background-color: green">16</td>
    <td style="background-color: green">20</td>
  </tr> 
  <tr>
    <th nowrap>Medium</th>
    <td style="background-color: orange">3</td>
    <td style="background-color: orange">6</td>
    <td style="background-color: orange">9</td>
    <td style="background-color: orange">12</td>
    <td style="background-color: green">15</td>
  </tr> 
  <tr>
    <th nowrap>Small</th>
    <td style="background-color: red">2</td>
    <td style="background-color: orange">4</td>
    <td style="background-color: orange">6</td>
    <td style="background-color: orange">8</td>
    <td style="background-color: orange">10</td>
  </tr> 
  <tr >
    <th nowrap>Very small</th>
    <td style="background-color: red">1</td>
    <td style="background-color: red">2</td>
    <td style="background-color: orange">3</td>
    <td style="background-color: orange">4</td>
    <td style="background-color: orange">5</td>
  </tr>
  <tr>
    <td colspan="2" rowspan="2"></td>
    <th nowrap>Very unlikely</th>
    <th nowrap>Unlikely</th>
    <th nowrap>Plausible</th>
    <th nowrap>Likely</th>
    <th nowrap>Very likely</th>
  </tr>
  <tr>
    <th colspan="5" style="text-align: center">Chance</th>
  </tr>
</table>

## Explanation
- **1 and 2:** No code test needed;
- **3 - 12:** A code test must be written, unless this is not justified due to cost or time involved and thus the business interest;
- **15 - 25:** A code test must be written.