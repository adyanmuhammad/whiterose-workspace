---
layout: service
title: "Decorating Services Within Your City"
permalink: /decorating/
number: 7
---

<p class="lead">
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur non odio ullamcorper, dignissim ante sed, molestie eros. Sed hendrerit molestie ante. Morbi ullamcorper nunc sit amet lacus sodales, et mattis orci ultrices. Nulla at augue scelerisque, consequat mauris in, pharetra arcu. Praesent sed nisi vel leo dapibus venenatis. Integer feugiat mi massa, vel varius magna efficitur id. Aenean sodales neque et massa auctor maximus. Quisque lacinia lorem in enim cursus, eget vestibulum diam iaculis.
</p>

Aenean interdum, dolor eget venenatis hendrerit, risus mi convallis mauris, in tempor turpis mauris non metus. Nullam viverra a libero ut pellentesque. Duis massa purus, interdum non sem in, hendrerit pellentesque magna. Vivamus sed accumsan ligula, vel tincidunt dolor. Nullam non varius mi. Nunc ac erat enim. Phasellus pellentesque tortor nisi, sed mattis eros pretium id. Curabitur tincidunt egestas viverra. Suspendisse semper nibh ut ipsum aliquet, eget accumsan mauris sagittis. In varius vel mauris porttitor elementum. Etiam iaculis risus in leo malesuada facilisis.

<div>
<img 
  class="img-responsive"
  {%- 
    assign service__image = site.data.services[0].title 
    | prepend: "/assets/images/services/" 
    | append: ".webp" 
  %}
  src="{{ service__image | relative_url }}" 
  alt="{{ site.data.services[0].title | capitalize }}"
  style="margin-bottom: 2rem;"
>
</div>

Sed mattis libero lorem, ut dapibus dui pretium malesuada. Nunc sit amet gravida est, egestas interdum lorem. Etiam eget commodo purus. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Nam consectetur dui sed lorem tincidunt, et consectetur elit mattis. Ut scelerisque rutrum porttitor. Donec vitae magna rhoncus sem blandit ornare. Etiam a purus vitae enim imperdiet auctor. Nulla maximus facilisis ligula, vitae lacinia sapien consequat quis. Aliquam lobortis, lacus ut blandit pulvinar, ex nulla tempus nisi, id aliquam nunc tellus quis nisi. Duis ut ante facilisis, pharetra ante eget, tempor purus.

Sed neque tellus, varius eget cursus ut, suscipit ac neque. Donec at nunc eu orci porta varius ut eget leo. Nullam vel erat consequat orci mollis dapibus. In eget nisi sed ante elementum efficitur ut at est. Vestibulum sit amet diam lacinia, suscipit nibh eu, ornare arcu. Sed malesuada elit ornare, euismod lacus condimentum, sollicitudin ex. Donec eget suscipit felis. Interdum et malesuada fames ac ante ipsum primis in faucibus. Pellentesque pharetra convallis eros, a hendrerit leo congue et. Nunc id sem lacinia, facilisis felis a, eleifend lorem.

Integer viverra ex at faucibus placerat. Aliquam eu neque eu mi mollis consequat vel in elit. Praesent malesuada elit et odio gravida, ac feugiat felis convallis. Praesent ut arcu egestas, vehicula lacus non, cursus lectus. Curabitur et placerat sem, eget imperdiet augue. Curabitur molestie, augue in porta congue, ipsum ipsum tristique tortor, et aliquet lorem felis id tellus. Nunc ultrices ipsum vel urna mollis, eu convallis ex condimentum. Suspendisse potenti.

<style>
  .col-sm-row-lg {
    display: flex;
    flex-direction: column;
  }
  @media (min-width: 960px) {
    .col-sm-row-lg {
      display: flex;
      flex-direction: row;
    }
  }
</style>

{% include service-info.html %}