---
layout: page
title: Visualising acoustic cues 
nav: false
description: 3D Gaussians with plotly
img:
importance: 1
category: work
---

In one of my research projects, I <a href="https://www.frontiersin.org/articles/10.3389/fpsyg.2021.676271/full#:~:text=Using%20Rational%20Models%20to%20Interpret%20the%20Results%20of%20Experiments%20on%20Accent%20Adaptation,-Maryann%20Tan1&text=Exposure%20to%20unfamiliar%20non%2Dnative,of%20the%20talker's%20phonetic%20cues.">analysed the outcomes of two accent adaptation experiments conducted in English and Swedish</a>. The two studies employed the same paradigm which produced contradicting results - one had a positive effect of exposure and the other showed a null effect. After ruling out type 1 or 2 errors and low statistical power we constructed ideal observers to determine if both results would have been predicted by models of speech perception that posit distributional learning when listeners adapt to unfamiliar talkers. 

To understand such models one presupposes:
<ul>
    <li>the listener perceives the segments of speech that make up a word (e.g. bed is made up 3 categories of sounds, b-e-d)</li>
    <li>the listener is sensitive to the acoustic cues that make up the sounds.</li>
    <li>more than one acoustic cue measurement can be mapped to the same sound category.</li>
    <li>the researcher knows which cues matter the most for identifying a given sound category.</li>
</ul>    

In distributional learning the listener tracks the regularities of acoustic cues and their occurence with the sound category of interest. Many acoustic cue measurements can map to the same category thus forming a distribution. 

One could loosely think of "bed" and "bet" as being differentiated by only the final sound (d/t). The acoustic cues that map to the categories "d" and "t" at the end of the word has been identified to be 3 temporal measures -- the duration of the previous vowel sound ("e"), the duration of closure (to produce d or t at the end of a word the talker has to momentarily stop the air-flow through his vocal tract), and the duration of the burst of air that follows release of the closure. 

<div style="padding-bottom:76.25%; position:relative; display:block; width: 100%">
<iframe width="100%" height="100%" frameborder="0" scrolling="no" src="/assets/plotly/p_en.html" frameborder="0" allowfullscreen="" style="position:absolute; top:0; left:0"></iframe>
</div>



<div class="caption">
    Production of "d"-words and "t"-ending words by native and non-native talkers of US English. Points show durational measures of vowel, closure, burst for each word. Ellipses represent the parameterised distributions of cues under Gaussian assumptions. 
</div>

We could in principle, map all the combinations of cue measurements that occur each time "d" is produced and all the combinations that occur each time "t" is produced and visualise the distributions that divide the two categories of sounds. We could compare data from native talkers with that of non-native talkers and see how they differ or don't differ. With these visual models we could reasonably predict that the greater the similarity the less there is for the listener to learn about the new talker since her cues would fall within an expected range.

In this project we compared the production of stop consonants ("d" and "t) in word-final contexts (e.g. bat and bad) of native and non-native speakers in both English and Swedish.


<div style="padding-bottom:76.25%; position:relative; display:block; width: 100%">
<iframe width="100%" height="100%" frameborder="0" scrolling="no" src="/assets/plotly/p_sw.html" frameborder="0" allowfullscreen="" style="position:absolute; top:0; left:0"></iframe>
</div>

<div class="caption">
    Same as previous plot but with Swedish word final "d" and "t". 
</div>








