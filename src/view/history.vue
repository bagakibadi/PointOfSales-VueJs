<template>
<div>
  <Navbar2/>
  <div>
    <Sidebar/>
  </div>
  <div>
    <Rectangle/>
  </div>
</div>
</template>

<script>
import Navbar2 from '../components/_module/Navbar2.vue';
import Sidebar from '../components/_module/Sidebar.vue';
import Rectangle from '../components/_module/Rectangle.vue';

export default {
  name: 'History',
  components: {
    Navbar2,
    Sidebar,
    Rectangle,
  },
};
</script>

<style scoped>

</style>
