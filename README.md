**Table 1. Power Comparison under two covariance matrices.**
![Table 1](Table_1.png)

<br>

**Table 2. Power comparison between MOD and MMD under different bandwidths.**
![Table 2](Table_2.png)

<br>

**Table 3. Power comparison of MOD and MMD for a modified version of Experiment III...**
![Table 3](Table_3.png)


**Figure C.1. Histograms of for $T_i$ and $T_i^2$ for one replication.**

![Figure C.1](Figure%20C.1.png)


**Table 1. Power Comparison under two covariance matrices.**

<table>
  <thead>
    <tr>
      <th align="center">$\delta$</th>
      <th align="center">$\text{Power}^{\mathrm{est}}$</th>
      <th align="center">$\text{Power}^{\mathrm{true}}$</th>
      <th align="center">$\Delta_1^{\mathrm{est}}$</th>
      <th align="center">$\Delta_1^{\mathrm{true}}$</th>
      <th align="center">$\Delta_2^{\mathrm{est}}$</th>
      <th align="center">$\Delta_2^{\mathrm{true}}$</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">0.8</td><td align="center">0.5450</td><td align="center">0.5150</td><td align="center">0.0016</td><td align="center">0.0016</td><td align="center">0.0005</td><td align="center">0.0005</td>
    </tr>
    <tr>
      <td align="center">0.9</td><td align="center">0.6300</td><td align="center">0.6300</td><td align="center">0.0020</td><td align="center">0.0020</td><td align="center">0.0007</td><td align="center">0.0007</td>
    </tr>
    <tr>
      <td align="center">1</td><td align="center">0.7150</td><td align="center">0.7150</td><td align="center">0.0026</td><td align="center">0.0025</td><td align="center">0.0009</td><td align="center">0.0009</td>
    </tr>
    <tr>
      <td align="center">1.1</td><td align="center">0.7750</td><td align="center">0.7950</td><td align="center">0.0032</td><td align="center">0.0031</td><td align="center">0.0012</td><td align="center">0.0012</td>
    </tr>
    <tr>
      <td align="center">1.2</td><td align="center">0.8400</td><td align="center">0.8450</td><td align="center">0.0040</td><td align="center">0.0038</td><td align="center">0.0016</td><td align="center">0.0015</td>
    </tr>
  </tbody>
</table>

<br>

**Table 2. Power comparison between MOD and MMD under different bandwidths.**

<table>
  <thead>
    <tr>
      <th align="center">Type</th>
      <th align="center">quantile</th>
      <th align="center">MOD</th>
      <th align="center">MMD</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="5" align="center" valign="middle"><strong>Mean</strong></td>
      <td align="center">0.1</td><td align="center">0.790</td><td align="center">0.955</td>
    </tr>
    <tr><td align="center">0.3</td><td align="center">0.775</td><td align="center">0.965</td></tr>
    <tr><td align="center">0.5</td><td align="center">0.785</td><td align="center">0.965</td></tr>
    <tr><td align="center">0.7</td><td align="center">0.760</td><td align="center">0.975</td></tr>
    <tr><td align="center">0.9</td><td align="center">0.725</td><td align="center">0.980</td></tr>
    <tr>
      <td rowspan="5" align="center" valign="middle"><strong>Covariance</strong></td>
      <td align="center">0.1</td><td align="center">0.720</td><td align="center">0.640</td>
    </tr>
    <tr><td align="center">0.3</td><td align="center">0.695</td><td align="center">0.540</td></tr>
    <tr><td align="center">0.5</td><td align="center">0.685</td><td align="center">0.385</td></tr>
    <tr><td align="center">0.7</td><td align="center">0.665</td><td align="center">0.285</td></tr>
    <tr><td align="center">0.9</td><td align="center">0.650</td><td align="center">0.210</td></tr>
    <tr>
      <td rowspan="5" align="center" valign="middle"><strong>Location</strong></td>
      <td align="center">0.1</td><td align="center">0.560</td><td align="center">0.565</td>
    </tr>
    <tr><td align="center">0.3</td><td align="center">0.580</td><td align="center">0.440</td></tr>
    <tr><td align="center">0.5</td><td align="center">0.570</td><td align="center">0.395</td></tr>
    <tr><td align="center">0.7</td><td align="center">0.545</td><td align="center">0.370</td></tr>
    <tr><td align="center">0.9</td><td align="center">0.510</td><td align="center">0.305</td></tr>
    <tr>
      <td rowspan="5" align="center" valign="middle"><strong>Distribution</strong></td>
      <td align="center">0.1</td><td align="center">0.505</td><td align="center">0.480</td>
    </tr>
    <tr><td align="center">0.3</td><td align="center">0.680</td><td align="center">0.585</td></tr>
    <tr><td align="center">0.5</td><td align="center">0.790</td><td align="center">0.640</td></tr>
    <tr><td align="center">0.7</td><td align="center">0.870</td><td align="center">0.645</td></tr>
    <tr><td align="center">0.9</td><td align="center">0.935</td><td align="center">0.575</td></tr>
  </tbody>
</table>

<br>

**Table 3. Power comparison of MOD and MMD for a modified version of Experiment III, in which only $5\%$ of the observations in $Y$ are drawn from a shifted alternative distribution.**

<table>
  <thead>
    <tr>
      <th align="center">Type</th>
      <th align="center">$\delta$</th>
      <th align="center">MOD</th>
      <th align="center">MMD</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="5" align="center" valign="middle"><strong>Mean</strong></td>
      <td align="center">1.1</td><td align="center">0.75</td><td align="center">0.54</td>
    </tr>
    <tr><td align="center">1.2</td><td align="center">0.78</td><td align="center">0.59</td></tr>
    <tr><td align="center">1.3</td><td align="center">0.83</td><td align="center">0.70</td></tr>
    <tr><td align="center">1.4</td><td align="center">0.86</td><td align="center">0.79</td></tr>
    <tr><td align="center">1.5</td><td align="center">0.89</td><td align="center">0.82</td></tr>
    <tr>
      <td rowspan="5" align="center" valign="middle"><strong>Covariance</strong></td>
      <td align="center">1.1</td><td align="center">0.70</td><td align="center">0.04</td>
    </tr>
    <tr><td align="center">1.2</td><td align="center">0.72</td><td align="center">0.04</td></tr>
    <tr><td align="center">1.3</td><td align="center">0.76</td><td align="center">0.04</td></tr>
    <tr><td align="center">1.4</td><td align="center">0.79</td><td align="center">0.04</td></tr>
    <tr><td align="center">1.5</td><td align="center">0.80</td><td align="center">0.05</td></tr>
    <tr>
      <td rowspan="5" align="center" valign="middle"><strong>Location</strong></td>
      <td align="center">1.1</td><td align="center">0.78</td><td align="center">0.11</td>
    </tr>
    <tr><td align="center">1.2</td><td align="center">0.81</td><td align="center">0.14</td></tr>
    <tr><td align="center">1.3</td><td align="center">0.85</td><td align="center">0.16</td></tr>
    <tr><td align="center">1.4</td><td align="center">0.86</td><td align="center">0.20</td></tr>
    <tr><td align="center">1.5</td><td align="center">0.91</td><td align="center">0.25</td></tr>
  </tbody>
</table>
