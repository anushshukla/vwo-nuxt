<template>
  <div>
    Page Index
  </div>
</template>

<script>
export default {
  head() {
    return {
      script: [
        {
          innerHTML: `
            // Your internal script code here
            console.log('Internal script executed');
          `,
        },
      ],
    };
  },
};
</script>
