<template>
    <div>
      <nav class="nav">
        <NuxtLink to="/">top page</NuxtLink>
        <NuxtLink to="/price">price page</NuxtLink>
        <NuxtLink to="/menu">menu page</NuxtLink>
      </nav>
      <slot />
    </div>

  </template>

<style>
.nav a{
    display: inline-block;
    margin-right: 10px;
}
</style>