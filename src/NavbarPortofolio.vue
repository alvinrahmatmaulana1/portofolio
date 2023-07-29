<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar >
      <template #logo>
          <h1 class="pl-3" style="font-family: Arial, Helvetica, sans-serif;">Alvin Rahmat Maulana</h1>
        
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink isActive link="#">Beranda</NavbarLink>
          <NavbarLink link="#">Tentang Saya</NavbarLink>
          <NavbarLink link="#">Kemampuan</NavbarLink>
          <NavbarLink link="#">Project</NavbarLink>
          <NavbarLink link="#">Kontak</NavbarLink>
        </NavbarCollapse>
      </template>
    </Navbar>
    
</template>