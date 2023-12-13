---
layout: page
title: FISH Analyze 
description: #Cell and Signal Analyze on FISH Images
img: assets/img/cellCover.png
importance: 1
category: work
---

The analysis of nuclei on fluorescent in situ hybridization (FISH) is an important technique used in pathology to identify and characterize genetic abnormalities and mutations in cells. This technique provides a way to visualize specific DNA sequences and chromosomal regions within the nuclei of cells, allowing for the detection of genetic changes that may be associated with diseases such as cancer.

FISH analysis can be used to detect a wide range of genetic abnormalities, including chromosomal translocations, deletions, and amplifications, as well as gene fusions and mutations. By detecting these genetic changes, FISH analysis can help pathologists to accurately diagnose and classify various types of cancers and other diseases, and to provide prognostic information regarding disease progression and treatment response.

Overall, our research introduces a specialized automated algorithm for fluorescence in situ hybridization (FISH) analysis, specifically designed for pathologists' use. The identification and examination of nuclei in FISH images play a critical role in pathology, particularly in cancer diagnosis and treatment. Manual detection of nuclei in FISH images is a time-consuming, subjective, and error-prone task for pathologists, leading to inconsistencies between observers and potential mistakes. Hence, there is a strong need for automated methods that can accurately detect and segment nuclei in FISH images, enhancing the precision and efficiency of cancer diagnosis.

In details, our approach offers a comprehensive analysis, encompassing both signal and cell detection and their analysis, all completed within seconds for a given image. Traditionally, pathologists would conduct this evaluation using QuPath. However, our prototype application not only delivers equivalent functionality but also presents the case and analysis conveniently on a single screen, offering channel options. This approach is highly beneficial as it also provides insights into signal visibility and cell nucleus boundaries by combining channels. 

<div class="caption">
    *The images displayed below exhibit the outcomes achieved using the prototype interface that I developed.
</div>

<div class="caption">
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cellAnalyze/18875_20_24_qupath.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The display of a case in QuPath.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cellAnalyze/18875_20_24_red_qupath.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cellAnalyze/18875_20_24_gr_qupath.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cellAnalyze/18875_20_24_blue_qupath.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The display of channels of the case in QuPath.
</div>

<div class="caption">
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cellAnalyze/18875_20_24_GTLabels.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The manual labelling of signals and cell nucleus by the pathologist on the case in QuPath.
</div>

<div class="caption">
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cellAnalyze/18875_20_24_elif_sonuc.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The analysis result of the case on the app.
</div>

<div class="caption">
    *I am unable to provide the technical specifics of the project due to the confidentiality requirements.
</div>



