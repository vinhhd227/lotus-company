<template>
  <header class="header-global">
    <base-nav class="navbar-main" transparent type="" effect="light" expand>
      <router-link slot="brand" class="navbar-brand mr-lg-5" to="/">
        <!-- <img src="img/brand/white.png" alt="logo" /> -->
         <p class="m-0">LOTUS COMPANY</p>
      </router-link>

      <div class="row" slot="content-header" slot-scope="{ closeMenu }">
        <div class="col-6 collapse-brand">
          <a
            href="https://demos.creative-tim.com/vue-argon-design-system/documentation/"
          >
            <img src="img/brand/blue.png" />
          </a>
        </div>
        <div class="col-6 collapse-close">
          <close-button @click="closeMenu"></close-button>
        </div>
      </div>

      <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
        <li>
          <a
            slot="title"
            href="#"
            class="nav-link"
            data-toggle="dropdown"
            role="button"
          >
            <!-- <i class="ni ni-ui-04 d-lg-none"></i> -->
            <span class="nav-link-inner--text">Trang chủ</span>
          </a>
        </li>
        <li>
          <a
            slot="title"
            href="#"
            class="nav-link"
            data-toggle="dropdown"
            role="button"
          >
            <!-- <i class="ni ni-ui-04 d-lg-none"></i> -->
            <span class="nav-link-inner--text">Giới thiệu</span>
          </a>
        </li>
        <base-dropdown tag="li" class="nav-item">
          <a
            slot="title"
            href="#"
            class="nav-link"
            data-toggle="dropdown"
            role="button"
          >
            <i class="ni ni-collection d-lg-none"></i>
            <span class="nav-link-inner--text">Giải pháp</span>
          </a>
          <a class="dropdown-item">Thiết bị</a>
          <a class="dropdown-item">Hóa chất công nghiệp</a>
          <a class="dropdown-item">Tư vấn chuyển giao công nghệ</a>
          <a class="dropdown-item">Vận chuyển, kho bãi</a>
        </base-dropdown>
        <li>
          <a
            slot="title"
            href="#contact"
            class="nav-link"
            data-toggle="dropdown"
            role="button"
          >
            <!-- <i class="ni ni-ui-04 d-lg-none"></i> -->
            <span class="nav-link-inner--text">Liên hệ</span>
          </a>
        </li>
      </ul>
    </base-nav>
  </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown,
  },
};
</script>
<style></style>
