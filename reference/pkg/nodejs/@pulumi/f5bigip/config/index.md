---
title: Module config
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

<a href="../index.html">@pulumi/f5bigip</a> &gt; config

<div class="toggleVisible" markdown="1">
<div class="collapsed" markdown="1">
<h2 class="pdoc-module-header toggleButton" title="Click to show Index">Index ▹</h2>
</div>
<div class="expanded" markdown="1">
<h2 class="pdoc-module-header toggleButton" title="Click to hide Index">Index ▾</h2>
<div class="pdoc-module-contents" markdown="1">
* <a href="#address">let address</a>
* <a href="#loginRef">let loginRef</a>
* <a href="#password">let password</a>
* <a href="#tokenAuth">let tokenAuth</a>
* <a href="#username">let username</a>

<a href="/config/vars.ts">config/vars.ts</a> 
</div>
</div>
</div>


<h2 class="pdoc-module-header" id="address">
<a class="pdoc-member-name" href="/config/vars.ts#L12">let <b>address</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>let</span> address: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> = <span class='s2'> __config.require(&#34;address&#34;)</span>;</pre>

Domain name/IP of the BigIP

</div>
<h2 class="pdoc-module-header" id="loginRef">
<a class="pdoc-member-name" href="/config/vars.ts#L16">let <b>loginRef</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>let</span> loginRef: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.get(&#34;loginRef&#34;)</span>;</pre>

Login reference for token authentication (see BIG-IP REST docs for details)

</div>
<h2 class="pdoc-module-header" id="password">
<a class="pdoc-member-name" href="/config/vars.ts#L20">let <b>password</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>let</span> password: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> = <span class='s2'> __config.require(&#34;password&#34;)</span>;</pre>

The user's password

</div>
<h2 class="pdoc-module-header" id="tokenAuth">
<a class="pdoc-member-name" href="/config/vars.ts#L24">let <b>tokenAuth</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>let</span> tokenAuth: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> = <span class='s2'> __config.getObject&lt;boolean&gt;(&#34;tokenAuth&#34;)</span>;</pre>

Enable to use an external authentication source (LDAP, TACACS, etc)

</div>
<h2 class="pdoc-module-header" id="username">
<a class="pdoc-member-name" href="/config/vars.ts#L28">let <b>username</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>let</span> username: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> = <span class='s2'> __config.require(&#34;username&#34;)</span>;</pre>

Username with API access to the BigIP

</div>