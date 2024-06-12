<script>

</script>
<template>
    <div class="prime-part-footer">
        <nav>
            <div class="list-item-footer">
                <ul>
                <li>Il Pastificio</li>
                <li><a href="#">IlPastificio</a></li>
                <li><a href="#">IlPastificio</a></li>
                <li><a href="#">IlPastificio</a></li>
                <li><a href="#">IlPastificio</a></li>
                <li><a href="#">IlPastificio</a></li>
            </ul>
            </div>
        </nav>
          
    </div>
    <div class="finish-main">
        <section class="rett-sign">
            <p>SIGN UP NOW!</p>
        </section>
        <section class="follow">
            <p>FOLLOW US!</p>
            <img src="../assets/img/footer-facebook.jpg" alt="">
            <img src="../assets/img/footer-periscope.jpg" alt="">
            <img src="../assets/img/footer-pinterest.jpg" alt="">
            <img src="../assets/img/footer-twitter.jpg" alt="">
            <img src="../assets/img/footer-youtube.jpg" alt="">
        </section>
    </div>
</template>
<style lang="scss" scoped>
@use '../assets/style/partials/variabls.scss' as *;
@use '../assets/style/general.scss' as *;
.finish-main{
    background-color: #303030;
    display: flex;
    justify-content: space-between;
    padding: 2rem;
    
}
.rett-sign{
    text-align: center;
    width: 200px;
    height: 30px;
    border: 3px solid #0282f9;
    color: white;
    font-size: 20px;
}
.follow{
    display: flex;
}




</style>