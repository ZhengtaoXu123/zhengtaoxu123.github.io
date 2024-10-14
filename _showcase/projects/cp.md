---
show: true
width: 12
date: 2022-6-30
group: Projects
---

<div class="p-3">
  <h3 class="mt-3">Image Completion with Structure Propagation</h3>
  <p>
    This project replicated the methodology from the paper <a href="https://www.cse.cuhk.edu.hk/~leojia/all_final_papers/ImageCompletion_SIGGRAPH05.pdf">"Image Completion with Structure Propagation"</a>, which enhances traditional image completion by using structural lines to guide the restoration process. The technique involves three main steps: users annotate important structures with lines, source patches are collected along these lines for structural propagation, and block-based texture synthesis completes the image. The implementation supports direct and curved lines, and allows for extensive user interactions such as selecting repair areas, drawing structure lines, specifying texture sources, and making photometric adjustments.
  </p>

  <!-- 图片展示部分 -->
  <div class="row project-images">
    <div class="col-3 centered-img tighter-spacing">
        <img src="{{ '/assets/images/projects/cp/car/1.png' | relative_url }}" class="w-100 rounded-sm mb-3" data-toggle="tooltip" title="original image">
        <img src="{{ '/assets/images/projects/cp/car/3.png' | relative_url }}" class="w-100 rounded-sm mb-3" data-toggle="tooltip" title="image after structure propagation">
    </div>
    <div class="col-3 centered-img tighter-spacing">
        <img src="{{ '/assets/images/projects/cp/car/2.png' | relative_url }}" class="w-100 rounded-sm mb-3" data-toggle="tooltip" title="image with structure line">
        <img src="{{ '/assets/images/projects/cp/car/4.png' | relative_url }}" class="w-100 rounded-sm mb-3" data-toggle="tooltip" title="image after texture propagation">
    </div>
    <div class="col-3 centered-img tighter-spacing">
        <img src="{{ '/assets/images/projects/cp/goose/1.jpg' | relative_url }}" class="w-100 rounded-sm mb-3" data-toggle="tooltip" title="original image">
        <img src="{{ '/assets/images/projects/cp/goose/3.png' | relative_url }}" class="w-100 rounded-sm mb-3" data-toggle="tooltip" title="image after structure propagation">
    </div>
    <div class="col-3 centered-img tighter-spacing">
        <img src="{{ '/assets/images/projects/cp/goose/2.png' | relative_url }}" class="w-100 rounded-sm mb-3" data-toggle="tooltip" title="image with structure line">
        <img src="{{ '/assets/images/projects/cp/goose/4.png' | relative_url }}" class="w-100 rounded-sm mb-3" data-toggle="tooltip" title="image after texture propagation">
    </div>
  </div>


</div>
