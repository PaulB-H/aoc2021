<h1>Day 3</h1>

<h3>Part 1</h3>
<p>Your puzzle input consists of a list of binary numbers, you will use this to determine the power level of the submarine.</p>

<pre><code>011000110010
111011101000
110100110010
011010101110
111010100100
100111111100
110001110000
...
</code></pre>

<p>The power consumption can be found by multiplying the gamma rate by the epsilon rate.</p>

<p>Each bit in the gamma rate can be determined by finding the <strong>MOST</strong> common bit in the corresponding position of all numbers in the report, while the epsilon rate can be determined by finding the <strong>LEAST</strong> common bit in the corresponding position instead.</p>
