<template>
  <main>
    <div class="a-spacing-large"> </div>
      <div class="container-fluid browsing-history">
        <div class="row">
          <div class="col-sm-8 col-8">
            <h1 class="a-size-large a-spacing-none a-text-normal">All products</h1>
            <div class="a-spacing-large"> </div>
            <!-- Button -->
            <nuxt-link  class="a-button-buy-again" to="/product">Add a New product</nuxt-link>
            <a href="" class="a-button-history margin-right-10">Add a category</a>
            <a href="" class="a-button-history margin-right-10">Add a owner</a>
          </div>
        </div>
      </div>
      <div class="a-spacing-large"> </div>
      <!-- Listing Page -->
      <div class="container-fluid browsing-history">
        <div class="col-xl-2 col-lg-2 col-md-3 col-sm-6 col-6 br bb">
        <div class="row">
          <div class="history-box">
             <a href="#" class="a-link-normal">
               <img src="#" class="img-fluid" />
             </a>
             <!-- product title -->
             <div class="a-spacing-top-base asin-title">
               <span class="a-text-normal">
                 <div class="p13n-sc-truncated">Product Title</div>
               </span>
             </div>
              <!-- product star -->
             <div class="a-row">
               <a href="#">
                 <i class="fas fa-star"></i>
                 <i class="fas fa-star"></i>
                 <i class="fas fa-star"></i>
                 <i class="fas fa-star"></i>
                 <i class="fas fa-star"></i>
               </a>
               <span class="a-letter-space "></span>
               <span class="a-color-tertiary a-size-small asin-reviews">5</span>
             </div>
              <!-- product price -->
             <div class="a-row">
               <span class="a-size-base a-color-price">
                 <span class="p13n-sc-price">$34</span>
               </span>
             </div>
             <!-- product button -->
             <div class="a-row">
               <a href="#" class="a-button-history margin-right-10">Update</a>
               <a href="#" class="a-button-history margin-right-10">Delete</a>
             </div>
            </div>
          </div>
        </div>
      </div>
    



   
  </main>
</template>

<script>
  export default {
    layout:"none"
  }
</script>


<style>

</style>