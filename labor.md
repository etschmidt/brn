---
layout: page
title: Labor
comments: false
---

<!-- Posts Index
================================================== -->
<section class="recent-posts">
    
    <div class="row listrecent">

        {% for post in site.categories.Labor %}

               {% include postbox.html %}          

        {% endfor %}
        
    </div>
    
</section>

<!-- Pagination
================================================== -->
<div class="bottompagination">
	<div class="pointerup"><i class="fa fa-caret-up"></i></div>
	<span class="navigation" role="navigation">
	    {% include pagination.html %}
	</span>
</div>