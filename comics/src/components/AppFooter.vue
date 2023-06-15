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
        <h3>DC
            <div class="bottom">
                <p>Terms of Use</p>
                <p>Comics</p>
                <p>Movies</p>
                <p>TV</p>
                <p>Games</p>
                <p>Videos</p>
                <p>News</p>
                <p>Games</p>
                <p>Videos</p>
                <p>News</p>
            </div>

        </h3>
        <h3>SITE
            <div class="bottom">
                <p>Characters</p>
                <p>Comics</p>
                <p>Movies</p>
                <p>TV</p>
            </div>
        </h3>

        
    </footer>

    <div class="lower-footer">
            <div class="sign-up">
                <h3>SIGN-UP NOW!</h3>
            </div>
            <div>
                <h3>FOLLOW US</h3>

            </div>

        </div>
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
    height: 20rem;
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

.lower-footer{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    padding-bottom: 3rem;
    padding-right: 10rem;
    height: 10rem;
    background-color: #303030;
    color: white;
}


</style>