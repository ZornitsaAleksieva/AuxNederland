<template>
<!-- eslint-disable max-len -->
<div class="container content">

  <img src='../assets/Logo1.png' class= "logo" alt='Logo1'>

  <div class="text">
  <p> Aux Nederland supports digital product companies with wisdom, competence, partnership and in-kind investments</p>

<div class="buttons">
  <a href="https://auxcode.com/" class="btn btn-primary" role="button" aria-pressed="true">To AuxCode.com <h2 class="arrow">↗</h2></a>
  <button type="button" class="btn btn-primary">Read more<h2 class="arrow">↗</h2></button>
</div>

  </div>
</div>

<img src="../assets/WindmillCrop.png" class="img-fluid myimage" alt="WindmillCrop">

<div class="container footer">

  <div class="contacts">
  <h6>Contacts</h6>
  <h6>T.E.Shaw</h6>
  <h6>t.e.shaw@auxnederlandbv.nl</h6>
  <h6>+ 31 970 1028 0106</h6>
  </div>

  <div class="other">
  <h6>© Aux Nederland B.V.</h6>
  <h6>Keizersgracht 241-2, 1016 EA Amsterdam, Netherlands</h6>
  <a class="link" href="#">Privacy policy</a>
  </div>

</div>

</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';

@Options({
  props: {
    msg: String,
  },
})
export default class HelloWorld extends Vue {
  msg!: string
}
</script>

<style scoped>

.logo {
  display: flex;
  width: 22rem;
  height: 3.5rem;
  margin-top: 2rem;
  margin-left: 2rem;
}

.content {
  display: flex;
  margin-top: 2rem;
  background: rgb(243,221,225);
  background: linear-gradient(0deg, rgba(243,221,225,1) 30%, rgba(242,242,242,1) 100%);
  border-radius: 20px;
  height: 40rem;
}

.text {
margin-top: 24rem;
margin-left: -20rem;
font-size: 23px;
text-align: left;
width: 41rem;
font-weight: 600;
}

.btn {
  display: flex;
  flex-direction: row;
  color:#2B2B2B;
  width: 16rem;
  height: 3.4rem;
  border-color: #DB3733;
  border-width: 3px;
  background-color: transparent;
  border-radius: 80px;
  margin-top: 1rem;
  margin-left: 10px;
  font-size: 19px;
  justify-content: center;
  padding: 10px 30px;
}

.buttons {
  display: flex;
}

.arrow {
  margin-left: 1.2rem;
  margin-top: -0.2rem;
  color: #DB3733;
}

.myimage {
  position: fixed;
  width: 45rem;
  height: auto;
  position: relative;
  position: absolute;
  top: 0;
  left: 0;
  margin-left: 54rem;
  margin-top: 5.6rem;
}

.footer {
  margin-top: 5.4rem;
  margin-bottom: 1rem;
  display: flex;
  justify-content: space-between;
  height: 15rem;
  background-color: #D83432;
  border-radius: 0px 0px 20px 20px;
}

h6 {
  margin-bottom: 1rem;
}

.contacts {
  text-align: left;
  color: #F2F2F2;
  margin: 2rem;
}

.other {
  text-align: right;
  color: #F2F2F2;
  margin: 2rem;
}

.link {
  text-decoration: none;
  text-align: right;
  color: #F2F2F2;
  line-height: 12rem;
}

@media only screen and (max-width: 375px) {
  .logo {
  height: 2.8rem;
  width: 17rem;
  margin-top: 1rem;
  margin-left: 0.9rem;
}
.content {
  margin-top: -2rem;
  border-radius: 20px;
  width: 21rem;
  height: 44rem;
  display: flex;
  justify-content: center;
}
.text {
margin-top: 16rem;
margin-left: -17.7rem;
font-size: 19.6px;
text-align: center;
width: 16rem;
}
.btn {
  width: 13rem;
  height: 3rem;
  border-width: 3px;
  border-radius: 80px;
  font-size: 1rem;
  padding: 11px 0;
  margin: 0 0 13px;
  text-align: center;
}
.buttons {
  margin-top: -1rem;
  margin-left: 0.2rem;
  display: table;
  padding: 2rem;
}
.arrow {
  margin-left: 1.2rem;
  margin-top: -0.2rem;
}

.myimage {
  width: 14rem;
  margin-left: 9rem;
  margin-top: 36.3rem;
}

.footer {
  margin-top: 3.8rem;
  margin-bottom: -2rem;
  height: 24rem;
  width: 21rem;
  flex-direction: column;
}

h6 {
  margin-top: 1rem;
  margin-bottom: 1rem;
}

.contacts {
  text-align: center;
  margin-top: 1rem;
}

.other {
  margin-top: -1rem;
  text-align: center;
}

.link {
  text-align: center;
  line-height: 5rem;
}
}
@media (max-width: 1024px) {
.logo {
  height: 4rem;
  width: 25rem;
  margin-top: 2rem;
  margin-left: 2rem;
}
.content {
  margin-top: -2rem;
  border-radius: 20px;
  width: 55rem;
  height: 60rem;
  justify-content: center;
}
.text {
margin-top: 25rem;
margin-left: -45rem;
font-size: 30px;
text-align: center;
width: 18rem;
}
.btn {
  width: 20rem;
  height: 5rem;
  border-width: 5px;
  border-radius: 80px;
  font-size: 1.5rem;
  padding: 11px 0;
  margin: 0 0 13px;
  text-align: center;
}
.buttons {
  margin-top: -1rem;
  margin-left: 0.2rem;
  display: table;
  padding: 2rem;
}
.arrow {
  margin-left: 1.2rem;
  margin-top: -0.2rem;
}

.myimage {
  width: 40rem;
  margin-left: 22rem;
  margin-top: 25.5rem;
}

.footer {
  display: flex;
  margin-top: 4rem;
  margin-bottom: -2rem;
  height: 15rem;
  width: 55rem;
  flex-direction: column;
  justify-content: space-between;
}

h6 {
  font-size: 1.2rem;
  margin-bottom: 1rem;
}
.contacts {
  text-align: left;
  margin: 1.5rem;
}

.other {
  text-align: right;
  margin: 2rem;
}

.link {
  text-align: right;
  line-height: 12rem;
}
}
</style>
