# OrchardCore Liquid Code Snippets
Useful OrchardCore Liquid syntax code snippets 

Test a condition in display url
<pre>
{%if Model.ContentItem | display_url contains 'home-page' %}
<strong>Yes! This is the Landing Page.</strong>
{% else %}
<strong>Nope! Not the Landing Page.</strong>
{% endif %}
</pre>
              
Always current footer copyright
<pre>
&copy;{{ "now" | date: "%Y" }} {{ Site.SiteName }}
</pre>
