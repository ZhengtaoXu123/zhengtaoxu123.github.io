---
show: true
width: 12
date: 2023-5-21
group: Projects
---

<div class="p-3">
  <h3 class="mt-3">Unbounded Scene Representation Based on Neural Radiance Fields (NeRF)</h3>
  <p>
    Neural Radiance Fields (NeRF) is a view synthesis technique for implicit scene representation, used in task like 3D reconstruction. While effective for small scenes, it struggles with unbounded large scenes, producing blurry images and slow training speeds. This project improved NeRF using <a href="https://jonbarron.info/mipnerf360/">Mip-NeRF 360</a> reproduction, <a href="https://segment-anything.com/">SAM image segmentation</a>, <a href="https://github.com/advimman/lama">LaMa image completion</a> to enhance performance in unbounded scenes.
  </p>

  <!-- 图片展示部分 -->
  <div class="row project-images">
    <div class="col-7 centered-img">
      <img src="{{ '/assets/images/projects/nerf/camera_position.gif' | relative_url }}" class="w-100 rounded-sm mb-3" data-toggle="tooltip" title="camera positions">
    </div>
    <div class="col-5 centered-img">
      <img src="{{ '/assets/images/projects/nerf/render_video.gif' | relative_url }}" class="w-100 rounded-sm mb-3" data-toggle="tooltip" title="render video">
    </div>
  </div>

</div>
