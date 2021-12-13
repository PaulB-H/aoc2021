<h1>Day 2</h1>

<h3>Part 1</h3>
<p>You are in a submarine that can take a series of commands like forward 1, down 2, or up 3:</p>

<pre><code>forward X increases the horizontal position by X units.
down X increases the depth by X units.
up X decreases the depth by X units.
</code></pre>

<p>Your input wil be a list of commands such as:</p>

<pre><code>forward 5
down 5
forward 8
up 3
down 8
forward 2
</code></pre>

<p>Your horizontal position and depth both start at 0.</p>

<p>What do you get if you multiply your final horizontal position by your final depth?</p>

<h3>Part 2</h3>
<p>In addition to horizontal position and depth, you'll also need to track a third value, aim, which also starts at 0. The commands also mean something entirely different than you first thought:</p>

<pre><code>down X increases your aim by X units.
up X decreases your aim by X units.
forward X does two things:
	It increases your horizontal position by X units.
	It increases your depth by your aim multiplied by X.
</code></pre>

<p>Using the same input, and the new aim value, what do you get if you multiply your final horizontal position by your final depth?</p>
