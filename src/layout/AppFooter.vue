<template>
  <footer class="footer">
    <div class="container pt-2" id="contact">
      <div class="row row-grid mt-1">
        <div class="col-lg-4">
          <h5 class="mt-3">Liên hệ</h5>
          <ul class="pl-0">
            <li class="list-group-item border-0 bg-trans p-1">
              Công ty cổ phần vật tư thiết bị Lotus
            </li>
            <li class="list-group-item border-0 bg-trans p-1">
              <i class="ni ni-mobile-button mr-2"></i>
              <a href="tel:0903455202"> 0903455202 </a>
            </li>
            <li class="list-group-item border-0 bg-trans p-1">
              <i class="ni ni-planet mr-2"></i>
              <a href="#"> lotuscompany.com.vn </a>
            </li>
            <li class="list-group-item border-0 bg-trans p-1">
              <i class="ni ni-email-83 mr-2"></i>
              <a href="mailto:contact@lotusco.com.vn">
                contact@lotusco.com.vn
              </a>
            </li>
          </ul>
        </div>
        <div class="col-lg-4 mt-0">
          <h5 class="mt-3">Địa chỉ</h5>
          <p class="mt-3">
            <i class="ni ni-square-pin mr-1"></i>
            Phòng 601, tầng 6, SKY CITY TOWER A, 88 Láng Hạ, Quận Đống Đa, Hà
            Nội
          </p>
        </div>
        <div class="col-lg-4 mt-0">
          <h5 class="mt-3">Theo dõi hoạt động của chúng tôi</h5>
          <p class="mt-3">
            Phương châm xây dựng một đội ngũ cán bộ, nhân viên có tính chuyên
            nghiệp cao, coi đó là tiền đề để tạo nên sức mạnh trong kinh doanh
            và thúc đẩy công ty phát triển một cách vững chắc.
          </p>
          <div class="mt-3">
            <base-button
              tag="a"
              href="#"
              type="warning"
              icon="fa fa-twitter"
              rounded
              icon-only
            ></base-button>
            <base-button
              tag="a"
              href="#"
              type="warning"
              icon="fa fa-facebook"
              rounded
              icon-only
            ></base-button>
            <base-button
              tag="a"
              href="#"
              type="warning"
              icon="fa fa-linkedin"
              rounded
              icon-only
            ></base-button>
          </div>
        </div>
      </div>
    </div>
    <div class="container">
      <hr />
      <div class="row align-items-center justify-content-md-between">
        <div class="col-md-6">
          <div class="copyright">
            &copy; {{ year }}
            <a
              href="https://www.creative-tim.com"
              target="_blank"
              rel="noopener"
              >Lotus company</a
            >
          </div>
        </div>
        <div class="col-md-6">
          <ul class="nav nav-footer justify-content-end">
            <li class="nav-item">
              <a
                href="#"
                class="nav-link"
                target="_blank"
                rel="noopener"
                >Trang chủ</a
              >
            </li>
            <li class="nav-item">
              <a
                href="#about"
                class="nav-link"
                target="_blank"
                rel="noopener"
                >Giới thiệu</a
              >
            </li>
            <li class="nav-item">
              <a
                href="#solution"
                class="nav-link"
                target="_blank"
                rel="noopener"
                >Giải pháp</a
              >
            </li>
            <li class="nav-item">
              <a
                href="#contact"
                class="nav-link"
                target="_blank"
                rel="noopener"
                >Liên hệ</a
              >
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  name: "app-footer",
  data() {
    return {
      year: new Date().getFullYear(),
    };
  },
};
</script>
<style lang="scss" scoped>
.bg-trans {
  background-color: transparent !important;
}
</style>
