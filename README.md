<h1>Invisible Ink</h1>

<p><br />
<br /></p>

<h2>Hide</h2>

<p>Invisible Ink lets hide text (and elements) with just a bit of CSS.</p>

<p><br />
<br /></p>

<h2>Playground</h2>

<p>You can play with Invisible Ink here: <a href="https://codepen.io/slate-coding/pen/qXMNwx">https://codepen.io/slate-coding/pen/qXMNwx</a></p>

<p><br />
<br /></p>

<h2>Usage</h2>

<h3>Documentation</h3>

<p><strong>Invisible Text</strong><br>
Just add the following HTML. This will make the text <strong>white</strong>. As soon as the user hovers over it, the text will appear.</p>

<pre><code class="html">  &lt;ink data-type=&quot;sharp-hover&quot;&gt;My Invisible Text&lt;/ink&gt;
</code></pre>

<p>Or, if you want the text to <em>fade</em> into view, do this instead:</p>

<pre><code class="html">  &lt;ink data-type=&quot;ease-in&quot; data-border=&quot;solid&quot;&gt;Invisible Text That Fades Into View...&lt;/ink&gt;
</code></pre>

<p><strong>Blurred Text</strong><br>
Add the following. This will blur the text in all browsers <strong>except in IE and Edge</strong>. When the blurred text is hovered it instantly becomes readable.</p>

<pre><code class="html">&lt;ink data-type=&quot;blurred&quot;&gt;Blurred Text!!!&lt;/ink&gt;
</code></pre>

<p>If you want the blurred text to <em>fade</em> into view, then:</p>

<pre><code class="html">&lt;ink data-type=&quot;blurred ease-in&quot;&gt;Yaay I Have Blurred Text&lt;/ink&gt;
</code></pre>

<p><strong>Redacted Text</strong><br>
This time, instead of Invisible Text or Blurred Text, we will make the text look as if some one went over the text with a permanent marker.</p>

<pre><code class="html">  &lt;ink data-type=&quot;redacted&quot;&gt;Permanent Markers Here&lt;/ink&gt; 
</code></pre>

<p>Making it fade into view:</p>

<pre><code class="html">  &lt;ink data-type=&quot;redacted&quot;&gt;Meeeeooooww Meow Meow&lt;/ink&gt; 
</code></pre>

<p><strong>Adding a Border to the underside of the Text</strong><br>
If you want a border under your text (see  the <a href="https://codepen.io/slate-coding/pen/qXMNwx">demo</a> to see how it would look), then just add <code>data-border=&quot;solid&quot;</code> to the <code>ink</code> element. Like this:</p>

<pre><code class="html">  &lt;ink data-border=&quot;solid&quot; data-type=&quot;redacted&quot;&gt;Meeeeooooww Meow Meow&lt;/ink&gt; 
</code></pre>

<pre><code class="html">&lt;ink data-border=&quot;solid&quot; data-type=&quot;blurred&quot;&gt;Blurred Text!!!&lt;/ink&gt;
</code></pre>

<pre><code class="html">  &lt;ink data-border=&quot;solid&quot; data-type=&quot;sharp-hover&quot;&gt;My Invisible Text&lt;/ink&gt;
</code></pre>

<h3>Installation</h3>

<p><strong>CDN version:</strong><br>
Simply add this reference to your HTML:</p>

<pre><code class="html">&lt;link rel=&quot;stylesheet&quot; href=&quot;http://slate-coding.zohosites.com/files/cdn/invisible-ink.min.css&quot; /&gt;
</code></pre>

<p><br />
<br /></p>

<p><strong>Manually:</strong><br>
Simply download <code>invisible-ink.min.css</code> from this repository and add it to your HTML. e.g.</p>

<pre><code class="html">&lt;link rel=&quot;stylesheet&quot; href=&quot;path/to/invisible-ink.min.css&quot;&gt;
</code></pre>

<p><br />
<br /></p>

<h3>Contributing</h3>

<p>To contribute to this project, you must:</p>

<ol>
<li>Fork this repo.</li>
<li>Make your changes.</li>
<li>Submit a pull request.</li>
</ol>
