<template>
    <header class="header">
        <div class="entry-content container-fluid">

            <div class="row">
                <div class="col-12 col-md-4">
                    <img src="./../../assets/logo.png" alt="">
                </div>
                <div class="col-12 col-md-8">
                    <h1>Blog Vue</h1>
                </div>
            </div>
        </div>
        <NavBar />
    </header>
</template>

<script>
import NavBar from "./navbar";

export default {
    components: {
        NavBar,
    }
}  
</script>
