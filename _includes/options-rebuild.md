These are all the options when building an apk.
<br /><br />
<strong><code>-a, --aapt &lt;FILE></code></strong>
<blockquote>Loads aapt from the specified file location, instead of relying on path. Falls back to <code>$PATH</code> loading, if no file found</blockquote>
<br />
<strong><code>-c, --copy-original</code></strong> - <span class="label label-danger">Will still require signature resign post API18</span>
<blockquote>Copies original <code>AndroidManifest.xml</code> and <code>META-INF</code> folder into built apk</blockquote>
<br />
<strong><code>-d, --debug</code></strong>
<blockquote>Adds <code>debuggable="true"</code> to AndroidManifest file.</blockquote>
<br />
<strong><code>-f, --force-all</code></strong>
<blockquote>Overwrites existing files during build, reassembling the <code>resources.arsc</code> file and <code>dex</code> file(s)</blockquote>
<br />
<strong><code>-o, --output &lt;FILE></code></strong>
<blockquote>The name and location of the apk that gets written</blockquote>
<br />
<strong><code>-p, --frame-path &lt;DIR></code></strong>
<blockquote>The location where framework files are loaded from</blockquote>
<br />