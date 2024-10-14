<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix Clone</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="main">
        <nav>
            <svg viewBox="0 0 111 30" version="1.1" fill="red" xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" class="NETFLIX-H">
                <g>
                    <path
                        d="M105.06233,14.2806261 L110.999156,30 C109.249227,29.7497422 107.500234,29.4366857 105.718437,29.1554972 L102.374168,20.4686475 L98.9371075,28.4375293 C97.2499766,28.1563408 95.5928391,28.061674 93.9057081,27.8432843 L99.9372012,14.0931671 L94.4680851,-5.68434189e-14 L99.5313525,-5.68434189e-14 L102.593495,7.87421502 L105.874965,-5.68434189e-14 L110.999156,-5.68434189e-14 L105.06233,14.2806261 Z M90.4686475,-5.68434189e-14 L85.8749649,-5.68434189e-14 L85.8749649,27.2499766 C87.3746368,27.3437061 88.9371075,27.4055675 90.4686475,27.5930265 L90.4686475,-5.68434189e-14 Z M81.9055207,26.93692 C77.7186241,26.6557316 73.5307901,26.4064111 69.250164,26.3117443 L69.250164,-5.68434189e-14 L73.9366389,-5.68434189e-14 L73.9366389,21.8745899 C76.6248008,21.9373887 79.3120255,22.1557784 81.9055207,22.2804387 L81.9055207,26.93692 Z M64.2496954,10.6561065 L64.2496954,15.3435186 L57.8442216,15.3435186 L57.8442216,25.9996251 L53.2186709,25.9996251 L53.2186709,-5.68434189e-14 L66.3436123,-5.68434189e-14 L66.3436123,4.68741213 L57.8442216,4.68741213 L57.8442216,10.6561065 L64.2496954,10.6561065 Z M45.3435186,4.68741213 L45.3435186,26.2498828 C43.7810479,26.2498828 42.1876465,26.2498828 40.6561065,26.3117443 L40.6561065,4.68741213 L35.8121661,4.68741213 L35.8121661,-5.68434189e-14 L50.2183897,-5.68434189e-14 L50.2183897,4.68741213 L45.3435186,4.68741213 Z M30.749836,15.5928391 C28.687787,15.5928391 26.2498828,15.5928391 24.4999531,15.6875059 L24.4999531,22.6562939 C27.2499766,22.4678976 30,22.2495079 32.7809542,22.1557784 L32.7809542,26.6557316 L19.812541,27.6876933 L19.812541,-5.68434189e-14 L32.7809542,-5.68434189e-14 L32.7809542,4.68741213 L24.4999531,4.68741213 L24.4999531,10.9991564 C26.3126816,10.9991564 29.0936358,10.9054269 30.749836,10.9054269 L30.749836,15.5928391 Z M4.78114163,12.9684132 L4.78114163,29.3429562 C3.09401069,29.5313525 1.59340144,29.7497422 0,30 L0,-5.68434189e-14 L4.4690224,-5.68434189e-14 L10.562377,17.0315868 L10.562377,-5.68434189e-14 L15.2497891,-5.68434189e-14 L15.2497891,28.061674 C13.5935889,28.3437998 11.906458,28.4375293 10.1246602,28.6868498 L4.78114163,12.9684132 Z">
                    </path>
                </g>
            </svg>
            <div style="display: flex;
            gap: 20px;">
                <button class="english">English</button>
                <button class="sign">Sign In</button>
            </div>
        </nav>
        <div class="box">
        </div>
        <div class="hero">
            <span>Unlimited movies, TV shows and more</span>
            <span>Watch anywhere. Cancel anytime.</span>
            <span>Ready to watch? Enter your email to create or restart your membership.</span>
            <div class="hero-buttons">
                <input type="text" placeholder="Email Address">
                <button class="btn-red">Get Started &gt</button>
            </div>

        </div>
        <div class="separation"></div>

    </div>

    <section class="first">
        <div>
            <span>Enjoy on your TV</span>
            <span>Watch on smart TVs, PlayStation, Xbox, Chromecast, Apple TV, Blu-ray players and more.</span>
        </div>
        <div class="secImg">
            <img src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/tv.png">

            <video src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/video-tv-in-0819.m4v"
                autoplay loop muted></video>
        </div>
    </section>
    <div class="separation"></div>

    <section class="first second">

        <div class="secImg">
            <img src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/mobile-0819.jpg" alt="">

        </div>
        <div>
            <span>Download your shows to watch offline</span><br>
            <span>Save your favourites easily and always have something to watch.</span>
        </div>
    </section>

    <div class="separation"></div>
    <section class="first third">
        <div>
            <span>Watch everywhere</span>
            <span>Stream unlimited movies and TV shows on your phone, tablet, laptop, and TV.</span>
        </div>

        <div class="secImg">
            <img src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/device-pile-in.png"
                alt="">
            <video src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/video-devices-in.m4v"
                autoplay loop muted></video>
        </div>
    </section>
    <div class="separation"></div>

    <section class="first fourth">

        <div class="secImg">
            <img src="https://occ-0-6246-2186.1.nflxso.net/dnm/api/v6/19OhWN2dO19C9txTON9tvTFtefw/AAAABVr8nYuAg0xDpXDv0VI9HUoH7r2aGp4TKRCsKNQrMwxzTtr-NlwOHeS8bCI2oeZddmu3nMYr3j9MjYhHyjBASb1FaOGYZNYvPBCL.png?r=54d"
                alt="">

        </div>
        <div>
            <span>Create profiles for kids</span><br>
            <span>Send children on adventures with their favourite characters in a space made just for them—free with
                your membership.</span>
        </div>
    </section>

    <div class="separation"></div>
    <section class="faq">
        <h2>Frequently Asked Questions</h2>
        <div class="faqbox">

            <span>What is NetFlix?</span>
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24" color="#ffffff"
                fill="none">
                <path d="M12 4V20M20 12H4" stroke="currentColor" stroke-width="1.5" stroke-linecap="round"
                    stroke-linejoin="round" />
            </svg>

        </div>
        <div class="faqbox1">

            <span>How much does Netflix cost?</span>
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24" color="#ffffff"
                fill="none">
                <path d="M12 4V20M20 12H4" stroke="currentColor" stroke-width="1.5" stroke-linecap="round"
                    stroke-linejoin="round" />
            </svg>

        </div>
        <div class="faqbox1">

            <span>Where can I watch?</span>
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24" color="#ffffff"
                fill="none">
                <path d="M12 4V20M20 12H4" stroke="currentColor" stroke-width="1.5" stroke-linecap="round"
                    stroke-linejoin="round" />
            </svg>

        </div>
        <div class="faqbox1">
            <span>How do I cancel?</span>
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24" color="#ffffff"
                fill="none">
                <path d="M12 4V20M20 12H4" stroke="currentColor" stroke-width="1.5" stroke-linecap="round"
                    stroke-linejoin="round" />
            </svg>

        </div>
        <div class="faqbox1">
            <span>What can I watch on Netflix?</span>
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24" color="#ffffff"
                fill="none">
                <path d="M12 4V20M20 12H4" stroke="currentColor" stroke-width="1.5" stroke-linecap="round"
                    stroke-linejoin="round" />
            </svg>

        </div>
        <div class="faqbox1">
            <span>Is Netflix good for kids?</span>
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="24" height="24" color="#ffffff"
                fill="none">
                <path d="M12 4V20M20 12H4" stroke="currentColor" stroke-width="1.5" stroke-linecap="round"
                    stroke-linejoin="round" />
            </svg>

        </div>

        <div class="actor">
            <span>Ready to watch? Enter your email to create or restart your membership.</span>
            <div class="actor-buttons">
                <input class="gojana" type="text" placeholder="Email Address">
                <button class="btn-red">Get Started &gt</button>
            </div>

        </div>
    </section>
    <div class="separation"></div>

    <footer>
        <div class="questions">
            Questions? Call <a href="000-800-919-1694">000-800-919-1694</a>
        </div>
        <div class="footer">
            <div class="footer-item">
                <a href="https://fast.com/">Speed Test</a>
                <a href="https://help.netflix.com/legal/privacy">Privacy</a>
                <a href="https://ir.netflix.net/">Investor Relations</a>
                <a href="https://help.netflix.com/en/node/412">FAQ</a>
            </div>
            <div class="footer-item">
                <a href="https://help.netflix.com/legal/notices">Legal Notices</a>
                <a href="faq">Cookie Preference</a>
                <a href="https://jobs.netflix.com/">Jobs</a>
                <a href="https://help.netflix.com/en">Help Centre</a>
            </div>
            <div class="footer-item">
                <a href="https://www.netflix.com/in/browse/genre/839338">Only on Netflix</a>
                <a href="https://help.netflix.com/en/node/134094">Coorporate Information</a>
                <a href="https://help.netflix.com/en/node/14361">Ways to Watch</a>
                <a href="https://www.netflix.com/login?nextpage=https%3A%2F%2Fwww.netflix.com%2Fyouraccount">Account</a>
            </div>

            <div class="footer-item">
                <a href="https://help.netflix.com/en/contactus">Contact Us</a>
                <a href="https://help.netflix.com/legal/termsofuse">Terms of Use</a>
                <a href="https://media.netflix.com/en/">Media Center</a>
            </div>
            <div class="questions">
                Netflix India
            </div>

        </div>
    </footer>

</body>

</html>
