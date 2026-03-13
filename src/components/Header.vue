<script setup lang="ts">
import Button from './button/Button.vue';

</script>

<template>
    <header class="bg-white border-b border-slate-200 sticky top-0 z-50">
        <div class="max-w-[1440px] mx-auto px-6 h-14 flex items-center justify-between">
        <div class="flex items-center gap-3">
        <!-- Logo Icon -->
        <div class="relative w-10 h-10">
            <img src="../assets/logo-cwf.png" alt="Logo" class="absolute inset-0 w-20 h-20 m-auto object-contain">
            <div class="w-10 h-20 absolute border-white opacity-20 transform -rotate-45"></div>
        </div>
        <h1 class="text-xl font-bold tracking-tight text-slate-900">Chenwoo Fishery Backoffice</h1>
        </div>
            <nav class="flex items-center gap-8">
                <ul class="flex items-center gap-8 text-sm font-medium text-slate-500">
                <li><a class="text-slate-900 border-blue-900 pb-7 pt-7" href="#">Catalog</a></li>
                <li><a class="hover:text-slate-900 transition-colors" href="#">Inventory</a></li>
                <li><a class="hover:text-slate-900 transition-colors" href="#">Orders</a></li>
                </ul>
                <div class="h-6 w-px bg-slate-200 mx-2"></div>
                    <Button name="Save Changes" />
                <div class="w-10 h-10 rounded-full bg-slate-200 flex items-center justify-center overflow-hidden border border-slate-300">
                <img alt="User Avatar" class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDmL_bj050tYULtQxMiFDdb-cBoMCGrmKRkfuuGGjqn1EQbzkqlkpIUR-qBFFn6OJzJJPJkVaY9NCI9ZFLK4MzaK6lVtUSpjzWviNCrCgfL-EvI5Qhy3zFTFQhbA8Fzp3heVVf8SGPitE60Yz5aJb1N29jJyyBj2QtYTOBJ5mfAyqns1WB5pPCYtdDeHB1ghaotZY0j4sKtH9d4i-nrsnBv5TyG4SQZQQZAoX-3JLRhEgKP0FNiGRc3XOGXjolqMnZhzHuOgycVTyc"/>
                </div>
            </nav>
        </div>
    </header>

    
</template>