<template>
    <div class="location">
        <div class="container">
            <div class="location-header">Manzilimiz</div>
            <div class="main">
                <div class="location__left">
                    <h3 class="location__left-title">Farg'ona viloyati, Rishton tumani, Uchariq.Ibn Sino Education</h3>
                    <iframe class="location__left-address"
                        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3039.0451036425547!2d71.25249447548136!3d40.385692957528626!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x38bb01cce3a664bf%3A0x655ad28fe9cf1574!2sIbn%20Sino%20Education!5e0!3m2!1suz!2s!4v1721538073635!5m2!1suz!2s"
                        style="border:0;" allowfullscreen="" loading="lazy"
                        referrerpolicy="no-referrer-when-downgrade"></iframe>
                </div>
                <div class="location__right">
                    <a href="tel:+998948553366" class="location__right-title">Tel: +998948553366</a>
                    <img src="../assets/img/locationimg.jpg" alt="" class="location__right-img">
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
@import "../assets/scss/main.scss";

.location {
    width: 100%; 
    height: 2500px;
    margin-bottom: 120px;
    &-header {
        @include font(36, 800, 1.2);
        margin-bottom: 40px;
        text-align: center;
        color: $text-color;
    }

    .main {
        display: flex;
        align-items: flex-start;
        gap: 100px;
    }

    &__left {
        &-title {
            margin-bottom: 30px;
            @include font(22, 700, 1.2);
            color: $text-color;
        }

        &-address {
            width: 650px;
            height: 450px;
            box-shadow: -5px -5px 10px #c9c9c9, 5px 5px 10px #c9c9c9;
        }
    }

    &__right {
        display: flex;
        flex-direction: column;
        &-title {
            @include font(18, 600, 1.2);
            color: $text-color;
        }

        &-img {
            margin-top: 30px;
            width: 600px;
            height: 450px;
            box-shadow: -5px -5px 10px #c9c9c9,5px 5px 10px #c9c9c9;
        }
    }
}
</style>