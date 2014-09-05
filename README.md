home-automation-demo-presentation
=================================

<h2>About</h2>
<p>A slide presentation demonstrating a simple home automation setup.</p>

<h2>Required for the demo</h2>
<ul>
	<li>Raspberry Pi</li>
	<li><a href="http://razberry.z-wave.me/">Z-Wave Daughter card</a></li>
	<li>At least one Z-Wave compatible device (light switch, wall outlet, etc.)</li>
	<li>Optional: Android <a href="#">demo app</a></li>
	<li>Optional: NFC Tags</li>
	<li>Optional: <a href="http://estimote.com/">Estimote</a> Beacons</li>
</ul>

<h2>Running Presentation Locally</h2>
<ol>
	<li>Install <a href="http://nodejs.org/">Node.js</a></li>
	<li>Install <a href="http://gruntjs.com/getting-started#installing-the-cli">Grunt</a></li>
	<li>Grab the slides</li>
</ol>
<pre>
	git clone https://github.com/jonpitch/home-automation-demo-presentation.git
	cd lib
	git clone https://github.com/hakimel/reveal.js.git
	cd reveal.js
	npm install
	# open /public/index.html
</pre>