# sidebar-nav
Best jQuery Treeview &amp; jQuery tree plugin with example of jquery treeview based on collapsed..
<h2>Featured</h2>
<ul>
<li>Bootstrap</li>
<li>Font Awesome</li>
<li>Tree View Style</li>
<li>Cross Browser Compatible</li>
<li>Responsive Design</li>
</ul>
<h2>How to use it:</h2>
<ul>
<li>Add references to jQuery library and the jQuery Sidebar Menu plugin's files into the html page.</li>
<pre>&lt;link rel="stylesheet" href="sidebar-menu.css"&gt;
&lt;script type="text/javascript" src="assets/jquery.min.js"&gt;&lt;/script&gt;
&lt;script type="text/javascript" src="assets/sidebar-menu.min.js"&gt;&lt;/script&gt;</pre>
<li>You might need to load the Bootstrap Framework and Font Awesome icons.
<pre>&lt;link rel="stylesheet" href="assets/bootstrap.min.css"/&gt;
&lt;link rel="stylesheet" href="assets/font-awesome.min.css"/&gt;</pre></li>
<li>Create a nested html list for the multi-level sidebar menu.
<pre>&lt;ul class="sidebar-menu"&gt;
  &lt;li class="header"&gt;Navigation&lt;/a&gt;&lt;/li&gt;
  &lt;!-- start of sub menu --&gt;
  &lt;li class="treeview"&gt;
    &lt;a href="#"&gt;
      &lt;i class="fa fa-dashboard"&gt;&lt;/i&gt; &lt;span&gt;Dashboard&lt;/span&gt;
      &lt;i class="fa fa-angle-left pull-right"&gt;&lt;/i&gt;
    &lt;/a&gt;
    &lt;!-- start of multi level menu --&gt;
    &lt;ul class="treeview-menu"&gt;
      &lt;li&gt;&lt;i class="fa fa-circle-o"&gt;&lt;/i&gt; Dashboard v1&lt;/li&gt;
      &lt;li&gt;&lt;i class="fa fa-circle-o"&gt;&lt;/i&gt; Dashboard v2&lt;/li&gt;
    &lt;/ul&gt;
    &lt;!-- end of multi level menu --&gt;
  &lt;/li&gt;
  &lt;!-- end of sub menu --&gt;
  &lt;li&gt;&lt;a href="#"&gt;Default&lt;/a&gt;&lt;/li&gt;
&lt;/ul&gt;</pre></li>
<li>Initialize the plugin and we're done.
<pre>$('.sidebar-menu').sidebarMenu()</pre></li>
</ul>
<h2>Credits</h2>
<ul>
<li>jQuery</li>
<li>Bootstrap</li>
<li>Font Awesome</li>
</ul>
