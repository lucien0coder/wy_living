  <!-- 发表内容与上传图片区 组件 -->
<template>
  <div class="container">
    <div class="notification">
      <div class="field">
        <textarea class="textarea" placeholder="10 lines of textarea" rows="10"></textarea>
      </div>
      <div class="field">
        <img src="https://bulma.io/images/placeholders/48x48.png">
        <img src="https://bulma.io/images/placeholders/48x48.png">
        <img src="https://bulma.io/images/placeholders/48x48.png">
        <div class="file is-small is-info is-boxed">
          <label class="file-label">
            <input class="file-input" type="file" name="resume">
            <span class="file-cta">
              <span class="file-icon">
                <i class="fa fa-cloud-upload"></i>
              </span>
              <span class="file-label">
                上传图片
              </span>
            </span>
          </label>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style>

</style>