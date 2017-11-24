  <!-- 输入评论模板组件 -->
<template>
  <div class="modal is-active">
    <div class="modal-background"></div>
    <div class="modal-content">
      <!-- 输入框组件 -->
      <div class="field">
        <label class="label has-text-white-bis">发表评论</label>
        <div class="control">
          <textarea class="textarea" placeholder="Textarea" rows="8"></textarea>
        </div>
      </div>
      <!-- 发送按钮组件 -->
      <div class="field is-grouped is-grouped-right">
        <div class="control">
          <button class="button is-link">发出</button>
        </div>
      </div>
    </div>
    <button class="modal-close is-large" aria-label="close"></button>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>