<template>
    <header>
        <div class="logo">
            <img src="" alt="logoImg" class="logo">
            <h3>BestGame</h3>
        </div>

        <nav>
            <ul>
                <li>Games</li>
                <li>Hits</li>
                <li>For gamers</li>
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
    }

    nav {
        ul {
            list-style-type: none;
            display: flex;

            li {
                padding: 5px;
                color: var(--main-text-color);
            }
        }

    }
</style>