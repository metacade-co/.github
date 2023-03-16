<style>
    .banner-image {
        width: 100%;
        margin-bottom: 32px;
    }

    .buttons-container {
        display: flex;
        gap: 10px;
    }

    .buttons-container__button {
        flex-grow: 0;
        flex-shrink: 1;
        
        font-family: Segoe UI;
        font-size: 16px;
        font-weight: 700;
        letter-spacing: 0.03em;
        text-transform: uppercase;

        padding: 17px 5%;
        border: none;
        clip-path: polygon(0 3px,3px 3px,3px 0,calc(100% - 3px) 0,calc(100% - 3px) 3px,100% 3px,100% calc(100% - 3px),calc(100% - 3px) calc(100% - 3px),calc(100% - 3px) 100%,3px 100%,3px calc(100% - 3px),0 calc(100% - 3px));
    }

    .buttons-container__button > a {
        text-decoration: none;
        color: black
    }

    .divider {
        height: 1px;
        margin: 24px 0px;
    }

    .dashed {
        border: none;
        border-bottom: 2px dashed #F5CA2A !important;

        margin: 44px 0px;
    }

    .section__heading {
        margin: 0;
        padding: 0;

        font-style: normal;
        font-weight: 400;
        font-size: 37px;
        line-height: 40px;
        text-transform: uppercase;
        color: #FFFFFF;
    }

    .socials {
        display: flex;
        align-items: flex-end;
        justify-content: space-between;
    }

    .socials__social-link-buttons {
        display: flex;
        gap: 16px;
    }

    .socials__social-link-buttons__button {
        width: 47px;
        height: 47px;
        padding: 8px;

        background-color: #00A2E9;

        border: none;
        clip-path: polygon(0 3px,3px 3px,3px 0,calc(100% - 3px) 0,calc(100% - 3px) 3px,100% 3px,100% calc(100% - 3px),calc(100% - 3px) calc(100% - 3px),calc(100% - 3px) 100%,3px 100%,3px calc(100% - 3px),0 calc(100% - 3px));
    }

    .metasystem__container {
        margin-top: 32px;
    }

    .metasystem__container-item {
        display: flex;
        align-items: start;
    }

    .metasystem__container-item > p {
        margin: 0;
        padding: 0;
        margin-left: 28px;

        font-family: Segoe UI;
        font-style: normal;
        font-weight: 400;
        font-size: 16px;
        line-height: 24px;
    }

    .metaplatform {
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .metaplatform__header {
        display: flex;
        align-items: center;
        gap: 18px;
    }

    .metaheads {
        display: flex;
        flex-direction: column;
        align-items: start;
    }

    .metaheads > img {
        width: 100%;
    }

    .metaheads__header {
        display: flex;
        gap: 16px;

        margin-bottom: 32px;
    }

</style>

<div class="main">
    <div>
        <img class="banner-image" src="./assets/headerBanner.png" />
    </div>
    <section class="buttons-container">
        <button class="buttons-container__button" style="background-color: #BE1EC7;">
            <a class=""href="https://metacade.co" style="color: white;">web site</a>
        </button>
        <button class="buttons-container__button" style="background-color: #00A2E9;">
            <a href="" style="color: white;">metacade platform</a>
        </button>
        <button class="buttons-container__button" style="background-color: #F5CA2A;">
            <a href="https://google.com">whitepaper</a>
        </button>
        <button class="buttons-container__button" style="background-color: #00D0AD;">
            <a href="https://google.com">certik audit</a>
        </button>
    </section>
    <hr class="divider dashed" />
    <section class="socials">
        <h2 class="section__heading">our socials</h2>
        <div class="socials__social-link-buttons">
            <button class="socials__social-link-buttons__button">
                <a href="https://metacade.co">
                    <img src="./assets/icons/linkIcon.svg" >
                </a>
            </button>
            <button class="socials__social-link-buttons__button" style="padding: 12px 8px; width: 49px;">
                <a href="https://metacade.co">
                    <img src="./assets/icons/youtubeIcon.svg">
                </a>
            </button>
            <button class="socials__social-link-buttons__button" style="width: 48px;">
                <a href="https://metacade.co">
                    <img src="./assets/icons/linkedinIcon.svg" >
                </a>
            </button>
            <button class="socials__social-link-buttons__button" style="width: 48px; height: 47.5px; padding: 8px 10.4px 7.5px">
                <a href="https://metacade.co">
                    <img src="./assets/icons/tiktokIcon.svg" >
                </a>
            </button>
            <button class="socials__social-link-buttons__button" style="padding: 10px 8px">
                <a href="https://metacade.co">
                    <img src="./assets/icons/discordIcon.svg" >
                </a>
            </button>
            <button class="socials__social-link-buttons__button" style="width: 49px;">
                <a href="https://metacade.co">
                    <img src="./assets/icons/telegramIcon.svg" >
                </a>
            </button>
            <button class="socials__social-link-buttons__button" style="width: 48px;">
                <a href="https://metacade.co">
                    <img src="./assets/icons/twitterIcon.svg" >
                </a>
            </button>
            <button class="socials__social-link-buttons__button" style="width: 48px; padding: 9px">
                <a href="https://metacade.co">
                    <img src="./assets/icons/instagramIcon.svg" >
                </a>
            </button>
        </div>
    </section>
    <hr class="divider dashed" />
    <section class="metasystem">
        <h2 class="section__heading">metasystem</h2>
        <div class="metasystem__container">
            <div class="metasystem__container-item">
                <img src="./assets/heartImage.png">
                <p>Our community hub will focus on the most pressing narratives and trending developments in the blockchain gaming ecosystem. With you, we want to blitz the Web3 market by building a one-stop platform for Metaverse enthusiasts to network and build their careers in the high-potential P2E world.</p>
            </div>
            <hr class="divider">
            <div class="metasystem__container-item">
                <img src="./assets/starImage.png">
                <p>Test Contributors will be rewarded in $MCADE along with limited edition staking options. When we say, "Metacade is designed by gamers, for gamers," we mean it. Access various ongoing side hustles by contributing alpha, content, opinions, and ideas in the community based on the trending topics each month.</p>
            </div>
            <hr class="divider">
            <div class="metasystem__container-item">
                <img src="./assets/shieldImage.png">
                <p>With Metacade, you don't need to be a games developer to become a key influencer. Search the live 'side hustles' each week, and contribute to the platform and community to reap attractive rewards.</p>
            </div>
        </div>
    </section>
    <hr class="divider dashed" />
    <section class="metaplatform">
        <div class="metaplatform__header">
            <img src="./assets/arrowLeftImage.png"/>
            <h2 class="section__heading">metacade <span style="color: #BE1EC7">Game platform</span></h2>
            <img src="./assets/arrowRightImage.png"/>
        </div>
        <img src="./assets/macbookImage.png">
    </section>
    <hr class="divider dashed" />
    <section class="metaheads">
         <div class="metaheads__header">
            <img src="./assets/icons/metaheadsIcon.png"/>
            <h2 class="section__heading">metaheads</h2>
        </div>
        <img src="./assets/metaheadsImage.png">
    </section>
    <hr class="divider dashed" />
</div>

