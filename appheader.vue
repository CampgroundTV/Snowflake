<template>
  <header class="header">
    <div class="logo">Campground</div>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Browse</a></li>
        <li><a href="#">Esports</a></li>
        <li><a href="#">Music</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style lang="scss" scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 2rem;
  background-color: #0e0e10;
  color: white;
  border-bottom: 1px solid #2c2c2c;

  .logo {
    font-size: 1.75rem;
    font-weight: bold;
  }

  nav ul {
    display: flex;
    list-style: none;

    li {
      margin-left: 1.5rem;

      a {
        color: white;
        text-decoration: none;
        font-size: 1rem;

        &:hover {
          text-decoration: underline;
        }
      }
    }
  }
}
</style>
