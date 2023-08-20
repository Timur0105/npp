<template>
  <div :class="styles.home">
    <div :class="styles.home_nav">
      <img src="@/assets/images/logo.png" alt="Logo" :class="styles.home_nav_img" />
      <ul :class="styles.home_nav_navbar">
        <li :class="styles.home_nav_navbar_item">
          <img
            src="@/assets/images/search.png"
            alt="Search"
            :class="styles.home_nav_navbar_item_img"
          />
        </li>
        <li :class="styles.home_nav_navbar_item">
          <img
            src="@/assets/images/cart.png"
            alt="Cart"
            :class="styles.home_nav_navbar_item_img"
          />
        </li>
        <li :class="styles.home_nav_navbar_item">
          <button :class="styles.home_nav_navbar_item_btn">Sign up</button>
        </li>
        <li :class="styles.home_nav_navbar_item">
          <button :class="styles.home_nav_navbar_item_btn1">Sign in</button>
        </li>
      </ul>
    </div>
    <div :class="styles.home_main">
      <div :class="styles.home_main_1">
        <div :class="styles.home_main_first">
          <img
            src="@/assets/images/plantbig.png"
            alt="PlantBig"
            :class="styles.home_main_first_img"
          />
          <div :class="styles.home_main_first_context">
            <p :class="styles.home_main_first_context_title">Kembang Flower Mantap</p>
            <p :class="styles.home_main_first_context_subtitle">
              Lorem Ipsum is simply dummy text of the printing and typesetting industry.
              Lorem Ipsum has been the industry's standard dummy text ever since the
              1500s,
            </p>
            <ul :class="styles.home_main_first_context_type">
              <li :class="styles.home_main_first_context_type_item">
                <img
                  src="@/assets/images/plant1.png"
                  alt=""
                  :class="styles.home_main_first_context_type_item_img"
                />
              </li>
              <li :class="styles.home_main_first_context_type_item">
                <img
                  src="@/assets/images/plant2.png"
                  alt=""
                  :class="styles.home_main_first_context_type_item_img"
                />
              </li>
            </ul>
          </div>
        </div>
      </div>
      <ul :class="styles.home_main_group">
        <li :class="styles.home_main_group_item">
          <img
            src="@/assets/images/group.png"
            alt="Group"
            :class="styles.home_main_group_item_img"
          />
          <p :class="styles.home_main_group_item_text">
            Lorem Ipsum is simply dummy text of the printing and typesetting industry.
            Lorem Ipsum has been the industry's standard
          </p>
        </li>
        <li :class="styles.home_main_group_item">
          <img
            src="@/assets/images/group2.png"
            alt="Group"
            :class="styles.home_main_group_item_img"
          />
          <p :class="styles.home_main_group_item_text">
            Lorem Ipsum is simply dummy text of the printing and typesetting industry.
            Lorem Ipsum has been the industry's standard
          </p>
        </li>
        <li :class="styles.home_main_group_item">
          <img
            src="@/assets/images/group3.png"
            alt="Group"
            :class="styles.home_main_group_item_img"
          />
          <p :class="styles.home_main_group_item_text">
            Lorem Ipsum is simply dummy text of the printing and typesetting industry.
            Lorem Ipsum has been the industry's standard
          </p>
        </li>
        <li :class="styles.home_main_group_item">
          <img
            src="@/assets/images/group4.png"
            alt="Group"
            :class="styles.home_main_group_item_img"
          />
          <p :class="styles.home_main_group_item_text">
            Lorem Ipsum is simply dummy text of the printing and typesetting industry.
            Lorem Ipsum has been the industry's standard
          </p>
        </li>
      </ul>
      <div :class="styles.home_main_featured">
        <p :class="styles.home_main_featured_title">Featured Plants</p>
        <ul :class="styles.home_main_featured_group">
          <li :class="styles.home_main_featured_group_item">
            <img
              src="@/assets/images/cactus.png"
              alt="Cactus"
              :class="styles.home_main_featured_group_item_img"
            />
            <p :class="styles.home_main_featured_group_item_title">Kaktus Plants</p>
            <p :class="styles.home_main_featured_group_item_price">IDR 85.000</p>
          </li>
          <li :class="styles.home_main_featured_group_item">
            <img
              src="@/assets/images/cactus1.png"
              alt="Cactus1"
              :class="styles.home_main_featured_group_item_img"
            />
            <p :class="styles.home_main_featured_group_item_title">Landak Plants</p>
            <p :class="styles.home_main_featured_group_item_price">IDR 105.000</p>
          </li>
          <li :class="styles.home_main_featured_group_item">
            <img
              src="@/assets/images/cactus2.png"
              alt="Cactus2"
              :class="styles.home_main_featured_group_item_img"
            />
            <p :class="styles.home_main_featured_group_item_title">Kecubung Plants</p>
            <p :class="styles.home_main_featured_group_item_price">IDR 85.000</p>
          </li>
          <li :class="styles.home_main_featured_group_item">
            <img
              src="@/assets/images/cactus3.png"
              alt="Cactus3"
              :class="styles.home_main_featured_group_item_img"
            />
            <p :class="styles.home_main_featured_group_item_title">Kecubung Plants</p>
            <p :class="styles.home_main_featured_group_item_price">IDR 85.000</p>
          </li>
          <li :class="styles.home_main_featured_group_item">
            <img
              src="@/assets/images/cactus4.png"
              alt="Cactus4"
              :class="styles.home_main_featured_group_item_img"
            />
            <p :class="styles.home_main_featured_group_item_title">Kecubing Plants</p>
            <p :class="styles.home_main_featured_group_item_price">IDR 85.000</p>
          </li>
        </ul>
      </div>
      <div :class="styles.home_main_help">
        <div :class="styles.home_main_help_context">
          <p :class="styles.home_main_help_context_title">
            Buy more plants, it helps you to be relaxed
          </p>
          <p :class="styles.home_main_help_context_text">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi gravida gravida
            aliquam. Pellentesque et lobortis nisl. Sed et mauris justo. Nulla eu enim non
            mauris maximus dignissim. Maecenas vitae eros sapien. Quisque pellentesque
            tempus dignissim.
          </p>
          <img
            src="@/assets/images/smallpic.png"
            alt="SmallPic"
            :class="styles.home_main_help_context_img"
          />
        </div>
        <div :class="styles.home_main_help_img">
          <img src="@/assets/images/bigpic.png" alt="BigPic" />
        </div>
      </div>
      <div :class="styles.home_main_favourite">
        <div :class="styles.home_main_favourite_context">
          <p :class="styles.home_main_favourite_context_title">
            Get your favourites plant on our shop now
          </p>
          <button :class="styles.home_main_favourite_context_btn" type="button">
            Visit Shop
          </button>
        </div>
        <img
          src="@/assets/images/lastpic.png"
          alt="LastPic"
          :class="styles.home_main_favourite_img"
        />
      </div>
    </div>
    <div :class="styles.home_footer">
      <ul :class="styles.home_footer_group">
        <li :class="styles.home_footer_group_item">
          <p :class="styles.home_footer_group_item_bigtitle">PLANTKU</p>
          <p :class="styles.home_footer_group_item_title">Plantku House</p>
          <p :class="styles.home_footer_group_item_subtitle1">
            Jl. Laksda Adisucipto No.51, Demangan, Kec. Depok, Kota Yogyakarta, Daerah
            Istimewa Yogyakarta 55282
          </p>
        </li>
        <li :class="styles.home_footer_group_item">
          <p :class="styles.home_footer_group_item_title">Perusahaan</p>
          <p :class="styles.home_footer_group_item_subtitle">Tentang Kami</p>
          <p :class="styles.home_footer_group_item_subtitle">Hubungi Kami</p>
        </li>
        <li :class="styles.home_footer_group_item">
          <p :class="styles.home_footer_group_item_title">Produk</p>
          <p :class="styles.home_footer_group_item_subtitle">Tanaman</p>
          <p :class="styles.home_footer_group_item_subtitle">Tanaman Lain</p>
        </li>
        <li :class="styles.home_footer_group_item">
          <p :class="styles.home_footer_group_item_title">Berlangganan Email Kami</p>
          <input type="text" :class="styles.home_footer_group_item_input" placeholder="Masukan Alamat Email">
          <button :class="styles.home_footer_group_item_btn">Submit</button>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
import styles from "./Home.module.scss";
export default {
  name: "Home",
  data() {
    return {
      styles,
    };
  },
};
</script>
