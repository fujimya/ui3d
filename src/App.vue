<template>
    <div>
        <b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand href="#">3D Viewer</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <!-- <b-nav-item href="#">Link</b-nav-item> -->
        <!-- <b-nav-item href="#" disabled>Disabled</b-nav-item> -->
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-form>
          <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
          <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
        </b-nav-form>

       
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
  <b-container fluid class="mt-5 text-center">
  <b-row >
    <b-col>
       <b-card
       header="3D 1"
       >
         <!-- <model-obj src="./aswd.obj"></model-obj> -->
         <!-- <model-collada src="./collada/elf/elf.dae"></model-collada> -->
         <model-ply src="./besar.ply"></model-ply>
       </b-card>
      </b-col>
       <b-col>
       <b-card
       header="3D 2"
       >
         <!-- <model-obj src="./aswd.obj"></model-obj> -->
         <!-- <model-collada src="./collada/elf/elf.dae"></model-collada> -->
         <model-ply src="./besar.ply"></model-ply>
       </b-card>
      </b-col>
       <b-col>
       <b-card
       header="3D 3"
       >
         <!-- <model-obj src="./aswd.obj"></model-obj> -->
         <!-- <model-collada src="./collada/elf/elf.dae"></model-collada> -->
         <model-ply src="./besar.ply"></model-ply>
       </b-card>
      </b-col>
       <b-col>
       <b-card
       header="3D 4"
       >
         <!-- <model-obj src="./aswd.obj"></model-obj> -->
         <!-- <model-collada src="./collada/elf/elf.dae"></model-collada> -->
         <model-ply src="./besar.ply"></model-ply>
       </b-card>
      </b-col>
  </b-row>
</b-container>
    </div>
</template>
<script>
// import { ModelObj } from 'vue-3d-model';
// export default {
//   components: { ModelObj }
// }

// import { ModelCollada } from 'vue-3d-model'

//     export default {
//         components: {
//             ModelCollada
//         }
//     }

 import { ModelPly } from 'vue-3d-model'

    export default {
        components: {
            ModelPly
        }
    }
</script>
