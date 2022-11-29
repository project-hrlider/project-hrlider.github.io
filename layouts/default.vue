<template>
    <div>
        <nav class="nav py-6">
            <NuxtLink class="nav__link text-green-500" to="/">Home</NuxtLink>
            <NuxtLink class="nav__link" to="/about">About</NuxtLink>
        </nav>
        <slot />
    </div>
</template>

<style>
.nav{
  display: flex;
  justify-content: center;
  gap: 12px;
}
</style>