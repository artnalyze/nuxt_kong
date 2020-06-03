<template>
  <div>
    <b-navbar type="dark" variant="dark">
      <b-navbar-nav>
        <nuxt-link to="/" class="nav-item nav-link">หน้าแรก</nuxt-link>
        <nuxt-link to="/admin" class="nav-item nav-link">ผู้ดูแล</nuxt-link>
        <nuxt-link to="/posts" class="nav-item nav-link">บทความ</nuxt-link>
        <nuxt-link to="/users" class="nav-item nav-link">สมาชิก</nuxt-link>
      </b-navbar-nav>
    </b-navbar>
    <nuxt/>
  </div>
</template>
