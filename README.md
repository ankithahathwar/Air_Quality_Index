<div align="center">
  <h1> Air Quality Analysis & Risk Assessment</h1>
  <p><strong>Analyzing air pollution across 110+ Indian cities using Data Science and Machine Learning.</strong></p>
</div>

<hr />

<h2> Project Overview</h2>
<p>
  This project focuses on taking messy, real-world air quality data and turning it into clear insights. I analyzed 12 different pollutants—like $PM_{2.5}$, $PM_{10}$, and $NO_x$—to understand pollution patterns and calculate health risks for different cities.
</p>

<h2> Technical Highlights</h2>
<ul>
  <li><strong>Smart Data Cleaning:</strong> I used <code>Linear Interpolation</code> and mean imputation to fill in missing sensor data, ensuring the analysis stayed accurate without losing important time-series information.</li>
  <li><strong>Clustering with PCA:</strong> Applied <code>Principal Component Analysis</code> to group cities into three main categories: Industrial-heavy, Vehicular-heavy, and Seasonal pollution zones.</li>
  <li><strong>Risk Scoring:</strong> I developed a custom <code>Composite Risk Index</code>. This combines pollutant levels with exposure time to show which cities actually have the highest health risks.</li>
  <li><strong>Correlation Analysis:</strong> Found that $PM_{2.5}$ and $PM_{10}$ are the biggest factors in air quality changes across most regions.</li>
</ul>

<h2> Tech Stack</h2>
<table>
  <tr>
    <td><strong>Languages</strong></td>
    <td>Python, SQL</td>
  </tr>
  <tr>
    <td><strong>Libraries</strong></td>
    <td>Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn</td>
  </tr>
  <tr>
    <td><strong>Concepts</strong></td>
    <td>Data Cleaning, Interpolation, PCA, Risk Modeling, EDA</td>
  </tr>
</table>

<h2>Key Findings</h2>
<ul>
  <li><strong>The Winter Spike:</strong> Pollution levels significantly increase in winter due to weather patterns and crop burning.</li>
  <li><strong>Top Risk Areas:</strong> Cities like Delhi and Patna consistently rank highest on the Risk Index.</li>
  <li><strong>Main Drivers:</strong> $PM_{2.5}$ has the strongest link to overall air quality changes (0.61 correlation).</li>
</ul>

<h2>How to Use</h2>
<ol>
  <li>Clone the repository.</li>
  <li>Install dependencies: <code>pip install pandas scikit-learn seaborn matplotlib</code>.</li>
  <li>Run <code>Cleaning.ipynb</code> to see the full data cleaning and interpolation process.</li>
</ol>

<hr />

<div align="center">
  <p><em>I am a CS student passionate about Data Science and always <strong>ready and keen to learn new things.</strong></em></p>
  <p>Feel free to connect or reach out!</p>
</div>
