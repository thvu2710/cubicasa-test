<script>
/**
 * Member UI component. Renders a nice member summary having image, name and description
 */
export default {
  name: 'CustomTaskList',
  props: {
    name: {
      type: String,
      default: null,
    },
  },
}
</script>
<template>
    <div class="media mt-1 border-top pt-3">
      <div class="media-body">
        <h6 class="mt-1 mb-0 font-size-15">{{ name }}</h6>
      </div>
      <div class="pointer-cursor">
        <i class="uil uil-info-circle"></i>
      </div>
    </div>
</template>
