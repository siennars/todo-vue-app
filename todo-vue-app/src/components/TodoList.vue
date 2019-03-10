<template>
    <div> 
        <ul v-for="todo in todos">
            <li>{{todo.title}}</li>
        </ul>
    </div>
</template>

<script>
export default {
    props: ['todos']
}
</script>


<style>

</style>