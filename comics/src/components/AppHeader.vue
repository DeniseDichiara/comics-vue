<template>
    <header>
        <nav>
            <img src="dc-logo.png" alt="logo">
            <ul>
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    name:'AppHeader',
    data(){
        return{

        }
    }
}
</script>

<style>
    header{
        padding-top: 2rem;
    }

    nav{
        display: flex;
        flex-direction: row;
        justify-content: space-around;
    }

    img{
        width: 4rem;
        height: 4rem;
    }

    ul{
        list-style: none;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
    }

    li{
        padding-right: 1rem;
    }


</style>