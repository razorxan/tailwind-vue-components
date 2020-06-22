<template>
    <div id="app" class="h-screen">
        <Navbar class="py-1 px-4">
            <NavbarItem
                class="bg-teal-900 text-white px-4 py-1 rounded focus:outline-none border-0 border-gray-900 focus:border-white focus:border-1"
            >CIAO</NavbarItem>
            <NavbarItem
                class="ml-2 bg-teal-900 text-white px-4 py-1 rounded focus:outline-none border-0 border-gray-900 focus:border-white focus:border-1"
            >CIAO</NavbarItem>
        </Navbar>
        <div class="relative w-full m-10">
            <button
                class="border rounded shadow block w-64 text-left px-2 py-1 max-h-xxl overflow-auto"
            >select</button>
            <div v-if="open" class="absolute w-auto left-0 p-2 rounded bg-white mt-2 border shadow">
                <button class="block px-2 py-1 text-left blocK">Value 1</button>
                <button class="block px-2 py-1 text-left blocK">Value 2 longer than the previous</button>
                <button class="block px-2 py-1 text-left blocK">Value 3</button>
                <button class="block px-2 py-1 text-left blocK">Value 4</button>
                <button class="block px-2 py-1 text-left blocK">Value 5</button>
                <button class="block px-2 py-1 text-left blocK">Value 3</button>
                <button class="block px-2 py-1 text-left blocK">Value 4</button>
                <button class="block px-2 py-1 text-left blocK">Value 5</button>
                <button class="block px-2 py-1 text-left blocK">Value 3</button>
                <button class="block px-2 py-1 text-left blocK">Value 4</button>
                <button class="block px-2 py-1 text-left blocK">Value 5</button>
                <button class="block px-2 py-1 text-left blocK">Value 3</button>
                <button class="block px-2 py-1 text-left blocK">Value 4</button>
                <button class="block px-2 py-1 text-left blocK">Value 5</button>
            </div>
        </div>
    </div>
</template>

<script>
import Navbar from "@/components/Navbar";
import NavbarItem from "@/components/Navbar/NavbarItem";
import "@/assets/styles/main.css";
export default {
    name: "App",
    components: { Navbar, NavbarItem },
    data() {
        return {
            open: true
        };
    }
};
</script>
<style>
</style>
