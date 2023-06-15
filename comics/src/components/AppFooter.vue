<template>
    <footer>
        <h3>DC COMICS
            <div class="bottom">
                <p>Characters</p>
                <p>Comics</p>
                <p>Movies</p>
                <p>TV</p>
                <p>Games</p>
                <p>Videos</p>
                <p>News</p>
            </div>
        </h3>
        <h3>DC</h3>
        <h3>SITE</h3>
    </footer>
</template>

<script>
export default {
    name: 'AppFooter',
    data() {
        return {

        }
    }
}
</script>

<style>
footer {
    background-color: #2b2b2b;
    height: 30rem;
    display: flex;
    flex-direction: row;
    color: white;
}

h3 {
    padding-right: 2rem;
    padding-top: 2rem;
    padding-left: 10rem;
}

p{
    font-size: small;
    color: #959595;
    padding-bottom: .5rem;
}

.bottom{
    padding-top: 1rem;
}
</style>