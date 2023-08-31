---
layout: page
title: Visualising acoustic cues 
nav: false
description: 3D Gaussians with plotly
img:
importance: 1
category: work
---

In one of my research projects, I <a href="https://www.frontiersin.org/articles/10.3389/fpsyg.2021.676271/full#:~:text=Using%20Rational%20Models%20to%20Interpret%20the%20Results%20of%20Experiments%20on%20Accent%20Adaptation,-Maryann%20Tan1&text=Exposure%20to%20unfamiliar%20non%2Dnative,of%20the%20talker's%20phonetic%20cues.">analysed the outcomes of two accent adaptation experiments conducted in English and Swedish</a>. The two studies employed the same paradigm but produced opposing effects. To work out whether source of the difference was due to hypothesis testing errors or low 
Second language speakers of a language produce sound segments differently from native speakers. This doesn't necessarily pose a challenge to the untrained native listener unless the words are produced in an acoustic space that don't fall within native listener expectations. One way to illustrate how an accent might be challenging to what native listeners expect is to visualise the differences. 

In this project we compared the production of stop consonants ("d" and "t) in word-final contexts (e.g. bat and bad) of native and non-native speakers.

<div style="padding-bottom:76.25%; position:relative; display:block; width: 100%">
<iframe width="100%" height="100%" frameborder="0" scrolling="no" src="/assets/plotly/3d_en.html" frameborder="0" allowfullscreen="" style="position:absolute; top:0; left:0"></iframe>
</div>




<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.





The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
