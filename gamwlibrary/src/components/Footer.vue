<template>
    <footer>
        <div class="container">
            <div class="fcolumn">
                <h3>Navigation</h3>
                <nav>
                    <ul>
                        <li><a href="#">About us</a></li>
                        <li><a href="#">Services</a></li>
                        <li><a href="#">Contacts</a></li>
                    </ul>
                </nav>
            </div>
            <div class="fcolumn">
                <h3>Follow us</h3>
                <a href="#" class="icon">
                    <i class="fa-brands fa-instagram"></i>
                    Instagram    
                </a>
                <a href="#" class="icon">
                    <i class="fa-brands fa-facebook"></i>
                    Facebook
                </a>
                <a href="#" class="icon">
                    <i class="fa-brands fa-telegram"></i>
                    Telegram
                </a>
            </div>
        </div>
        <div class="fbottom">
            <p>© 2025 SashaVova Inc. All rights reserved.</p>
        </div>
    </footer>
</template>

<style>
    footer {
        color: var(--main-text-color);
        background: var(--additional-color);
        height: 155px;
        position: absolute;
        bottom: 0;
        right: 0;
        width: 100%;
    }

    .container {
        display: flex;
        justify-content: space-around;
        margin: 0 auto;
    }

    .icon {
        color: var(--additional-text-color);
        margin-right: 15px;
        text-decoration: none;
    }

    .fbottom {
        color: var(--border-button-color);
        text-align: center;
        border-top: 1px solid var(--border-button-color)
    }
</style>