<h3>Howdy!</h3>

<p>Welcome, I hope that this project will assist you with adding <em>jump lists</em> to your site and avoid
the hurdles that I encountered</p>

<p>Visit the webpage for an example: <a href="http://davidahill.github.com/ie9-jump-lists">davidahill.github.com/ie9-jump-lists</a></p>

<h3>Usage</h3>

<p>The name of the shortcut. If absent the title is used.</p>
<pre>
<code>&lt;meta name="application-name" content="IE9 Jump Lists Example" /&gt;</code>
</pre>

<p>Optional text that is displayed as a tooltip when the mouse pointer 
hovers over the pinned site shortcut icon in the Windows Start menu or desktop.</p>
<pre>
<code>&lt;meta name="msapplication-tooltip" content="github : IE9 Jump Lists" /&gt;</code>
</pre>

<p>The meat of the example. These entries will included in your pinned jump list.</p>
<p>Here are the three attributes that need to be included:</p>
<ul>
	<li>Name: This is the visual name of the link on the jump list.</li>
	<li>Action: The url the user will be sent to.</li>
	<li>Icon URI: A link to the <i>favicon</i> that will appear to the left of the name.</li>
</ul>

<pre>
<code>&lt;meta name="msapplication-task" content="name=IE9 Jump List Home; action-uri=https://github.com/davidahill/ie9-jump-lists/; icon-uri=https://github.com/favicon.ico" /&gt;
&lt;meta name="msapplication-task"  content="name=IE9 Jump List Home; action-uri=https://github.com/davidahill/ie9-jump-lists/; icon-uri=https://github.com/favicon.ico" /&gt;
&lt;meta name="msapplication-task" content="name=github Home; action-uri=https://github.com/; icon-uri=https://github.com/favicon.ico" /&gt;
&lt;meta name="msapplication-task" content="name=jQuery; action-uri=http://jquery.com/; icon-uri=http://static.jquery.com/favicon.ico" /&gt;</code>
</pre>

<p>The link to the pinned icon, 64x64 icon file is best. Create one here; <a href="http://www.favicon.co.uk/index.php">http://www.favicon.co.uk/</a></p>
<pre>
<code>&lt;link rel="shortcut icon" href="/favicon.ico" /&gt;</code>
</pre>

<p>The initial size of the pinned site browser window. Minimum 800x600.</p>
<pre>
<code>&lt;meta name="msapplication-window" content="width=800; height=600" /&gt;</code>
</pre>

<p>The color of the navigation buttons in the pinned site browser window. Any named color or 
hex color value. If this meta element is absent, the color is based on the shortcut icon.</p>
<pre>
<code>&lt;meta name="msapplication-navbutton-color" content="blue" /&gt;</code>
</pre>
