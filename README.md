<html>
<ul class="doc-side-nav">
   {% assign current = page.url | downcase | split: '/' %}
	<li><h5 class="doc-side-nav-title"><a href="{{ site.baseurl }}/about/">About</a></h5></li>
	<li class="doc-side-nav-list-item">
	<a href="{{ site.baseurl }}/about/intro" {% if current[2] == 'intro.html' %}class='current'{% endif %}>
	Introduction</a></li>
	<li class="doc-side-nav-list-item">
	<a href="{{ site.baseurl }}/about/philosophy" {% if current[2] == 'philosophy.html' %}class='current'{% endif %}>
	Philosophy</a></li>
	<li class="doc-side-nav-list-item">
	<a href="{{ site.baseurl }}/about/compatibility" {% if current[2] == 'compatibility.html' %}class='current'{% endif %}>
	Compatibility</a></li>
   <li class="doc-side-nav-title">
   <a href="{{ site.baseurl }}/about/design/" {% if current[2] == 'design' %}class='current'{% endif %}>
   Design Notes</a></li>
  <li class="doc-side-nav-list-item">
  <a href="{{ site.baseurl }}/about/design/mutex" {% if current[3] == 'mutex.html' %}class='current'{% endif %}>
   absl::Mutex</a></li>
   <li class="doc-side-nav-list-item">
   <a href="{{ site.baseurl }}/about/design/dropin-types" {% if current[3] == 'dropin-types.html' %}class='current'{% endif %}>
   Pre-Adopted std:: types</a></li>
 </ul>
    </html>
