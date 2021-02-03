<template>
    <div>
        <header class="py-6">
            <div class="max-w-7xl mx-auto px-4">
                <div class="flex justify-between items-center">
                    <Logo class="w-32 text-gray-900"/>
                    <nav>
                        <inertia-link href="/">Home</inertia-link>
                    </nav>
                </div>
            </div>
        </header>
        <main>
            <slot/>
        </main>
        <footer class="">
            <div class="max-w-7xl mx-auto px-4">
                <div class="bg-gray-900 text-white rounded-t-3xl px-28 py-6 flex justify-between items-center">
                    <Logo class="w-32 text-white"/>
                    <div>
                        <p>&copy; @ilmala - devchallenge.io 2021</p>
                    </div>
                </div>
            </div>
        </footer>
    </div>
</template>

<script>
import Logo from "../Components/Logo"

export default {
    name: "AppLayout",
    components: {
        Logo
    }
}
</script>

<style scoped>

</style>
