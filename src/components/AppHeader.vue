<script>
export default{
    data(){
        return{
            navHeaderLink:[
                {
                    id: 1,
                    title: "characters",
                    url: "#",
                    active: false,

                },
                {
                    id: 2,
                    title: "comics",
                    url: "#",
                    active: true,

                },
                {
                    id: 3,
                    title: "movies",
                    url: "#",
                    active: false,

                },
                {
                    id: 4,
                    title: "movies",
                    url: "#",
                    active: false,

                },
                {
                    id: 5,
                    title: "movies",
                    url: "#",
                    active: false,

                },
                {
                    id: 6,
                    title: "movies",
                    url: "#",
                    active: false,

                },
                {
                    id: 7,
                    title: "movies",
                    url: "#",
                    active: false,

                },
                {
                    id: 8,
                    title: "movies",
                    url: "#",
                    active: false,

                },
                {
                    id: 9,
                    title: "movies",
                    url: "#",
                    active: false,

                },

            ]
        }
    }
}

</script>
<template>
    <header>
        <div class="header-logo-navbar">
            <section id="logo">
            <img src="../assets/img/dc-logo.png" alt="dc logo">
        </section>
        <section id="navBar">
            <nav>
                <ul>
                    <li v-for="link in navHeaderLink" key="link.id" >
                        {{ link.title }}
                    </li>
            
                </ul>
            </nav>
        </section>

        </div>
    </header>
  
</template>
<style lang="scss">
@use '../assets/style/partials/variabls.scss' as *;
@use '../assets/style/general.scss' as *;
.header-logo-navbar{
    display: flex;
    justify-content: center;
}
ul{
    display: flex;
    justify-content: center;
    padding: 3rem;

}
li{
    margin-right: 1rem;
    &.active{
        color: $color-second-main;
        border-bottom: $color-second-main;
    }
}
</style>