---
layout: about
title: About
permalink: /


news: true  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

<div class="row">
	{% include video.html path="assets/video/elongasome-0001-0200.mp4" class="img-fluid rounded z-depth-1" controls=false autoplay=true loop=true muted=true width=100 %}	
</div>

<div class="row">
	<video style="width:100%" src="assets/video/elongasome-0001-0200.mp4" controls="" width="100%"></video>
</div>


<div class="row">
	<video style="width:100%" src="assets/video/pexels-engin-akyurt-6069112-960x540-30fps.mp4" controls="" width="100%"></video>
</div>

<div class="row">
	{% include video.html path="assets/video/pexels-engin-akyurt-6069112-960x540-30fps.mp4" class="img-fluid rounded z-depth-1" controls=false autoplay=true loop=true muted=true %}
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/elongasome-0001-0200.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true width=100 %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/pexels-engin-akyurt-6069112-960x540-30fps.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>

Welcome to the Elongasome sLOLA project website!

We are multi-disciplinary consortium of scientists working to understand the molecular basis of  bacterial cell wall synthesis by the elongasome protein complex. 

The elongasome is a protein complex that builds the cell wall of rod-shaped bacteria. This protein complex is a major antibiotic target and is found in many bacteria, including major pathogens such as *Eschericia coli* and *Pseudomonas aeruginosa*.

This project is funded by the UK Biotechnology and Biological Sciences Research Council *Strategic Longer and Larger (sLOLA)* initiative.



<!-- 
Disable slideshow for now until we have some photos
Uncomment to reenable slideshow
<script>
    var myIndex = 0;
    carousel();

    function carousel() {
        var i;
        var x = document.getElementsByClassName("mySlides");
        for (i = 0; i < x.length; i++) {
            x[i].style.display = "none";  
        }
        myIndex++;
        if (myIndex > x.length) {myIndex = 1}    
        x[myIndex-1].style.display = "block";  
        setTimeout(carousel, 4000); // Change image every 2 seconds
    }
</script> 
-->