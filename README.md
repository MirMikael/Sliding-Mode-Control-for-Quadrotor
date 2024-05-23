<h2>Sliding Surface:</h2>

<p>For each state variable <em>i</em>, the sliding surface <em>S<sub>i</sub></em> is defined as:</p>

<code>S<sub>i</sub> = ė + &lambda;<sub>i</sub> &middot; e</code>

<p>Where:</p>
<ul>
  <li><code>ė</code> is the derivative of the error.</li>
  <li><code>&lambda;<sub>i</sub></code> is the control gain for the <em>i</em>th state variable.</li>
  <li><code>e</code> represents the error between the desired and actual values of the state variable.</li>
</ul>

<h2>Switching Function:</h2>

<p>The switching function <em>&#x1F7A4;S</em> is given by:</p>

<code>&#x1F7A4;S = k &middot; tanh(S)</code>

<p>Where:</p>
<ul>
  <li><code>S</code> is the sliding surface.</li>
  <li><code>k</code> is the gain parameter.</li>
  <li><code>tanh</code> denotes the hyperbolic tangent function.</li>
</ul>

<p>For the following state variables <em>i</em>:</p>
<p><em>i</em> can take values of &phi;, &theta;, &psi;, X, Y, Z.</p>
