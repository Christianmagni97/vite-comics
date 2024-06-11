<script>

</script>
<template>
    <header>
        <section id="logo">
            <img src="../assets/img/dc-logo.png" alt="dc logo">
        </section>
        <section id="navBar">
            <nav>
                <ul>
                    <li>CHARACTERS</li>
                    <li class="active">COMICS</li>
                    <li>MOVIES</li>
                    <li>TV</li>
                    <li>GAMES</li>
                    <li>CHARACTERS</li>
                </ul>
            </nav>

        </section>
    </header>
  
</template>
<style lang="scss">
@use '../assets/style/partials/variabls.scss' as *;
ul{
    display: flex;

}
li{
    margin-right: 1rem;
    &.active{
        color: $color-second-main;
        border-bottom: $color-second-main;
    }
}
</style>