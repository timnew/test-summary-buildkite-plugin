#### broken

<details>
<summary>Show additional failures</summary>
<ul>
<li>
<details>
<summary>
<code>./spec/lib/url_whitelist_spec.rb: UrlWhitelist with domain wildcard should be allowed url</code>
</summary>
<dl>
<dt>Message</dt>
<dd>
<pre><code>expected http://foo.example.com to be allowed by [&quot;*.foo.example.com&quot;] with resource_scheme http</code></pre>
</dd>
</dl>
</details>
</li>
<li>
<details>
<summary>
<code>./spec/lib/url_whitelist_spec.rb: UrlWhitelist with domain wildcard should not be allowed url</code>
</summary>
<dl>
<dt>Message</dt>
<dd>
<pre><code>expected http://bar.foo.example.com not to be allowed by [&quot;*.foo.example.com&quot;] with resource_scheme http</code></pre>
</dd>
<dt>Details</dt>
<dd>
<pre><code>Failure/Error: it { expect(url).not_to be_allowed_url }
  expected http://bar.foo.example.com not to be allowed by [&quot;*.foo.example.com&quot;] with resource_scheme http
./spec/lib/url_whitelist_spec.rb:92:in `block (4 levels) in &lt;top (required)&gt;&#39;</code></pre>
</dd>
</dl>
</details>
</li>
</ul>

</details>
