<template>
  <div class="home">
    <RestaurantRow/>
  </div>
</template>

<script>
// IMPORT
// import BDD from '../BDD.js'

// COMPONENTS
import RestaurantRow from '../components/RestaurantRow.vue';
export default {
    name: 'HomePage',
    components: {
        RestaurantRow,
    },
    setup() {
        class Restaurant {
            constructor(name, note, image, drive_time){
                this.name = name
                this.note = note
                this.image = image
                this.drive_time = drive_time
            }
        }

        var resto = new Restaurant('toto', 4.5, 'img', '45mn')

        console.log(resto)
    }

}
</script>

<style>

</style>