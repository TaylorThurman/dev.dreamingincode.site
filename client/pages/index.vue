<template>
    <div class="container">
        <div class="overlay">
            <SleepyDude class="sleepy-dude" />
            <p>Coming Soon</p>
        </div>
    </div>
</template>

<script>
    import SleepyDude from '../components/SleepyDude'

    export default {
        components: {
            SleepyDude
        },
        data() {
            return {}
        },
    }
</script>

<style>
    body {
        margin: 0;
        background: #373737;
    }

    .container {
        height: 80vh;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .overlay {
        position: absolute;
        color: white;
    }

    .sleepy-dude {
        margin-left: 55px
    }

    p {
        margin: 10px 0 0 0;
        font-size: 36px;
    }
</style>