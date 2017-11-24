  <!-- 关注卡片 组件-->
<template>
  <div class="card">
    <header class="card-header">
        <p class="card-header-title">
          Component
        </p>
      </header>
    <div class="card-image">
      <figure class="image is-2by1">
        <img src="https://bulma.io/images/placeholders/640x320.png" alt="Placeholder image">
      </figure>
    </div>
    <div class="card-content">
      <div class="content">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        Phasellus nec iaculis mauris. <a>@bulmaio</a>.
        <a href="#">#css</a> <a href="#">#responsive</a>
      </div>
      <nav class="level is-mobile">
        <div class="level-left">
          <a class="level-item">
            <span class="icon is-small"><i class="fa fa-reply"></i></span>
          </a>
          <a class="level-item">
            <span class="icon is-small"><i class="fa fa-retweet"></i></span>
          </a>
          <a class="level-item">
            <span class="icon is-small"><i class="fa fa-heart"></i></span>
          </a>
        </div>
        <span class="tag">#Tag label#</span>
      </nav>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>