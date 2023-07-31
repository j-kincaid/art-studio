<template>
  <header class="main-header">
    <div class="switch">
      <div class="flicker"></div>
      <div class="moon"></div>
    </div>
    <h1 class="name"><router-link to="/">Jessica Kincaid</router-link></h1>

    <h2 class="headline">Open Studio</h2>
    <ul class="top-nav">
      <li>
        <div class="dropdown">
          <button class="dropbtn">art</button>
          <div class="dropdown-content">
            <a><router-link to="/dream">dreams</router-link></a> 
            <router-link to="/nature">nature</router-link>
            <router-link to="/abstract">abstract</router-link>
          </div>
        </div>
      </li>
      <li>
        <router-link to="/about">about</router-link>
      </li>
      <li>
        <router-link to="/resume">resume</router-link>
      </li>
    </ul>
  </header>
</template>

<script setup>


</script>