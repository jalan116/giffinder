<template>
    <input class="container block mx-auto rounded-full mt-8 p-2 text-2xl 
    outline-none text-center focus:ring-4 foucs:ring-green-500 focus:ring-opacity-50" 
    type="text" placeholder="I'm looking for ..." 
    v-model="searchItem"
    @change="getGifs"/>
</template>

<script setup>
import { searchItem, getGifs} from '../helpers/useGifs'
</script>