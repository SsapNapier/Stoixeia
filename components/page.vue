<template>
  <section>
    <div class="wrap">
      <div class="container">
        <div class="FirstBall"></div>
        <div class="MassMediaLinks">
          <img class="Social" src="/linked.svg" alt="">
          <img class="Social" src="/fb.svg" alt="">
          <img class="Social" src="/inst.svg" alt="">
          <img class="Social" src="/vk_ic.svg" alt="">
        </div>
        <div class="Content">
          <div class="SecondBall"></div>
          <div class="Name">
            <h1 class="Member">Elena Mikheeva</h1>
          </div>
        </div>
        <div class="Mail">
          <h3 class="E-adress">eo.mikheeva@gmail.com</h3>
        </div>
        <div class="Phone">
          <h3 class="Number">+7 (915) 369-43-96</h3>
        </div>
      </div>
      <footer>
        <div  class="OtherText">
          <div class="love">
            <p class="studio">In love with BI</p>
          </div>
          <div class="logo">
            <p class="studio">Founder & CEO of</p>
            <img class="web" src="/iw_logo_site.svg" alt="">
          </div>
        </div>
      </footer>
      </div>

  </section>
</template>

<script>

</script>

<style lang="sass">
@import '../assets/variables'
.container
  min-height: 94vh
.FirstBall
  position: relative
  left: 86%
  width: 14%
  padding-top: 14%
  border-radius: 0 0 15% 100% / 0 0 0% 100%
  background-color: $BallColor
  z-index: 1
@media screen and (max-width: 1024px)
  .FirstBall
    left: 82%
    width: 18%
    padding-top: 18%
@media screen and (max-width: 480px)
  .FirstBall
    left: 76%
    width: 24%
    padding-top: 24%
.MassMediaLinks
  display: flex
  justify-content: space-between
  width: 24.5%
  margin: auto
  margin-top: 8%
.MassMediaLinks .Social
  margin-top: 3%
  width: 14%
@media screen and (max-width: 768px)
  .MassMediaLinks
    width: 30%
  .MassMediaLinks .Social
    width: 16%
.Content
  display: -webkit-flex
  -webkit-align-items: center
  display: flex
  align-items: center
  margin-top: 6%
@media screen and (max-width: 1024px)
  .Content
    margin-top: 9%
.SecondBall
  position: absolute
  display: flex
  align-items: center
  width: 14%
  padding-top: 28%
  border-radius: 0 100% 100% 0 / 0 50% 50% 0
  background-color: $BallColor
  z-index: 1
@media screen and (max-width: 1024px)
  .SecondBall
    width: 18%
    padding-top: 36%
@media screen and (max-width: 480px)
  .SecondBall
    width: 24%
    padding-top: 48%
.Name
  position: relative
  left: 20px
  display: flex
  margin: 0 auto
  z-index: 2
@media screen and (max-width: 768px)
  .Name
    left: 10px
.Name .Member
  color: $NameColor
  font-family: Klaxons
  font-size: 3.4rem
  letter-spacing: 0.43em
  font-weight: normal
  display: flex
.Mail
  display: flex
  justify-content: center
.Mail .E-adress
  color: white
  font-family: AvenirNextLight
  font-size: 1.4rem
  font-weight: 200
  margin-top: 5%
@media screen and (max-width: 1024px)
  .Mail .E-adress
     margin-top: 8%
@media screen and (max-width: 768px)
  .Mail .E-adress
    margin-top: 9%
    font-size: 2.1rem
@media screen and (max-width: 480px)
  .Mail .E-adress
    margin-top: 12%
    font-size: 2.1rem
.Phone
  display: flex
  justify-content: center
  margin-top: 6%
  padding-bottom: 9%
@media screen and (max-width: 768px)
  .Phone
    margin-top: 12%
    padding-bottom: 10%
@media screen and (max-width: 480px)
  .Phone
    margin-top: 15%
.Phone .Number
  color: white
  font-family: AvenirNextLight
  font-weight: 50
  font-size: 1.35rem
@media screen and (max-width: 768px)
  .Phone .Number
    font-size: 1.6rem
.OtherText
  padding-bottom: 3%
  display: flex
  font-family: AvenirNext
  color: white
  width: 95%
  margin: auto
  font-size: 20px
  justify-content: space-between
.OtherText .studio
  font-size: 0.68rem
@media screen and (max-width: 768px)
  .OtherText .studio
    font-size: 1rem
@media screen and (max-width: 480px)
  .OtherText .studio
    font-size: 1.2rem
.love,
.logo
  display: flex
  display: flex
  align-items: center
.logo .studio
  flex-shrink: 0
.logo .web
  margin-left: 5%
  height: 22px
@media screen and (max-width: 768px)
  .logo .web
      height: 14px
</style>
