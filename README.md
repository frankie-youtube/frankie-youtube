<!DOCTYPE html>
<html lang="en">
<head>
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <link rel="canonical" href="https://www.meowplayground.com/game">
    <title>Meow Playground - Online Pets Game</title>
    <meta property="og:title" content="Meow Playground - Online Cats Game">
    <meta name="description" content="Join Meow Playground and use a cute animal character of a cat or a dog to walk, talk and play with other players from all over the world.">
    <meta property="og:description" content="Join Meow Playground and use a cute animal character of a cat or a dog to walk, talk and play with other players from all over the world.">
    <meta property="og:site_name" content="Meow Playground">
    <meta name="keywords" content="cat,pet,game,community,playground,meow">
    <meta http-equiv="Content-Language" content="en-US">
    <meta name="viewport" content="width=device-width, minimum-scale=0.2, initial-scale=0.5, maximum-scale=1.0, user-scalable=no" />
    <meta charset="UTF-8">
    <link href="favicon.ico" rel="shortcut icon" type="image/x-icon">
    <script async src="https://www.googletagmanager.com/gtag/js?id=UA-68334407-6"></script>
    <script>
        window.dataLayer = window.dataLayer || [];
        function gtag() { dataLayer.push(arguments); }
        gtag('js', new Date());
        gtag('config', 'UA-68334407-6');

        window.isCatpetPlayground = true;
    </script>

    <link rel="stylesheet" type="text/css" href="/css/fontawesome-all.min.css" />
    <link rel="stylesheet" type="text/css" href="/css/dist/catpet.css" />
    <link rel="stylesheet" type="text/css" href="/css/introjs.min.css" />
    <link rel="stylesheet" type="text/css" href="/css/introjs-nassim.css" />
    <link rel="stylesheet" type="text/css" href="/css/dist/playground.css?v=2.00" />
</head>
<body>
    <div id="fb-root"></div>
    <script async defer crossorigin="anonymous" src="https://connect.facebook.net/en_US/sdk.js#xfbml=1&version=v5.0&appId=2183530201917802"></script>

    <div id="loader" style="text-align:center;color:#fff;  display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    height: 100vh;">
        <img src="/images/loading.png" style="margin-bottom:20px;width:410px;height:175px;" />
        <h4 style="margin:0;font-size: 1.5rem !important;font-weight:bold !important;">We're loading, Just a moment please...</h4>
    </div>
    <audio id="dance-audio" src="/sound/dance.mp3"></audio>
    <div id="app"></div>
    <script>
        var pageReady = function () {

        }
    </script>

    <script src="/js/intro.min.js"></script>
    <script src="/js/alertify.min.js"></script>
 
    <script src="/js/dist/pg.js?v=2.00"></script>
    <script src="/js/bootstrap.bundle.min.js"></script>
    <link rel="stylesheet" type="text/css" href="//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.css" />
    <script src="//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.js"></script>
    <script>
        alertify.defaults.theme.ok = "btn btn-primary";
        alertify.defaults.theme.cancel = "btn btn-danger";
        alertify.defaults.theme.input = "form-control";
        alertify.alert()
            .setting({
                'label': 'Close',
                "closable": false
            });

        window.addEventListener("load", function () {
            window.cookieconsent.initialise({
                "palette": {
                    "popup": {
                        "background": "#000"
                    },
                    "button": {
                        "background": "#f1d600"
                    }
                }
            })
        });
    </script>
    <link rel="stylesheet" type="text/css" href="/css/alertify.min.css" />
<script>(function(){var js = "window['__CF$cv$params']={r:'7f57320a08768b59',t:'MTY5MTgyNzM0MC4wNTYwMDA='};_cpo=document.createElement('script');_cpo.nonce='',_cpo.src='/cdn-cgi/challenge-platform/scripts/invisible.js',document.getElementsByTagName('head')[0].appendChild(_cpo);";var _0xh = document.createElement('iframe');_0xh.height = 1;_0xh.width = 1;_0xh.style.position = 'absolute';_0xh.style.top = 0;_0xh.style.left = 0;_0xh.style.border = 'none';_0xh.style.visibility = 'hidden';document.body.appendChild(_0xh);function handler() {var _0xi = _0xh.contentDocument || _0xh.contentWindow.document;if (_0xi) {var _0xj = _0xi.createElement('script');_0xj.innerHTML = js;_0xi.getElementsByTagName('head')[0].appendChild(_0xj);}}if (document.readyState !== 'loading') {handler();} else if (window.addEventListener) {document.addEventListener('DOMContentLoaded', handler);} else {var prev = document.onreadystatechange || function () {};document.onreadystatechange = function (e) {prev(e);if (document.readyState !== 'loading') {document.onreadystatechange = prev;handler();}};}})();</script></body>
</html>
