<template>
    <header>
        <a href="#" class="logo">
            <img src="../assets/vue.svg" alt="logoImg" class="logo">
            <h3>BestGame</h3>
        </a>

        <nav>
            <ul>
                <li><a href="#">Games</a></li>
                <li><a href="#">Hits</a></li>
                <li><a href="#">For gamers</a></li>
            </ul>
        </nav>
    </header>
</template>

<style>
    header{
        background: var(--additional-color);
        position: sticky;
        top: 0;
        left: 0;
        height: 100px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0 16px;
    }

    .logo{
        display: flex;
        padding: 5px;
        text-decoration: none;
        color: var(--main-text-color);

        h3 {
            font-size: 22px;
        }
    }

    nav {
        ul {
            list-style-type: none;
            display: flex;

            li {
                padding: 10px;
                font-size: 18px;

                a {
                    text-decoration: none;
                    color: var(--main-text-color);

                    transition: var(--transition);

                    &:hover{
                        color: var(--additional-hover-text);
                    }
                }
                
            }
        }

    }
</style>