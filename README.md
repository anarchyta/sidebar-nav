# sidebar-nav
Best jQuery Treeview &amp; jQuery tree plugin with example of jquery treeview based on collapsed..
# Featured

* Bootstrap
* Font Awesome
* Tree View Style
* Cross Browser Compatible
* Responsive Design

# How to use it:

## Add references to jQuery library and the jQuery Sidebar Menu plugin's files into the html page.

<pre>&lt;link rel="stylesheet" href="css/sidebar-nav.css"/&gt;
&lt;script type="text/javascript" src="js/jquery.min.js"&gt;&lt;/script&gt;
&lt;script type="text/javascript" src="js/sidebar-nav.js"&gt;&lt;/script&gt;</pre>

## You might need to load the Bootstrap Framework and Font Awesome icons.

<pre>&lt;link rel="stylesheet" href="css/bootstrap.min.css"/&gt;
&lt;link rel="stylesheet" href="css/font-awesome.min.css"/&gt;</pre>

## Create a nested html list for the multi-level sidebar menu.

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
&lt;/ul&gt;</pre>
## Initialize the plugin and we're done.

<pre>$('.sidebar-menu').anarchytreeview()</pre>

# Credits

* jQuery
* Bootstrap
* Font Awesome
