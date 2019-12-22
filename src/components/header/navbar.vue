<template>
  <div class="entry-navbar">

        <ul class="nav justify-content-center pt-2 pb-2 bg-dark">
            <li
                v-for="link in links"
                :key="link"
                class="nav-item">
                <a
                    :href="link.href"
                    class="nav-link active"
                >{{ link.text }}</a>
            </li>
        </ul>

    </div>
</template>

<script>
export default {
    data(){
        return {
            links: [
                {
                    text: "Home",
                    href: "/"
                },
                {
                    text: "Blog",
                    href: "/blog"
                },
                {
                    text: "About",
                    href: "/about"
                },
                {
                    text: "Contact",
                    href: "/contact"
                },                
            ]
        }
    }
}
</script>