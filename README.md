<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>Resume</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            height: 100%;
        }

        body {
            min-height: 100%;
            background: #eee;
            font-family: 'Lato', sans-serif;
            font-weight: 400;
            color: #222;
            font-size: 14px;
            line-height: 26px;
            padding-bottom: 50px;
        }

        .container {
            max-width: 700px;
            background: #fff;
            margin: 0px auto 0px;
            box-shadow: 1px 1px 2px #DAD7D7;
            border-radius: 3px;
            padding: 40px;
            margin-top: 50px;
        }

        .header {
            margin-bottom: 30px;
        }

        .full-name {
            font-size: 40px;
            text-transform: uppercase;
            margin-bottom: 5px;
        }

        .first-name {
            font-weight: 700;
        }

        .contact-info {
            margin-bottom: 20px;
        }

        .email,
        .phone {
            color: #999;
            font-weight: 300;
        }

        .separator {
            height: 10px;
            display: inline-block;
            border-left: 2px solid #999;
            margin: 0px 10px;
        }

        .position {
            font-weight: bold;
            display: inline-block;
            margin-right: 10px;
            text-decoration: underline;
        }

        .details {
            line-height: 20px;
        }

        .section {
            margin-bottom: 40px;
        }

        .section:last-of-type {
            margin-bottom: 0px;
        }

        .section__title {
            letter-spacing: 2px;
            color: #54AFE4;
            font-weight: bold;
            margin-bottom: 10px;
            text-transform: uppercase;
        }

        .section__list-item {
            margin-bottom: 40px;
        }

        .section__list-item:last-of-type {
            margin-bottom: 0;
        }

        .left,
        .right {
            vertical-align: top;
            display: inline-block;
        }

        .left {
            width: 60%;
        }

        .right {
            text-align: right;
            width: 39%;
        }

        .name {
            font-weight: bold;
        }

        a {
            text-decoration: none;
            color: #000;
            font-style: italic;
        }

        a:hover {
            text-decoration: underline;
            color: #000;
        }

        .skills__item {
            margin-bottom: 10px;
        }

        input {
            display: none;
        }

        label {
            display: inline-block;
            width: 20px;
            height: 20px;
            background: #C3DEF3;
            border-radius: 20px;
            margin-right: 3px;
        }

        input:checked+label {
            background: #79A9CE;
        }
    </style>
</head>

<body>
    <link href='https://fonts.googleapis.com/css?family=Lato:400,300,700' rel='stylesheet' type='text/css'>

    <div class="container">
        <div class="header">
            <div class="full-name">
                <span class="first-name">Nicky</span>
            </div>
            <div class="contact-info">
                <span class="email">Email: </span>
                <span class="email-val">nickybustamam2004@gmail.com</span>
                <span class="separator"></span>
                <span class="phone">Phone: </span>
                <span class="phone-val">0968136315</span>
            </div>

            <div>
                <img src="donald-5103361_960_720.png" width="60%">
            </div>

            <div class="about">
                <span class="position">Front-End Developer </span>
                <span class="desc">
                    I am a front-end developer with more than 3 years of experience writing React. I'm
                    motivated, result-focused and seeking a successful team-oriented company with opportunity to grow.
                </span>
            </div>
        </div>
        <div class="details">
            
            <div class="section">
                <div class="section__title">Education</div>
                <div class="section__list">
                    <div class="section__list-item">
                        <div class="left">
                            <div class="name">National Taiwan Ocean University</div>
                            <div class="addr">Keelung, Taiwan</div>
                            <div class="duration">Sep 2022 - Jun 2026</div>
                        </div>
                        <div class="right">
                            <div class="name">Undergraduate Student</div>
                            <div class="desc">Did this and that</div>
                        </div>
                    </div>
                </div>

            </div>
            <div class="section">
                <div class="section__title">Projects</div>
                <div class="section__list">
                    <div class="section__list-item">
                        <div class="name">DSP</div>
                        <div class="text">I am a front-end developer with more than 3 years of experience writing Angular. I'm motivated, result-focused and seeking a successful team-oriented company
                            with opportunity to grow.</div>
                    </div>

                    <div class="section__list-item">
                        <div class="name">DSP</div>
                        <div class="text">I am a front-end developer with more than 3 years of experience writing Vue. I'm motivated, result-focused and seeking a successful team-oriented company
                            with opportunity to grow. <a href="/login">link</a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="section">
                <div class="section__title">Skills</div>
                <div class="skills">
                    <div class="skills__item">
                        <div class="left">
                            <div class="name">
                                Javascript
                            </div>
                        </div>
                        <div class="right">
                            <input id="ck1" type="checkbox" checked />

                            <label for="ck1"></label>
                            <input id="ck2" type="checkbox" checked />

                            <label for="ck2"></label>
                            <input id="ck3" type="checkbox"  />

                            <label for="ck3"></label>
                            <input id="ck4" type="checkbox"  />
                            <label for="ck4"></label>
                            <input id="ck5" type="checkbox" />
                            <label for="ck5"></label>

                        </div>
                    </div>

                </div>
                <div class="skills__item">
                    <div class="left">
                        <div class="name">
                            CSS</div>
                    </div>
                    <div class="right">
                        <input id="ck1" type="checkbox" checked />

                        <label for="ck1"></label>
                        <input id="ck2" type="checkbox" checked />

                        <label for="ck2"></label>
                        <input id="ck3" type="checkbox" checked />

                        <label for="ck3"></label>
                        <input id="ck4" type="checkbox" checked/>
                        <label for="ck4"></label>
                        <input id="ck5" type="checkbox" />
                        <label for="ck5"></label>

                    </div>
                </div>

            </div>
            <div class="section">
                <div class="section__title">
                    Interests
                </div>
                <div class="section__list">
                    <div class="section__list-item">
                        Badminton, gaming.
                    </div>
                </div>
            </div>
        </div>
    </div>
    </div>
</body>

</html>
