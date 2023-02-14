<script>
import { onMounted } from '@vue/runtime-core'
export default {
  setup() {
    onMounted(() => {
      
    })
  },
}
</script>
<template>
  <section class="py-2 hero text-light">
    <div class="row justify-content-center">
      <h1 class="text-center"
        ><strong>MONO </strong>
        <span class="thumb-navbar"><strong>CHROME</strong></span></h1
      >
      <div class="col-md-8 col-lg-6 col-12">
        <h1 class="text-center web-title color-2">
         Mencerdaskan Kehidupan Bangsa
        </h1>
        <p class="text-center text-tiga">Cerdik, Cerdas, Cekatan</p>
        <p class="text-center  sub-title"><strong>Monochrome</strong>
          merupakan badan usaha yang bergerak dibidang pengadaan barang dan jasa,
          yang telah dirintis sejak 2020 dan dikembangkan oleh 10 mahasiswa dari elemen yang berbeda. dengan berbagai
          jasa seperti :
        </p>
        <div class="text-center">
          <span class="ms-3 badge bg-success">Programing</span>
          <span class="ms-3 badge bg-danger">Karya Tulis Ilmiah</span>
          <span class="ms-3 badge bg-warning">IT Support</span>
          <span class="ms-3 badge bg-dark">Design</span>
          <span class="ms-3 badge bg-primary">Pendidikan</span>
        </div>
      </div>
    </div>
  </section>
  <section class="work text-center">
    <div class="bg-dark">
        <div class="card border-0 bg-transparent">
          <div class="card-body">
            <div class="row d-flex justify-content-center">
              <div class="col-md-2 col-lg-2 col-sm-2 col-4">
                <img src="https://cdn-icons-png.flaticon.com/512/1605/1605350.png" width="70" alt="" srcset="">
                <h4 class="text-light mt-3"><strong>120</strong> Client</h4>
              </div>
              <div class="col-md-2 col-lg-2 col-sm-2 col-4">
                <img src="https://cdn-icons-png.flaticon.com/512/5455/5455723.png" width="70" alt="" srcset="">
                <h4 class="text-light mt-3"><strong>2</strong> Mitra</h4>
              </div>
            </div>
          </div>
        </div>
    </div>
  </section>
</template>
<style scoped>
  section{
    margin-top: 60px;
  }
  .text-tiga{
    font-size:30px;
  }
</style>

