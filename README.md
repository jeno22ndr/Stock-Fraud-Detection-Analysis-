<div class="badges">
  <img alt="Languages" src="https://img.shields.io/github/languages/top/jeno22ndr/Stock-Fraud-Detection-Analysis?style=for-the-badge">
  <img alt="Last Commit" src="https://img.shields.io/github/last-commit/jeno22ndr/Stock-Fraud-Detection-Analysis?style=for-the-badge&color=blue">
  <img alt="Stars" src="https://img.shields.io/github/stars/jeno22ndr/Stock-Fraud-Detection-Analysis?style=for-the-badge&color=yellow">
  <a href="LICENSE"><img alt="License" src="https://img.shields.io/github/license/jeno22ndr/Stock-Fraud-Detection-Analysis?style=for-the-badge"></a>
  <img alt="Issues" src="https://img.shields.io/github/issues/jeno22ndr/Stock-Fraud-Detection-Analysis?style=for-the-badge&color=red">
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#overview">Project Overview</a></li>
    <li><a href="#objective">Objective</a></li>
    <li><a href="#features">Key Analysis Highlights</a></li>
    <li><a href="#datasets">Datasets Used</a></li>
    <li><a href="#tools">Tools & Technologies</a></li>
    <li><a href="#setup">How to Run</a></li>
    <li><a href="#structure">Repo Structure</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#faq">FAQ</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<h2 id="overview">Project Overview</h2>
<p>
  A comprehensive framework to detect anomalies and potential fraud in stock trading data, leveraging statistical analysis, anomaly detection, and supervised learning.
</p>

<h2 id="objective">Objective</h2>
<ul>
  <li>Spot outliers in price and volume that may signal fraudulent activity.</li>
  <li>Develop interpretable ML classifiers distinguishing normal vs. anomalous days.</li>
  <li>Provide actionable visual dashboards for forensic investigators.</li>
</ul>

<h2 id="features">Key Analysis Highlights</h2>
<table>
  <tr><th>Component</th><th>Techniques</th><th>Outcome</th></tr>
  <tr><td>EDA</td><td>Volume & Price Trends</td><td>Identified volatility clusters</td></tr>
  <tr><td>Anomaly Detection</td><td>Isolation Forest, LOF, One-Class SVM</td><td>Detected ~5% outliers</td></tr>
  <tr><td>Classification</td><td>Logistic Regression, RF, XGBoost</td><td>ROC-AUC > 0.92</td></tr>
  <tr><td>Visualization</td><td>Matplotlib, Seaborn</td><td>Interactive anomaly timelines</td></tr>
</table>

<h2 id="datasets">Datasets Used</h2>
<ul>
  <li><code>Stock Market Anomaly Detection Dataset.csv</code>: OHLC prices, volume, labeled anomalies.</li>
  <li>Simulated to reflect realistic fraud patterns.</li>
</ul>

<h2 id="tools">Tools & Technologies</h2>
<ul>
  <li>Python 3.8+</li>
  <li>Jupyter Notebook</li>
  <li>Pandas, NumPy</li>
  <li>Matplotlib, Seaborn</li>
  <li>Scikit-learn, XGBoost</li>
</ul>


<h2 id="structure">Repository Structure</h2>
<pre><code>Stock-Fraud-Detection-Analysis/

  <h2 id="roadmap">Roadmap</h2>
<ul>
  <li>✅ Core EDA & Anomaly Methods</li>
  <li>✅ Classification & Model Evaluation</li>
  <li>⬜️ Deploy interactive dashboard</li>
  <li>⬜️ Real-time streaming anomaly alerts</li>
  <li>⬜️ Integrate additional market indicators</li>
</ul>

<h2 id="faq">FAQ</h2>
<details>
  <summary>What data format is required?</summary>
  <p>CSV with columns: Date, Open, High, Low, Close, Volume, Label.</p>
</details>
<details>
  <summary>Can I add more classifiers?</summary>
  <p>Yes, simply implement in the notebook under the modeling section.</p>
</details>

<h2 id="license">License</h2>
<p>MIT &copy; 2025 Jeno Nadar. See <ahref="LICENSE">LICENSE</a> for details.</p>

<h2 id="contact">Contact</h2>
<p>Questions? <a href="mailto:jeno@example.com">Email me</a> or submit an issue.</p>
<h2 id="setup">How to Run the Analysis</h2>
<pre><code>git clone https://github.com/jeno22ndr/Stock-Fraud-Detection-Analysis.git
