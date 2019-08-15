<template>
    <header class="header">
        <div class="container">
            <div class="header__inside">
                <nuxt-link to="/">
                <h1 class="logo">
                    ;
                </h1>
                </nuxt-link>
                <nav class="nav">
                    <ul class="nav__list">
                        <li class="nav__list__item nav__list__item--first">
                            <nuxt-link to="/">Home</nuxt-link>
                        </li>
                        <li class="nav__list__item">
                            <nuxt-link to="/blog">Blog</nuxt-link>
                        </li>
                    </ul>
                </nav>
         </div>
        </div>
    </header>
</template>
<style lang="scss" scoped>
.logo {
    transition: 0.3s linear;
    &:hover {
        color: #8234fc;
    }
}
.header {
    background-color: #fff;
    padding: 15px;
    border-bottom: 1px solid #efefef;

    &__inside {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
}
.nav {
    &__list {
        display: flex;
        &__item {
            margin-left: 10px;
            font-weight: bold;
            transition: 0.3s linear;
            &:hover {
                color: #8234fc;
            }

            &--first {
                border-right: 1px solid black;
                padding-right: 10px;
            }
        }
    }
}
</style>