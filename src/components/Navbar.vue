<template>
    <nav>
        <div class="menu">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">កម្សាន្ត</a></li>
                <li><a href="#">បច្ចេកវិទ្យា</a></li>
                <li><a href="#">ជីវិតនិងសង្គម</a></li>
                <li><a href="#">កីឡា</a></li>
                <li><a href="#"> Auto Talk</a></li>
            </ul>
        </div>
    </nav>
</template>
<script setup>

</script>
<style  scoped>
    nav{
        width: 100%;
        background-color: #fa1939;
        height: 60px;
        .menu{
            width: 80%;
            margin: auto;
            height: 100%;
            ul{
                display: flex;
                height: 100%;
                gap: 20px;
                li{
                    list-style: none;
                    height: 100%;
                    display: flex;
                    align-items: center;
                    padding: 0 10px;
                    a{
                        color: #e0e0e0;
                        text-transform: uppercase;
                        text-decoration: none;
                        font-size: 20px;
                        font-weight: bold;
                    }
                }
                li:hover{
                    background-color: #ca142f;
                }
                li:hover a{
                    color: #fff;
                }
            }
        }
    }
</style>