<h1>📊 IBM SPSS Statistical Analysis – Hypothesis Testing Project</h1>

<p>
This project demonstrates how to apply <b>statistical hypothesis testing</b> using <b>IBM SPSS</b>, <b>Excel</b>, <b>manual calculations</b>, and <b>Python (SciPy)</b>.  
It includes two real-world case studies that use <b>paired sample t-tests</b> and <b>independent two-sample t-tests</b> to evaluate performance improvement.
</p>

<br>

<h2>📁 Project Overview</h2>

<p>This project contains:</p>
<ul>
  <li>📝 <b>Case Study 1:</b> Effect of a speed &amp; agility camp on player sprint performance</li>
  <li>📝 <b>Case Study 2:</b> Effectiveness of a new textbook on student test scores</li>
  <li>🧮 Manual calculations (means, standard deviations, t-statistic, p-value)</li>
  <li>📊 Excel results</li>
  <li>📈 IBM SPSS output</li>
  <li>🐍 Python implementation using SciPy</li>
</ul>

<br>

<h2>📝 Case Study 1 — Paired Sample t-Test</h2>

<h3>❓ Research Question</h3>
<p><b>Does a training camp improve players' 30-yard dash speed?</b></p>

<h3>🔹 Hypotheses</h3>
<ul>
  <li><b>H₀:</b> Mean speed before = Mean speed after</li>
  <li><b>H₁:</b> Mean speed before ≠ Mean speed after</li>
</ul>

<h3>🔹 Summary Statistics</h3>
<ul>
  <li>n = 15 players</li>
  <li>Mean (Before) = 5.062</li>
  <li>Mean (After) = 4.969</li>
  <li>Mean Difference = 0.093</li>
  <li>SD of Differences = 0.336</li>
</ul>

<h3>🔹 Results</h3>
<ul>
  <li><b>t-Statistic:</b> 1.075</li>
  <li><b>p-value:</b> 0.3005 (two-tailed)</li>
</ul>

<h3>🔹 Conclusion</h3>
<p>❌ There is <b>no statistically significant improvement</b> in sprint speed after the camp.</p>
<p>Since <b>p &gt; 0.05</b>, we <b>fail to reject</b> the null hypothesis (H₀).</p>

<br>

<h2>📝 Case Study 2 — Independent Two-Sample t-Test</h2>

<h3>❓ Research Question</h3>
<p><b>Does the new textbook improve student test scores?</b></p>

<h3>🔹 Hypotheses</h3>
<ul>
  <li><b>H₀:</b> μ<sub>old</sub> = μ<sub>new</sub> (no improvement)</li>
  <li><b>H₁:</b> μ<sub>new</sub> &gt; μ<sub>old</sub> (new book improves scores)</li>
</ul>

<h3>🔹 Summary Statistics</h3>
<ul>
  <li>n₁ = 15 (old book)</li>
  <li>n₂ = 15 (new book)</li>
  <li>SD<sub>old</sub> = 13.346</li>
  <li>SD<sub>new</sub> = 10.112</li>
  <li>df = 28</li>
</ul>

<h3>🔹 Results</h3>
<ul>
  <li><b>t-Statistic:</b> 2.159</li>
  <li><b>p-value (one-tailed):</b> 0.0198</li>
</ul>

<h3>🔹 Conclusion</h3>
<p>✅ There is a <b>statistically significant improvement</b> in scores with the new textbook.</p>
<p>Since <b>p &lt; 0.05</b>, we <b>reject</b> the null hypothesis (H₀).</p>

<br>

<h2>🛠 Tools &amp; Technologies Used</h2>

<h3>📐 Statistical Techniques</h3>
<ul>
  <li>Paired Sample t-Test</li>
  <li>Independent Two-Sample t-Test</li>
  <li>Hypothesis formulation (H₀, H₁)</li>
  <li>p-value interpretation</li>
</ul>

<h3>🧪 Software</h3>
<ul>
  <li>IBM SPSS</li>
  <li>Microsoft Excel</li>
  <li>Python (SciPy)</li>
  <li>Manual statistical computation</li>
</ul>

<h3>🐍 Python Example (SciPy)</h3>

<pre><code>from scipy import stats

# Paired t-test (Case Study 1)
stats.ttest_rel(before_camp, after_camp)

# Independent two-sample t-test (Case Study 2)
stats.ttest_ind(old_book, new_book, equal_var=True)
</code></pre>

<br>

<h2>📌 Key Learnings</h2>

<ul>
  <li>How to compute test statistics manually (mean, SD, t-value)</li>
  <li>How to validate results using <b>Excel</b>, <b>SPSS</b>, and <b>Python</b></li>
  <li>How to interpret <b>p-values</b> and make decisions about hypotheses</li>
  <li>How to compare <b>paired vs. independent samples</b> in practice</li>
</ul>

<br>

<h2>🏁 Summary</h2>

<p>
This project is a compact but complete demonstration of <b>hypothesis testing in practice</b>, combining:
</p>

<ul>
  <li>✔ Statistical theory</li>
  <li>✔ Manual calculation</li>
  <li>✔ Spreadsheet analysis (Excel)</li>
  <li>✔ Professional statistical software (SPSS)</li>
  <li>✔ Python-based automation (SciPy)</li>
</ul>

<p>
It highlights my ability to apply statistical thinking to real-world problems, verify results across tools, and clearly communicate conclusions.
</p>
