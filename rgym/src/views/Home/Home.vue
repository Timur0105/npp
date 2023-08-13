<template>
  <div :class="styles.home">
    <div :class="styles.home_navbar">
      <div :class="styles.home_navbar_time">
        <img :class="styles.home_navbar_time_logo" src="@/assets/images/rgym.png" />
        <img
          src="@/assets/images/group.png"
          alt="Group"
          :class="styles.home_navbar_time_watch"
        />
      </div>
      <ul :class="styles.home_navbar_list">
        <li :class="styles.home_navbar_list_item">Training</li>
        <li :class="styles.home_navbar_list_item">Studio Classes</li>
        <li :class="styles.home_navbar_list_item">Lifestyle</li>
        <button type="button" :class="styles.home_navbar_list_item">Contact</button>
      </ul>
    </div>
    <div :class="styles.home_start">
      <p :class="styles.home_start_text">Making Different from other builders.</p>
      <div :class="styles.home_start_gr">
        <button :class="styles.home_start_btn">Get Started</button>
        <img
          src="@/assets/images/vector.png"
          alt="Vector"
          :class="styles.home_start_vector"
        />
      </div>
    </div>
    <div :class="styles.home_popular">
      <h1 :class="styles.home_popular_title">Popular Exercise</h1>
      <p :class="styles.home_popular_subtitle">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam dui neque sa
        gittis magna erat sagittis morbi. Id libero. Lorem ipsum dolor sit amet,
        consectetur adipiscing elit.
      </p>
      <img
        src="@/assets/images/vector01.png"
        alt="Vector01"
        :class="styles.home_popular_img"
      />
      <ul :class="styles.home_popular_worklist">
        <li :class="styles.home_popular_worklist_item">
          <img src="@/assets/images/workout1.png" alt="Workout1" />
        </li>
        <li :class="styles.home_popular_worklist_item">
          <img src="@/assets/images/workout2.png" alt="Workout2" />
        </li>
        <li :class="styles.home_popular_worklist_item">
          <img src="@/assets/images/workout3.png" alt="Workout3" />
        </li>
        <li :class="styles.home_popular_worklist_item">
          <img src="@/assets/images/workout4.png" alt="Workout4" />
        </li>
        <li :class="styles.home_popular_worklist_item">
          <img src="@/assets/images/workout5.png" alt="Workout5" />
        </li>
      </ul>
      <div :class="styles.home_popular_plan">
        <div :class="styles.home_popular_plan_text1">
          <p :class="styles.home_popular_plan_text">
            The ultimate online personal training plans
          </p>
        </div>
        <div :class="styles.home_popular_plan_sidetext">
          <section :class="styles.home_popular_plan_sidetext_line"></section>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam dui neque sa
          gittis magna erat sagittis morbi. Id libero. Lorem ipsum dolor sit amet,
          consectetur adipiscing elit. Aliquam dui neque sa gittis magna erat sagittis
          morbi. Id libero.
        </div>
      </div>
    </div>
    <div :class="styles.home_training">
      <div :class="styles.home_training_intro">
        <img
          src="@/assets/images/train01.png"
          alt="Training"
          :class="styles.home_training_intro_img"
        />
        <div :class="styles.home_training_intro_text">
          <p :class="styles.home_training_intro_text_title">Personal Training</p>
          <p :class="styles.home_training_intro_text_subtitle">Gym time optimized</p>
          <p :class="styles.home_training_intro_text_subtext">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam dui neque sa
            gittis magna erat sagittis morbi. Id libero. Lorem ipsum dolor sit amet,
            consectetur adipiscing elit. Aliquam dui neque sa gittis magna erat sagittis
            morbi. Id libero.
          </p>
        </div>
      </div>
      <div :class="styles.home_training_fullimages">
        <img
          src="@/assets/images/train02.png"
          alt="Training02"
          :class="styles.home_training_fullimages_n2"
        />
        <img
          src="@/assets/images/train03.png"
          alt="Training03"
          :class="styles.home_training_fullimages_n3"
        />
        <img
          src="@/assets/images/train04.png"
          alt="Training04"
          :class="styles.home_training_fullimages_n4"
        />
        <img
          src="@/assets/images/train05.png"
          alt="Training05"
          :class="styles.home_training_fullimages_n5"
        />
        <img
          src="@/assets/images/train06.png"
          alt="Training06"
          :class="styles.home_training_fullimages_n6"
        />
        <div :class="styles.home_training_fullimages_textbox">
          <img
            src="@/assets/images/welcome.png"
            alt="Welcom"
            :class="styles.home_training_fullimages_textbox_title"
          />
          <p :class="styles.home_training_fullimages_textbox_text">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam dui neque sa
            gittis magna erat sagittis morbi. Id libero.
          </p>
        </div>
      </div>
      <img
        src="@/assets/images/backpic.png"
        alt="BackPic"
        :class="styles.home_training_login_img"
      />
      <div :class="styles.home_training_login">
        <p :class="styles.home_training_login_title">Subscribe to our newsletter</p>
        <p :class="styles.home_training_login_subtitle">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam dui neque.
        </p>
        <button :class="styles.home_training_login_email" type="button">
          Enter Email
        </button>
        <button :class="styles.home_training_login_submit" type="button">Submit</button>
      </div>
    </div>
    <div :class="styles.home_footer">
      <div :class="styles.home_footer_group">
        <div :class="styles.home_footer_group_items">
          <img src="@/assets/images/rgym.png" alt="RGym" :class="styles.home_footer_group_items_img">
          <p :class="styles.home_footer_group_items_subtext">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam 
          </p>
        </div>
        <div :class="styles.home_footer_group_items">
          <p :class="styles.home_footer_group_items_title">
            Information
          </p>
          <ul :class="styles.home_footer_group_items_list">
            <li :class="styles.home_footer_group_items_list_items">About us</li>
            <li :class="styles.home_footer_group_items_list_items">Lifestyle</li>
            <li :class="styles.home_footer_group_items_list_items">Fitness</li>
            <li :class="styles.home_footer_group_items_list_items">Pricing</li>
          </ul>
        </div>
        <div :class="styles.home_footer_group_items">
          <p :class="styles.home_footer_group_items_title">
            More Links
          </p>
          <ul :class="styles.home_footer_group_items_list">
            <li :class="styles.home_footer_group_items_list_items">Gallery</li>
            <li :class="styles.home_footer_group_items_list_items">ClubLocation</li>
            <li :class="styles.home_footer_group_items_list_items">Behind the scence</li>
            <li :class="styles.home_footer_group_items_list_items">Contact</li>
          </ul>
        </div>
        <div :class="styles.home_footer_group_items">
          <p :class="styles.home_footer_group_items_title">
            Follow Us On!
          </p>
          <div :class="styles.home_footer_group_items_limg">
            <img src="@/assets/images/face.png" alt="Facebook" :class="styles.home_footer_group_items_limg_img">
            <img src="@/assets/images/twitter.png" alt="Twitter" :class="styles.home_footer_group_items_limg_img">
            <img src="@/assets/images/insta.png" alt="Instagram" :class="styles.home_footer_group_items_limg_img">
          </div>
        </div>
      </div>
      <p :class="styles.home_footer_copyright">
        This is copyright => Timur Joldasbayev timurjoldasbaev02@gmail.com
      </p>
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
