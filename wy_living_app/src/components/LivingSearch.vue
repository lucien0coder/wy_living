  <!-- 详细搜索 组件 -->
<template>
  <div class="container">
    <div class="notification">
      <!-- 搜索框 组件-->
      <div class="field is-grouped">
        <p class="control is-expanded">
          <input class="input" type="text" placeholder="Find a repository">
        </p>
        <p class="control">
          <a class="button is-info">
            <span class="icon"><i class="fa fa-search"></i></span>
          </a>
        </p>
      </div>
      <!-- condition 组件 -->
      <!-- 时间组件 -->
      <div class="field">
        <label for="" class="label">入驻日期</label>
        <div class="control">
          <input class="input" type="date" name="" id=""> 
        </div>
      </div>
      <div class="field">
        <label for="" class="label">离开日期</label>
        <div class="control">
          <input type="date" name="" id="" class="input">
        </div>
      </div>

      <!-- 所在地与星级下拉组件 -->
      <div class="field">
        <div class="control has-icons-left">
          <div class="select">
            <select>
              <option selected>所在地</option>
              <option>Select dropdown</option>
              <option>With options</option>
            </select>
          </div>
          <span class="icon is-small is-left">
            <i class="fa fa-envelope"></i>
          </span>
        </div>
      </div>
      <div class="field ">
        <div class="control has-icons-left">
          <div class="select">
            <select>
              <option selected>星级</option>
              <option>Select dropdown</option>
              <option>With options</option>
            </select>
          </div>
          <span class="icon is-small is-left">
            <i class="fa fa-envelope"></i>
          </span>
        </div>
      </div>
      <!-- 标签 组件 -->
      <div class="field is-grouped is-grouped-multiline">
        <p class="control">
          <a class="button">
            自然
          </a>
        </p>
        <p class="control">
          <a class="button">
            园林
          </a>
        </p>
        <p class="control">
          <a class="button">
            欧式
          </a>
        </p>
        <p class="control">
          <a class="button">
            现代
          </a>
        </p>
        <p class="control">
          <a class="button">
            Five
          </a>
        </p>
        <p class="control">
          <a class="button">
            Size
          </a>
        </p>
        <p class="control">
          <a class="button">
            Seven
          </a>
        </p>
        <p class="control">
          <a class="button">
            Eight
          </a>
        </p>
        <p class="control">
          <a class="button">
            Nine
          </a>
        </p>
      </div>
      <hr>
      <!-- 搜索条件汇总 组件 -->
      <div class="field is-grouped is-grouped-multiline">
        <div class="control">
          <div class="tags has-addons">
            <a class="tag is-link">欧式</a>
            <a class="tag is-delete"></a>
          </div>
        </div>
      
        <div class="control">
          <div class="tags has-addons">
            <a class="tag is-link">海南</a>
            <a class="tag is-delete"></a>
          </div>
        </div>
      
        <div class="control">
          <div class="tags has-addons">
            <a class="tag is-link">4星级以上</a>
            <a class="tag is-delete"></a>
          </div>
        </div>
      
        <div class="control">
          <div class="tags has-addons">
            <a class="tag is-link">自然</a>
            <a class="tag is-delete"></a>
          </div>
        </div>
      
        <div class="control">
          <div class="tags has-addons">
            <a class="tag is-link">2017-12-01至2018-02-25</a>
            <a class="tag is-delete"></a>
          </div>
        </div>
      
        <div class="control">
          <div class="tags has-addons">
            <a class="tag is-link">Community</a>
            <a class="tag is-delete"></a>
          </div>
        </div>
      
        <div class="control">
          <div class="tags has-addons">
            <a class="tag is-link">Documentation</a>
            <a class="tag is-delete"></a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  
}
<script>

<style>

</style>