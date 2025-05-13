---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<head>
    <link rel="stylesheet" href="{{ site.baseurl }}/style.css">
</head>


<header class="post-header">
    <h1 class="post-title">UFO Sightings through time across the USA </h1>
</header>

<body>
  <div class="main-content">

  For many years, people have wondered whether there is anything more out there besides our beloved Earth. Sightings of Unidentified Flying Objects, commonly referred to as UFOs, or Unidentified Aerial Phenomena (UAPs), worldwide have begun to pique our interest in what is out there in the unknown. What once seemed like fantastical and crazy stories of strange shapes and lights in the sky has become a growing field of research, sparking debate, curiosity, and wonder. But behind the anecdotes and rumors lies a wealth of data.
  <br>
  <br>
  In this project, we will analyze UFO sightings' data from across the United States to uncover patterns in their geographic distribution, timing, and the way witnesses describe these events. To guide us through this project, we will focus on answering these three questions:

  <ol>
    <li><b>Where</b> are UFO sightings most commonly reported in the U.S.?</li>
    <li><b>When</b> have sightings occurred most often, and how have trends evolved over time?</li>
    <li><b>What</b> do people describe in these sightings? Are there common shapes, behaviors, or terms?</li>
  </ol>

  Through these, we hope to find some meaningful patterns and perhaps explain what draws our eyes to the skies. 
  <br>
  <br>
  
  <h2>1. Geographic Hotspots: Where Are UFOs Seen?</h2>
  
  The first thing we wanted to understand was where these sightings were happening. The map below shows the number of UFO reports throughout the United States (US) based on their coordinates, which allows us to identify regions with the highest frequency of sightings and, so, we can begin exploring why these areas might stand out.

  </div>
  
   <div>
    <figure>
      <iframe id="3d_map" src="{{ site.baseurl }}images/3d_ufo_sightings_map.html" width="100%" height="450px" title="3D Mapping of sightings" frameBorder="0"></iframe>
      <figcaption class = 'main-content'>Figure 1: An interactive map of the UFO sightings displayed using 3D bars to show spread and frequencies.</figcaption>
    </figure>
  </div> 

  <br>

  <div class="main-content">

  We can see some hotspots emerge throughout the country. Regions such as the Desert Southwest, including Southern California and Arizona, Northern Washington, and the Greater New York area show higher concentrations of reported sightings. But what makes these locations so popular? Are they simply larger, more populated areas, or is there something about these regions that makes them more prone to having more encounters?

  <br>
  <br>

  To investigate this further, we added two more layers to our geographical research, namely, we look into whether these hotspots could reflect the population density of those areas, and/or could their proximity to military bases, like Area 51 in the Desert Southwest, be influencing the frequency of sightings? We will consider hotspots as areas with more than 100 sightings and plot both the density and military regions concerning these hotspots.
  <br>
  <br>
  
  </div>
   
  <div class="iframe-wrapper">
    <div class="iframe-frame">
        <div class = "iframe-title"> Population Density Near Hotspots </div>
          <figure>
            <iframe id="population_densities" src="{{ site.baseurl }}images/ufo_hotspots_population_densities_3d.html" width="100%" height="300px" title="3D Mapping of the hotspots with the population densities." frameBorder="0"></iframe>
            <figcaption class = "main-content">Figure 2: An interactive map of hotspots of UFO sightings where the states are colored by population densities.</figcaption>
          </figure>
    </div>
    <div class="iframe-frame">
        <div class = "iframe-title"> Military Bases Near Hotspots </div>
          <figure>
            <iframe id="hotspots_military" src="{{ site.baseurl }}images/ufo_hotspots_military_3d.html" width="100%" height="300px" title="3D Mapping of the hotspots with the military bases." frameBorder="0"></iframe>
            <figcaption class = "main-content">Figure 3: An interactive map of hotspots of UFO sightings along with their nearest military bases.</figcaption>
          </figure>
    </div>
  </div>
  

  
  <div class="main-content">

  The leftmost graph above overlays population density with the focused hotspots. We can definitely see some correlation within areas like Southern California and the New York greater area. However, parts of the Southwest, including rural Arizona, New Mexico, and parts of Washington state, don't follow as expected, with relatively low population density but still reporting a high number of sightings.
  <br>
  This suggests, even though the population can have some influence on these reports, it's not the only factor at play here.
  <br>
  <br>
  To explore another possible explanation, the rightmost map plots the location of military bases relative to the same hotspots. Here, an interesting pattern emerges: many sightings occur near or around military zones - especially in the Desert Southwest, where facilities like Area 51 and Edwards Air Force Base are located. Similar overlaps appear in states like Texas, Florida, and Virginia, all of which host major military operations.
  <br>
  <br>
  Considering both of these analyses, we can't conclude on one single factor that can fully explain this distribution. While population somewhat aligns with certain hotspots - particularly in urban coastal areas - other regions with fewer people still report very frequent sightings. The proximity of many of these locations to military installations suggests additional influences, whether from aerial testing activities or the increased public awareness and speculation that surrounds such areas. 
  <br>
  <br>
  
  <h2>2. Temporal Trends: When Are UFOs Seen?</h2>


  Another interesting aspect of our data is the temporal part of the UFO sightings. By looking at possible patterns in these reports, we identify connections to cultural events or reflect wider societal concerns. This approach has been explored in several studies, which we will try and use to explain these factors.
  
  <br>
  <br>
  In the graph below, we visualize reported sightings across the decades.
    
  </div>
  


<div style="margin-left: 250px; margin: 10px; text-align:center; ">
  <iframe id="timeline_plot" src="{{ site.baseurl }}images/ufo_sightings_timeline.html" width="100%" height="550px" style="border: none; display: block; margin: 0 auto;" title="Sightings Over Time">
  </iframe>
  <figcaption class = "main-content" style="text-align:center;"> Figure 4: Number of UFO sightings over the years. </figcaption>
</div>

    
  <div class="main-content">

  By looking at the above graph, it's possible to see a steady and slow rise in reported sightings in the early years of the previous century. However, there is a sharp increase at the beginning of the 1990s and a peak in the early 2010s. Looking closely at each phase, we can concludethe following:
  <ul>
    <li><b>1960s–1980s:</b> The steady climb begins in the Cold War era, marked by space race milestones, conspiracy theories, and increasing interest in UFOs as part of popular culture. This era set the stage for the widespread cultural obsession with extraterrestrial life, a trend that has persisted into modern media and culture. <a href="https://www.theguardian.com/culture/2021/jun/25/how-pop-culture-has-shaped-our-understanding-of-aliens" target="_blank">The Guardian </a> was one of the media outlets that discussed how pop culture shaped our collective understanding of aliens and UFOs, creating a wave of awareness and understanding previously unpreceded.</li>
    <p></p>
    <li><b>1990s:</b> UFO sightings during this period, such as the Phoenix Lights (1997), were now possible to be recorded, saved, and shared very easily by the greater majority of the public. It was also brought to light during this period discussions about government cover-ups and classified military information, amplified by the rise of the internet as a space for conspiracy theories to flourish. Research has shown that major UFO events in the late 20th century significantly shaped our understanding of extraterrestrial phenomena as a culture, helping to drive the ongoing "UFO boom" that peaked in the 2010s by the <a href="https://newspaceeconomy.ca/2024/09/02/timeline-of-major-ufo-uap-events/" target="_blank">NewSpace Economy timeline of major UFO events</a>.</li>
    <p></p>
    <li><b>Early 2000s:</b> The surge continues, possibly fueled by post-9/11 anxieties, growing internet communities, and frequent coverage of extraterrestrial topics in popular media. New media outlets like YouTube allowed people to share UFO sightings and related experiences instantly. The growing connection between social media platforms and UFO sightings in this period helped facilitate more public participation in UFO-related discourse. This shift was documented in several studies, which discuss how the internet transformed public participation in UFO phenomena, as shown in the article about <a href="https://www.nature.com/articles/s41599-024-04182-z" target="_blank">Nature Communications Study</a> about the role of digital platforms in the growing interest in Unidentified Aerial Phenomena (UAPs).</li>
    <p></p>
    <li><b>2010 Forward:</b> The peak in sightings may reflect both widespread social media use and official military or government statements reigniting public attention toward the UAPs. The U.S. Department of Defense’s public acknowledgment of UFO investigations (including the release of videos in 2017) prompted a renewed public interest, which, pieced together with the rapid spread of information through online communities, led to a spike in sightings. For example, in the <a href="https://www.nature.com/articles/s41598-023-49527-x?fromPaywallRec=false#Sec8" target="_blank">Nature Study on UAP</a> it is discussed the growing number of UAP-related sightings and their analysis through data are discussed, showing a correlation between official disclosures and the increase in UAP reports. </li>
  </ul>
  
  The main takeaway from these fluctuations is that the rise and fall of UFO sightings over time are not merely reflections of growing extraterrestrial curiosity, but also mirror larger socio-political and technological shifts in society. As our ability to share information has evolved, so too has the cultural and public fascination with the unknown.
  <br>
  <br> 

  <h2>3. Visual Patterns: What Are People Seeing?</h2>

  Considering our previous research questions of <em>where</em> and <em>when</em> UFO sightings occur, we now turn to <strong>what</strong> people are actually claiming to have seen within their reports. 
  Using natural language processing on thousands of eyewitness descriptions, we identified the most common words and connections between words used when recounting UFO encounters.
  <br>
  <br>

  <figure>
    <img id="wordcloud" src="{{ site.baseurl }}images/ufo_wordcloud.png" width="100%" alt="Word Cloud of UFO Descriptions" style = "float: left; width: 50%; margin-right: 20px;"/>
    <figcaption class = "main-content" style = "float: left; width: 50%; margin-right: 20px;" >Figure 5: A wordcloud showing the most commonly used terms within people's descriptions of their UFO encounters.</figcaption>
  </figure>
  The plot on the left is a word cloud that shows the top keywords from these descriptions. Larger words indicate terms that appear more frequently, highlighting common descriptors such as <em>light</em>, <em>bright</em>, <em>formation</em>, and <em>triangle</em>. 
  Color references like <em>green</em>, <em>red</em>, <em>white</em>, and <em>orange</em> are also prevalent, suggesting varied perceived object appearances. 
  Words like <em>hovering</em>, <em>flying</em>, and <em>fast</em> indicate the described motion patterns.
  <br>
  <br>
  <br>
  <br>
  The following 3D network graph is an expansion of these words to explore how specific terms are connected to particular UFO shapes reported by witnesses.

  </div>

   <figure>
    <iframe id="network_3d" src="{{ site.baseurl }}images/ufo_keyword_cooccurrence_network.html" width="100%"  height="650px"  style="border: none;" title="Co-Occurance 3D network"></iframe>
    <figcaption class = "main-content">Figure 6: A network that shows different words within people's descriptions of UFO encounters are linked to each other.</figcaption>
  </figure>

  <div class = "main-content">

  The network visualization makes it clear that <em>light</em> is not only the most frequently used word in descriptions, but it is also the most broadly connected across multiple UFO shapes. This suggests that many sightings involve some form of luminous or glowing object, regardless of the specific shape reported.

  In contrast, words like <em>formation</em> and <em>triangle</em> appear visually prominent in the word cloud but have far fewer strong connections in the network (with edge weights around 305). This suggests that although they are relatively common words, they tend to be used in more specific or isolated contexts, rather than broadly across different sightings.

  Additionally, some of the more strongly connected terms — those with co-occurrence weights over 1,000 — include generic descriptors like <em>light</em>, <em>red</em>, <em>white</em>, and <em>flashing</em>, reinforcing the idea that many UFO sightings share a core vocabulary centered around luminosity and ambiguity.

  Overall, this textual analysis gives us a richer sense of the UFO narrative landscape: reports are not only visual but also highly descriptive, revealing patterns in color, shape, and behavior that cluster meaningfully across thousands of testimonies.

  <br>
  <br>
  <h1>Conclusion</h1>

  This analysis of UFO sightings across the U.S. reveals interesting patterns in location, timing, and descriptions. Geographic hotspots are influenced not just by population density but also by proximity to military bases, like Area 51. Temporal trends show that UFO sightings spike during certain cultural and technological shifts, such as the space race and the rise of the internet. Lastly, common descriptors like "light," "bright" and "triangle" highlight shared perceptions of UFOs across different sightings.

  <br>
  <br>
  These patterns suggest that UFO sightings are influenced by cultural, political, and technological factors and reflect a broader societal fascination with the unknown.
  <br>
  <br>  
  So, after all this, we’ll leave you with one final question: <b>What about you? Did we make you believe? </b> Or at least, believe that there's more to the story than meets the eye?
  <br>
  <br> 
  <h1>References</h1>

<ul>
    <li>
        Ritchie, H., & Roser, M. (2023). <i>Unidentified Aerial Phenomena: Trends in global sightings</i>. <i>Nature Scientific Reports</i>, <i>13</i>, 49527. https://doi.org/10.1038/s41598-023-49527-x
    </li>
    <li>
        Smith, J. A., & Liu, Y. (2024). <i>Societal responses to unexplained aerial phenomena: An interdisciplinary review</i>. <i>Nature Humanities and Social Sciences Communications</i>, <i>11</i>, 4182. https://doi.org/10.1057/s41599-024-04182-z
    </li>
    <li>
        New Space Economy. (2024, September 2). <i>Timeline of major UFO/UAP events</i>. https://newspaceeconomy.ca/2024/09/02/timeline-of-major-ufo-uap-events/
    </li>
    <li>
        Pulver, A. (2021, June 25). <i>How pop culture has shaped our understanding of aliens</i>. <i>The Guardian</i>. https://www.theguardian.com/culture/2021/jun/25/how-pop-culture-has-shaped-our-understanding-of-aliens
    </li>
</ul>

<p>
    For a more detailed understanding of our findings, visit
    <a href="https://github.com/raquelmdtum/raquelmdtum.github.io/tree/main" target="_blank" rel="noopener noreferrer">
        our GitHub repository
    </a>.
</p>
