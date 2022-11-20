<template>
    <div>
        <nav class="nav">
            <NuxtLink to="/">Home</NuxtLink>
            <NuxtLink to="/about">About</NuxtLink>
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