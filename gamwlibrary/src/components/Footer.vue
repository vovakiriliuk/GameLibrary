<template>
    <footer>
        <div class="container">
            <div class="footer-navigation">
                    <ul>
                        <li><a href="#">About us</a></li>
                        <li><a href="#">Services</a></li>
                        <li><a href="#">Contacts</a></li>
                        <li><a href="#">Privacy Policy</a></li>
                        <li><a href="#">For gamers</a></li>
                        <li><a href="#">Other information</a></li>
                    </ul>
            </div>
            
            <div class="footer-icons">
                <h3>Follow us in:</h3>
                <ul>
                    <li>
                        <a href="#" class="icon">
                            <i class="fa-brands fa-instagram"></i>
                            Instagram    
                        </a>
                    </li>
                    <li>
                        <a href="#" class="icon">
                            <i class="fa-brands fa-facebook"></i>
                            Facebook
                        </a>
                    </li>
                    <li>
                       <a href="#" class="icon">
                            <i class="fa-brands fa-telegram"></i>
                            Telegram
                        </a> 
                    </li>
                </ul>
                
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
        padding-bottom: 16px;
    }

    .container {
        display: flex;
        justify-content: space-between;
        margin: 0 auto;
    }

    .footer-navigation ul {
        display: grid;
        grid-template-columns: repeat(2,1fr);
        grid-template-rows: repeat(3,1fr);
        gap: 5px;

        list-style-type: none;

        a {
            text-decoration: none;
            color: var(--main-text-color);
            transition: var(--transition);

            &:hover {
                color: var(--additional-hover-text);
            }
        }
    }

    .footer-icons {
        display: flex;
        align-items: flex-start;
        padding-right: 16px;

        ul {
            list-style-type: none;
            padding-left: 20px;

            li {
                padding: 5px;
            }
            a {
                text-decoration: none;
                color: var(--main-text-color);
                transition: var(--transition);

                &:hover {
                    color: var(--additional-hover-text);
                }
            }
        }
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