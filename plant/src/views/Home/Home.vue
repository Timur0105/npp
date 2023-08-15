<template>
  <div :class="styles.home">
    <div :class="styles.home_nav">
      <p :class="styles.home_nav_logo">Plant</p>
      <ul :class="styles.home_nav_navbar">
        <li :class="styles.home_nav_navbar_items">Home</li>
        <li :class="styles.home_nav_navbar_items">Services</li>
        <li :class="styles.home_nav_navbar_items">About Us</li>
        <li :class="styles.home_nav_navbar_items">Blog</li>
        <li :class="styles.home_nav_navbar_items">Contact</li>
      </ul>
      <div :class="styles.home_nav_btns">
        <button style="button" :class="styles.home_nav_log">Login</button>
        <button style="button" :class="styles.home_nav_btn">Sign Up</button>
      </div>
    </div>
    <div :class="styles.home_main">
      <div :class="styles.home_main_homeplant">
        <div :class="styles.home_main_homeplant_context">
          <p :class="styles.home_main_homeplant_context_title">
            Growing Beautiful Plants at Home
          </p>
          <p :class="styles.home_main_homeplant_context_subtitle">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Eu, tempor, accumsan
            sit amet nunc cursus. Nec tristique at in erat lectus mas sa diam. Lectus
            elit, nulla elementum fringilla at.
          </p>
          <button style="button" :class="styles.home_main_homeplant_context_btn">
            Learn More
          </button>
          <ul :class="styles.home_main_homeplant_context_rate">
            <li :class="styles.home_main_homeplant_context_rate_items">
              <p :class="styles.home_main_homeplant_context_rate_items_num">2000+</p>
              <p :class="styles.home_main_homeplant_context_rate_items_text">Delivery</p>
            </li>
            <li :class="styles.home_main_homeplant_context_rate_items">
              <p :class="styles.home_main_homeplant_context_rate_items_num">1200+</p>
              <p :class="styles.home_main_homeplant_context_rate_items_text">Customers</p>
            </li>
            <li :class="styles.home_main_homeplant_context_rate_items">
              <p :class="styles.home_main_homeplant_context_rate_items_num">1000+</p>
              <p :class="styles.home_main_homeplant_context_rate_items_text">Product</p>
            </li>
          </ul>
        </div>
        <div :class="styles.home_main_homeplant_images">
          <img
            src="@/assets/images/cactus.png"
            alt="Cactus"
            :class="styles.home_main_homeplant_images_cactus"
          />
          <img
            src="@/assets/images/item1.png"
            alt="Item1"
            :class="styles.home_main_homeplant_images_item1"
          />
          <img
            src="@/assets/images/item2.png"
            alt="Item2"
            :class="styles.home_main_homeplant_images_item2"
          />
          <img
            src="@/assets/images/item3.png"
            alt="Item3"
            :class="styles.home_main_homeplant_images_item3"
          />
          <img
            src="@/assets/images/leaf.png"
            alt="Leaf"
            :class="styles.home_main_homeplant_images_leaf"
          />
        </div>
      </div>
      <div :class="styles.home_main_plants">
        <div :class="styles.home_main_plants_context">
          <p :class="styles.home_main_plants_context_title">
            We have lots of plants collection for you and your family
          </p>
          <img
            src="@/assets/images/frame.png"
            alt="Frame"
            :class="styles.home_main_plants_context_frame"
          />
        </div>
        <div :class="styles.home_main_plants_images">
          <img
            src="@/assets/images/plant1.png"
            alt="Plant1"
            :class="styles.home_main_plants_images_plant1"
          />
          <img
            src="@/assets/images/plant2.png"
            alt="Plant2"
            :class="styles.home_main_plants_images_plant1"
          />
          <img
            src="@/assets/images/plant3.png"
            alt="Plant3"
            :class="styles.home_main_plants_images_plant1"
          />
        </div>
      </div>
      <div :class="styles.home_main_banzay">
        <img
          src="@/assets/images/banzay.png"
          alt="Banzay"
          :class="styles.home_main_banzay_img"
        />
        <div :class="styles.home_main_banzay_context">
          <p :class="styles.home_main_banzay_context_title">About Us</p>
          <p :class="styles.home_main_banzay_context_subtitle">
            Continue to Develop to Became Global Company
          </p>
          <p :class="styles.home_main_banzay_context_text">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Eu, tempor, accumsan
            sit amet nunc cursus. Nec tristique at in erat lectus mas sa diam. Lectus
            elit, nulla elementum fringilla at. Lorem ipsum dolor sit amet, consectetur
            adipiscing elit. Eu, tempor, accumsan sit amet nunc cursus. Nec tristique at
            in erat lectus mas sa diam. Lectus elit, nulla elementum fringilla at.
          </p>
          <p :class="styles.home_main_banzay_context_subtext">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Eu, tempor, accumsan
            sit amet nunc cursus.
          </p>
          <button :class="styles.home_main_banzay_context_btn">Read More</button>
        </div>
      </div>
      <div :class="styles.home_main_best">
        <p :class="styles.home_main_best_title">Our Best Product</p>
        <ul :class="styles.home_main_best_list">
          <li :class="styles.home_main_best_list_item">New Plants</li>
          <li :class="styles.home_main_best_list_item">New Arrivalls</li>
          <li :class="styles.home_main_best_list_item">Sale</li>
        </ul>
        <ul :class="styles.home_main_best_group">
          <li :class="styles.home_main_best_group_item">
            <img
              src="@/assets/images/best1.png"
              alt="best1"
              :class="styles.home_main_best_group_item_img"
            />
            <p :class="styles.home_main_best_group_item_title">Outdoor Plant</p>
            <img
              src="@/assets/images/stars.png"
              alt="Stars"
              :class="styles.home_main_best_group_item_star"
            />
            <p :class="styles.home_main_best_group_item_price">$50.00</p>
          </li>
          <li :class="styles.home_main_best_group_item">
            <img
              src="@/assets/images/best2.png"
              alt="best2"
              :class="styles.home_main_best_group_item_img"
            />
            <p :class="styles.home_main_best_group_item_title">Monstera Plant</p>
            <img
              src="@/assets/images/stars.png"
              alt="Stars"
              :class="styles.home_main_best_group_item_star"
            />
            <p :class="styles.home_main_best_group_item_price">$50.00</p>
          </li>
          <li :class="styles.home_main_best_group_item">
            <img
              src="@/assets/images/best3.png"
              alt="best3"
              :class="styles.home_main_best_group_item_img"
            />
            <p :class="styles.home_main_best_group_item_title">Pottel Plant</p>
            <img
              src="@/assets/images/stars.png"
              alt="Stars"
              :class="styles.home_main_best_group_item_star"
            />
            <p :class="styles.home_main_best_group_item_price">$50.00</p>
          </li>
          <li :class="styles.home_main_best_group_item">
            <img
              src="@/assets/images/best4.png"
              alt="best4"
              :class="styles.home_main_best_group_item_img"
            />
            <p :class="styles.home_main_best_group_item_title">Indoor Plant</p>
            <img
              src="@/assets/images/stars.png"
              alt="Stars"
              :class="styles.home_main_best_group_item_star"
            />
            <p :class="styles.home_main_best_group_item_price">$50.00</p>
          </li>
        </ul>
        <button :class="styles.home_main_best_btn" :style="button">View All</button>
      </div>
      <div :class="styles.home_main_opinion">
        <img
          src="@/assets/images/group.png"
          alt="group"
          :class="styles.home_main_opinion_img"
        />
      </div>
      <div :class="styles.home_main_subscribe">
        <div :class="styles.home_main_subscribe_context">
          <p :class="styles.home_main_subscribe_context_title">
            Subscribe Our Newsletter
          </p>
          <p :class="styles.home_main_subscribe_context_subtitle">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Eu, at tempor,
            accumsan sit amet nunc cursus.
          </p>
          <div :class="styles.home_main_subscribe_context_in">
            <input
              type="text"
              :class="styles.home_main_subscribe_context_in_input"
              placeholder="Enter mail...."
            />
            <button :class="styles.home_main_subscribe_context_in_btn" type="button">
              Subscribe
            </button>
          </div>
        </div>
        <div :class="styles.home_main_subscribe_image">
          <img
            src="@/assets/images/noname.png"
            alt="Noname"
            :class="styles.home_main_subscribe_image_img"
          />
        </div>
      </div>
      <div :class="styles.home_main_focus">
        <p :class="styles.home_main_focus_title">Follow Us on Instagram</p>
        <p :class="styles.home_main_focus_subtitle">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Eu, tempor, accu msan
          sit amet nunc cursus. Nec tristique at in erat lectus
        </p>
        <div :class="styles.home_main_focus_imgroup">
          <img src="@/assets/images/list.png" alt="ListImages" :class="styles.home_main_focus_imgroup_img">
        </div>
      </div>
    </div>
    <div :class="styles.home_footer">
      <img src="@/assets/images/footer.png" alt="footer" :class="styles.home_footer_img">
    </div>
  </div>
</template>

<script>
import styles from "./Home.modules.scss";
export default {
  name: "Home",
  data() {
    return {
      styles,
    };
  },
};
</script>
