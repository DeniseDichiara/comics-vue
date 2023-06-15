<template>
    <div>
        <h1>App Header</h1>
        <div>
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
        </div>
    </div>
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
    ul{
        list-style: none;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
    }

    main-flex{
        display: flex;
        flex-direction: row;
    }
</style>