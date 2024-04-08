---
layout: page
title: HE2DAPI
description: #Mapping region from H&E to DAPI
img: assets/img/he2dapi_cover.png
importance: 3
category: work
---

Hematoxylin and Eosin (H&E) staining is a commonly used method in pathology to identify different cell types in tissue samples based on the morphology of the stained cells. However, this staining method may not always provide sufficient information for accurate identification of cell types. In contrast, 4',6-diamidino-2-phenylindole (DAPI) staining provides information on the location and distribution of cells within tissues based on the staining of cell nuclei.

Therefore, the matching of a reference region in an H&E image with a corresponding region in a DAPI image is essential in pathology, particularly in cancer diagnosis. The complementary information provided by both imaging methods helps to accurately identify cell types, visualize tissue structures more clearly, and ultimately aid in the better diagnosis of diseases and identification of abnormalities in tissue samples.

To accurately align the designated region from the HE image with the DAPI image, preliminary preprocessing steps are conducted. Following this, the rotational invariant Scale-Invariant Feature Transform (SIFT) algorithm is employed to detect keypoints common to both images. This process entails comparing the chosen window from the HE image, named as the reference window, with the extracted windows from the DAPI image, ensuring that these extracted windows maintain identical dimensions to the reference window. Consequently, the most similar regions are pinpointed for the user. The images below illustrate the correspondence between the region chosen by the user in the H&E image and its counterpart in the DAPI image.

<div class="caption">
    *The images displayed below exhibit the outcomes achieved using the prototype interface that I developed.
</div>

<div class="caption">
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/HE2DAPI_1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Example of matching region from a H&E to DAPI image. 
</div>


<div class="caption">
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/HE2DAPI_2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Another example of matching region from a H&E to DAPI image. 
</div>

<div class="caption">
    *I am unable to provide the technical specifics of the project due to the confidentiality requirements.
</div>

