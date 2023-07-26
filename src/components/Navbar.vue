<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar>
      <template #logo>
        <NavbarLogo link="" alt="" image-url="https://images.hive.blog/p/3W72119s5BjWPGGUiZ9pqnZoj8JHYxCCp9dtn2QVeTRakW9srxfsqGGjSNrC3peGsGp9N716Fo92E2gUyXYt4gKt4u6m3cfwQPkfFjMDr3RDKUaXXHHWAA?format=match&mode=fit&width=768">
            Emporium Otaku
        </NavbarLogo>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink isActive link="#">Homepage</NavbarLink>
          <NavbarLink link="#">Categories</NavbarLink>
          <NavbarLink link="#">Blog</NavbarLink>
          <NavbarLink link="#">Contact</NavbarLink>
        </NavbarCollapse>
      </template>
    </Navbar>
</template>
