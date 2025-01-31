---
title: Discovering the mechanism of action of drugs with a sparse explainable network
tags: [XAI, Deep Learning,Drug Response Prediction, MoA]
style: fill
color: primary 
comments: true
description: SparseGO is an effective XAI method for predicting, but more importantly, understanding drug response.
---
You can read the article [here](https://www.thelancet.com/journals/ebiom/article/PIIS2352-3964(23)00333-X/fulltext).


<iframe src="https://www.thelancet.com/journals/ebiom/article/PIIS2352-3964(23)00333-X/fulltext" width="100%" height="500px"></iframe>

{% include elements/button.html link="https://github.com/KatynaSada/SparseGO" text="View code" %}

{% if page.comments %}
<div id="disqus_thread"></div>
<script>
    /**
    *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
    *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
    /*
    var disqus_config = function () {
    this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    */
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://katynasada-github-io.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}