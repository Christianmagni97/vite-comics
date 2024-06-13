<script>

</script>
<template>
    <div class="prime-part-footer">
        <nav class="footer-link">
            <ul>
                <li>ciao</li>
                <li>ciao</li>
                <li>ciao</li>
            </ul>
        </nav>
        <nav class="footer-link">
            <ul>
                <li>salve</li>
                <li>salve</li>
                <li>salve</li>
            </ul>
        </nav>
        <img src="../assets/img/dc-logo-bg.png" alt="dc-logo" class="img-logo.footer">
    </div>
    <div class="finish-main">
        <section class="rett-sign">
            <p>SIGN UP NOW!</p>
        </section>
        <section class="follow">
            <p>FOLLOW US!</p>
            <img src="../assets/img/footer-facebook.png" alt="">
            <img src="../assets/img/footer-periscope.png" alt="">
            <img src="../assets/img/footer-pinterest.png" alt="">
            <img src="../assets/img/footer-twitter.png" alt="">
            <img src="../assets/img/footer-youtube.png" alt="">
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
    color: white;
}
.footer-link{
    display: flex;
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
    align-items: center;
}
.follow img{
    width: 30px;
    height: 30px;
    margin-left: 10px;
}
.prime-part-footer{
    display: flex;
    background-image: url(../assets/img/footer-bg.jpg);
    width: 100%;
    height: 400px;
   
}
</style>