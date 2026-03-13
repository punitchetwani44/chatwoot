<script>
export default {
  props: {
    disableBranding: {
      type: Boolean,
      default: false,
    },
  },
};
</script>

<template>
  <div
    v-if="!disableBranding"
    class="px-0 py-3 flex justify-center"
  >
    
      href="https://optywise.com"
      rel="noreferrer noopener nofollow"
      target="_blank"
      class="branding--link text-n-slate-11 hover:text-n-slate-12 cursor-pointer text-xs inline-flex hover:opacity-100 opacity-90 no-underline justify-center items-center leading-3"
    >
      <span>Powered by Optywise</span>
    </a>
  </div>
  <div v-else class="p-3" />
</template>
