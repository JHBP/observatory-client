<template>
  <div class="container pt-4">

    <h3>Active Projects</h3>

    <div class="row">
      <div class="col-lg-12">
        <ProjectSearch/>
      </div>
    </div>

  	<div class="row">
      <div class="col-lg-9">

  			<ul class="list-group mt-2 mb-4 text-center">
  				<a class="list-group-item" href="/#/projects/new">NEW</a>
  			</ul>

  			<ListView :collection="collection"/>

  		</div>

      <ProjectPinned/>

  	</div>
  </div>
</template>

<!-- // // // //  -->

<script>
import store from '@/store'
import ListView from './list.vue'
import ProjectSearch from './search.vue'
import ProjectPinned from './pinned.vue'

export default {
  props: ['collection'],
  computed: {
    fetching () {
      return store.getters['project/fetching']
    }
  },
  components: {
    ListView,
    ProjectSearch,
    ProjectPinned
  }
}
</script>


