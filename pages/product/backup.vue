<template>
  <main>
    <div class="container-fluid">
      <div class="row">
        <div class="col-sm-3"></div>
        <div class="col-sm-6">
          <div class="a-section">
            <div class="a-spacing-top-medium"></div>
            <h2 style="text-align:center">Add a New Product</h2>

            <form action="">
              <!-- Category -->
              <div class="a-spacing-top-medium">
                <label for="">category</label>
                <select class="a-select-option">
                  <option value="mobile phone">mobile phone</option>
                  <option value="television">television</option>
                  <option value="refrigerator">refrigerator</option>
                </select>
              </div>
              <!-- owner -->
              <div class="a-spacing-top-medium">
                <label for="">owner</label>
                <select class="a-select-option">
                  <option value="sanju">sanju</option>
                  <option value="jishnu">jishnu</option>
                </select>
              </div>
              <!-- Title -->
              <div class="a-spacing-top-medium">
                <label  for="">Title</label>
                <input type="text" class="a-input-text" style="width:100%"> 
              </div>
              <!-- price -->
              <div class="a-spacing-top-medium">
                <label  for="">Price</label>
                <input type="number" class="a-input-text" style="width:100%"> 
              </div>

              <!-- Description -->
              <div class="a-spacing-top-medium">
                <label  for="">Description</label>
                 <textarea placeholder="provide details the product description" 
                 style="width: 100%"></textarea>
              </div>

              <!-- Photo -->
              <div class="a-spacing-top-medium">
                <label  for="">Add Photo</label>
                 <div class="a-row a-spacing-top-medium">
                   <label class="choosefile-button">
                     <i class="fal fa-plus"></i>
                     <input type="file">
                     <p style="margin-top :-70px"></p>
                   </label>
                 </div>
              </div>
              <hr>
              <div class="a-spacing-top-large">
                <span class="a-button-register">
                  <span class="a-button-inner">
                    <span class="a-button-text">Add Product</span>
                  </span>
                </span>
              </div> 
            </form>
          </div>

        </div>
        <div class="col-sm-3"></div>
      </div>
    </div>
  </main>
</template>


<script>
  export default {
  //  data () {
  //   return {
  //               category:"",
  //               owner:"",
  //               title:"",
  //               price:"",
  //               description:"",
  //               fileName:"",
  //               selectedFile:""
  //           }
  //  },
  //  methods: {
  //   onFileSelected(event){
  //     alert("file section")
  //     this.selectedFile=event.target.files[0]
  //     console.log(this.selectedFile)
  //     this.fileName=event.target.files[0].name
  //   },
  //   submit(){
  //     alert("hi")
  //   }
  // },
  layout: 'special',
}