---
title: Team
nav:
  order: 3
---

# Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}
   
{% include section.html %}

### Alumni

**Elif Abacilar** spent her school summer holidays with us to learn all about spatial transcriptomics. We look forward to meeting again!

**Jonathan Thielmann** joined us for his MSc in Computer Science and did a phenomenal deep dive into XAI. Now continuing to track relevances in neural networks over at the Fraunhofer Institute.

**Caroline Forsythe**, bioinformatician by day and fitness instructor by evening, moved back to the US after her MSc with us.

**Shubhangi Kaushik** completed her MSc in Bioinformatics, developing a neural network model for predicting gene amplification from H&E images.

**Konrad Grapentin** joined us for a placement during his medical degree to systematically review ecDNA-immune interactions.

**Hamidreza Parand** interned with us during his MSc in Epidemiology, investigating metrics for spatially patterned gene expression that helped our XAI work along.

**Pedram Ramezani** helped us set up deep learning architectures as a student assistant, and went on to finish medical school.

**Jonas Lehmitz** left neurology training to complete an MSc in Data Science, and joined us for his thesis work on spatial transcriptomics data analysis. He subsequently moved to Munich to bring machine learning into hospital software. Fingers crossed!

**Mohammad el-Ismail** worked on his MSc thesis with us, making deep learning based predictions from H&E images of pancreatic cancer. Then went into industry as a computer vision engineer. 

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
