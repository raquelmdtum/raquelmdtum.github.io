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

  We are able to see some hotspots emerge throughout the country. Regions such as the Desert Southwest - including Southern California and Arizona - Northern Washington and the Greater New York area show higher concentrations of reported sightings. But what makes these locations so popular? Are they simply larger, more populated areas, or is there something about these regions that makes them more prone to have more encounters?

  <br>
  <br>

  To investigate this further, we added to more aspects to our geographical research. Could these hotspots reflect the population density of those areas, or might their procimity to military bases, like Area 51 in the Desert Southwest, be influencing the frequency of sightings? We will consider hotspot areas as those with 300+ sightings and plot both the density and military regions in relation to these hotspots.
  <br>
  <br>
  
  </div>

  <div class="iframe-wrapper">
    <div class="iframe-frame">
        <div class = "iframe-title"> Population Density Near Hotspots </div>
        <iframe id="population_densities" src="{{ site.baseurl }}images/ufo_hotspots_population_densities_3d.html" width="100%" height="350px" title="3D Mapping of the hotspots with the population densities." frameBorder="0"></iframe>
    </div>
    <div class="iframe-frame">
        <div class = "iframe-title"> Military Bases Near Hotspots </div>
        <iframe id="hotspots_military" src="{{ site.baseurl }}images/ufo_hotspots_military_3d.html" width="100%" height="350px" title="3D Mapping of the hotspots with the military bases." frameBorder="0"></iframe>
    </div>
  </div>


  
  <div class="main-content">

  <b> UNTIL HERE </b>
  The left most graph above overlays population density with the focused hotspots. We can definetly see some correlation within areas like Southern California and the New York greater area. However, parts of the Southwest, including rural Arizona, New Mexico and the parts of the Washington state, don't follow as expected, with 
  
   which hav It reveals that many of the hotspots—such as those in Southern California, the New York–New Jersey metro area, and Florida—closely align with densely populated areas. This correlation suggests that more populated regions naturally produce more sightings, likely due to the higher number of potential observers and easier access to technology for reporting incidents.
  <br>
  However, this pattern doesn’t fully explain all hotspot areas. For example, parts of the Southwest, including rural Arizona and New Mexico, report a high number of sightings despite relatively lower population densities.
  <br>
  <br>
  To explore another possible explanation, the second map plots the location of military bases relative to the same UFO hotspots. Here, an interesting pattern emerges: many sightings occur near or around military zones—especially in the Desert Southwest, where facilities like Area 51 and Edwards Air Force Base are located. Similar overlaps appear in states like Texas, Florida, and Virginia, all of which host major military operations.
  <br>
  This raises the possibility that classified military aircraft or exercises may be mistaken for UFOs. Alternatively, it invites speculation about whether these regions truly experience more unexplained activity.
  <br>
  <br>

</div>

  <div>
    <iframe id="hotspots_military" src="{{ site.baseurl }}images/ufo_hotspots_military_3d.html" width="100%" height="450px" title="3D Mapping of the hotspots with the military bases." frameBorder="0"></iframe>
  </div>

  <div class="main-content">
    <h2>2. Temporal Trends: When Are UFOs Seen?</h2>
    
    Understanding the timing of sightings can offer insight into public interest, media influence, or political context. Below, we chart the number of sightings over time alongside the sitting U.S. president.
    
  </div>
  
  <div>
    <iframe id="timeline_plot" src="{{ site.baseurl }}images/ufo_sightings_presidents.html" width="100%"  height="750px"  style="border: none;" title="Sightings Over Time and Presidency"></iframe>
  </div>
    
  <div class="main-content">

    Looking at UFO sightings across decades a steady and slow rise among the 1960s, there is also a dramatic increase beginning in the 1990s and peaking in the early 2010s. Some of these spikes align closely with major cultural, political, and technological moments, suggesting that these reports may not just reflect unexplained phenomena, but also mirror societal moods, pop culture narratives, and platforms where stories can be shared.

    <ul>
    <li><b>1960s–1980s:</b> The steady climb begins in the Cold War era, marked by space race milestones, conspiracy theories, and increasing interest in UFOs as part of popular culture. This era set the stage for the widespread cultural obsession with extraterrestrial life, a trend that has persisted into modern media and culture. <a href="https://www.theguardian.com/culture/2021/jun/25/how-pop-culture-has-shaped-our-understanding-of-aliens" target="_blank">The Guardian discusses how pop culture, including these shows, shaped our collective understanding of aliens and UFOs.</a></li>

    <li><b>Late 1990s:</b> UFO sightings during this period, such as the Phoenix Lights (1997) and Gulf Breeze sightings (1995), were covered by the media and spiked curiosity among the population about possible alien encounters. This was also a time of increased discussion about government cover-ups and classified military information, amplified by the rise of the internet as a space for conspiracy theories to flourish. Research has shown that major UFO events in the late 20th century significantly shaped our understanding of extraterrestrial phenomena as a culture, helping to drive the ongoing "UFO boom" that peaked in the 2010s. <a href="https://newspaceeconomy.ca/2024/09/02/timeline-of-major-ufo-uap-events/" target="_blank">NewSpace Economy timeline of major UFO events</a>.</li>

    <li><b>Early 2000s:</b> The surge continues, possibly fueled by post-9/11 anxieties, growing internet communities, and frequent coverage of extraterrestrial topics in popular media. New media outlets like YouTube allowed people to share UFO sightings and related experiences instantly. Additionally, the rise of the internet led to more widespread and immediate public access to information about UFOs encouraging widespread interest. The growing connection between social media platforms and UFO sightings in this period helped facilitate more public participation in UFO-related discourse. This shift was documented in several studies, which discuss how the internet transformed public participation in UFO phenomena, as shown in the article from <em>Nature Communications</em> about the role of digital platforms in the growing interest in UAPs. <a href="https://www.nature.com/articles/s41599-024-04182-z" target="_blank">Nature Communications Study</a>.</li>

    <li><b>2010–2014:</b> The peak in sightings may reflect both widespread social media use and official military or government statements reigniting public attention toward unidentified aerial phenomena.The U.S. Department of Defense’s public acknowledgment of UFO investigations (including the release of videos in 2017) prompted a renewed public interest, which dovetailed with an increasingly connected world where sightings could be shared instantly across platforms like Twitter and Facebook. This era saw a spike in sightings tied to both increased government transparency and the rapid spread of information through online communities. For example, a study published in <em>Nature</em> discusses the growing number of UAP-related sightings and their analysis through data, showing a correlation between official disclosures and the increase in UAP reports. <a href="https://www.nature.com/articles/s41598-023-49527-x?fromPaywallRec=false#Sec8" target="_blank">Nature Study on UAP</a>.</li>

    </ul>

    <h3>References & Sources</h3>
    <ul>
        <li><a href="https://newspaceeconomy.ca/2024/09/02/timeline-of-major-ufo-uap-events/" target="_blank">NewSpace Economy: Timeline of Major UFO Events</a></li>
        <li><a href="https://www.nature.com/articles/s41599-024-04182-z" target="_blank">Nature Communications: Study on the Role of Digital Platforms in UFO/UAP Growth</a></li>
        <li><a href="https://www.nature.com/articles/s41598-023-49527-x?fromPaywallRec=false#Sec8" target="_blank">Nature: UAP Study and Sightings Data Analysis</a></li>
        <li><a href="https://www.theguardian.com/culture/2021/jun/25/how-pop-culture-has-shaped-our-understanding-of-aliens" target="_blank">The Guardian: How Pop Culture Shaped Our Understanding of Aliens</a></li>
    </ul>


    <h2>What Are People Seeing?</h2>
  </div>

  <img id="wordcloud" src="{{ site.baseurl }}images/ufo_wordcloud.png" width="100%" alt="Word Cloud of UFO Descriptions"/>

<url> https://www.nature.com/articles/s41599-024-04182-z
</body>
