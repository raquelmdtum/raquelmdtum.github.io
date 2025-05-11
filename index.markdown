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

  For many years, people from all over wonder if there is anything more out there besides our beloved Earth. Unidentified Flying Objects sights all over the world sparks curiosity if there actually is something beyond our current knowledge. What once seemed like fantastical and crazy storied of strange shapes and lights in the sky has become a growing field of research, sparking debate, curiosity, and wonder. But behind the anecdotes and rumors lies a wealth of data.
  <br>
  <br>
  In this project, we analyze UFO sighting data from across the United States to uncover patterns in their geographic distribution, timing, and the way witnesses describe these events. To guide us through this project, we will be focused on uncovering these three questions:

  <ol>
    <li><b>Where</b> are UFO sightings most commonly reported in the U.S.?</li>
    <li><b>When</b> have sightings occurred most often, and how have trends evolved over time?</li>
    <li><b>What</b> do people describe in these sightings? Are there common shapes, behaviors, or terms?</li>
  </ol>

  Through these, we hope to uncover some meaningful patterns and perhaps understand what draws our eyes to the skies. 
  <br>
  <br>
  
  <h2>1. Geographic Hotspots: Where Are UFOs Seen?</h2>
  
  The first thing we wanted to understand was where these sightings are happening. The map below shows the number of UFO reports throught the US based on their coordinates, allowing us to identify regions with the highest frequency of sightings and begin exploring why these areas might stand out.

  </div>

  <div>
    <iframe id="3d_map" src="{{ site.baseurl }}images/3d_ufo_sightings_map.html" width="100%" height="450px" title="3D Mapping of sightings" frameBorder="0"></iframe>
  </div>

  <br>

  <div class="main-content">

  We are able to see some hotspots emerge throughout the country. Regions such as the Desert Southwest, including Southern California and Arizona, Northern Washington and the Greater New York area show higher concentrations of reported sightings. But what makes these locations so popular? Are they simply larger, more populated areas, or is there something about these regions that makes them more prone to have more encounters?

  <br>
  <br>

  To investigate this further, we added two more aspects to our geographical research. Could these hotspots reflect the population density of those areas, or might their procimity to military bases, like Area 51 in the Desert Southwest, be influencing the frequency of sightings? We will consider hotspot areas as those with 100+ sightings and plot both the density and military regions in relation to these hotspots.
  <br>
  <br>
  
  </div>

  <div class="iframe-wrapper">
    <div class="iframe-frame">
        <div class = "iframe-title"> Population Density Near Hotspots </div>
        <iframe id="population_densities" src="{{ site.baseurl }}images/ufo_hotspots_population_densities_3d.html" width="100%" height="300px" title="3D Mapping of the hotspots with the population densities." frameBorder="0"></iframe>
    </div>
    <div class="iframe-frame">
        <div class = "iframe-title"> Military Bases Near Hotspots </div>
        <iframe id="hotspots_military" src="{{ site.baseurl }}images/ufo_hotspots_military_3d.html" width="100%" height="300px" title="3D Mapping of the hotspots with the military bases." frameBorder="0"></iframe>
    </div>
  </div>


  
  <div class="main-content">

  The left most graph above overlays population density with the focused hotspots. We can definetly see some correlation within areas like Southern California and the New York greater area. However, parts of the Southwest, including rural Arizona, New Mexico and the parts of the Washington state, don't follow as expected, with relatively low population density but still reporting a high number of sightings.
  <br>
  This suggests, even though the population can have some influence on these reports, its not the only factor at play here.
  <br>
  <br>
  To explore another possible explanation, the right most map plots the location of military bases relative to the same hotspots. Here, an interesting pattern emerges: many sightings occur near or around military zones—especially in the Desert Southwest, where facilities like Area 51 and Edwards Air Force Base are located. Similar overlaps appear in states like Texas, Florida, and Virginia, all of which host major military operations.
  <br>
  <br>
  Considering both of these analysis, we can't conclude on one single factor that can fully explain this distribution. While population somewhat aligns with certain hotspots - particularly in urban coastal areas - other regions with fewer people still report very frequent sightings. The proximity of many of these locations to military installations suggests additional influences, whether from aerial testing activities or the increased public awareness and speculation that surrounds such areas. 
  <br>
  <br>
  
  <h2>2. Temporal Trends: When Are UFOs Seen?</h2>


  Another interesting aspect of our data is the timing of UFO sightings. By looking at possible patterns in these reports, we identify connections to cultural events or reflect wider societal concerns. This approach has been explored in several studies which we will try and use to explain these factors.
  
  <br>
  <br>
  In the graph below, we visualize reported sightings across the decades, aligning them with U.S. presidential terms. This helps us look for patterns and surges in public reporting, and assess whether leadership changes, national discourse, or specific political eras might correlate with heightened UFO activity.
    
  </div>
  
  <div style="display: flex; justify-content: center; align-items: center; margin: 20px 0; margin-left: 20px;">
    <iframe id="timeline_plot" src="{{ site.baseurl }}images/ufo_sightings_presidents.html" width="100%"  height="550px"  style="border: none;" title="Sightings Over Time and Presidency"></iframe>
  </div>
    
  <div class="main-content">

  By looking at the above graph, its possible to see a steady and slow rise of reported sightings along the early years of the previous century. However, there is a sharp increase in the begining of the 1990s and peak in the early 2010s. Looking closely at each phase we can conclude:
  <ul>
    <li><b>1960s–1980s:</b> The steady climb begins in the Cold War era, marked by space race milestones, conspiracy theories, and increasing interest in UFOs as part of popular culture. This era set the stage for the widespread cultural obsession with extraterrestrial life, a trend that has persisted into modern media and culture. <a href="https://www.theguardian.com/culture/2021/jun/25/how-pop-culture-has-shaped-our-understanding-of-aliens" target="_blank">The Guardian </a> was one of the media outlets that discusses how pop culture, including these shows, shaped our collective understanding of aliens and UFOs creating a wave of awareness and understanding previously unpreceded.</li>
    <li><b>1990s:</b> UFO sightings during this period, such as the Phoenix Lights (1997), were now possible to be recorded, saved and shared very easily by the the greater majority of the public. It was also brought to light during this period discussions about government cover-ups and classified military information, amplified by the rise of the internet as a space for conspiracy theories to flourish. Research has shown that major UFO events in the late 20th century significantly shaped our understanding of extraterrestrial phenomena as a culture, helping to drive the ongoing "UFO boom" that peaked in the 2010s by the <a href="https://newspaceeconomy.ca/2024/09/02/timeline-of-major-ufo-uap-events/" target="_blank">NewSpace Economy timeline of major UFO events</a>.</li>
    <li><b>Early 2000s:</b> The surge continues, possibly fueled by post-9/11 anxieties, growing internet communities, and frequent coverage of extraterrestrial topics in popular media. New media outlets like YouTube allowed people to share UFO sightings and related experiences instantly. The growing connection between social media platforms and UFO sightings in this period helped facilitate more public participation in UFO-related discourse. This shift was documented in several studies, which discuss how the internet transformed public participation in UFO phenomena, as shown in the article about <a href="https://www.nature.com/articles/s41599-024-04182-z" target="_blank">Nature Communications Study</a> about the role of digital platforms in the growing interest in UAPs.</li>
    <li><b>2010 Forward:</b> The peak in sightings may reflect both widespread social media use and official military or government statements reigniting public attention toward unidentified aerial phenomena. The U.S. Department of Defense’s public acknowledgment of UFO investigations (including the release of videos in 2017) prompted a renewed public interest, which pieced together with the rapid spread of information through online communities, led to a spike in sightings. For example, in the <a href="https://www.nature.com/articles/s41598-023-49527-x?fromPaywallRec=false#Sec8" target="_blank">Nature Study on UAP</a> it is discussed the growing number of UAP-related sightings and their analysis through data, showing a correlation between official disclosures and the increase in UAP reports. </li>
  </ul>
  
  The main takeaway from these fluctuations is that the rise and fall of UFO sightings over time are not merely reflections of growing extraterrestrial curiosity, but also mirror larger socio-political and technological shifts in society. As our ability to share information has evolved, so too has the cultural and public fascination with the unknown.

  <h2>What Are People Seeing?</h2>

  Considering our previous research questions of <em>where</em> and <em>when</em> UFO sightings occur, the want to finalize our analysis with uncovering what people are actually seeing. 


  

  </div>

  <img id="wordcloud" src="{{ site.baseurl }}images/ufo_wordcloud.png" width="100%" alt="Word Cloud of UFO Descriptions"/>

  <iframe id="cooccurrence plot" src="{{ site.baseurl }}images/ufo_keyword_cooccurrence_network.html" width="100%"  height="750px"  style="border: none;" title="Sightings Over Time and Presidency"></iframe>

<url> https://www.nature.com/articles/s41599-024-04182-z
</body>
