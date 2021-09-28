<template>
<div
    class="entry-container mb-3 pointer p-2"
    @click="$router.push({name: 'entry', params:{id:10}})"
    >
    <div class="entry-title d-flex">
        <span class="text-success fs-5 fw-bold">15</span>
        <span class="mx-1 fs-5">Julio</span>
        <span class="mx-2 fw-light">2021, jueves</span>
    </div>

    <div class="entry-description">
        Consectetur voluptate et duis eu aute excepteur elit qui sunt eiusmod non nostrud adipisicing. Eu voluptate deserunt do culpa nisi proident. Pariatur qui nulla labore mollit culpa officia consectetur deserunt minim aliquip sunt nostrud. Ad laboris commodo eiusmod tempor non sint duis. Est duis ullamco fugiat laborum labore quis in anim sunt. Incididunt laboris enim est deserunt est ullamco id mollit velit enim pariatur ad pariatur. Veniam qui enim adipisicing velit consectetur officia anim.
    </div>
</div>
  
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container{
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;
    &:hover {
        background-color: lighten($color: grey, $amount: 45%);
        transition: 0.2s all ease-in;
    }
    .entry-description{
        font-size: 12px;

    }
}

</style>