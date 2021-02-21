<template>
  <div>
    <div class="md-layout">
      <div class="md-layout-item md-size-50 mx-auto text-center">
        <h2 class="title">Pick the best plan for you</h2>
        <h5 class="description">All subcriptions are monthly</h5>
      </div>
    </div>
    <div class="md-layout">
      <div class="md-layout-item md-medium-size-25 md-small-size-50 md-xsmall-size-100 md-size-25">
        <pricing-card card-class="md-card-plain" icon-color="icon-white">
          <h6 slot="category" class="category">Bronze</h6>
          <md-icon slot="icon">weekend</md-icon>
          <h3 slot="title" class="title">Free</h3>
          <div slot="description" class="card-description">
            <ul>
              <li>MySql Adapter</li>
              <li>Chat Support</li>
              <li>We'll be your friends</li>
            </ul>
          </div>
          <md-button slot="footer" class="md-white md-round">Choose Plan</md-button>
        </pricing-card>
      </div>
      <div class="md-layout-item md-medium-size-25 md-small-size-50 md-xsmall-size-100 md-size-25">
        <pricing-card icon-color="icon-success">
          <h6 slot="category" class="category">Silver</h6>
          <md-icon slot="icon">home</md-icon>
          <h3 slot="title" class="title">29$</h3>
          <div slot="description" class="card-description">
            <ul>
              <li>MySql Adapter</li>
              <li>Snowflake Adapter</li>
              <li>Chat Support</li>
            </ul>
          </div>
          <md-button slot="footer" class="md-success md-round">Choose Plan</md-button>
        </pricing-card>
      </div>
      <div class="md-layout-item md-medium-size-25 md-small-size-50 md-xsmall-size-100 md-size-25">
        <pricing-card card-class="md-card-plain" icon-color="icon-white">
          <h6 slot="category" class="category">Gold</h6>
          <md-icon slot="icon">business</md-icon>
          <h3 slot="title" class="title">69$</h3>
          <div slot="description" class="card-description">
            <ul>
              <li>All Adapters</li>
              <li>Single Sign On</li>
              <li>Chat Support</li>
            </ul>
          </div>
          <md-button slot="footer" class="md-white md-round">Choose Plan</md-button>
        </pricing-card>
      </div>
      <div class="md-layout-item md-medium-size-25 md-small-size-50 md-xsmall-size-100 md-size-25">
        <pricing-card card-class="md-card-plain" icon-color="icon-white">
          <h6 slot="category" class="category">Enterprise</h6>
          <md-icon slot="icon">account_balance</md-icon>
          <h3 slot="title" class="title">159$</h3>
          <p
            slot="description"
            class="card-description"
          >This plan provides all features and 24/7 Support.</p>
          <md-button slot="footer" class="md-white md-round">Choose Plan</md-button>
        </pricing-card>
      </div>
    </div>
  </div>
</template>
<script>
import { PricingCard } from "@/components";
export default {
  components: {
    PricingCard
  }
};
</script>
<style scoped>
.text-center {
  text-align: center;
}
</style>
