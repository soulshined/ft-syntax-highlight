
## Supported Tags

Name | Uses
--- | ---
attribute | attributes of elements <element attribute="">
identifier | all elemetns &lt;root&gt; etc
identifier-namespace | name prefixes
url | link value
value | the value of an attribute
comment | a comment

## Examples

**Output:**

![syntax highlighter example: xml](../../misc/syntax-theme-midnight.PNG)

**Source Code:**
```html
<pre class="ft-syntax-highlight" data-syntax="xml" data-syntax-theme="midnight" data-showTooltips="true">
  <code>
  <span class="comment">&lt;!-- this is a namespace example --&gt;</span>
  &lt;<span class="identifier">root</span> <span class="attribute">xmlns</span>:<span class="identifier-namespace">h</span>="<span class="url">http://www.w3.org/TR/html4/</span>"&gt;

  &lt;<span class="identifier-namespace">h</span>:<span class="identifier">table</span>&gt;
    &lt;<span class="identifier-namespace">h</span>:<span class="identifier">tr</span>&gt;
      &lt;<span class="namespace">h</span>:<span class="identifier">td</span>&gt;Apples&lt;<span class="identifier-namespace">/h</span>:<span class="identifier">td</span>&gt;
      &lt;<span class="identifier-namespace">h</span>:<span class="identifier">td</span>&gt;Bananas&lt;<span class="identifier-namespace">/h</span>:<span class="identifier">td</span>&gt;
    &lt;<span class="identifier-namespace">/h</span>:<span class="identifier">tr</span>&gt;
  &lt;<span class="identifier-namespace">/h</span>:<span class="identifier">table</span>&gt;

  &lt;<span class="identifier">/root</span>&gt;

  <span class="comment">&lt;!-- this is a generic example --&gt;</span>
  &lt;<span class="identifier">bookstore</span>&gt;
    &lt;<span class="identifier">book</span> <span class="attribute">category</span>="<span class="value">children</span>"&gt;
      &lt;<span class="identifier">title</span>&gt;Harry Potter&lt;<span class="identifier">/title</span>&gt;
      &lt;<span class="identifier">author</span>&gt;J K. Rowling&lt;<span class="identifier">/author</span>&gt;
      &lt;<span class="identifier">year</span>&gt;2005&lt;<span class="identifier">/year</span>&gt;
      &lt;<span class="identifier">price</span>&gt;29.99&lt;<span class="identifier">/price</span>&gt;
    &lt;<span class="identifier">/book</span>&gt;
    &lt;<span class="identifier">book</span> <span class="attribute">category</span>="<span class="value">web</span>"&gt;
      &lt;<span class="identifier">title</span>&gt;Learning XML&lt;<span class="identifier">/title</span>&gt;
      &lt;<span class="identifier">author</span>&gt;Erik T. Ray&lt;<span class="identifier">/author</span>&gt;
      &lt;<span class="identifier">year</span>&gt;2003&lt;<span class="identifier">/year</span>&gt;
      &lt;<span class="identifier">price</span>&gt;39.95&lt;<span class="identifier">/price</span>&gt;
    &lt;<span class="identifier">/book</span>&gt;
  &lt;<span class="identifier">/bookstore</span>&gt;
  </code>
</pre>
```
