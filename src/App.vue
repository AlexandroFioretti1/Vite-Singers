<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
    components: {
        HelloWorld,
    }
}
</script>

<template>
    <section class="vue-home">
        <div class="container">
            <div class="row">
                <div class="col-12 d-flex flex-column justify-content-center align-items-center vh-100">
                    <div class="logos">
                        <a href="https://vitejs.dev" target="_blank">
                            <img src="/vite.svg" class="logo" alt="Vite logo" />
                        </a>
                        <a href="https://vuejs.org/" target="_blank">
                            <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
                        </a>
                    </div>
                    <HelloWorld />
                </div>
            </div>
        </div>
    </section>
</template>

