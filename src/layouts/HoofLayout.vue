<template>
  <nav>
    <ul>
      <li>
        <router-link to="/">Home</router-link>
      </li>
      <li>
        <router-link to="/about">About</router-link>
      </li>
      <li>
        <router-link to="/syntra">Syntra</router-link>
      </li>
    </ul>
  </nav>

  <router-view />

  <footer>
    <p>© 2022 - Code Coaching</p>
  </footer>
</template>
