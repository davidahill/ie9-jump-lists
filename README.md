<h3>Howdy!</h3>

<p>Welcome, I hope that this project will assist you with adding <em>jump lists</em> to your site and avoid
the hurdles that I encountered</p>

<p>Visit the webpage for an example. <a href="http://davidahill.github.com/ie9-jump-lists">http://davidahill.github.com/ie9-jump-lists</a></p>

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
<pre>
    <code>&lt;meta name="msapplication-task" content="name=Watch This; action-uri=https://github.com/davidahill/ie9-jump-lists/toggle_watch; icon-uri=https://github.com/favicon.ico" /&gt;
	&lt;meta name="msapplication-task" content="name=Fork This; action-uri=https://github.com/davidahill/ie9-jump-lists/fork; icon-uri=https://github.com/favicon.ico" /&gt;
	&lt;meta name="msapplication-task" content="name=github Home; action-uri=https://github.com/; icon-uri=https://github.com/favicon.ico" /&gt;
	&lt;meta name="msapplication-task" content="name=jQuery; action-uri=http://jquery.com/; icon-uri=http://static.jquery.com/favicon.ico" /&gt;</code>
</pre>

<p>The link to the pinned icon, 64x64 icon file is best. Create one here; http://www.favicon.co.uk/index.php</p>
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
