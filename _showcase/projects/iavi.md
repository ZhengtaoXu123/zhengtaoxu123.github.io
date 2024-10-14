---
show: true
width: 12
date: 2021-12-31
group: Projects
---

<div class="p-3">
  <h3 class="mt-3">A Homemade Newtonian Reflecting Telescope</h3>
  <p>
    This project built a Newtonian reflecting telescope and used it to observe the moon. During the observations, issues such as shaking images, inability to see the entire view of the moon, and low definition were encountered. By adding a tripod, implementing image stitching, and using a single image haze removal algorithm for dehazing, we finally obtained a high-definition panoramic view of the entire moon.
  </p>

  <!-- 图片展示部分 -->
  <div class="row project-images">
    <div class="col centered-img">
      <img src="{{ '/assets/images/projects/iavi/telescope.png' | relative_url }}" class="w-100 rounded-sm mb-3" data-toggle="tooltip" title="our telescope">
    </div>
    <div class="col centered-img">
      <img src="{{ '/assets/images/projects/iavi/moon.gif' | relative_url }}" class="w-100 rounded-sm mb-3" data-toggle="tooltip" title="captured moon">
      <img src="{{ '/assets/images/projects/iavi/moon2.gif' | relative_url }}" class="w-100 rounded-sm mb-3" data-toggle="tooltip" title="captured moon after processing">
    </div>
    <div class="col centered-img">
      <img src="{{ '/assets/images/projects/iavi/moon.png' | relative_url }}" class="w-100 rounded-sm mb-3" data-toggle="tooltip" title="full view of moon after processing">
    </div>
  </div>


</div>
