<script setup>
import { ref } from 'vue';
const like = ref(0);
const sad = ref(0);
function likeS() {
    like.value++;
}
function Sads() {
    sad.value++;
}
</script>

<template>
    <div class="d-flex flex-row">
        <div name="like">
            <button class="btn btn-primary m-1" @click="likeS()">
like
                {{ like }}
            </button>
        </div>
        <div name="sad">
            <button class="btn btn-danger m-1" @click="Sads()">
sad
                {{ sad }}
            </button>
        </div>
    </div>
</template>