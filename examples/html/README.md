
## Supported Tags

Name | Uses
--- | ---
selector | class, id, data-attr, href, rel, etc
selector-native | built in tags (ul, li, nav, header, h1, h2, h3, span, img, pre, code, meta, title etc)
url | the value of an href or src tag
value | the value of a tag attribute (ex: style="value")
comment | an HTML comment

## Examples

**Output:**
![ui-theme-dark html example](../../misc/ui-theme-dark.PNG)

**Source Code:**
```html
<pre class="ft-syntax-highlight" data-syntax="html" data-syntax-theme="one-dark" data-showTooltips="true">
  <code>
  <span class="newline"></span>
  <span class="newline">&lt;<span class="selector-native">noscript</span> <span class="selector">id</span>=<span class="value">"myDiv"</span>&gt; </span>
  <span class="newline">  &lt;<span class="selector-native">div</span> <span class="selector">class</span>=<span class="value">"alert alert-danger"</span>&gt; </span>
  <span class="newline">    You don't have javascript enabled #Sad </span>
  <span class="newline"></span>
  <span class="newline">    This will only display when javascript is not enabled</span>
  <span class="newline"></span>
  <span class="newline">   For more details see &lt;<span class="selector-native">a</span> <span class="selector">href</span>="<span class="url">https://www.somewebsite.com</span>" <span class="selector">target</span>="<span class="value">_blank</span>">here&lt;/<span class="selector-native">a</span>&gt;</span>
  <span class="newline">  &lt;/<span class="selector-native">div</span>&gt;</span>
  <span class="newline">&lt;/<span class="selector-native">noscript</span>&gt;<span class="comment">&lt;!-- END OF NOSCRIPT-CONTAINER --&gt;</span></span>
  <span class="newline"></span>
  </code>
</pre>
```
