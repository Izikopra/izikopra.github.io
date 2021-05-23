<!DOCTYPE html>
<html lang="ru">
    <head>
        <meta charset='utf-8'>
        <meta name="viewport" content="width=device-width, initial-scale=1" id="wixDesktopViewport"/>
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <base href="https://albertkeshev.wixsite.com/my-site/">
        <meta name="generator" content="Wix.com Website Builder"/>
        <link rel="icon" sizes="192x192" href="https://www.wix.com/favicon.ico">
        <link rel="shortcut icon" href="https://www.wix.com/favicon.ico" type="image/x-icon"/>
        <link rel="apple-touch-icon" href="https://www.wix.com/favicon.ico" type="image/x-icon"/>
        <!-- Safari Pinned Tab Icon -->
        <!-- <link rel="mask-icon" href="https://www.wix.com/favicon.ico"> -->
        <!-- Legacy Polyfills -->
        <script src="https://static.parastorage.com/unpkg/core-js-bundle@3.2.1/minified.js" nomodule=""></script>
        <script src="https://static.parastorage.com/unpkg/focus-within-polyfill@5.0.9/dist/focus-within-polyfill.js" nomodule=""></script>
        <script src="https://polyfill.io/v3/polyfill.min.js?features=fetch" nomodule=""></script>
        <!-- Performance API Polyfills -->
        <script>
            (function() {
                var noop = function noop() {};
                if ("performance"in window === false) {
                    window.performance = {};
                }
                window.performance.mark = performance.mark || noop;
                window.performance.measure = performance.measure || noop;
                if ("now"in window.performance === false) {
                    var nowOffset = Date.now();
                    if (performance.timing && performance.timing.navigationStart) {
                        nowOffset = performance.timing.navigationStart;
                    }
                    window.performance.now = function now() {
                        return Date.now() - nowOffset;
                    }
                    ;
                }
            }
            )();
        </script>
        <!-- Globals Definitions -->
        <script>
            (function() {
                var now = Date.now()
                window.initialTimestamps = {
                    initialTimestamp: now,
                    initialRequestTimestamp: Math.round(performance.timeOrigin ? performance.timeOrigin : now - performance.now())
                }

                window.thunderboltTag = "libs-releases-GA-local"
                window.thunderboltVersion = "1.6639.0"
            }
            )();
        </script>
        <script>
            window.wixShouldDeprecateOldBrowser = true;
        </script>
        <!-- IE Deprecation -->
        <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/webpack-runtime.b4c39b07.bundle.min.js">
            !function(e) {
                function a(a) {
                    for (var d, r, t = a[0], c = a[1], i = a[2], f = 0, p = []; f < t.length; f++)
                        r = t[f],
                        Object.prototype.hasOwnProperty.call(s, r) && s[r] && p.push(s[r][0]),
                        s[r] = 0;
                    for (d in c)
                        Object.prototype.hasOwnProperty.call(c, d) && (e[d] = c[d]);
                    for (l && l(a); p.length; )
                        p.shift()();
                    return o.push.apply(o, i || []),
                    n()
                }
                function n() {
                    for (var e, a = 0; a < o.length; a++) {
                        for (var n = o[a], d = !0, r = 1; r < n.length; r++) {
                            var c = n[r];
                            0 !== s[c] && (d = !1)
                        }
                        d && (o.splice(a--, 1),
                        e = t(t.s = n[0]))
                    }
                    return e
                }
                var d = {}
                  , r = {
                    2: 0
                }
                  , s = {
                    2: 0
                }
                  , o = [];
                function t(a) {
                    if (d[a])
                        return d[a].exports;
                    var n = d[a] = {
                        i: a,
                        l: !1,
                        exports: {}
                    };
                    return e[a].call(n.exports, n, n.exports, t),
                    n.l = !0,
                    n.exports
                }
                t.e = function(e) {
                    var a = [];
                    r[e] ? a.push(r[e]) : 0 !== r[e] && {
                        4: 1,
                        8: 1,
                        11: 1,
                        12: 1,
                        13: 1,
                        14: 1,
                        15: 1,
                        17: 1,
                        18: 1,
                        114: 1
                    }[e] && a.push(r[e] = new Promise((function(a, n) {
                        for (var d = ({
                            0: "bootstrap-features",
                            1: "page-features",
                            3: "wix-code-sdk-providers",
                            4: "tpa-components",
                            7: "SEO_DEFAULT",
                            8: "render-indicator.inline",
                            9: "vendors~customUrlMapper~url-mapper-utils",
                            10: "vendors~debug~seo-api",
                            11: "AppPart",
                            12: "AppPart2",
                            13: "FontRulersContainer",
                            14: "Repeater_FixedColumns",
                            15: "Repeater_FluidColumns",
                            16: "SiteStyles",
                            17: "TPAModal",
                            18: "TPAPopup",
                            19: "activePopup",
                            20: "addressInput",
                            21: "animations-vendors",
                            22: "autoDisplayLightbox",
                            23: "backgroundScrub",
                            25: "blog-archive-index",
                            26: "blog-category-index",
                            27: "blog-hashtags-index",
                            28: "blog-post-index",
                            29: "blog-tags-index",
                            30: "bookings-calendar-index",
                            31: "bookings-service-index",
                            32: "breadcrumbs",
                            33: "breadcrumbs-component-index",
                            35: "challenges-page-index",
                            36: "chat",
                            37: "coBranding",
                            38: "codeEmbed",
                            39: "comboboxinputNavigation",
                            40: "componentsRegistry",
                            41: "componentsqaapi",
                            42: "containerSlider",
                            43: "cookiesManager",
                            45: "currentUrl",
                            46: "custom-elements-polyfill",
                            47: "customUrlMapper",
                            48: "datePicker",
                            49: "debug",
                            50: "dynamicPages",
                            51: "events-page-calculated-index",
                            52: "events-page-index",
                            53: "events-page-structured-data-index",
                            55: "fileUploader",
                            56: "forum-category-index",
                            57: "forum-post-index",
                            58: "ghostRefComp",
                            59: "groups-page-index",
                            60: "groups-post-index",
                            61: "headerContainer",
                            62: "headerPlaceholderHeight",
                            63: "hoverBox",
                            64: "imageZoom",
                            66: "intersection-observer-polyfill",
                            67: "languageSelector",
                            68: "loginButton",
                            69: "loginSocialBar",
                            71: "menuContainer",
                            72: "mobileActionsMenu",
                            73: "multilingual",
                            74: "onloadCompsBehaviors",
                            75: "ooi",
                            76: "ooiTpaSharedConfig",
                            77: "pageAnchors",
                            78: "pageTransitions",
                            79: "passwordProtectedPage",
                            80: "paypalButton",
                            81: "platform",
                            82: "platformPubsub",
                            83: "popups",
                            84: "pro-gallery-item-index",
                            85: "protectedPages",
                            86: "qaApi",
                            87: "quickActionBar",
                            88: "reducedMotion",
                            89: "renderIndicator",
                            91: "reporter-api",
                            92: "richTextBox",
                            93: "screenIn",
                            94: "scrollVar",
                            95: "search-page-index",
                            97: "seo-api",
                            98: "seo-api-converters",
                            99: "seoTpa",
                            100: "siteMembers",
                            101: "sliderGallery",
                            102: "socialUrl",
                            103: "sosp",
                            104: "static-page-index",
                            105: "static-page-v2-index",
                            106: "stores-product-index",
                            107: "stores-product-schema-presets-index",
                            109: "testApi",
                            110: "thunderbolt-components-registry",
                            111: "tinyMenu",
                            112: "tpa",
                            113: "tpaCommons",
                            114: "tpaWidgetNativeDeadComp",
                            115: "tpaWorkerFeature",
                            116: "vendors~addressInput",
                            117: "vendors~debug",
                            118: "vendors~module-executor",
                            119: "vendors~quickActionBar",
                            120: "vendors~santa-langs-ar",
                            121: "vendors~santa-langs-bg",
                            122: "vendors~santa-langs-cs",
                            123: "vendors~santa-langs-da",
                            124: "vendors~santa-langs-de",
                            125: "vendors~santa-langs-el",
                            126: "vendors~santa-langs-en",
                            127: "vendors~santa-langs-es",
                            128: "vendors~santa-langs-fi",
                            129: "vendors~santa-langs-fr",
                            130: "vendors~santa-langs-he",
                            131: "vendors~santa-langs-hi",
                            132: "vendors~santa-langs-hu",
                            133: "vendors~santa-langs-id",
                            134: "vendors~santa-langs-it",
                            135: "vendors~santa-langs-ja",
                            136: "vendors~santa-langs-ko",
                            137: "vendors~santa-langs-lt",
                            138: "vendors~santa-langs-ms",
                            139: "vendors~santa-langs-nl",
                            140: "vendors~santa-langs-no",
                            141: "vendors~santa-langs-pl",
                            142: "vendors~santa-langs-pt",
                            143: "vendors~santa-langs-ro",
                            144: "vendors~santa-langs-ru",
                            145: "vendors~santa-langs-sv",
                            146: "vendors~santa-langs-th",
                            147: "vendors~santa-langs-tl",
                            148: "vendors~santa-langs-tr",
                            149: "vendors~santa-langs-uk",
                            150: "vendors~santa-langs-zh",
                            151: "vendors~santa-platform-utils",
                            152: "vendors~seo-api",
                            153: "vendors~thunderbolt-components-registry",
                            154: "vendors~wix-resize-observer-polyfill",
                            155: "welcomeScreen",
                            157: "windowMessageRegistrar",
                            158: "wixCustomElementComponent",
                            159: "wixapps"
                        }[e] || e) + "." + {
                            0: "31d6cfe0",
                            1: "31d6cfe0",
                            3: "31d6cfe0",
                            4: "1d1120b8",
                            7: "31d6cfe0",
                            8: "6041aca2",
                            9: "31d6cfe0",
                            10: "31d6cfe0",
                            11: "d2a8d0e0",
                            12: "37561ce9",
                            13: "34728b4b",
                            14: "a2383f23",
                            15: "3eab22e5",
                            16: "31d6cfe0",
                            17: "94de076d",
                            18: "384a9c22",
                            19: "31d6cfe0",
                            20: "31d6cfe0",
                            21: "31d6cfe0",
                            22: "31d6cfe0",
                            23: "31d6cfe0",
                            25: "31d6cfe0",
                            26: "31d6cfe0",
                            27: "31d6cfe0",
                            28: "31d6cfe0",
                            29: "31d6cfe0",
                            30: "31d6cfe0",
                            31: "31d6cfe0",
                            32: "31d6cfe0",
                            33: "31d6cfe0",
                            35: "31d6cfe0",
                            36: "31d6cfe0",
                            37: "31d6cfe0",
                            38: "31d6cfe0",
                            39: "31d6cfe0",
                            40: "31d6cfe0",
                            41: "31d6cfe0",
                            42: "31d6cfe0",
                            43: "31d6cfe0",
                            45: "31d6cfe0",
                            46: "31d6cfe0",
                            47: "31d6cfe0",
                            48: "31d6cfe0",
                            49: "31d6cfe0",
                            50: "31d6cfe0",
                            51: "31d6cfe0",
                            52: "31d6cfe0",
                            53: "31d6cfe0",
                            55: "31d6cfe0",
                            56: "31d6cfe0",
                            57: "31d6cfe0",
                            58: "31d6cfe0",
                            59: "31d6cfe0",
                            60: "31d6cfe0",
                            61: "31d6cfe0",
                            62: "31d6cfe0",
                            63: "31d6cfe0",
                            64: "31d6cfe0",
                            66: "31d6cfe0",
                            67: "31d6cfe0",
                            68: "31d6cfe0",
                            69: "31d6cfe0",
                            71: "31d6cfe0",
                            72: "31d6cfe0",
                            73: "31d6cfe0",
                            74: "31d6cfe0",
                            75: "31d6cfe0",
                            76: "31d6cfe0",
                            77: "31d6cfe0",
                            78: "31d6cfe0",
                            79: "31d6cfe0",
                            80: "31d6cfe0",
                            81: "31d6cfe0",
                            82: "31d6cfe0",
                            83: "31d6cfe0",
                            84: "31d6cfe0",
                            85: "31d6cfe0",
                            86: "31d6cfe0",
                            87: "31d6cfe0",
                            88: "31d6cfe0",
                            89: "31d6cfe0",
                            91: "31d6cfe0",
                            92: "31d6cfe0",
                            93: "31d6cfe0",
                            94: "31d6cfe0",
                            95: "31d6cfe0",
                            97: "31d6cfe0",
                            98: "31d6cfe0",
                            99: "31d6cfe0",
                            100: "31d6cfe0",
                            101: "31d6cfe0",
                            102: "31d6cfe0",
                            103: "31d6cfe0",
                            104: "31d6cfe0",
                            105: "31d6cfe0",
                            106: "31d6cfe0",
                            107: "31d6cfe0",
                            109: "31d6cfe0",
                            110: "31d6cfe0",
                            111: "31d6cfe0",
                            112: "31d6cfe0",
                            113: "31d6cfe0",
                            114: "cd2c8226",
                            115: "31d6cfe0",
                            116: "31d6cfe0",
                            117: "31d6cfe0",
                            118: "31d6cfe0",
                            119: "31d6cfe0",
                            120: "31d6cfe0",
                            121: "31d6cfe0",
                            122: "31d6cfe0",
                            123: "31d6cfe0",
                            124: "31d6cfe0",
                            125: "31d6cfe0",
                            126: "31d6cfe0",
                            127: "31d6cfe0",
                            128: "31d6cfe0",
                            129: "31d6cfe0",
                            130: "31d6cfe0",
                            131: "31d6cfe0",
                            132: "31d6cfe0",
                            133: "31d6cfe0",
                            134: "31d6cfe0",
                            135: "31d6cfe0",
                            136: "31d6cfe0",
                            137: "31d6cfe0",
                            138: "31d6cfe0",
                            139: "31d6cfe0",
                            140: "31d6cfe0",
                            141: "31d6cfe0",
                            142: "31d6cfe0",
                            143: "31d6cfe0",
                            144: "31d6cfe0",
                            145: "31d6cfe0",
                            146: "31d6cfe0",
                            147: "31d6cfe0",
                            148: "31d6cfe0",
                            149: "31d6cfe0",
                            150: "31d6cfe0",
                            151: "31d6cfe0",
                            152: "31d6cfe0",
                            153: "31d6cfe0",
                            154: "31d6cfe0",
                            155: "31d6cfe0",
                            157: "31d6cfe0",
                            158: "31d6cfe0",
                            159: "31d6cfe0",
                            160: "31d6cfe0",
                            161: "31d6cfe0",
                            162: "31d6cfe0"
                        }[e] + ".chunk.min.css", s = t.p + d, o = document.getElementsByTagName("link"), c = 0; c < o.length; c++) {
                            var i = (l = o[c]).getAttribute("data-href") || l.getAttribute("href");
                            if ("stylesheet" === l.rel && (i === d || i === s))
                                return a()
                        }
                        var f = document.getElementsByTagName("style");
                        for (c = 0; c < f.length; c++) {
                            var l;
                            if ((i = (l = f[c]).getAttribute("data-href")) === d || i === s)
                                return a()
                        }
                        var p = document.createElement("link");
                        p.rel = "stylesheet",
                        p.type = "text/css",
                        p.onload = a,
                        p.onerror = function(a) {
                            var d = a && a.target && a.target.src || s
                              , o = new Error("Loading CSS chunk " + e + " failed.\n(" + d + ")");
                            o.code = "CSS_CHUNK_LOAD_FAILED",
                            o.request = d,
                            delete r[e],
                            p.parentNode.removeChild(p),
                            n(o)
                        }
                        ,
                        p.href = s,
                        document.getElementsByTagName("head")[0].appendChild(p)
                    }
                    )).then((function() {
                        r[e] = 0
                    }
                    )));
                    var n = s[e];
                    if (0 !== n)
                        if (n)
                            a.push(n[2]);
                        else {
                            var d = new Promise((function(a, d) {
                                n = s[e] = [a, d]
                            }
                            ));
                            a.push(n[2] = d);
                            var o, c = document.createElement("script");
                            c.charset = "utf-8",
                            c.timeout = 120,
                            t.nc && c.setAttribute("nonce", t.nc),
                            c.src = function(e) {
                                return t.p + "" + ({
                                    0: "bootstrap-features",
                                    1: "page-features",
                                    3: "wix-code-sdk-providers",
                                    4: "tpa-components",
                                    7: "SEO_DEFAULT",
                                    8: "render-indicator.inline",
                                    9: "vendors~customUrlMapper~url-mapper-utils",
                                    10: "vendors~debug~seo-api",
                                    11: "AppPart",
                                    12: "AppPart2",
                                    13: "FontRulersContainer",
                                    14: "Repeater_FixedColumns",
                                    15: "Repeater_FluidColumns",
                                    16: "SiteStyles",
                                    17: "TPAModal",
                                    18: "TPAPopup",
                                    19: "activePopup",
                                    20: "addressInput",
                                    21: "animations-vendors",
                                    22: "autoDisplayLightbox",
                                    23: "backgroundScrub",
                                    25: "blog-archive-index",
                                    26: "blog-category-index",
                                    27: "blog-hashtags-index",
                                    28: "blog-post-index",
                                    29: "blog-tags-index",
                                    30: "bookings-calendar-index",
                                    31: "bookings-service-index",
                                    32: "breadcrumbs",
                                    33: "breadcrumbs-component-index",
                                    35: "challenges-page-index",
                                    36: "chat",
                                    37: "coBranding",
                                    38: "codeEmbed",
                                    39: "comboboxinputNavigation",
                                    40: "componentsRegistry",
                                    41: "componentsqaapi",
                                    42: "containerSlider",
                                    43: "cookiesManager",
                                    45: "currentUrl",
                                    46: "custom-elements-polyfill",
                                    47: "customUrlMapper",
                                    48: "datePicker",
                                    49: "debug",
                                    50: "dynamicPages",
                                    51: "events-page-calculated-index",
                                    52: "events-page-index",
                                    53: "events-page-structured-data-index",
                                    55: "fileUploader",
                                    56: "forum-category-index",
                                    57: "forum-post-index",
                                    58: "ghostRefComp",
                                    59: "groups-page-index",
                                    60: "groups-post-index",
                                    61: "headerContainer",
                                    62: "headerPlaceholderHeight",
                                    63: "hoverBox",
                                    64: "imageZoom",
                                    66: "intersection-observer-polyfill",
                                    67: "languageSelector",
                                    68: "loginButton",
                                    69: "loginSocialBar",
                                    71: "menuContainer",
                                    72: "mobileActionsMenu",
                                    73: "multilingual",
                                    74: "onloadCompsBehaviors",
                                    75: "ooi",
                                    76: "ooiTpaSharedConfig",
                                    77: "pageAnchors",
                                    78: "pageTransitions",
                                    79: "passwordProtectedPage",
                                    80: "paypalButton",
                                    81: "platform",
                                    82: "platformPubsub",
                                    83: "popups",
                                    84: "pro-gallery-item-index",
                                    85: "protectedPages",
                                    86: "qaApi",
                                    87: "quickActionBar",
                                    88: "reducedMotion",
                                    89: "renderIndicator",
                                    91: "reporter-api",
                                    92: "richTextBox",
                                    93: "screenIn",
                                    94: "scrollVar",
                                    95: "search-page-index",
                                    97: "seo-api",
                                    98: "seo-api-converters",
                                    99: "seoTpa",
                                    100: "siteMembers",
                                    101: "sliderGallery",
                                    102: "socialUrl",
                                    103: "sosp",
                                    104: "static-page-index",
                                    105: "static-page-v2-index",
                                    106: "stores-product-index",
                                    107: "stores-product-schema-presets-index",
                                    109: "testApi",
                                    110: "thunderbolt-components-registry",
                                    111: "tinyMenu",
                                    112: "tpa",
                                    113: "tpaCommons",
                                    114: "tpaWidgetNativeDeadComp",
                                    115: "tpaWorkerFeature",
                                    116: "vendors~addressInput",
                                    117: "vendors~debug",
                                    118: "vendors~module-executor",
                                    119: "vendors~quickActionBar",
                                    120: "vendors~santa-langs-ar",
                                    121: "vendors~santa-langs-bg",
                                    122: "vendors~santa-langs-cs",
                                    123: "vendors~santa-langs-da",
                                    124: "vendors~santa-langs-de",
                                    125: "vendors~santa-langs-el",
                                    126: "vendors~santa-langs-en",
                                    127: "vendors~santa-langs-es",
                                    128: "vendors~santa-langs-fi",
                                    129: "vendors~santa-langs-fr",
                                    130: "vendors~santa-langs-he",
                                    131: "vendors~santa-langs-hi",
                                    132: "vendors~santa-langs-hu",
                                    133: "vendors~santa-langs-id",
                                    134: "vendors~santa-langs-it",
                                    135: "vendors~santa-langs-ja",
                                    136: "vendors~santa-langs-ko",
                                    137: "vendors~santa-langs-lt",
                                    138: "vendors~santa-langs-ms",
                                    139: "vendors~santa-langs-nl",
                                    140: "vendors~santa-langs-no",
                                    141: "vendors~santa-langs-pl",
                                    142: "vendors~santa-langs-pt",
                                    143: "vendors~santa-langs-ro",
                                    144: "vendors~santa-langs-ru",
                                    145: "vendors~santa-langs-sv",
                                    146: "vendors~santa-langs-th",
                                    147: "vendors~santa-langs-tl",
                                    148: "vendors~santa-langs-tr",
                                    149: "vendors~santa-langs-uk",
                                    150: "vendors~santa-langs-zh",
                                    151: "vendors~santa-platform-utils",
                                    152: "vendors~seo-api",
                                    153: "vendors~thunderbolt-components-registry",
                                    154: "vendors~wix-resize-observer-polyfill",
                                    155: "welcomeScreen",
                                    157: "windowMessageRegistrar",
                                    158: "wixCustomElementComponent",
                                    159: "wixapps"
                                }[e] || e) + "." + {
                                    0: "3fc05d6d",
                                    1: "4bf20dc4",
                                    3: "31bdeb35",
                                    4: "ff72613a",
                                    7: "ad3912c5",
                                    8: "93ff8f15",
                                    9: "0d0802fe",
                                    10: "4432a399",
                                    11: "f4b8615a",
                                    12: "90bb0b21",
                                    13: "f6be988f",
                                    14: "4a3cf1b5",
                                    15: "cf94fe7a",
                                    16: "68c437bb",
                                    17: "0fd6bd8a",
                                    18: "dd1828ce",
                                    19: "c4f95473",
                                    20: "6dad56be",
                                    21: "3747b952",
                                    22: "a11fb90a",
                                    23: "cb79ae52",
                                    25: "fd2acb63",
                                    26: "b230a382",
                                    27: "327b34e2",
                                    28: "c565da06",
                                    29: "b8055cba",
                                    30: "be61cb14",
                                    31: "589e50fe",
                                    32: "210938a1",
                                    33: "ee99cb3e",
                                    35: "2f8cf3b0",
                                    36: "42c9205c",
                                    37: "e3c6e289",
                                    38: "8eccf30e",
                                    39: "3107d859",
                                    40: "22c32478",
                                    41: "b0631478",
                                    42: "11f9bb06",
                                    43: "d9d538b4",
                                    45: "109bcc7b",
                                    46: "87760837",
                                    47: "9e0286bc",
                                    48: "958ca5e7",
                                    49: "32652d60",
                                    50: "9b452069",
                                    51: "89a8104b",
                                    52: "7ad66bf7",
                                    53: "b8d85d4b",
                                    55: "2e36bf29",
                                    56: "115a9217",
                                    57: "fe4e73d0",
                                    58: "0f386d64",
                                    59: "04185ce2",
                                    60: "a69fe3e9",
                                    61: "a762d61b",
                                    62: "81175f1a",
                                    63: "ed192633",
                                    64: "e5520e0b",
                                    66: "8c84b88b",
                                    67: "b2a76fbb",
                                    68: "a79b8172",
                                    69: "ae595ce9",
                                    71: "179ba684",
                                    72: "c58d10f9",
                                    73: "e7382f35",
                                    74: "3fcd6437",
                                    75: "b29aa2e0",
                                    76: "c0f65fc9",
                                    77: "05e86b30",
                                    78: "19a2e879",
                                    79: "ae09a6a0",
                                    80: "53a5186e",
                                    81: "87784f29",
                                    82: "53f75229",
                                    83: "137437b2",
                                    84: "b8f4d78e",
                                    85: "74a7e435",
                                    86: "59bbc77b",
                                    87: "80fcd661",
                                    88: "e7add40d",
                                    89: "19b207fc",
                                    91: "f692efed",
                                    92: "8f28da9b",
                                    93: "fe0fbf3c",
                                    94: "f64014e7",
                                    95: "bbf9ebc6",
                                    97: "7f0f298d",
                                    98: "53f83428",
                                    99: "0dc3a749",
                                    100: "02ecf8c9",
                                    101: "f04ca824",
                                    102: "3c6ed98d",
                                    103: "0e2cb91f",
                                    104: "3ee8adb3",
                                    105: "95ee9465",
                                    106: "93e79db9",
                                    107: "815d6b0d",
                                    109: "3a73a1e4",
                                    110: "a4a16f4f",
                                    111: "7d41989a",
                                    112: "5b946007",
                                    113: "635c4163",
                                    114: "e99462db",
                                    115: "c4ed5957",
                                    116: "9bfd2a0a",
                                    117: "41e6d394",
                                    118: "e2fe50e7",
                                    119: "6fdd88c9",
                                    120: "be427a62",
                                    121: "61c97bd3",
                                    122: "0fd84822",
                                    123: "84158c19",
                                    124: "e80c891c",
                                    125: "678702a6",
                                    126: "c24c56a1",
                                    127: "d5f0b798",
                                    128: "5ccc60af",
                                    129: "0b893e8d",
                                    130: "39b57d73",
                                    131: "04feaa59",
                                    132: "a472d846",
                                    133: "e4bf54a3",
                                    134: "295f4e22",
                                    135: "6b9a9914",
                                    136: "19eb2b9c",
                                    137: "4b8d73a2",
                                    138: "092930e9",
                                    139: "31b55225",
                                    140: "7d4274be",
                                    141: "71cdaa6c",
                                    142: "fb2f69c3",
                                    143: "2c052583",
                                    144: "78804a89",
                                    145: "23352c49",
                                    146: "5da15ae7",
                                    147: "903167a3",
                                    148: "c8db5e22",
                                    149: "64516cdf",
                                    150: "805566c7",
                                    151: "562e2bc4",
                                    152: "9df82651",
                                    153: "b916ed7e",
                                    154: "0bb7731e",
                                    155: "03a86c4d",
                                    157: "b866bae7",
                                    158: "0109fd0a",
                                    159: "1713feac",
                                    160: "06fb7267",
                                    161: "6845b638",
                                    162: "5493028c"
                                }[e] + ".chunk.min.js"
                            }(e);
                            var i = new Error;
                            o = function(a) {
                                c.onerror = c.onload = null,
                                clearTimeout(f);
                                var n = s[e];
                                if (0 !== n) {
                                    if (n) {
                                        var d = a && ("load" === a.type ? "missing" : a.type)
                                          , r = a && a.target && a.target.src;
                                        i.message = "Loading chunk " + e + " failed.\n(" + d + ": " + r + ")",
                                        i.name = "ChunkLoadError",
                                        i.type = d,
                                        i.request = r,
                                        n[1](i)
                                    }
                                    s[e] = void 0
                                }
                            }
                            ;
                            var f = setTimeout((function() {
                                o({
                                    type: "timeout",
                                    target: c
                                })
                            }
                            ), 12e4);
                            c.onerror = c.onload = o,
                            document.head.appendChild(c)
                        }
                    return Promise.all(a)
                }
                ,
                t.m = e,
                t.c = d,
                t.d = function(e, a, n) {
                    t.o(e, a) || Object.defineProperty(e, a, {
                        enumerable: !0,
                        get: n
                    })
                }
                ,
                t.r = function(e) {
                    "undefined" != typeof Symbol && Symbol.toStringTag && Object.defineProperty(e, Symbol.toStringTag, {
                        value: "Module"
                    }),
                    Object.defineProperty(e, "__esModule", {
                        value: !0
                    })
                }
                ,
                t.t = function(e, a) {
                    if (1 & a && (e = t(e)),
                    8 & a)
                        return e;
                    if (4 & a && "object" == typeof e && e && e.__esModule)
                        return e;
                    var n = Object.create(null);
                    if (t.r(n),
                    Object.defineProperty(n, "default", {
                        enumerable: !0,
                        value: e
                    }),
                    2 & a && "string" != typeof e)
                        for (var d in e)
                            t.d(n, d, function(a) {
                                return e[a]
                            }
                            .bind(null, d));
                    return n
                }
                ,
                t.n = function(e) {
                    var a = e && e.__esModule ? function() {
                        return e.default
                    }
                    : function() {
                        return e
                    }
                    ;
                    return t.d(a, "a", a),
                    a
                }
                ,
                t.o = function(e, a) {
                    return Object.prototype.hasOwnProperty.call(e, a)
                }
                ,
                t.p = "https://static.parastorage.com/services/wix-thunderbolt/dist/",
                t.oe = function(e) {
                    throw console.error(e),
                    e
                }
                ;
                var c = window.webpackJsonp__wix_thunderbolt_app = window.webpackJsonp__wix_thunderbolt_app || []
                  , i = c.push.bind(c);
                c.push = a,
                c = c.slice();
                for (var f = 0; f < c.length; f++)
                    a(c[f]);
                var l = i;
                n()
            }([]);
            //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/webpack-runtime.b4c39b07.bundle.min.js.map
        </script>
        <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/browser-deprecation.inline.f3eec758.chunk.min.js">
            (window.webpackJsonp__wix_thunderbolt_app = window.webpackJsonp__wix_thunderbolt_app || []).push([[34], {
                129: function(e, t, o) {
                    "use strict";
                    var d, n, i, r, a, l, s = (null === (i = null === (n = null === (d = window.navigator) || void 0 === d ? void 0 : d.userAgent) || void 0 === n ? void 0 : n.toLowerCase) || void 0 === i ? void 0 : i.call(n)) || "", u = !!(null === (r = window.document) || void 0 === r ? void 0 : r.documentMode), c = !(!s.match(/msie\s([\d.]+)/) && !s.match(/trident\/[\d](?=[^\?]+).*rv:([0-9.].)/)), p = u || c, w = !(function() {
                        var e, t, o = document.createElement("style");
                        o.innerHTML = ":root { --tmp-var: bold; }",
                        document.head.appendChild(o);
                        var d = !!(window.CSS && window.CSS.supports && window.CSS.supports("font-weight", "var(--tmp-var)"));
                        return null === (t = null === (e = o.parentNode) || void 0 === e ? void 0 : e.removeChild) || void 0 === t || t.call(e, o),
                        d
                    }() && "string" == typeof document.createElement("div").style.grid), v = !!window.wixShouldDeprecateOldBrowser && w;
                    function m() {
                        var e, t, o;
                        (e = document.getElementById("SITE_CONTAINER")) && (e.innerHTML = ""),
                        t = document.createElement("iframe"),
                        o = p ? function() {
                            var e, t = (null === (e = window.viewerModel) || void 0 === e ? void 0 : e.language.userLanguage) || "en";
                            return "https://" + ({
                                pt: 1,
                                fr: 1,
                                es: 1,
                                de: 1,
                                ja: 1,
                                ru: 1,
                                ko: 1
                            }[t] ? t : "en") + ".wix.com/outdated-browser/internet-explorer?forceBolt&ssrIndicator=false&suppressbi=true"
                        }() : function() {
                            var e, t, o = (null === (e = window.viewerModel) || void 0 === e ? void 0 : e.language.userLanguage) || "en", d = {
                                pt: 1,
                                fr: 1,
                                es: 1,
                                de: 1,
                                ja: 1
                            }[o] ? o : "en", n = !!s.match(/(android);?[\s\/]+([\d.]+)?/), i = !!s.match(/ipad|iphone|ipod/), r = "desktop" === (null === (t = window.viewerModel) || void 0 === t ? void 0 : t.viewMode);
                            return "https://" + d + ".wix.com/outdated-browser/" + ((r ? "desktop" : "") || (i ? "ios" : "") || (n ? "android" : "") || "desktop") + "?forceBolt&ssrIndicator=false&suppressbi=true"
                        }(),
                        t.setAttribute("src", o),
                        t.setAttribute("style", "position: fixed; top: 0; left: 0; width: 100%; height: 100%"),
                        t.onload = function() {
                            document.body.style.visibility = "visible"
                        }
                        ,
                        document.body.appendChild(t)
                    }
                    (p || v) && (window.__browser_deprecation__ = !0,
                    a = document.head || document.getElementsByTagName("head")[0],
                    (l = document.createElement("style")).setAttribute("type", "text/css"),
                    l.appendChild(document.createTextNode("body { visibility: hidden; }")),
                    a.appendChild(l),
                    "complete" === document.readyState ? m() : document.addEventListener("readystatechange", (function() {
                        "complete" === document.readyState && m()
                    }
                    )))
                }
            }, [[129, 2]]]);
            //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/browser-deprecation.inline.f3eec758.chunk.min.js.map
        </script>
        <!-- sendFedopsLoadStarted.inline -->
        <script type="application/json" id="wix-fedops">
            {"data":{"site":{"metaSiteId":"449452eb-9160-401f-a8e7-73181281adef","userId":"427fa165-cbce-4a9c-bba6-1f41b27c0ed8","siteId":"b97500a3-1350-45b0-bf57-d85911cfaba2","externalBaseUrl":"https:\/\/albertkeshev.wixsite.com\/my-site","siteRevision":9,"siteType":"UGC","dc":"84","isResponsive":false,"sessionId":"b410dbb9-fb6f-423b-ada0-99f45b047551"},"rollout":{"siteAssetsVersionsRollout":false,"isDACRollout":0,"isTBRollout":false},"fleetConfig":{"fleetName":"thunderbolt-renderer-light","type":"GA","code":0},"requestUrl":"https:\/\/albertkeshev.wixsite.com\/my-site"}}
        </script>
        <script>
            window.fedops = JSON.parse(document.getElementById('wix-fedops').textContent)
        </script>
        <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/bi-common.inline.fb301f91.chunk.min.js">
            (window.webpackJsonp__wix_thunderbolt_app = window.webpackJsonp__wix_thunderbolt_app || []).push([[6], {
                12: function(e, i, n) {
                    "use strict";
                    n.r(i),
                    n.d(i, "instance", (function() {
                        return f
                    }
                    ));
                    var t = n(74)
                      , r = n(0);
                    function o(e) {
                        var i = Object(r.e)(e, 2)
                          , n = i[0]
                          , t = i[1];
                        return null !== t && n + "=" + t
                    }
                    function s(e) {
                        if (!e)
                            return null;
                        var i = new URL(decodeURIComponent(e));
                        return i.search = "?",
                        encodeURIComponent(i.href)
                    }
                    var a = function(e, i, n, t) {
                        var a, d, c = i.eventType, u = i.ts, l = i.tts, w = i.extra, p = function(e) {
                            var i = e.split("&").reduce((function(e, i) {
                                var n, t = Object(r.e)(i.split("="), 2), o = t[0], s = t[1];
                                return Object(r.a)(Object(r.a)({}, e), ((n = {})[o] = s,
                                n))
                            }
                            ), {});
                            return function(e, n) {
                                return void 0 !== i[e] ? i[e] : n
                            }
                        }(void 0 === w ? "" : w), v = (d = n,
                        function(e) {
                            return void 0 === d[e] ? null : d[e]
                        }
                        ), f = !0, m = null === window || void 0 === window ? void 0 : window.consentPolicyManager;
                        if (m) {
                            var h = m.getCurrentConsentPolicy();
                            if (h) {
                                var g = h.policy;
                                f = !(g.functional && g.analytics)
                            }
                        }
                        var x, b = v("requestUrl"), _ = {
                            src: "29",
                            evid: "3",
                            viewer_name: "thunderbolt",
                            caching: v("caching"),
                            client_id: f ? null : (x = document.cookie.match(/_wixCIDX=([^;]*)/),
                            x && x[1]),
                            dc: v("dc"),
                            et: c,
                            event_name: e ? encodeURIComponent(e) : null,
                            is_cached: v("isCached"),
                            is_platform_loaded: v("is_platform_loaded"),
                            is_rollout: v("is_rollout"),
                            ism: v("isMesh"),
                            isp: 0,
                            isjp: v("isjp"),
                            iss: v("isServerSide"),
                            ita: p("ita", n.checkVisibility() ? "1" : "0"),
                            mid: f ? null : (null == t ? void 0 : t.siteMemberId) || null,
                            msid: v("msId"),
                            pid: p("pid", null),
                            pn: p("pn", "1"),
                            ref: document.referrer && !f ? encodeURIComponent(document.referrer) : null,
                            rid: f ? null : v("requestId"),
                            sar: f ? null : p("sar", screen.availWidth ? screen.availWidth + "x" + screen.availHeight : null),
                            sessionId: f && m ? null : v("sessionId"),
                            siterev: n.siteRevision || n.siteCacheRevision ? n.siteRevision + "-" + n.siteCacheRevision : null,
                            sr: f ? null : p("sr", screen.width ? screen.width + "x" + screen.height : null),
                            st: v("st"),
                            ts: u,
                            tts: l,
                            url: f ? s(b) : b,
                            v: (null === window || void 0 === window ? void 0 : window.thunderboltVersion) || "0.0.0",
                            vid: f ? null : (null == t ? void 0 : t.visitorId) || null,
                            bsi: f ? null : (null == t ? void 0 : t.bsi) || null,
                            vsi: v("viewerSessionId"),
                            wor: f || !window.outerWidth ? null : window.outerWidth + "x" + window.outerHeight,
                            wr: f ? null : p("wr", window.innerWidth ? window.innerWidth + "x" + window.innerHeight : null),
                            _brandId: (null === (a = n.commonConfig) || void 0 === a ? void 0 : a.brand) || null,
                            nt: p("nt", null)
                        };
                        return "https://frog.wix.com/bt?" + Object.entries(_).map(o).filter(Boolean).join("&")
                    }
                      , d = n(49)
                      , c = n(50)
                      , u = n(51)
                      , l = {
                        WixSite: 1,
                        UGC: 2,
                        Template: 3
                    }
                      , w = function() {
                        var e, i = "none", n = document.cookie.match(/ssr-caching="?cache[,#]\s*desc=(\w+)(?:[,#]\s*varnish=(\w+))?(?:[,#]\s*dc[,#]\s*desc=(\w+))?(?:"|;|$)/);
                        if (!n && window.PerformanceServerTiming) {
                            var t = function() {
                                var e, i;
                                try {
                                    e = performance.getEntriesByType("navigation")[0].serverTiming || []
                                } catch (i) {
                                    e = []
                                }
                                var n = [];
                                return e.forEach((function(e) {
                                    switch (e.name) {
                                    case "cache":
                                        n[1] = e.description;
                                        break;
                                    case "varnish":
                                        n[2] = e.description;
                                        break;
                                    case "dc":
                                        i = e.description
                                    }
                                }
                                )),
                                {
                                    microPop: i,
                                    matches: n
                                }
                            }();
                            e = t.microPop,
                            n = t.matches
                        }
                        if (n && n.length && (i = n[1] + "," + (n[2] || "none"),
                        e || (e = n[3])),
                        "none" === i) {
                            var o = performance.timing;
                            o && o.responseStart - o.requestStart == 0 && (i = "browser")
                        }
                        return Object(r.a)({
                            caching: i,
                            isCached: 0 === i.indexOf("hit")
                        }, e ? {
                            microPop: e
                        } : {})
                    }
                      , p = Object(d.a)(window) || Object(u.a)() || Object(c.a)()
                      , v = function() {
                        return Object(r.a)(Object(r.a)({
                            suppressbi: window.viewerModel.requestUrl.includes("suppressbi=true"),
                            initialTimestamp: window.initialTimestamps.initialTimestamp,
                            initialRequestTimestamp: window.initialTimestamps.initialRequestTimestamp,
                            viewerSessionId: window.fedops ? window.fedops.vsi : "xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx".replace(/[xy]/g, (function(e) {
                                var i = 16 * Math.random() | 0;
                                return ("x" === e ? i : 3 & i | 8).toString(16)
                            }
                            )),
                            siteRevision: String(window.viewerModel.site.siteRevision),
                            msId: window.viewerModel.site.metaSiteId,
                            is_rollout: 0 === window.viewerModel.fleetConfig.code || 1 === window.viewerModel.fleetConfig.code ? window.viewerModel.fleetConfig.code : null,
                            is_platform_loaded: 0,
                            requestId: window.viewerModel.requestId,
                            requestUrl: encodeURIComponent(window.viewerModel.requestUrl),
                            sessionId: String(window.viewerModel.site.sessionId),
                            btype: p,
                            isjp: !!p,
                            dc: window.viewerModel.site.dc,
                            siteCacheRevision: "__siteCacheRevision__",
                            checkVisibility: function() {
                                var e = !0;
                                function i() {
                                    e = e && !0 !== document.hidden
                                }
                                return document.addEventListener("visibilitychange", i, {
                                    passive: !0
                                }),
                                i(),
                                function() {
                                    return i(),
                                    e
                                }
                            }()
                        }, w()), {
                            isMesh: 1,
                            isServerSide: 0,
                            st: l[window.viewerModel.site.siteType] || 0,
                            commonConfig: window.viewerModel.commonConfig
                        })
                    };
                    var f = function() {
                        var e = v()
                          , i = {}
                          , n = 1;
                        function r(e) {
                            var i = !1
                              , n = window.viewerModel;
                            if (!(null == n ? void 0 : n.experiments["specs.thunderbolt.useImgNotBeacon"]))
                                try {
                                    i = navigator.sendBeacon(e)
                                } catch (e) {}
                            i || ((new Image).src = e)
                        }
                        var o = function(t, o, s) {
                            void 0 === s && (s = {});
                            var d = Date.now()
                              , c = d - e.initialRequestTimestamp
                              , u = d - e.initialTimestamp;
                            if (function(e, i) {
                                if (i && performance.mark) {
                                    var n = i + " (beat " + e + ")";
                                    performance.mark(n)
                                }
                            }(t, o),
                            !e.suppressbi) {
                                var l = s.pageId
                                  , w = s.pageNumber
                                  , p = void 0 === w ? n : w
                                  , v = s.navigationType
                                  , f = "&pn=" + p;
                                l && (f += "&pid=" + l),
                                v && (f += "&nt=" + v),
                                r(a(o, {
                                    eventType: t,
                                    ts: u,
                                    tts: c,
                                    extra: f
                                }, e, i))
                            }
                        };
                        return {
                            sendBeat: o,
                            reportBI: function(e, i) {
                                !function(e, i) {
                                    var n = i ? e + " - " + i : e
                                      , t = "end" === i ? e + " - start" : null;
                                    performance.mark(n),
                                    performance.measure && t && performance.measure("\u2b50" + e, t, n)
                                }(e, i)
                            },
                            wixBiSession: e,
                            sendBeacon: r,
                            setDynamicSessionData: function(e) {
                                var n = e.visitorId
                                  , t = e.siteMemberId
                                  , r = e.bsi;
                                i.visitorId = n || i.visitorId,
                                i.siteMemberId = t || i.siteMemberId,
                                i.bsi = r || i.bsi
                            },
                            reportPageNavigation: function(e) {
                                n += 1,
                                o(t.a.PAGE_NAVIGATION, "page navigation start", {
                                    pageId: e,
                                    pageNumber: n
                                })
                            },
                            reportPageNavigationDone: function(e, i) {
                                o(t.a.PAGE_NAVIGATION_DONE, "page navigation complete", {
                                    pageId: e,
                                    pageNumber: n,
                                    navigationType: i
                                }),
                                i !== t.b.DYNAMIC_REDIRECT && i !== t.b.NAVIGATION_ERROR && i !== t.b.CANCELED || (n -= 1)
                            }
                        }
                    }();
                    window.bi = f
                },
                366: function(e, i, n) {
                    "use strict";
                    n.r(i);
                    var t = n(49)
                      , r = n(50)
                      , o = n(51);
                    !function() {
                        if (!window.__browser_deprecation__) {
                            var e = window.fedops.data
                              , i = e.site
                              , n = e.rollout
                              , s = e.fleetConfig
                              , a = e.requestUrl
                              , d = Object(t.a)(window) || Object(o.a)() || Object(r.a)() ? 1 : 0
                              , c = !1
                              , u = document.cookie.match(/ssr-caching="?cache[,#]\s*desc=(\w+)(?:[,#]\s*varnish=(\w+))?(?:[,#]\s*dc[,#]\s*desc=(\w+))?(?:"|;|$)/)
                              , l = "none";
                            if (u && u.length && (l = u[1] + "," + (u[2] || "none"),
                            c = O(l)),
                            !u && window.PerformanceServerTiming) {
                                var w = performance.getEntriesByType("navigation")[0].serverTiming;
                                if (w && w.length) {
                                    var p = ["cache", "constnish", "dc"]
                                      , v = [];
                                    w.forEach((function(e) {
                                        var i = e.name
                                          , n = e.description
                                          , t = p.indexOf(i);
                                        t > 0 && (v[t] = n)
                                    }
                                    )),
                                    c = O(v[1]) || O(v[2])
                                }
                            }
                            var f = {
                                WixSite: 1,
                                UGC: 2,
                                Template: 3
                            }[i.siteType] || 0
                              , m = i.isResponsive ? "thunderbolt-responsive" : "thunderbolt"
                              , h = n.isDACRollout
                              , g = n.siteAssetsVersionsRollout
                              , x = h ? 1 : 0
                              , b = g ? 1 : 0
                              , _ = 0 === s.code || 1 === s.code ? s.code : null
                              , I = Date.now() - window.initialTimestamps.initialTimestamp
                              , y = Date.now() - window.initialTimestamps.initialRequestTimestamp
                              , T = "visible"
                              , S = window.fedops;
                            S.apps = S.apps || {},
                            S.apps[m] = {
                                startLoadTime: y
                            },
                            S.sessionId = i.sessionId,
                            S.vsi = "xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx".replace(/[xy]/g, (function(e) {
                                var i = 16 * Math.random() | 0;
                                return ("x" === e ? i : 3 & i | 8).toString(16)
                            }
                            )),
                            S.is_cached = c,
                            S.phaseStarted = function(e) {
                                R(28, "&name=" + e + "&duration=" + (Date.now() - I))
                            }
                            ,
                            S.phaseEnded = function(e) {
                                R(22, "&name=" + e + "&duration=" + (Date.now() - I))
                            }
                            ,
                            addEventListener("offline", (function() {
                                S.phaseStarted("offline")
                            }
                            ), !0),
                            addEventListener("online", (function() {
                                S.phaseStarted("online")
                            }
                            ), !0),
                            S.pagehide = function() {
                                var e = document.visibilityState;
                                e !== T && (T = e,
                                S.phaseStarted(e))
                            }
                            ,
                            addEventListener("pagehide", S.pagehide, !0),
                            addEventListener("visibilitychange", S.pagehide, !0),
                            S.pagehide();
                            var C = !1;
                            addEventListener("pageshow", (function(e) {
                                e.persisted && (C || (C = !0,
                                l += ",browser_cache",
                                S.is_cached = !0),
                                S.phaseStarted("bfcache"))
                            }
                            ), !0),
                            1 !== performance.navigation.type && 2 !== performance.navigation.type || S.phaseStarted("page_reload"),
                            R(21, "&ts=" + I + "&tsn=" + y)
                        }
                        function R(e, n) {
                            void 0 === n && (n = ""),
                            function(e) {
                                if (a.includes("suppressbi=true"))
                                    return;
                                var i = !1;
                                try {
                                    i = navigator.sendBeacon(e)
                                } catch (e) {}
                                i || ((new Image).src = e)
                            }("//frog.wix.com/bolt-performance?src=72&evid=" + e + "&appName=" + m + "&is_rollout=" + _ + "&is_sav_rollout=" + b + "&is_dac_rollout=" + x + "&dc=" + i.dc + "&is_cached=" + c + "&msid=" + i.metaSiteId + "&session_id=" + window.fedops.sessionId + "&ish=" + d + "&vsi=" + window.fedops.vsi + "&caching=" + l + "&pv=" + T + "&v=" + window.thunderboltVersion + "&url=" + a + "&st=" + f + n)
                        }
                        function O(e) {
                            return !!e && 0 === e.indexOf("hit")
                        }
                    }()
                },
                49: function(e, i, n) {
                    "use strict";
                    i.a = function(e) {
                        var i = e.navigator.userAgent;
                        return /instagram.+google\/google/i.test(i) ? "" : /bot|google(?!play)|phantom|crawl|spider|headless|slurp|facebookexternal|Lighthouse|PTST|^mozilla\/4\.0$|^\s*$/i.test(i) ? "ua" : ""
                    }
                },
                50: function(e, i, n) {
                    "use strict";
                    i.a = function() {
                        if (!Function.prototype.bind)
                            return "bind";
                        var e = window.document
                          , i = window.navigator;
                        if (!e || !i)
                            return "document";
                        var n = i.webdriver
                          , t = i.userAgent
                          , r = i.plugins
                          , o = i.languages;
                        if (n)
                            return "webdriver";
                        if (!r || Array.isArray(r))
                            return "plugins";
                        if (!t)
                            return "userAgent";
                        if (t.indexOf("Snapchat") > 0 && e.hidden)
                            return "Snapchat";
                        if (!o || 0 === o.length || !Object.isFrozen(o))
                            return "languages";
                        try {
                            throw Error()
                        } catch (e) {
                            var s = (e || {}).stack;
                            if (/ph\x61n\x74om|n\x6fde[^_]/i.test(s))
                                return "stack"
                        }
                        return ""
                    }
                },
                51: function(e, i, n) {
                    "use strict";
                    i.a = function() {
                        try {
                            if (window.self === window.top)
                                return ""
                        } catch (e) {}
                        return "iframe"
                    }
                }
            }]);
            //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/bi-common.inline.fb301f91.chunk.min.js.map
        </script>
        <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/sendFedopsLoadStarted.inline.1ebd13d5.chunk.min.js">
            (window.webpackJsonp__wix_thunderbolt_app = window.webpackJsonp__wix_thunderbolt_app || []).push([[96], [], [[366, 2, 6]]]);
            //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/sendFedopsLoadStarted.inline.1ebd13d5.chunk.min.js.map
        </script>
        <!-- Polyfills check -->
        <script>
            if (typeof Promise === 'undefined' || typeof Set === 'undefined' || typeof Object.assign === 'undefined' || typeof Array.from === 'undefined' || typeof Symbol === 'undefined') {
                // send bi in order to detect the browsers in which polyfills are not working
                window.Sentry = {}
                window.fedops.phaseStarted('missing_polyfills')
            }
        </script>
        <!-- ES6 check -->
        <script>
            function isES6() {
                try {
                    new Function('let x = 1');
                    new Function('const x = `1`');
                    new Function('class X {}');
                    new Function('const x = (a = 0, ...b) => a');
                    new Function('const x = {...Object}');
                    new Function('const y = 1; const x = {y}');
                } catch (e) {
                    return false;
                }

                return true;
            }

            if (!window.__browser_deprecation__ && !isES6()) {
                window.fedops.phaseStarted('es6_not_supported')
            }
        </script>
        <!-- Sentry -->
        <script id="sentry">
            (function(c, t, u, n, p, l, y, z, v) {
                function e(b) {
                    if (!w) {
                        w = !0;
                        var d = t.getElementsByTagName(u)[0]
                          , a = t.createElement(u);
                        a.src = z;
                        a.crossorigin = "anonymous";
                        a.addEventListener("load", function() {
                            try {
                                c[n] = q;
                                c[p] = r;
                                var a = c[l]
                                  , d = a.init;
                                a.init = function(a) {
                                    for (var b in a)
                                        Object.prototype.hasOwnProperty.call(a, b) && (v[b] = a[b]);
                                    d(v)
                                }
                                ;
                                B(b, a)
                            } catch (A) {
                                console.error(A)
                            }
                        });
                        d.parentNode.insertBefore(a, d)
                    }
                }
                function B(b, d) {
                    try {
                        for (var a = 0; a < b.length; a++)
                            if ("function" === typeof b[a])
                                b[a]();
                        var f = m.data
                          , g = !1
                          , h = !1;
                        for (a = 0; a < f.length; a++)
                            if (f[a].f) {
                                h = !0;
                                var e = f[a];
                                !1 === g && "init" !== e.f && d.init();
                                g = !0;
                                d[e.f].apply(d, e.a)
                            }
                        !1 === h && d.init();
                        var k = c[n]
                          , l = c[p];
                        for (a = 0; a < f.length; a++)
                            f[a].e && k ? k.apply(c, f[a].e) : f[a].p && l && l.apply(c, [f[a].p])
                    } catch (C) {
                        console.error(C)
                    }
                }
                for (var g = !0, x = !1, k = 0; k < document.scripts.length; k++)
                    if (-1 < document.scripts[k].src.indexOf(y)) {
                        g = "no" !== document.scripts[k].getAttribute("data-lazy");
                        break
                    }
                var w = !1
                  , h = []
                  , m = function(b) {
                    (b.e || b.p || b.f && -1 < b.f.indexOf("capture") || b.f && -1 < b.f.indexOf("showReportDialog")) && g && e(h);
                    m.data.push(b)
                };
                m.data = [];
                c[l] = {
                    onLoad: function(b) {
                        h.push(b);
                        g && !x || e(h)
                    },
                    forceLoad: function() {
                        x = !0;
                        g && setTimeout(function() {
                            e(h)
                        })
                    }
                };
                "init addBreadcrumb captureMessage captureException captureEvent configureScope withScope showReportDialog".split(" ").forEach(function(b) {
                    c[l][b] = function() {
                        m({
                            f: b,
                            a: arguments
                        })
                    }
                });
                var q = c[n];
                c[n] = function(b, d, a, f, e) {
                    m({
                        e: [].slice.call(arguments)
                    });
                    q && q.apply(c, arguments)
                }
                ;
                var r = c[p];
                c[p] = function(b) {
                    m({
                        p: b.reason
                    });
                    r && r.apply(c, arguments)
                }
                ;
                g || setTimeout(function() {
                    e(h)
                })
            }
            )(window, document, "script", "onerror", "onunhandledrejection", "Sentry", "14370afcdc17429f9e418d5ffbd0334a", "https://browser.sentry-cdn.com/5.21.4/bundle.min.js", {
                "dsn": "https://14370afcdc17429f9e418d5ffbd0334a@sentry.wixpress.com/277"
            });
        </script>
        <!-- Viewer Model -->
        <script type="application/json" id="wix-viewer-model">
            {"requestUrl":"https:\/\/albertkeshev.wixsite.com\/my-site","siteFeatures":["bootstrap","assetsLoader","businessLogger","commonConfig","componentsLoader","consentPolicy","dashboardWixCodeSdk","dynamicPages","locationWixCodeSdk","navigationManager","ooi","pages","popups","protectedPages","renderer","reporter","router","seoWixCodeSdk","seo","sessionManager","siteMembersWixCodeSdk","siteMembers","siteScrollBlocker","siteWixCodeSdk","stores","structureApi","tpaCommons","translations","warmupData","windowMessageRegistrar","windowWixCodeSdk","wixEmbedsApi","componentsReact","platform"],"site":{"metaSiteId":"449452eb-9160-401f-a8e7-73181281adef","userId":"427fa165-cbce-4a9c-bba6-1f41b27c0ed8","siteId":"b97500a3-1350-45b0-bf57-d85911cfaba2","externalBaseUrl":"https:\/\/albertkeshev.wixsite.com\/my-site","siteRevision":9,"siteType":"UGC","dc":"84","isResponsive":false,"sessionId":"b410dbb9-fb6f-423b-ada0-99f45b047551"},"isMobileDevice":false,"viewMode":"desktop","formFactor":"desktop","deviceInfo":{"deviceClass":"Desktop"},"media":{"staticMediaUrl":"https:\/\/static.wixstatic.com\/media","mediaRootUrl":"https:\/\/static.wixstatic.com\/","staticVideoUrl":"https:\/\/video.wixstatic.com\/"},"language":{"userLanguage":"ru","userLanguageResolutionMethod":"QueryParam","siteLanguage":"ru","isMultilingualEnabled":false,"directionByLanguage":"ltr"},"mode":{"qa":false,"debug":false,"ssrIndicator":false,"ssrOnly":false,"editorElementsVersion":"1.5781.0"},"requestId":"request-id-placeholder","siteFeaturesConfigs":{"assetsLoader":{},"consentPolicy":{"isWixSite":false},"dashboardWixCodeSdk":{},"dynamicPages":{"prefixToRouterFetchData":{"account":{"urlData":{"basePath":"https:\/\/albertkeshev.wixsite.com\/my-site\/_api\/santa-members-server","queryParams":"viewMode=site","appDefinitionId":"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9"},"optionsData":{"bodyData":{"pageRoles":{"0009f56b-44da-464d-b0d0-8a468b470a9b":{"id":"q75r8","title":"Мой аккаунт"}},"routerPrefix":"\/account","config":{"type":"private","patterns":{"\/my-account":{"socialHome":false,"appData":{"appDefinitionId":"14cffd81-5215-0a7f-22f8-074b0e2401fb","appPageId":"member_info","menuOrder":3,"visibleForRoles":[]},"page":"0009f56b-44da-464d-b0d0-8a468b470a9b","seoData":{"title":"Мой аккаунт","description":"","keywords":"","noIndex":"true"},"title":"Мой аккаунт"}}}},"headers":{"Content-Type":"application\/json"}}},"profile":{"urlData":{"basePath":"https:\/\/albertkeshev.wixsite.com\/my-site\/_api\/santa-members-server","queryParams":"viewMode=site","appDefinitionId":"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9"},"optionsData":{"bodyData":{"pageRoles":{},"routerPrefix":"\/profile","config":{"type":"public"}},"headers":{"Content-Type":"application\/json"}}}},"routerPagesSeoToIdMap":{"my-account":"q75r8"},"externalBaseUrl":"https:\/\/albertkeshev.wixsite.com\/my-site","viewMode":"desktop"},"fedopsWixCodeSdk":{"isWixSite":false},"locationWixCodeSdk":{"routersConfigMap":{"routers-kp0uk509":{"prefix":"account","appDefinitionId":"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9","config":"{\"type\":\"private\",\"patterns\":{\"\/my-account\":{\"socialHome\":false,\"appData\":{\"appDefinitionId\":\"14cffd81-5215-0a7f-22f8-074b0e2401fb\",\"appPageId\":\"member_info\",\"menuOrder\":3,\"visibleForRoles\":[]},\"page\":\"0009f56b-44da-464d-b0d0-8a468b470a9b\",\"seoData\":{\"title\":\"Мой аккаунт\",\"description\":\"\",\"keywords\":\"\",\"noIndex\":\"true\"},\"title\":\"Мой аккаунт\"}}}","group":"members","pages":{"0009f56b-44da-464d-b0d0-8a468b470a9b":"q75r8"}},"routers-kp0uk50c":{"prefix":"profile","appDefinitionId":"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9","config":"{\"type\":\"public\"}","group":"members"}},"baseUrl":"https:\/\/albertkeshev.wixsite.com\/my-site","urlMappings":null},"onloadCompsBehaviors":{},"ooiTpaSharedConfig":{"imageSpriteUrl":"https:\/\/static.parastorage.com\/\/services\/santa-resources\/resources\/viewer\/editorUI\/fonts.v14.png","wixStaticFontsLinks":["https:\/\/static.parastorage.com\/\/services\/santa-resources\/resources\/viewer\/user-site-fonts\/v12\/languages.css"]},"ooi":{"ooiComponentsData":{"1380bba0-253e-a800-a235-88821cf3f8a4":{"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/gallery.bundle.min.js","widgetId":"1380bba0-253e-a800-a235-88821cf3f8a4","noCssComponentUrl":"","staticBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-ooi\/1.527.0\/","isLoadable":false},"1380bbc4-1485-9d44-4616-92e36b1ead6b":{"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-icon\/1.924.0\/cartIcon.bundle.min.js","widgetId":"1380bbc4-1485-9d44-4616-92e36b1ead6b","noCssComponentUrl":"","staticBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-ooi\/1.527.0\/","isLoadable":false},"13a94f09-2766-3c40-4a32-8edb5acdd8bc":{"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-page\/1.1877.0\/productPage.bundle.min.js","widgetId":"13a94f09-2766-3c40-4a32-8edb5acdd8bc","noCssComponentUrl":"","staticBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-ooi\/1.527.0\/","isLoadable":false},"13ec3e79-e668-cc0c-2d48-e99d53a213dd":{"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-widget\/1.1031.0\/productWidget.bundle.min.js","widgetId":"13ec3e79-e668-cc0c-2d48-e99d53a213dd","noCssComponentUrl":"","staticBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-ooi\/1.527.0\/","isLoadable":false},"14666402-0bc7-b763-e875-e99840d131bd":{"sentryDsn":"https:\/\/8c4075d5481d476e945486754f783364@sentry.io\/1865790","componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-add-to-cart\/1.518.0\/addToCart.bundle.min.js","widgetId":"14666402-0bc7-b763-e875-e99840d131bd","noCssComponentUrl":"","staticBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-ooi\/1.527.0\/","isLoadable":false},"a63a5215-8aa6-42af-96b1-583bfd74cff5":{"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-wishlist\/1.978.0\/wishlist.bundle.min.js","widgetId":"a63a5215-8aa6-42af-96b1-583bfd74cff5","noCssComponentUrl":"","staticBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-ooi\/1.527.0\/","isLoadable":false},"1380bbab-4da3-36b0-efb4-2e0599971d14":{"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-ooi\/1.527.0\/cartViewerWidget.bundle.min.js","widgetId":"1380bbab-4da3-36b0-efb4-2e0599971d14","noCssComponentUrl":"","staticBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-ooi\/1.527.0\/","isLoadable":false},"13afb094-84f9-739f-44fd-78d036adb028":{"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/gallery.bundle.min.js","widgetId":"13afb094-84f9-739f-44fd-78d036adb028","noCssComponentUrl":"","staticBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-ooi\/1.527.0\/","isLoadable":false},"139a41fd-0b1d-975f-6f67-e8cbdf8ccc82":{"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/sliderGallery.bundle.min.js","widgetId":"139a41fd-0b1d-975f-6f67-e8cbdf8ccc82","noCssComponentUrl":"","staticBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-ooi\/1.527.0\/","isLoadable":false},"14cefc05-d163-dbb7-e4ec-cd4f2c4d6ddd":{"componentUrl":"https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0\/ProfileCardViewerWidget.bundle.min.js","widgetId":"14cefc05-d163-dbb7-e4ec-cd4f2c4d6ddd","noCssComponentUrl":"","staticBaseUrl":"https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0\/","isLoadable":false}},"viewMode":"Site","formFactor":"Desktop","blogMobileComponentUrl":"undefinedfeed-page-mobile-viewer.bundle.min.js"},"protectedPages":{"passwordProtected":{}},"reporter":{"userId":"427fa165-cbce-4a9c-bba6-1f41b27c0ed8","metaSiteId":"449452eb-9160-401f-a8e7-73181281adef","isPremium":false,"isViewerMode":true,"isFBServerEventsAppProvisioned":false,"dynamicPagesIds":["q75r8"]},"router":{"baseUrl":"https:\/\/albertkeshev.wixsite.com\/my-site","mainPageId":"b5oae","pages":{"dxg3k":"427fa1_33f3f097eefd3794393995fca7c28f6f_9","s96vf":"427fa1_90ef0bdbfdbc7cc57935b700e4185e70_7","mm6wp":"427fa1_7a726ae54a9e5ced20dcd967e5d1c93f_9","s7y5i":"427fa1_a5fc5ef14a57272ed4ed172bc701aef1_9","wtx54":"427fa1_026c66c84ba070111d2d760d858c70b6_3","c42uf":"427fa1_4f4a04eefc38e59d31d08fd7725a2450_9","b5oae":"427fa1_ed82a8b7efcf3cde6463246d6c8b865a_9"},"routes":{".\/7":{"type":"Static","pageId":"dxg3k"},".\/5":{"type":"Static","pageId":"s96vf"},".\/popup-mm6wp":{"type":"Static","pageId":"mm6wp"},".\/6-8":{"type":"Static","pageId":"s7y5i"},".\/blank-3":{"type":"Static","pageId":"wtx54"},".\/6":{"type":"Static","pageId":"c42uf"},".\/4":{"type":"Static","pageId":"b5oae"},".\/account":{"type":"Dynamic"},".\/profile":{"type":"Dynamic"},".\/":{"type":"Static","pageId":"b5oae"}},"isWixSite":false},"searchWixCodeSdk":{"language":"ru"},"seo":{"context":{"siteName":"My Site","siteUrl":"https:\/\/albertkeshev.wixsite.com\/my-site","indexSite":false,"defaultUrl":"https:\/\/albertkeshev.wixsite.com\/my-site","currLangIsOriginal":true,"homePageTitle":"4","ogType":"article","businesLocale":"ru-ru"},"metaTags":[{"name":"fb_admins_meta_tag","value":"","property":false}],"customHeadTags":"","isInSEO":false,"hasBlogAmp":false,"mainPageId":"b5oae"},"sessionManager":{"appsInstances":{"undefined":{},"14bca956-e09f-f4d6-14d7-466cb3f09103":{"instance":"RFbHgOJmxBEDIYR7-8rxFY5JWWEauj0NAgNqwyzOTW0.eyJpbnN0YW5jZUlkIjoiZGQwMTMwYmItMDNjYS00ODZlLTliNWMtODE5NGVkMDgzNjcxIiwiYXBwRGVmSWQiOiIxNGJjYTk1Ni1lMDlmLWY0ZDYtMTRkNy00NjZjYjNmMDkxMDMiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiJhNmE4ZDM0OC1lNmRiLTRjMDktYTEyNS0xYjVmNzI4MjA5MjAiLCJiaVRva2VuIjoiOTk5NTYyNTAtOTJhYS0wODcxLTMzYmItZjI4Y2ZmODk5YjllIiwic2l0ZU93bmVySWQiOiI0MjdmYTE2NS1jYmNlLTRhOWMtYmJhNi0xZjQxYjI3YzBlZDgiLCJjYWNoZSI6dHJ1ZX0"},"141fbfae-511e-6817-c9f0-48993a7547d1":{"instance":"ycs94KE5ohqQPGR_Y_NP2BA-r10TNubfr_D0lfmbbgQ.eyJpbnN0YW5jZUlkIjoiZDY5NWFhZTgtZWNjMi00NjQ1LTg0NjYtYjQxNTU1NTIxNDQ5IiwiYXBwRGVmSWQiOiIxNDFmYmZhZS01MTFlLTY4MTctYzlmMC00ODk5M2E3NTQ3ZDEiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OFoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiJmYmY0NDBlZS03YTZlLTQ3Y2UtYTgzNC04NTUyNzY4MjI1M2IiLCJiaVRva2VuIjoiOTIwMWY4MDMtN2RhMi0wNjVhLTJjODEtYzcwZDQ3ZDNiOWE2Iiwic2l0ZU93bmVySWQiOiI0MjdmYTE2NS1jYmNlLTRhOWMtYmJhNi0xZjQxYjI3YzBlZDgiLCJjYWNoZSI6dHJ1ZX0"},"13ee94c1-b635-8505-3391-97919052c16f":{"instance":"b2bW3ERQF-IVZlqE18lMmEHRiGQMe9KEKQ1EX3bu2Rw.eyJpbnN0YW5jZUlkIjoiMTFlYzAxYjctYmIyNS00NzQ3LTkzNjMtZTcyMGViN2I2YjM0IiwiYXBwRGVmSWQiOiIxM2VlOTRjMS1iNjM1LTg1MDUtMzM5MS05NzkxOTA1MmMxNmYiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiI3YWNhOTdhOC01OTA4LTRkZDctOTc1NC01YTVhODBiODQ0YmEiLCJiaVRva2VuIjoiNTU3ODUzNWMtMmE0NS0wNzU4LTNiODQtOTQzOGY5ZmFjNmRiIiwic2l0ZU93bmVySWQiOiI0MjdmYTE2NS1jYmNlLTRhOWMtYmJhNi0xZjQxYjI3YzBlZDgiLCJjYWNoZSI6dHJ1ZX0"},"150ae7ee-c74a-eecd-d3d7-2112895b988a":{"instance":"sU7HnmVnuKWueklJzuTSiVw2IxHRmxkza_m_nQdnwYw.eyJpbnN0YW5jZUlkIjoiMTY4NDAwNzgtMjQ0Ny00MDI0LTgxYTgtMTg2YWY2MGQxYjFkIiwiYXBwRGVmSWQiOiIxNTBhZTdlZS1jNzRhLWVlY2QtZDNkNy0yMTEyODk1Yjk4OGEiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiJlNTE0YjM5Ni0xNDhkLTRmZDUtOTUwMi02YTdmNjExZDU3ZjQiLCJiaVRva2VuIjoiNTIxMDUyOTMtYjUyNy0wMDNiLTI5NGYtNmI3MmU0OGNiNmYyIiwic2l0ZU93bmVySWQiOiI0MjdmYTE2NS1jYmNlLTRhOWMtYmJhNi0xZjQxYjI3YzBlZDgiLCJjYWNoZSI6dHJ1ZX0"},"a322993b-2c74-426f-bbb8-444db73d0d1b":{"instance":"Az25RsXPYDWM6Tr3x2BBNef6V-nY-wetmUBzMX8pIak.eyJpbnN0YW5jZUlkIjoiYTcyMjcwYmUtNTVlYS00NzhhLTg5M2UtOTJjODgyMDc1ZmRkIiwiYXBwRGVmSWQiOiJhMzIyOTkzYi0yYzc0LTQyNmYtYmJiOC00NDRkYjczZDBkMWIiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiIzMDU4OWNhOS1hOWFkLTRiOWQtYjU3OC0yNzc1NDdjOTRhZTciLCJiaVRva2VuIjoiZTNiNjIyNTUtYzQ4YS0wNzk1LTIxZDktZTFkMDkwODZmMjMyIiwic2l0ZU93bmVySWQiOiI0MjdmYTE2NS1jYmNlLTRhOWMtYmJhNi0xZjQxYjI3YzBlZDgiLCJjYWNoZSI6dHJ1ZX0"},"55cd9036-36bb-480b-8ddc-afda3cb2eb8d":{"instance":"XbG1FGqNX-Ms-d6N7xj0CXt9tY-8ASpa7dt52jyp9Xs.eyJpbnN0YW5jZUlkIjoiMzhlY2Q0ZWEtNDY0Yi00NTdmLWI2M2UtY2U5MTY2ZTU2ODIxIiwiYXBwRGVmSWQiOiI1NWNkOTAzNi0zNmJiLTQ4MGItOGRkYy1hZmRhM2NiMmViOGQiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiJlOWQxNWZiMi1hZjYzLTQ1NzYtYTZiNC1jZWI2ZGQxODAwNGUiLCJiaVRva2VuIjoiN2M3ODg2MDEtZDcyYi0wNTYwLTFlZDktYmQ4OTc0NjRjNWNlIiwic2l0ZU93bmVySWQiOiI0MjdmYTE2NS1jYmNlLTRhOWMtYmJhNi0xZjQxYjI3YzBlZDgiLCJjYWNoZSI6dHJ1ZX0"},"f123e8f1-4350-4c9b-b269-04adfadda977":{"instance":"UDhde9ed0IemPUpTl0SezY25z_chBcKqBN5JeGG7-as.eyJpbnN0YW5jZUlkIjoiYWVlMTg1NDAtNzU2Yy00M2U0LWIwNWEtNDM0OWJjODc4ZjQzIiwiYXBwRGVmSWQiOiJmMTIzZThmMS00MzUwLTRjOWItYjI2OS0wNGFkZmFkZGE5NzciLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiI1NmUxYzc5MS00NjdiLTQxOTQtODYyOS01YWQxZTM1ZDJmZGMiLCJiaVRva2VuIjoiZWE3NWQ3YWItZTQwYy0wM2ZiLTE4YmQtMzA1MWFlMDYyMmFjIiwic2l0ZU93bmVySWQiOiI0MjdmYTE2NS1jYmNlLTRhOWMtYmJhNi0xZjQxYjI3YzBlZDgiLCJjYWNoZSI6dHJ1ZX0"},"9bead16f-1c73-4cda-b6c4-28cff46988db":{"instance":"SA0Ha7TsdwUt2zGbqu2bYsM1-XLzzmM1SE7bbRvYdlI.eyJpbnN0YW5jZUlkIjoiNzM1NzU3YTktNDVmOS00NTg4LThhNWMtMjAwYmMzMDNmOTBmIiwiYXBwRGVmSWQiOiI5YmVhZDE2Zi0xYzczLTRjZGEtYjZjNC0yOGNmZjQ2OTg4ZGIiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiIxZWRmMDg1ZS1jZmRlLTQ2M2EtYTI5ZC0zOGZlOTJiZGU2M2UiLCJiaVRva2VuIjoiMzdjMzA1NDItZDQ5OS0wNTk3LTIyYmItNTMxM2QxODI1NGUwIiwic2l0ZU93bmVySWQiOiI0MjdmYTE2NS1jYmNlLTRhOWMtYmJhNi0xZjQxYjI3YzBlZDgiLCJjYWNoZSI6dHJ1ZX0"},"1480c568-5cbd-9392-5604-1148f5faffa0":{"instance":"Gy0EoAZMPUkOI1ao55L2alLGjEqkeCgp9yft3QXMnJg.eyJpbnN0YW5jZUlkIjoiMmMwYzRmYjItZDI4OC00MzAxLThmMzUtOTQwMGRmOWM0OTU1IiwiYXBwRGVmSWQiOiIxNDgwYzU2OC01Y2JkLTkzOTItNTYwNC0xMTQ4ZjVmYWZmYTAiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiJjMzZmZWRiMi1kMzFjLTQxNzAtOGVjYS1lYzIwZTRiYzhhZmEiLCJiaVRva2VuIjoiNjg5ODFkNTktNDNlOC0wMzFlLTI3ZDItZTcxOGNkMWRlNGJhIiwic2l0ZU93bmVySWQiOiI0MjdmYTE2NS1jYmNlLTRhOWMtYmJhNi0xZjQxYjI3YzBlZDgiLCJjYWNoZSI6dHJ1ZX0"},"14d7032a-0a65-5270-cca7-30f599708fed":{"instance":"SPF192-2LfuP7oOP4o-vOrU3jtxDx2SQWlmqHldzrn4.eyJpbnN0YW5jZUlkIjoiYTAzYzljYjQtMDdkMy00NzQyLWFjMGMtNTgwZWZhNDkxYWRkIiwiYXBwRGVmSWQiOiIxNGQ3MDMyYS0wYTY1LTUyNzAtY2NhNy0zMGY1OTk3MDhmZWQiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsImJpVG9rZW4iOiJlNGE4Y2U1Zi05NmIzLTA3NWQtMDRlYi0yYjE2ZThjOGI3MzIiLCJzaXRlT3duZXJJZCI6IjQyN2ZhMTY1LWNiY2UtNGE5Yy1iYmE2LTFmNDFiMjdjMGVkOCIsImNhY2hlIjp0cnVlfQ"},"13aa9735-aa50-4bdb-877c-0bb46804bd71":{"instance":"i9OiCydvsjs8b-IjObPXikml5fMC_ApOzIA9pDqDoOc.eyJpbnN0YW5jZUlkIjoiNGNlMzRkM2MtN2RhZi00OGI3LWJkOTctMjNhZWU3ZTE2Y2IwIiwiYXBwRGVmSWQiOiIxM2FhOTczNS1hYTUwLTRiZGItODc3Yy0wYmI0NjgwNGJkNzEiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiI3OGFhZjZhYy02MTA0LTRlMzctYjJkOC0wZmY3OWJkZTgzNTciLCJiaVRva2VuIjoiMDg3NzFmZDctZWNjZi0wOGE4LTE1NzAtNTBiNmY1NjBjMTVmIiwic2l0ZU93bmVySWQiOiI0MjdmYTE2NS1jYmNlLTRhOWMtYmJhNi0xZjQxYjI3YzBlZDgiLCJjYWNoZSI6dHJ1ZX0"},"d70b68e2-8d77-4e0c-9c00-c292d6e0025e":{"instance":"NUBFD2F4GIdZ456loDYlV_0YMP2Jv_8id6FJsyHNPqg.eyJpbnN0YW5jZUlkIjoiYzMzNjIyYjQtN2Y1OC00OTNhLTljMzUtM2NlNGFkZjY2ZGNlIiwiYXBwRGVmSWQiOiJkNzBiNjhlMi04ZDc3LTRlMGMtOWMwMC1jMjkyZDZlMDAyNWUiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiI4MTdjZGUzZC1hN2Q3LTQ4MmItYjBmZS1iYTRlZjllODRiMTMiLCJiaVRva2VuIjoiODdhMjcwNWYtZWUzOC0wOTI1LTM0ZDItNGZmY2JmNzdjMDIxIiwic2l0ZU93bmVySWQiOiI0MjdmYTE2NS1jYmNlLTRhOWMtYmJhNi0xZjQxYjI3YzBlZDgiLCJjYWNoZSI6dHJ1ZX0"},"14b89688-9b25-5214-d1cb-a3fb9683618b":{"instance":"ZQMQgTyvz-caT7SKp97s3Alvrbeygr4mWHfNAMTlFc4.eyJpbnN0YW5jZUlkIjoiNGExMTQ3NjgtNjgyMi00Mzc4LTlkNmYtODg2N2U5NGZlNTg0IiwiYXBwRGVmSWQiOiIxNGI4OTY4OC05YjI1LTUyMTQtZDFjYi1hM2ZiOTY4MzYxOGIiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiJkNWQxZGFkMy1jYzlhLTQyYjItYmQ0Zi0wODVmMDMzMWE2NTkiLCJiaVRva2VuIjoiMGU4NTE1ODMtZjk0Mi0wMzY3LTM1ODgtZmI3ZmZiY2U0ODZiIiwic2l0ZU93bmVySWQiOiI0MjdmYTE2NS1jYmNlLTRhOWMtYmJhNi0xZjQxYjI3YzBlZDgiLCJjYWNoZSI6dHJ1ZX0"},"135c3d92-0fea-1f9d-2ba5-2a1dfb04297e":{"instance":"3YR5u8nuSnwQVtbPK_ZlQN7EmuyQnF2nXKZE3rdBOJ8.eyJpbnN0YW5jZUlkIjoiNmE3NDU4Y2ItMDUyZS00ZTUyLTkzY2YtYmFmMWQ0OTNhZDlkIiwiYXBwRGVmSWQiOiIxMzVjM2Q5Mi0wZmVhLTFmOWQtMmJhNS0yYTFkZmIwNDI5N2UiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiJmZWRjZWRhMy1lYTg3LTRjNjQtOTkwZC1mM2M0YzJiNzE5YTIiLCJiaVRva2VuIjoiMmVlMDBhMjAtOTQ0ZS0wZTRkLTNiMjgtYzllOWM2MTIwMDcyIiwic2l0ZU93bmVySWQiOiI0MjdmYTE2NS1jYmNlLTRhOWMtYmJhNi0xZjQxYjI3YzBlZDgiLCJjYWNoZSI6dHJ1ZX0"},"146c0d71-352e-4464-9a03-2e868aabe7b9":{"instance":"pvT92JAKqdy-x3ibda751FV7nisjSdWdnUr6WqG-KV0.eyJpbnN0YW5jZUlkIjoiNjQ1N2FlNzUtMTdmZS00MTliLThiNDUtZGM1MTdkZmM4ZWM5IiwiYXBwRGVmSWQiOiIxNDZjMGQ3MS0zNTJlLTQ0NjQtOWEwMy0yZTg2OGFhYmU3YjkiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiI3MTE4MzY3Zi1kOTc5LTRjYWUtYTZmZi04ODQ2ZTQ1ZmUzZjMiLCJiaVRva2VuIjoiMjBjM2ZjOWUtODY5ZS0wMTg0LTIzYTItYWY0OTZmN2QyMzI2Iiwic2l0ZU93bmVySWQiOiI0MjdmYTE2NS1jYmNlLTRhOWMtYmJhNi0xZjQxYjI3YzBlZDgiLCJjYWNoZSI6dHJ1ZX0"},"139ef4fa-c108-8f9a-c7be-d5f492a2c939":{"instance":"-au5o33oYMtDSH_R3qpstLFh_Y79_g9eYDYU6mR9AEk.eyJpbnN0YW5jZUlkIjoiMGU5ZDAyZjgtM2RmYi00YTQyLWExNmUtMzQ2ZDJmZDE3YjgxIiwiYXBwRGVmSWQiOiIxMzllZjRmYS1jMTA4LThmOWEtYzdiZS1kNWY0OTJhMmM5MzkiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OFoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiJkMjMzZTM0YS0yZDgzLTQ2ZGUtODk1OS1lNmNkOTcyM2EyYTQiLCJiaVRva2VuIjoiNGEwOTUwMTMtYWM5Yi0wYTVkLTA5ODktNDc3NTNkNTBkNjZlIiwic2l0ZU93bmVySWQiOiI0MjdmYTE2NS1jYmNlLTRhOWMtYmJhNi0xZjQxYjI3YzBlZDgiLCJjYWNoZSI6dHJ1ZX0"},"307ba931-689c-4b55-bb1d-6a382bad9222":{"instance":"uJX_U9ziV0jZp9qZ7v12VKrIvZG-IbfgqDomSLDMqVU.eyJpbnN0YW5jZUlkIjoiZTAyODI5ZWQtMWEwZS00YjI3LWE0ZDItZjJmY2I2NmY1MDIxIiwiYXBwRGVmSWQiOiIzMDdiYTkzMS02ODljLTRiNTUtYmIxZC02YTM4MmJhZDkyMjIiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiIxMDFlMDU4NS0zZWU2LTQ4ZDctOTc3Yy1kMTdhMWQxYzhlZjYiLCJiaVRva2VuIjoiYTRiYzdiMDYtOGI2ZS0wYjM4LTBjMzUtODFlNGE0ZWVmZGNlIiwic2l0ZU93bmVySWQiOiI0MjdmYTE2NS1jYmNlLTRhOWMtYmJhNi0xZjQxYjI3YzBlZDgiLCJjYWNoZSI6dHJ1ZX0"},"ea2821fc-7d97-40a9-9f75-772f29178430":{"instance":"u13k9PuFtAdTGQC4p3YqrT71syXdTDc0R_gnTtsKksE.eyJpbnN0YW5jZUlkIjoiNTMwYjRiODEtZDBlNi00MzUwLWE1OTctNjdlNmQwZjRkZGJlIiwiYXBwRGVmSWQiOiJlYTI4MjFmYy03ZDk3LTQwYTktOWY3NS03NzJmMjkxNzg0MzAiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsIm9yaWdpbkluc3RhbmNlSWQiOiIwOWIxMDBkNi1hZmMyLTRiYWUtODdjNi1jYmY0NjM4M2M0MDEiLCJiaVRva2VuIjoiMTc5ZjE5NmEtNDE4Ni0wMzRmLTBkNzAtMTRmZWMyNzU3MDUxIiwic2l0ZU93bmVySWQiOiI0MjdmYTE2NS1jYmNlLTRhOWMtYmJhNi0xZjQxYjI3YzBlZDgiLCJjYWNoZSI6dHJ1ZX0"},"daa0ec09-7595-441b-b3ea-d275ac27b36f":{"instance":"_hVTPmA8PzZ4HPOIV6y5NBtFIOQe_07ItjxUKItGllM.eyJpbnN0YW5jZUlkIjoiZjYyMzRjMzgtODkyNi00N2Y2LTg2YzAtZDQ4YTljNjE2MmRjIiwiYXBwRGVmSWQiOiJkYWEwZWMwOS03NTk1LTQ0MWItYjNlYS1kMjc1YWMyN2IzNmYiLCJzaWduRGF0ZSI6IjIwMjEtMDUtMjNUMTI6NDE6MTIuMzY5WiIsImRlbW9Nb2RlIjpmYWxzZSwic2l0ZU93bmVySWQiOiI0MjdmYTE2NS1jYmNlLTRhOWMtYmJhNi0xZjQxYjI3YzBlZDgiLCJjYWNoZSI6dHJ1ZX0"},"36c09775-5ced-4ae9-9ba9-0c3119fbd7c1":{"instance":"beXoX6Fm97SKkNj5kXyULZg3v4lzvZm6_59qor4AX5o.eyJpbnN0YW5jZUlkIjoiNTA4OWYzN2YtM2ZmMy00MWZlLWI1MzgtYzhhOGU3N2Q0NGUzIiwiYXBwRGVmSWQiOiIzNmMwOTc3NS01Y2VkLTRhZTktOWJhOS0wYzMxMTlmYmQ3YzEiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsImJpVG9rZW4iOiIxNDFkYTE5NC1hZTkzLTAxZTEtMWRkZi1iYmIwZjVmY2U5MGMiLCJzaXRlT3duZXJJZCI6IjQyN2ZhMTY1LWNiY2UtNGE5Yy1iYmE2LTFmNDFiMjdjMGVkOCIsImNhY2hlIjp0cnVlfQ"},"1380b703-ce81-ff05-f115-39571d94dfcd":{"instance":"Ps3gXOuXA5zdM8h52OGZm0OtLUknBkLS4CO4FvlJuSE.eyJpbnN0YW5jZUlkIjoiNDRlNmNlYjYtNTQwOS00ZGNmLTg4YTctYzYxOGYwMzc1NDg2IiwiYXBwRGVmSWQiOiIxMzgwYjcwMy1jZTgxLWZmMDUtZjExNS0zOTU3MWQ5NGRmY2QiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsImJpVG9rZW4iOiIwMDcyOWM1ZC1jNTY5LTBkZDAtMjA0MC1iNTAwZTJiNmY5NjkiLCJzaXRlT3duZXJJZCI6IjQyN2ZhMTY1LWNiY2UtNGE5Yy1iYmE2LTFmNDFiMjdjMGVkOCIsImNhY2hlIjp0cnVlfQ"},"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9":{"instance":"om4iekmivrN-If5OhtN7uEQlsGxRLLpNJd5XiZlbbmM.eyJpbnN0YW5jZUlkIjoiODcwNWY3OTItODMwMy00NDIxLTkwMGMtMmQwNDI4ZjcwZmZmIiwiYXBwRGVmSWQiOiIxNGNjNTliYy1mMGI3LTE1YjgtZTFjNy04OWNlNDFkMGUwYzkiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsImJpVG9rZW4iOiJjMzkxYTU3OS0xMjYzLTA0M2UtMzhlYi01ZTFjM2E3NmEyMTAiLCJzaXRlT3duZXJJZCI6IjQyN2ZhMTY1LWNiY2UtNGE5Yy1iYmE2LTFmNDFiMjdjMGVkOCIsImNhY2hlIjp0cnVlfQ"},"14ce28f7-7eb0-3745-22f8-074b0e2401fb":{"instance":"KLglGVbGNu6MrmPbb3cvGaOF-SIb_BOWiAZTRJh8POM.eyJpbnN0YW5jZUlkIjoiYzVkYzYzYmItZjMzNy00ZTYzLWE3MTctMDAwY2UwOTllODIzIiwiYXBwRGVmSWQiOiIxNGNlMjhmNy03ZWIwLTM3NDUtMjJmOC0wNzRiMGUyNDAxZmIiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsImJpVG9rZW4iOiI4MTQ4MzE1MC02MjU3LTBlN2MtMGZmMC03MzE0ZjIxODQ1Y2MiLCJzaXRlT3duZXJJZCI6IjQyN2ZhMTY1LWNiY2UtNGE5Yy1iYmE2LTFmNDFiMjdjMGVkOCIsImNhY2hlIjp0cnVlfQ"},"14cffd81-5215-0a7f-22f8-074b0e2401fb":{"instance":"MNqGYVxmvqoddeDCV_CsPOAzM5zrrYkIg8mJKA0pl3k.eyJpbnN0YW5jZUlkIjoiYmRlNTA3ZmQtMGYzMC00NGUzLTlhMzgtNWFmNTU4NzMzMWI4IiwiYXBwRGVmSWQiOiIxNGNmZmQ4MS01MjE1LTBhN2YtMjJmOC0wNzRiMGUyNDAxZmIiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsImJpVG9rZW4iOiJmOTcxNTUxNi05ZTUwLTA0ZmMtMzJkZi0yOWVkNGFmMjljNTciLCJzaXRlT3duZXJJZCI6IjQyN2ZhMTY1LWNiY2UtNGE5Yy1iYmE2LTFmNDFiMjdjMGVkOCIsImNhY2hlIjp0cnVlfQ"},"1505b775-e885-eb1b-b665-1e485d9bf90e":{"instance":"9zLB7yjzrqZiNKuvWbE-nbgatlStwwVeMby_Vd1lxNM.eyJpbnN0YW5jZUlkIjoiOTVmM2ZkNzAtYjBiZS00YWU1LWE5MTktZTc3YWZhYTUyOTM5IiwiYXBwRGVmSWQiOiIxNTA1Yjc3NS1lODg1LWViMWItYjY2NS0xZTQ4NWQ5YmY5MGUiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsImJpVG9rZW4iOiJkMTY3YWY5Yi0yMWRlLTBhZmEtMDFmZS05NDYyZTgyNDg0ZDYiLCJzaXRlT3duZXJJZCI6IjQyN2ZhMTY1LWNiY2UtNGE5Yy1iYmE2LTFmNDFiMjdjMGVkOCIsImNhY2hlIjp0cnVlfQ"},"4aebd0cb-fbdb-4da7-b5d1-d05660a30172":{"instance":"Z54ujmNygnoZOh1qh0kwZuhwnYfXsUkeZ_MTW2BEBSI.eyJpbnN0YW5jZUlkIjoiYjc3MTY3NjgtZjcxMy00NDFlLTk4NjktYzU0M2I5MDFlZjc2IiwiYXBwRGVmSWQiOiI0YWViZDBjYi1mYmRiLTRkYTctYjVkMS1kMDU2NjBhMzAxNzIiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsImJpVG9rZW4iOiJmM2U1MzU4My02NjczLTA0MDEtMzA4ZS1iNjViYWI4MDQyOTkiLCJzaXRlT3duZXJJZCI6IjQyN2ZhMTY1LWNiY2UtNGE5Yy1iYmE2LTFmNDFiMjdjMGVkOCIsImNhY2hlIjp0cnVlfQ"},"22bef345-3c5b-4c18-b782-74d4085112ff":{"instance":"eMLRpC8BZxhM3EB6iWts8lrANeGSwmLJacL49m4vy20.eyJpbnN0YW5jZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwiYXBwRGVmSWQiOiIyMmJlZjM0NS0zYzViLTRjMTgtYjc4Mi03NGQ0MDg1MTEyZmYiLCJtZXRhU2l0ZUlkIjoiNDQ5NDUyZWItOTE2MC00MDFmLWE4ZTctNzMxODEyODFhZGVmIiwic2lnbkRhdGUiOiIyMDIxLTA1LTIzVDEyOjQxOjEyLjM2OVoiLCJkZW1vTW9kZSI6ZmFsc2UsInNpdGVPd25lcklkIjoiNDI3ZmExNjUtY2JjZS00YTljLWJiYTYtMWY0MWIyN2MwZWQ4IiwiY2FjaGUiOnRydWV9"}},"dynamicModelApiUrl":"https:\/\/albertkeshev.wixsite.com\/my-site\/_api\/v2\/dynamicmodel","expiryTimeoutOverride":0},"siteMembersWixCodeSdk":{"isPreviewMode":false,"smToken":"","smcollectionId":"449452eb-9160-401f-a8e7-73181281adef"},"siteMembers":{"collectionExposure":"Public","smcollectionId":"449452eb-9160-401f-a8e7-73181281adef","smToken":"","protectedHomepage":false,"memberInfoAppId":3202,"isCommunityInstalled":false},"siteWixCodeSdk":{"siteRevision":9,"regionalSettings":"ru-ru","language":"ru","currency":"RUB","mainPageId":"b5oae","appsData":{"2":{},"4":{"appDefinitionId":"14bca956-e09f-f4d6-14d7-466cb3f09103"},"5":{"appDefinitionId":"141fbfae-511e-6817-c9f0-48993a7547d1"},"6":{"appDefinitionId":"13ee94c1-b635-8505-3391-97919052c16f"},"7":{"appDefinitionId":"150ae7ee-c74a-eecd-d3d7-2112895b988a"},"8":{"appDefinitionId":"a322993b-2c74-426f-bbb8-444db73d0d1b"},"9":{"appDefinitionId":"55cd9036-36bb-480b-8ddc-afda3cb2eb8d"},"10":{"appDefinitionId":"f123e8f1-4350-4c9b-b269-04adfadda977"},"11":{"appDefinitionId":"9bead16f-1c73-4cda-b6c4-28cff46988db"},"12":{"appDefinitionId":"1480c568-5cbd-9392-5604-1148f5faffa0"},"13":{"appDefinitionId":"14d7032a-0a65-5270-cca7-30f599708fed"},"14":{"appDefinitionId":"13aa9735-aa50-4bdb-877c-0bb46804bd71"},"15":{"appDefinitionId":"d70b68e2-8d77-4e0c-9c00-c292d6e0025e"},"16":{"appDefinitionId":"14b89688-9b25-5214-d1cb-a3fb9683618b"},"18":{"appDefinitionId":"135c3d92-0fea-1f9d-2ba5-2a1dfb04297e"},"19":{"appDefinitionId":"146c0d71-352e-4464-9a03-2e868aabe7b9"},"20":{"appDefinitionId":"139ef4fa-c108-8f9a-c7be-d5f492a2c939"},"21":{"appDefinitionId":"307ba931-689c-4b55-bb1d-6a382bad9222"},"22":{"appDefinitionId":"ea2821fc-7d97-40a9-9f75-772f29178430"},"23":{"appDefinitionId":"daa0ec09-7595-441b-b3ea-d275ac27b36f"},"24":{"appDefinitionId":"36c09775-5ced-4ae9-9ba9-0c3119fbd7c1"},"1703":{"appDefinitionId":"1380b703-ce81-ff05-f115-39571d94dfcd"},"2147":{"appDefinitionId":"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9"},"2633":{"appDefinitionId":"14ce28f7-7eb0-3745-22f8-074b0e2401fb"},"3202":{"appDefinitionId":"14cffd81-5215-0a7f-22f8-074b0e2401fb"},"3609":{"appDefinitionId":"1505b775-e885-eb1b-b665-1e485d9bf90e"},"4433":{"appDefinitionId":"4aebd0cb-fbdb-4da7-b5d1-d05660a30172"},"-666":{"appDefinitionId":"22bef345-3c5b-4c18-b782-74d4085112ff"}},"pageIdToPrefix":{"q75r8":"account"},"routerPrefixes":{"0009f56b-44da-464d-b0d0-8a468b470a9b":{"name":"account","prefix":"\/account","type":"dynamicPages"}},"baseUrl":"https:\/\/albertkeshev.wixsite.com\/my-site","timezone":"Europe\/Moscow","pageIdToTitle":{"dxg3k":"7","s96vf":"5","mm6wp":"Приветствие (во весь экран)","s7y5i":"6-8","wtx54":"Новая страница","c42uf":"6","b5oae":"4","q75r8":"Мой аккаунт"},"urlMappings":null},"tinyMenu":{"languages":false},"tpaCommons":{"widgetsClientSpecMapData":{"141995eb-c700-8487-6366-a482f7432e2b":{"widgetUrl":"https:\/\/so-feed.codev.wixapps.net\/widget","mobileUrl":"https:\/\/so-feed.codev.wixapps.net\/widget","tpaWidgetId":"shoutout_feed","appPage":{},"applicationId":18,"appDefinitionName":"Email Marketing","appDefinitionId":"135c3d92-0fea-1f9d-2ba5-2a1dfb04297e","allowScrolling":false},"2b0423db-abfa-45fb-8d1e-284fed57c195":{"widgetUrl":"https:\/\/gifted.co\/wix\/card","mobileUrl":"https:\/\/gifted.co\/wix\/card","tpaWidgetId":"2b0423db-abfa-45fb-8d1e-284fed57c195","appPage":{"id":"Gift Card","name":"Gift Card","defaultPage":"","hidden":false,"multiInstanceEnabled":false,"order":1,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"applicationId":23,"appDefinitionName":"Gifted","appDefinitionId":"daa0ec09-7595-441b-b3ea-d275ac27b36f","allowScrolling":false},"1380bba0-253e-a800-a235-88821cf3f8a4":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/gallery","mobileUrl":"https:\/\/ecom.wix.com\/storefront\/gallery","appPage":{"id":"product_gallery","name":"Shop","defaultPage":"","hidden":false,"multiInstanceEnabled":true,"order":1,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"applicationId":1703,"appDefinitionName":"Wix Stores","appDefinitionId":"1380b703-ce81-ff05-f115-39571d94dfcd","allowScrolling":false},"14e121c8-00a3-f7cc-6156-2c82a2ba8fcb":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/order-history","mobileUrl":"https:\/\/ecom.wix.com\/storefront\/order-history","appPage":{"id":"order_history","name":"My Orders","defaultPage":"","hidden":true,"multiInstanceEnabled":false,"order":5,"indexable":false,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"applicationId":1703,"appDefinitionName":"Wix Stores","appDefinitionId":"1380b703-ce81-ff05-f115-39571d94dfcd","allowScrolling":false},"1380bbc4-1485-9d44-4616-92e36b1ead6b":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/cartwidget","mobileUrl":"https:\/\/ecom.wix.com\/storefront\/cartwidget","tpaWidgetId":"shopping_cart_icon","appPage":{},"applicationId":1703,"appDefinitionName":"Wix Stores","appDefinitionId":"1380b703-ce81-ff05-f115-39571d94dfcd","allowScrolling":false},"13a94f09-2766-3c40-4a32-8edb5acdd8bc":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/product","mobileUrl":"https:\/\/ecom.wix.com\/storefront\/product","appPage":{"id":"product_page","name":"Product Page","defaultPage":"","hidden":true,"multiInstanceEnabled":false,"order":2,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"applicationId":1703,"appDefinitionName":"Wix Stores","appDefinitionId":"1380b703-ce81-ff05-f115-39571d94dfcd","allowScrolling":false},"14fd5970-8072-c276-1246-058b79e70c1a":{"widgetUrl":"https:\/\/ecom.wixapps.net\/storefront\/checkout","mobileUrl":"https:\/\/ecom.wixapps.net\/storefront\/checkout","appPage":{"id":"checkout","name":"Checkout","defaultPage":"","hidden":true,"multiInstanceEnabled":false,"order":6,"indexable":false,"fullPage":false,"landingPageInMobile":true,"hideFromMenu":true},"applicationId":1703,"appDefinitionName":"Wix Stores","appDefinitionId":"1380b703-ce81-ff05-f115-39571d94dfcd","allowScrolling":true},"13ec3e79-e668-cc0c-2d48-e99d53a213dd":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/product-widget-view","mobileUrl":"https:\/\/ecom.wix.com\/storefront\/product-widget-view","tpaWidgetId":"product_widget","appPage":{},"applicationId":1703,"appDefinitionName":"Wix Stores","appDefinitionId":"1380b703-ce81-ff05-f115-39571d94dfcd","allowScrolling":false},"14666402-0bc7-b763-e875-e99840d131bd":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/add-to-cart","mobileUrl":"https:\/\/ecom.wix.com\/storefront\/add-to-cart","tpaWidgetId":"add_to_cart_button","appPage":{},"applicationId":1703,"appDefinitionName":"Wix Stores","appDefinitionId":"1380b703-ce81-ff05-f115-39571d94dfcd","allowScrolling":false},"a63a5215-8aa6-42af-96b1-583bfd74cff5":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/wishlist","mobileUrl":"https:\/\/ecom.wix.com\/storefront\/wishlist","appPage":{"id":"wishlist","name":"My Wishlist","defaultPage":"","hidden":true,"multiInstanceEnabled":false,"order":7,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"applicationId":1703,"appDefinitionName":"Wix Stores","appDefinitionId":"1380b703-ce81-ff05-f115-39571d94dfcd","allowScrolling":false},"1380bbab-4da3-36b0-efb4-2e0599971d14":{"widgetUrl":"https:\/\/editor-flow.wixapps.net\/render\/wixstores-client-cart-ooi\/1.527.0\/editor\/cart.html","mobileUrl":"https:\/\/editor-flow.wixapps.net\/render\/wixstores-client-cart-ooi\/1.527.0\/editor\/cart.html","appPage":{"id":"shopping_cart","name":"Cart Page","defaultPage":"","hidden":true,"multiInstanceEnabled":false,"order":3,"indexable":false,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"applicationId":1703,"appDefinitionName":"Wix Stores","appDefinitionId":"1380b703-ce81-ff05-f115-39571d94dfcd","allowScrolling":false},"13afb094-84f9-739f-44fd-78d036adb028":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/gallery","mobileUrl":"https:\/\/ecom.wix.com\/storefront\/gallery","tpaWidgetId":"grid_gallery","appPage":{},"applicationId":1703,"appDefinitionName":"Wix Stores","appDefinitionId":"1380b703-ce81-ff05-f115-39571d94dfcd","allowScrolling":false},"139a41fd-0b1d-975f-6f67-e8cbdf8ccc82":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/minigallery","mobileUrl":"https:\/\/ecom.wix.com\/storefront\/minigallery","tpaWidgetId":"slider_gallery","appPage":{},"applicationId":1703,"appDefinitionName":"Wix Stores","appDefinitionId":"1380b703-ce81-ff05-f115-39571d94dfcd","allowScrolling":false},"1380bbb4-8df0-fd38-a235-88821cf3f8a4":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/success","mobileUrl":"https:\/\/ecom.wix.com\/storefront\/success","appPage":{"id":"thank_you_page","name":"Thank You Page","defaultPage":"","hidden":true,"multiInstanceEnabled":false,"order":4,"indexable":false,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"applicationId":1703,"appDefinitionName":"Wix Stores","appDefinitionId":"1380b703-ce81-ff05-f115-39571d94dfcd","allowScrolling":false},"14cefc05-d163-dbb7-e4ec-cd4f2c4d6ddd":{"widgetUrl":"https:\/\/editor-flow.wixapps.net\/render\/profile-card-tpa-ooi\/1.248.0\/editor\/ProfileCard.html","mobileUrl":"https:\/\/editor-flow.wixapps.net\/render\/profile-card-tpa-ooi\/1.248.0\/editor\/ProfileCard.html","tpaWidgetId":"profile","appPage":{},"applicationId":2633,"appDefinitionName":"Profile Card","appDefinitionId":"14ce28f7-7eb0-3745-22f8-074b0e2401fb","allowScrolling":false},"14dd1af6-3e02-63db-0ef2-72fbc7cc3136":{"widgetUrl":"https:\/\/members.wixapps.net\/member-info\/view","mobileUrl":"https:\/\/members.wixapps.net\/member-info\/view","appPage":{"id":"member_info","name":"My Account","defaultPage":"","hidden":false,"multiInstanceEnabled":false,"order":1,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"applicationId":3202,"appDefinitionName":"Member Account Info","appDefinitionId":"14cffd81-5215-0a7f-22f8-074b0e2401fb","allowScrolling":false},"151290e1-62a2-0775-6fbc-02182fad5dec":{"widgetUrl":"https:\/\/addresses.wixapps.net\/addresses\/address-book","mobileUrl":"https:\/\/addresses.wixapps.net\/addresses\/address-book","appPage":{"id":"my_addresses","name":"My Addresses","defaultPage":"","hidden":false,"multiInstanceEnabled":false,"order":1,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"applicationId":3609,"appDefinitionName":"My Addresses","appDefinitionId":"1505b775-e885-eb1b-b665-1e485d9bf90e","allowScrolling":false},"6467c15e-af3c-4e8d-b167-41bfb8efc32a":{"widgetUrl":"https:\/\/cashier.wixapps.net\/wallet","mobileUrl":"https:\/\/cashier.wixapps.net\/wallet","appPage":{"id":"my_wallet","name":"My Wallet","defaultPage":"","hidden":false,"multiInstanceEnabled":false,"order":1,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"applicationId":4433,"appDefinitionName":"My Wallet","appDefinitionId":"4aebd0cb-fbdb-4da7-b5d1-d05660a30172","allowScrolling":false}},"appsClientSpecMapByApplicationId":{"18":{"widgets":{"141995eb-c700-8487-6366-a482f7432e2b":{"widgetUrl":"https:\/\/so-feed.codev.wixapps.net\/widget","widgetId":"141995eb-c700-8487-6366-a482f7432e2b","refreshOnWidthChange":true,"mobileUrl":"https:\/\/so-feed.codev.wixapps.net\/widget","published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{},"tpaWidgetId":"shoutout_feed","default":true}},"applicationId":18,"appDefinitionName":"Email Marketing"},"23":{"widgets":{"2b0423db-abfa-45fb-8d1e-284fed57c195":{"widgetUrl":"https:\/\/gifted.co\/wix\/card","widgetId":"2b0423db-abfa-45fb-8d1e-284fed57c195","refreshOnWidthChange":true,"mobileUrl":"https:\/\/gifted.co\/wix\/card","appPage":{"id":"Gift Card","name":"Gift Card","defaultPage":"","hidden":false,"multiInstanceEnabled":false,"order":1,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":false,"shouldBeStretchedByDefault":true,"shouldBeStretchedByDefaultMobile":true,"componentFields":{},"tpaWidgetId":"2b0423db-abfa-45fb-8d1e-284fed57c195","default":false}},"applicationId":23,"appDefinitionName":"Gifted"},"1703":{"widgets":{"1380bba0-253e-a800-a235-88821cf3f8a4":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/gallery","widgetId":"1380bba0-253e-a800-a235-88821cf3f8a4","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/gallery","appPage":{"id":"product_gallery","name":"Shop","defaultPage":"","hidden":false,"multiInstanceEnabled":true,"order":1,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"useSsrSeo":true,"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/gallery.bundle.min.js","controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/galleryController.bundle.min.js","minHeightInMobile":340,"mobileSettingsEnabled":true,"controllerUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/<%=serviceVersion('wixstores-client-gallery')%>\/galleryController.bundle.min.js","componentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/<%=serviceVersion('wixstores-client-gallery')%>\/gallery.bundle.min.js"},"default":true},"14e121c8-00a3-f7cc-6156-2c82a2ba8fcb":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/order-history","widgetId":"14e121c8-00a3-f7cc-6156-2c82a2ba8fcb","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/order-history","appPage":{"id":"order_history","name":"My Orders","defaultPage":"","hidden":true,"multiInstanceEnabled":false,"order":5,"indexable":false,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":false,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":true,"componentFields":{},"default":false},"1380bbc4-1485-9d44-4616-92e36b1ead6b":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/cartwidget","widgetId":"1380bbc4-1485-9d44-4616-92e36b1ead6b","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/cartwidget","published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-icon\/1.924.0\/cartIcon.bundle.min.js","componentName":"cartWidget","controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-icon\/1.924.0\/cartIconController.bundle.min.js","controllerUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-icon\/<%=serviceVersion('wixstores-client-cart-icon')%>\/cartIconController.bundle.min.js","componentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-icon\/<%=serviceVersion('wixstores-client-cart-icon')%>\/cartIcon.bundle.min.js","noCssComponentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-icon\/<%=serviceVersion('wixstores-client-cart-icon')%>\/cartIconNoCss.bundle.min.js"},"tpaWidgetId":"shopping_cart_icon","default":false},"13a94f09-2766-3c40-4a32-8edb5acdd8bc":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/product","widgetId":"13a94f09-2766-3c40-4a32-8edb5acdd8bc","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/product","appPage":{"id":"product_page","name":"Product Page","defaultPage":"","hidden":true,"multiInstanceEnabled":false,"order":2,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"useSsrSeo":true,"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-page\/1.1877.0\/productPage.bundle.min.js","controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-page\/1.1877.0\/productPageController.bundle.min.js","controllerUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-page\/<%=serviceVersion('wixstores-client-product-page')%>\/productPageController.bundle.min.js","componentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-page\/<%=serviceVersion('wixstores-client-product-page')%>\/productPage.bundle.min.js","noCssComponentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-page\/<%=serviceVersion('wixstores-client-product-page')%>\/productPageNoCss.bundle.min.js"},"default":false},"14fd5970-8072-c276-1246-058b79e70c1a":{"widgetUrl":"https:\/\/ecom.wixapps.net\/storefront\/checkout","widgetId":"14fd5970-8072-c276-1246-058b79e70c1a","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wixapps.net\/storefront\/checkout","appPage":{"id":"checkout","name":"Checkout","defaultPage":"","hidden":true,"multiInstanceEnabled":false,"order":6,"indexable":false,"fullPage":false,"landingPageInMobile":true,"hideFromMenu":true},"published":true,"mobilePublished":true,"seoEnabled":false,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":true,"componentFields":{"minHeightInMobile":480,"fullPageDesktopOnly":true},"default":false},"13ec3e79-e668-cc0c-2d48-e99d53a213dd":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/product-widget-view","widgetId":"13ec3e79-e668-cc0c-2d48-e99d53a213dd","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/product-widget-view","published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"useSsrSeo":true,"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-widget\/1.1031.0\/productWidget.bundle.min.js","controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-widget\/1.1031.0\/productWidgetController.bundle.min.js","minHeightInMobile":354,"controllerUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-widget\/<%=serviceVersion('wixstores-client-product-widget')%>\/productWidgetController.bundle.min.js","componentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-widget\/<%=serviceVersion('wixstores-client-product-widget')%>\/productWidget.bundle.min.js","noCssComponentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-widget\/<%=serviceVersion('wixstores-client-product-widget')%>\/productWidgetNoCss.bundle.min.js"},"tpaWidgetId":"product_widget","default":false},"14666402-0bc7-b763-e875-e99840d131bd":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/add-to-cart","widgetId":"14666402-0bc7-b763-e875-e99840d131bd","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/add-to-cart","published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-add-to-cart\/1.518.0\/addToCartController.bundle.min.js","componentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-add-to-cart\/<%=serviceVersion('wixstores-client-add-to-cart')%>\/addToCart.bundle.min.js","componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-add-to-cart\/1.518.0\/addToCart.bundle.min.js","controllerUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-add-to-cart\/<%=serviceVersion('wixstores-client-add-to-cart')%>\/addToCartController.bundle.min.js","viewer":{"errorReporting":{"url":"https:\/\/8c4075d5481d476e945486754f783364@sentry.io\/1865790"}}},"tpaWidgetId":"add_to_cart_button","default":false},"a63a5215-8aa6-42af-96b1-583bfd74cff5":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/wishlist","widgetId":"a63a5215-8aa6-42af-96b1-583bfd74cff5","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/wishlist","appPage":{"id":"wishlist","name":"My Wishlist","defaultPage":"","hidden":true,"multiInstanceEnabled":false,"order":7,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":false,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-wishlist\/1.978.0\/wishlist.bundle.min.js","controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-wishlist\/1.978.0\/wishlistController.bundle.min.js","controllerUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-wishlist\/<%=serviceVersion('wixstores-client-wishlist')%>\/wishlistController.bundle.min.js","componentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-wishlist\/<%=serviceVersion('wixstores-client-wishlist')%>\/wishlist.bundle.min.js"},"default":false},"1380bbab-4da3-36b0-efb4-2e0599971d14":{"widgetUrl":"https:\/\/editor-flow.wixapps.net\/render\/wixstores-client-cart-ooi\/1.527.0\/editor\/cart.html","widgetId":"1380bbab-4da3-36b0-efb4-2e0599971d14","refreshOnWidthChange":true,"mobileUrl":"https:\/\/editor-flow.wixapps.net\/render\/wixstores-client-cart-ooi\/1.527.0\/editor\/cart.html","appPage":{"id":"shopping_cart","name":"Cart Page","defaultPage":"","hidden":true,"multiInstanceEnabled":false,"order":3,"indexable":false,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-ooi\/1.527.0\/cartViewerWidget.bundle.min.js","controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-ooi\/1.527.0\/cartController.bundle.min.js","controllerUrlTemplate":"<%= serviceUrl('wixstores-client-cart-ooi', 'cartController.bundle.min.js') %>","componentUrlTemplate":"<%= serviceUrl('wixstores-client-cart-ooi', 'cartViewerWidget.bundle.min.js') %>"},"default":false},"13afb094-84f9-739f-44fd-78d036adb028":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/gallery","widgetId":"13afb094-84f9-739f-44fd-78d036adb028","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/gallery","published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"useSsrSeo":true,"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/gallery.bundle.min.js","controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/galleryController.bundle.min.js","mobileSettingsEnabled":true,"controllerUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/<%=serviceVersion('wixstores-client-gallery')%>\/galleryController.bundle.min.js","componentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/<%=serviceVersion('wixstores-client-gallery')%>\/gallery.bundle.min.js"},"tpaWidgetId":"grid_gallery","default":false},"139a41fd-0b1d-975f-6f67-e8cbdf8ccc82":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/minigallery","widgetId":"139a41fd-0b1d-975f-6f67-e8cbdf8ccc82","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/minigallery","published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/sliderGallery.bundle.min.js","controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/sliderGalleryController.bundle.min.js","controllerUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/<%=serviceVersion('wixstores-client-gallery')%>\/sliderGalleryController.bundle.min.js","componentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/<%=serviceVersion('wixstores-client-gallery')%>\/sliderGallery.bundle.min.js"},"tpaWidgetId":"slider_gallery","default":false},"1380bbb4-8df0-fd38-a235-88821cf3f8a4":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/success","widgetId":"1380bbb4-8df0-fd38-a235-88821cf3f8a4","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/success","appPage":{"id":"thank_you_page","name":"Thank You Page","defaultPage":"","hidden":true,"multiInstanceEnabled":false,"order":4,"indexable":false,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-worker\/1.1257.0\/thankYouPageController.bundle.min.js","iframeWithPlatform":true},"default":false}},"applicationId":1703,"appDefinitionName":"Wix Stores"},"2633":{"widgets":{"14cefc05-d163-dbb7-e4ec-cd4f2c4d6ddd":{"widgetUrl":"https:\/\/editor-flow.wixapps.net\/render\/profile-card-tpa-ooi\/1.248.0\/editor\/ProfileCard.html","widgetId":"14cefc05-d163-dbb7-e4ec-cd4f2c4d6ddd","refreshOnWidthChange":true,"mobileUrl":"https:\/\/editor-flow.wixapps.net\/render\/profile-card-tpa-ooi\/1.248.0\/editor\/ProfileCard.html","published":true,"mobilePublished":true,"seoEnabled":false,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":true,"componentFields":{"mobileSettingsEnabled":true,"controllerUrl":"https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0\/ProfileCardController.bundle.min.js","componentUrlTemplate":"<%= serviceUrl('profile-card-tpa-ooi', 'ProfileCardViewerWidget.bundle.min.js') %>","componentUrl":"https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0\/ProfileCardViewerWidget.bundle.min.js","controllerUrlTemplate":"<%= serviceUrl('profile-card-tpa-ooi', 'ProfileCardController.bundle.min.js') %>"},"tpaWidgetId":"profile","default":true}},"applicationId":2633,"appDefinitionName":"Profile Card"},"3202":{"widgets":{"14dd1af6-3e02-63db-0ef2-72fbc7cc3136":{"widgetUrl":"https:\/\/members.wixapps.net\/member-info\/view","widgetId":"14dd1af6-3e02-63db-0ef2-72fbc7cc3136","refreshOnWidthChange":true,"mobileUrl":"https:\/\/members.wixapps.net\/member-info\/view","appPage":{"id":"member_info","name":"My Account","defaultPage":"","hidden":false,"multiInstanceEnabled":false,"order":1,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":false,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":true,"componentFields":{},"default":true}},"applicationId":3202,"appDefinitionName":"Member Account Info"},"3609":{"widgets":{"151290e1-62a2-0775-6fbc-02182fad5dec":{"widgetUrl":"https:\/\/addresses.wixapps.net\/addresses\/address-book","widgetId":"151290e1-62a2-0775-6fbc-02182fad5dec","refreshOnWidthChange":true,"mobileUrl":"https:\/\/addresses.wixapps.net\/addresses\/address-book","appPage":{"id":"my_addresses","name":"My Addresses","defaultPage":"","hidden":false,"multiInstanceEnabled":false,"order":1,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":false,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":true,"componentFields":{},"default":true}},"applicationId":3609,"appDefinitionName":"My Addresses"},"4433":{"widgets":{"6467c15e-af3c-4e8d-b167-41bfb8efc32a":{"widgetUrl":"https:\/\/cashier.wixapps.net\/wallet","widgetId":"6467c15e-af3c-4e8d-b167-41bfb8efc32a","refreshOnWidthChange":true,"mobileUrl":"https:\/\/cashier.wixapps.net\/wallet","appPage":{"id":"my_wallet","name":"My Wallet","defaultPage":"","hidden":false,"multiInstanceEnabled":false,"order":1,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":false,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":true,"componentFields":{},"default":true}},"applicationId":4433,"appDefinitionName":"My Wallet"}},"appsClientSpecMapData":{"135c3d92-0fea-1f9d-2ba5-2a1dfb04297e":{"applicationId":18,"appDefinitionName":"Email Marketing","appFields":{"premiumBundle":{"parentAppId":"ee21fe60-48c5-45e9-95f4-6ca8f9b1c9d9","parentAppSlug":"ee21fe60-48c5-45e9-95f4-6ca8f9b1c9d9"}},"isWixTPA":true},"daa0ec09-7595-441b-b3ea-d275ac27b36f":{"applicationId":23,"appDefinitionName":"Gifted","appFields":{},"isWixTPA":false},"1380b703-ce81-ff05-f115-39571d94dfcd":{"applicationId":1703,"appDefinitionName":"Wix Stores","appFields":{"platform":{"baseUrls":{"galleryBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/","cartIconBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-icon\/1.924.0\/","addToCartBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-add-to-cart\/1.518.0\/","productPageBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-page\/1.1877.0\/","productWidgetBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-widget\/1.1031.0\/","staticsBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-ooi\/1.527.0","wishlistBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-wishlist\/1.978.0\/"},"editorScriptUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-worker\/1.1489.0\/editor.bundle.min.js","viewerScriptUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-worker\/1.1489.0\/viewerScript.bundle.min.js","baseUrlsTemplate":{"staticsBaseUrl":"<%= serviceUrl('wixstores-client-cart-ooi', '\/') %>","addToCartBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-add-to-cart\/<%=serviceVersion('wixstores-client-add-to-cart')%>\/","cartIconBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-icon\/<%=serviceVersion('wixstores-client-cart-icon')%>\/","productWidgetBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-widget\/<%=serviceVersion('wixstores-client-product-widget')%>\/","galleryBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/<%=serviceVersion('wixstores-client-gallery')%>\/","wishlistBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-wishlist\/<%=serviceVersion('wixstores-client-wishlist')%>\/","productPageBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-page\/<%=serviceVersion('wixstores-client-product-page')%>\/"},"margins":{"desktop":{"top":{"type":"PX","value":0},"right":{"type":"PX","value":0},"bottom":{"type":"PX","value":0},"left":{"type":"PX","value":0}}},"viewerScriptUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-worker\/<%=serviceVersion('wixstores-client-worker')%>\/viewerScript.bundle.min.js","isStretched":{"desktop":false,"tablet":false,"mobile":false},"docking":{"desktop":{"horizontal":"HCENTER","vertical":"TOP_DOCKING"}}},"appConfig":{"siteConfig":{"siteStructureApi":"wixArtifactId:com.wixpress.serverless.serverless-wixstores-tpa-site-ss"}}},"isWixTPA":true},"14ce28f7-7eb0-3745-22f8-074b0e2401fb":{"applicationId":2633,"appDefinitionName":"Profile Card","appFields":{"platform":{"editorScriptUrl":"https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0\/editorScript.bundle.min.js","baseUrls":{"staticsBaseUrl":"https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0","staticsEditorBaseUrl":"https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0"},"baseUrlsTemplate":{"staticsBaseUrl":"<%= serviceUrl('profile-card-tpa-ooi', '\/') %>"},"margins":{"desktop":{"top":{"type":"PX","value":0},"right":{"type":"PX","value":0},"bottom":{"type":"PX","value":0},"left":{"type":"PX","value":0}},"tablet":{"top":{},"right":{},"bottom":{},"left":{}},"mobile":{"top":{},"right":{},"bottom":{},"left":{}}},"height":{"desktop":{},"tablet":{},"mobile":{}},"viewerScriptUrlTemplate":"<%= serviceUrl('profile-card-tpa-ooi', 'viewerScript.bundle.min.js') %>","isStretched":{},"docking":{"desktop":{"horizontal":"HCENTER","vertical":"TOP_DOCKING"},"tablet":{},"mobile":{}},"viewerScriptUrl":"https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0\/viewerScript.bundle.min.js","errorReporting":{},"width":{"desktop":{},"tablet":{},"mobile":{}},"viewer":{"errorReporting":{}}}},"isWixTPA":true},"14cffd81-5215-0a7f-22f8-074b0e2401fb":{"applicationId":3202,"appDefinitionName":"Member Account Info","appFields":{},"isWixTPA":true},"1505b775-e885-eb1b-b665-1e485d9bf90e":{"applicationId":3609,"appDefinitionName":"My Addresses","appFields":{},"isWixTPA":true},"4aebd0cb-fbdb-4da7-b5d1-d05660a30172":{"applicationId":4433,"appDefinitionName":"My Wallet","appFields":{},"isWixTPA":true}},"previewMode":false,"siteRevision":9,"isPremiumDomain":false,"userFileDomainUrl":"filesusr.com","metaSiteId":"449452eb-9160-401f-a8e7-73181281adef","routersConfig":{"routers-kp0uk509":{"prefix":"account","appDefinitionId":"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9","config":"{\"type\":\"private\",\"patterns\":{\"\/my-account\":{\"socialHome\":false,\"appData\":{\"appDefinitionId\":\"14cffd81-5215-0a7f-22f8-074b0e2401fb\",\"appPageId\":\"member_info\",\"menuOrder\":3,\"visibleForRoles\":[]},\"page\":\"0009f56b-44da-464d-b0d0-8a468b470a9b\",\"seoData\":{\"title\":\"Мой аккаунт\",\"description\":\"\",\"keywords\":\"\",\"noIndex\":\"true\"},\"title\":\"Мой аккаунт\"}}}","group":"members","pages":{"0009f56b-44da-464d-b0d0-8a468b470a9b":"q75r8"}},"routers-kp0uk50c":{"prefix":"profile","appDefinitionId":"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9","config":"{\"type\":\"public\"}","group":"members"}},"routersByPrefix":{"account":{"routerId":"routers-kp0uk509"},"profile":{"routerId":"routers-kp0uk50c"}},"viewMode":"site","externalBaseUrl":"https:\/\/albertkeshev.wixsite.com\/my-site","tpaModalConfig":{"wixTPAs":{"4":true,"5":true,"6":true,"7":true,"8":true,"9":true,"10":true,"11":true,"12":true,"13":true,"14":true,"15":true,"16":true,"18":true,"19":true,"20":true,"21":true,"22":true,"24":true,"1703":true,"2147":true,"2633":true,"3202":true,"3609":true,"4433":true}},"appSectionParams":{},"requestUrl":"https:\/\/albertkeshev.wixsite.com\/my-site","isMobileView":false,"deviceType":"desktop","isMobileDevice":false,"extras":{"currency":"RUB"},"tpaDebugParams":{"debugApp":null,"petri_ovr":null},"locale":"ru","timeZone":"Europe\/Moscow","debug":false,"regionalLanguage":"ru"},"windowWixCodeSdk":{"locale":"ru-ru","previewMode":false,"isMobileFriendly":true,"formFactor":"Desktop","pageIdToRouterAppDefinitionId":{"q75r8":"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9"}},"wixEmbedsApi":{"isAdminPage":false},"platform":{"landingPageId":"b5oae","isChancePlatformOnLandingPage":true,"clientWorkerUrl":"https:\/\/static.parastorage.com\/services\/wix-thunderbolt\/dist\/clientWorker.88b35cf2.bundle.min.js","bootstrapData":{"isMobileView":false,"appsSpecData":{"1380b703-ce81-ff05-f115-39571d94dfcd":{"appDefinitionId":"1380b703-ce81-ff05-f115-39571d94dfcd","type":"public","instanceId":"44e6ceb6-5409-4dcf-88a7-c618f0375486","appDefinitionName":"Wix Stores","isWixTPA":true},"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9":{"appDefinitionId":"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9","type":"public","instanceId":"8705f792-8303-4421-900c-2d0428f70fff","appDefinitionName":"Members Area","isWixTPA":true},"14ce28f7-7eb0-3745-22f8-074b0e2401fb":{"appDefinitionId":"14ce28f7-7eb0-3745-22f8-074b0e2401fb","type":"public","instanceId":"c5dc63bb-f337-4e63-a717-000ce099e823","appDefinitionName":"Profile Card","isWixTPA":true}},"appsUrlData":{"1380b703-ce81-ff05-f115-39571d94dfcd":{"appDefId":"1380b703-ce81-ff05-f115-39571d94dfcd","appDefName":"Wix Stores","viewerScriptUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-worker\/1.1489.0\/viewerScript.bundle.min.js","baseUrls":{"galleryBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/","cartIconBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-icon\/1.924.0\/","addToCartBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-add-to-cart\/1.518.0\/","productPageBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-page\/1.1877.0\/","productWidgetBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-widget\/1.1031.0\/","staticsBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-ooi\/1.527.0\/","wishlistBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-wishlist\/1.978.0\/"},"widgets":{"1380bba0-253e-a800-a235-88821cf3f8a4":{"controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/galleryController.bundle.min.js","componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/gallery.bundle.min.js","noCssComponentUrl":"","widgetId":"1380bba0-253e-a800-a235-88821cf3f8a4"},"14e121c8-00a3-f7cc-6156-2c82a2ba8fcb":{"controllerUrl":"","componentUrl":"","noCssComponentUrl":"","widgetId":"14e121c8-00a3-f7cc-6156-2c82a2ba8fcb"},"1380bbc4-1485-9d44-4616-92e36b1ead6b":{"controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-icon\/1.924.0\/cartIconController.bundle.min.js","componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-icon\/1.924.0\/cartIcon.bundle.min.js","noCssComponentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-icon\/1.924.0\/cartIconNoCss.bundle.min.js","widgetId":"1380bbc4-1485-9d44-4616-92e36b1ead6b"},"13a94f09-2766-3c40-4a32-8edb5acdd8bc":{"controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-page\/1.1877.0\/productPageController.bundle.min.js","componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-page\/1.1877.0\/productPage.bundle.min.js","noCssComponentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-page\/1.1877.0\/productPageNoCss.bundle.min.js","widgetId":"13a94f09-2766-3c40-4a32-8edb5acdd8bc"},"14fd5970-8072-c276-1246-058b79e70c1a":{"controllerUrl":"","componentUrl":"","noCssComponentUrl":"","widgetId":"14fd5970-8072-c276-1246-058b79e70c1a"},"13ec3e79-e668-cc0c-2d48-e99d53a213dd":{"controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-widget\/1.1031.0\/productWidgetController.bundle.min.js","componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-widget\/1.1031.0\/productWidget.bundle.min.js","noCssComponentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-widget\/1.1031.0\/productWidgetNoCss.bundle.min.js","widgetId":"13ec3e79-e668-cc0c-2d48-e99d53a213dd"},"14666402-0bc7-b763-e875-e99840d131bd":{"controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-add-to-cart\/1.518.0\/addToCartController.bundle.min.js","componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-add-to-cart\/1.518.0\/addToCart.bundle.min.js","noCssComponentUrl":"","errorReportingUrl":"https:\/\/8c4075d5481d476e945486754f783364@sentry.io\/1865790","widgetId":"14666402-0bc7-b763-e875-e99840d131bd"},"a63a5215-8aa6-42af-96b1-583bfd74cff5":{"controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-wishlist\/1.978.0\/wishlistController.bundle.min.js","componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-wishlist\/1.978.0\/wishlist.bundle.min.js","noCssComponentUrl":"","widgetId":"a63a5215-8aa6-42af-96b1-583bfd74cff5"},"1380bbab-4da3-36b0-efb4-2e0599971d14":{"controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-ooi\/1.527.0\/cartController.bundle.min.js","componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-ooi\/1.527.0\/cartViewerWidget.bundle.min.js","noCssComponentUrl":"","widgetId":"1380bbab-4da3-36b0-efb4-2e0599971d14"},"13afb094-84f9-739f-44fd-78d036adb028":{"controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/galleryController.bundle.min.js","componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/gallery.bundle.min.js","noCssComponentUrl":"","widgetId":"13afb094-84f9-739f-44fd-78d036adb028"},"139a41fd-0b1d-975f-6f67-e8cbdf8ccc82":{"controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/sliderGalleryController.bundle.min.js","componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/sliderGallery.bundle.min.js","noCssComponentUrl":"","widgetId":"139a41fd-0b1d-975f-6f67-e8cbdf8ccc82"},"1380bbb4-8df0-fd38-a235-88821cf3f8a4":{"controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-worker\/1.1257.0\/thankYouPageController.bundle.min.js","componentUrl":"","noCssComponentUrl":"","widgetId":"1380bbb4-8df0-fd38-a235-88821cf3f8a4"}}},"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9":{"appDefId":"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9","appDefName":"Members Area","viewerScriptUrl":"https:\/\/static.parastorage.com\/services\/santa-members-viewer-app\/1.762.0\/app.bundle.min.js","baseUrls":{},"widgets":{}},"14ce28f7-7eb0-3745-22f8-074b0e2401fb":{"appDefId":"14ce28f7-7eb0-3745-22f8-074b0e2401fb","appDefName":"Profile Card","viewerScriptUrl":"https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0\/viewerScript.bundle.min.js","baseUrls":{"staticsBaseUrl":"https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0\/","staticsEditorBaseUrl":"https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0"},"widgets":{"14cefc05-d163-dbb7-e4ec-cd4f2c4d6ddd":{"controllerUrl":"https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0\/ProfileCardController.bundle.min.js","componentUrl":"https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0\/ProfileCardViewerWidget.bundle.min.js","noCssComponentUrl":"","widgetId":"14cefc05-d163-dbb7-e4ec-cd4f2c4d6ddd"}}}},"componentSdksServerUrl":"https:\/\/static.parastorage.com\/services\/editor-elements\/1.5781.0\/componentSSRSdks.bundle.js","componentSdksClientUrl":"https:\/\/static.parastorage.com\/services\/editor-elements\/dist\/componentSdks.fbf38484.bundle.min.js","location":{"domain":"wixsite.com","externalBaseUrl":"https:\/\/albertkeshev.wixsite.com\/my-site","isPremiumDomain":false,"metaSiteId":"449452eb-9160-401f-a8e7-73181281adef","userFileDomainUrl":"filesusr.com"},"bi":{"ownerId":"427fa165-cbce-4a9c-bba6-1f41b27c0ed8","isMobileFriendly":true,"isPreview":false},"platformAPIData":{"routersConfigMap":{"routers-kp0uk509":{"prefix":"account","appDefinitionId":"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9","config":"{\"type\":\"private\",\"patterns\":{\"\/my-account\":{\"socialHome\":false,\"appData\":{\"appDefinitionId\":\"14cffd81-5215-0a7f-22f8-074b0e2401fb\",\"appPageId\":\"member_info\",\"menuOrder\":3,\"visibleForRoles\":[]},\"page\":\"0009f56b-44da-464d-b0d0-8a468b470a9b\",\"seoData\":{\"title\":\"Мой аккаунт\",\"description\":\"\",\"keywords\":\"\",\"noIndex\":\"true\"},\"title\":\"Мой аккаунт\"}}}","group":"members","pages":{"0009f56b-44da-464d-b0d0-8a468b470a9b":"q75r8"}},"routers-kp0uk50c":{"prefix":"profile","appDefinitionId":"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9","config":"{\"type\":\"public\"}","group":"members"}}},"wixCodeBootstrapData":{"wixCloudBaseDomain":"wix-code.com","dbsmViewerApp":"https:\/\/static.parastorage.com\/services\/dbsm-viewer-app\/1.2624.0","wixCodePlatformBaseUrl":"https:\/\/static.parastorage.com\/services\/wix-code-platform\/1.839.0","wixCodePageIds":{},"elementorySupport":{"baseUrl":"https:\/\/albertkeshev.wixsite.com\/my-site\/_api\/wix-code-public-dispatcher\/siteview"}},"disabledPlatformApps":{},"studioAppsAppDefinitionIds":[],"widgetNames":{"1380b703-ce81-ff05-f115-39571d94dfcd":{"appDefinitionId":"1380b703-ce81-ff05-f115-39571d94dfcd","widgets":{"1380bba0-253e-a800-a235-88821cf3f8a4":"product_gallery","14e121c8-00a3-f7cc-6156-2c82a2ba8fcb":"order_history","1380bbc4-1485-9d44-4616-92e36b1ead6b":"shopping_cart_icon","13a94f09-2766-3c40-4a32-8edb5acdd8bc":"product_page","14fd5970-8072-c276-1246-058b79e70c1a":"checkout","13ec3e79-e668-cc0c-2d48-e99d53a213dd":"product_widget","14666402-0bc7-b763-e875-e99840d131bd":"add_to_cart_button","a63a5215-8aa6-42af-96b1-583bfd74cff5":"wishlist","1380bbab-4da3-36b0-efb4-2e0599971d14":"shopping_cart","13afb094-84f9-739f-44fd-78d036adb028":"grid_gallery","139a41fd-0b1d-975f-6f67-e8cbdf8ccc82":"slider_gallery","1380bbb4-8df0-fd38-a235-88821cf3f8a4":"thank_you_page"}},"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9":{"appDefinitionId":"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9","widgets":{}},"14ce28f7-7eb0-3745-22f8-074b0e2401fb":{"appDefinitionId":"14ce28f7-7eb0-3745-22f8-074b0e2401fb","widgets":{"14cefc05-d163-dbb7-e4ec-cd4f2c4d6ddd":"profile"}}},"essentials":{"appsConductedExperiments":{}}},"appsOnPageScriptsUrls":{"14ce28f7-7eb0-3745-22f8-074b0e2401fb":["https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0\/viewerScript.bundle.min.js","https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0\/ProfileCardController.bundle.min.js"],"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9":["https:\/\/static.parastorage.com\/services\/santa-members-viewer-app\/1.762.0\/app.bundle.min.js"]},"debug":{"disablePlatform":false,"disableSnapshots":false,"enableSnapshots":false}}},"siteAssets":{"dataFixersParams":{"ck":6,"experiments":{"dm_fixMobileHoverBoxDesign":true,"bv_removeMenuDataFromPageJson":true,"bv_migrateResponsiveLayoutToSingleLayoutData":true,"bv_migrateResponsiveToVariantsModels":true,"bv_cartPageResponsiveLayoutFixer":true,"bv_remove_add_chat_viewer_fixer":"new"},"dfVersion":"1.1273.0","isHttps":true,"isUrlMigrated":true,"metaSiteId":"449452eb-9160-401f-a8e7-73181281adef","quickActionsMenuEnabled":false,"siteId":"b97500a3-1350-45b0-bf57-d85911cfaba2","siteRevision":9,"v":3},"modulesParams":{"features":{"moduleName":"thunderbolt-features","contentType":"application\/json","resourceType":"features","languageResolutionMethod":"QueryParam","isMultilingualEnabled":false,"externalBaseUrl":"https:\/\/albertkeshev.wixsite.com\/my-site","useSandboxInHTMLComp":true},"platform":{"moduleName":"thunderbolt-platform","contentType":"application\/json","resourceType":"platform","externalBaseUrl":"https:\/\/albertkeshev.wixsite.com\/my-site"},"css":{"moduleName":"thunderbolt-css","contentType":"text\/css","resourceType":"css","stylableMetaData":"thunderbolt-elements.ac7f0a5e1344d4ad71c9e3b579d27c30e68f2d30","stylableMetadataURLs":null,"ooiVersions":""}},"clientTopology":{"mediaRootUrl":"https:\/\/static.wixstatic.com","staticMediaUrl":"https:\/\/static.wixstatic.com\/media","moduleRepoUrl":"https:\/\/static.parastorage.com\/unpkg","fileRepoUrl":"https:\/\/static.parastorage.com\/services","siteAssetsUrl":"https:\/\/siteassets.parastorage.com","pageJsonServerUrls":["https:\/\/pages.wixstatic.com","https:\/\/staticorigin.wixstatic.com","https:\/\/fallback.wix.com\/wix-html-editor-pages-webapp\/page"],"pathOfTBModulesInFileRepoForFallback":"wix-thunderbolt\/dist\/","pathToEditorElementsModulesInFileRepoForFallback":"editor-elements\/dist\/"},"siteScopeParams":{"wixCodePageIds":[],"hasTPAWorkerOnSite":false,"viewMode":"desktop","freemiumBanner":true,"coBrandingBanner":false,"mobileActionsMenu":false,"isWixSite":false,"urlFormatModel":{"format":"slash","forbiddenPageUriSEOs":["app","apps","_api","robots.txt","sitemap.xml","feed.xml","sites"],"pageIdToResolvedUriSEO":{}},"pageJsonFileNames":{"dxg3k":"427fa1_33f3f097eefd3794393995fca7c28f6f_9.json","s96vf":"427fa1_90ef0bdbfdbc7cc57935b700e4185e70_7.json","mm6wp":"427fa1_7a726ae54a9e5ced20dcd967e5d1c93f_9.json","s7y5i":"427fa1_a5fc5ef14a57272ed4ed172bc701aef1_9.json","wtx54":"427fa1_026c66c84ba070111d2d760d858c70b6_3.json","c42uf":"427fa1_4f4a04eefc38e59d31d08fd7725a2450_9.json","b5oae":"427fa1_ed82a8b7efcf3cde6463246d6c8b865a_9.json","masterPage":"427fa1_688aa459a4c5ad817788c570cda819e2_9.json"},"protectedPageIds":["q75r8"],"routersInfo":{"configMap":{"routers-kp0uk509":{"prefix":"account","appDefinitionId":"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9","config":"{\"type\":\"private\",\"patterns\":{\"\/my-account\":{\"socialHome\":false,\"appData\":{\"appDefinitionId\":\"14cffd81-5215-0a7f-22f8-074b0e2401fb\",\"appPageId\":\"member_info\",\"menuOrder\":3,\"visibleForRoles\":[]},\"page\":\"0009f56b-44da-464d-b0d0-8a468b470a9b\",\"seoData\":{\"title\":\"Мой аккаунт\",\"description\":\"\",\"keywords\":\"\",\"noIndex\":\"true\"},\"title\":\"Мой аккаунт\"}}}","group":"members","pages":{"0009f56b-44da-464d-b0d0-8a468b470a9b":"q75r8"}},"routers-kp0uk50c":{"prefix":"profile","appDefinitionId":"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9","config":"{\"type\":\"public\"}","group":"members"}}},"anonymousClientSpecMap":{"2":{"type":"sitemembers","applicationId":2,"collectionType":"Open","collectionFormFace":"Register","collectionExposure":"Public","smcollectionId":"449452eb-9160-401f-a8e7-73181281adef","instanceId":"","instance":""},"4":{"type":"public","applicationId":4,"appDefinitionId":"14bca956-e09f-f4d6-14d7-466cb3f09103","appDefinitionName":"Wix Cashier","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":{"platform":{"editorScriptUrl":"https:\/\/cashier.wixapps.net\/cashier-settings-server\/cashier-site-worker\/editor-script.js"}}},"5":{"type":"public","applicationId":5,"appDefinitionId":"141fbfae-511e-6817-c9f0-48993a7547d1","appDefinitionName":"Inbox","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":{}},"6":{"type":"public","applicationId":6,"appDefinitionId":"13ee94c1-b635-8505-3391-97919052c16f","appDefinitionName":"Wix Invoices","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":null},"7":{"type":"public","applicationId":7,"appDefinitionId":"150ae7ee-c74a-eecd-d3d7-2112895b988a","appDefinitionName":"Marketing Integration","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":{}},"8":{"type":"public","applicationId":8,"appDefinitionId":"a322993b-2c74-426f-bbb8-444db73d0d1b","appDefinitionName":"One App","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":{},"version":"0.0.26"},"9":{"type":"public","applicationId":9,"appDefinitionId":"55cd9036-36bb-480b-8ddc-afda3cb2eb8d","appDefinitionName":"PriceQuotes","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":{}},"10":{"type":"public","applicationId":10,"appDefinitionId":"f123e8f1-4350-4c9b-b269-04adfadda977","appDefinitionName":"Promote Home","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":{}},"11":{"type":"public","applicationId":11,"appDefinitionId":"9bead16f-1c73-4cda-b6c4-28cff46988db","appDefinitionName":"Facebook Ads","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":{}},"12":{"type":"public","applicationId":12,"appDefinitionId":"1480c568-5cbd-9392-5604-1148f5faffa0","appDefinitionName":"Get Found on Google","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":{}},"13":{"type":"public","applicationId":13,"appDefinitionId":"14d7032a-0a65-5270-cca7-30f599708fed","appDefinitionName":"WixCoupons","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":{"nonDiscoverable":true}},"14":{"type":"public","applicationId":14,"appDefinitionId":"13aa9735-aa50-4bdb-877c-0bb46804bd71","appDefinitionName":"Promote SEO Patterns","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":{}},"15":{"type":"public","applicationId":15,"appDefinitionId":"d70b68e2-8d77-4e0c-9c00-c292d6e0025e","appDefinitionName":"Promote SEO Tools","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":{}},"16":{"type":"public","applicationId":16,"appDefinitionId":"14b89688-9b25-5214-d1cb-a3fb9683618b","appDefinitionName":"Mobile App-Social Posts","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":{}},"18":{"type":"public","applicationId":18,"appDefinitionId":"135c3d92-0fea-1f9d-2ba5-2a1dfb04297e","appDefinitionName":"Email Marketing","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{"141995eb-c700-8487-6366-a482f7432e2b":{"widgetUrl":"https:\/\/so-feed.codev.wixapps.net\/widget","widgetId":"141995eb-c700-8487-6366-a482f7432e2b","refreshOnWidthChange":true,"mobileUrl":"https:\/\/so-feed.codev.wixapps.net\/widget","published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{},"tpaWidgetId":"shoutout_feed","default":true}},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":{"premiumBundle":{"parentAppId":"ee21fe60-48c5-45e9-95f4-6ca8f9b1c9d9","parentAppSlug":"ee21fe60-48c5-45e9-95f4-6ca8f9b1c9d9"}}},"19":{"type":"public","applicationId":19,"appDefinitionId":"146c0d71-352e-4464-9a03-2e868aabe7b9","appDefinitionName":"Ascend Tasks","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":{}},"20":{"type":"public","applicationId":20,"appDefinitionId":"139ef4fa-c108-8f9a-c7be-d5f492a2c939","appDefinitionName":"Automated Emails","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":null},"21":{"type":"public","applicationId":21,"appDefinitionId":"307ba931-689c-4b55-bb1d-6a382bad9222","appDefinitionName":"Video Maker","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":{}},"22":{"type":"public","applicationId":22,"appDefinitionId":"ea2821fc-7d97-40a9-9f75-772f29178430","appDefinitionName":"Workflows","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":{}},"23":{"type":"public","applicationId":23,"appDefinitionId":"daa0ec09-7595-441b-b3ea-d275ac27b36f","appDefinitionName":"Gifted","instance":"","instanceId":"","sectionUrl":"https:\/\/gifted.co\/wix\/card","sectionMobileUrl":"https:\/\/gifted.co\/wix\/card","sectionPublished":true,"sectionMobilePublished":true,"sectionSeoEnabled":true,"sectionDefaultPage":"","sectionRefreshOnWidthChange":true,"widgets":{"2b0423db-abfa-45fb-8d1e-284fed57c195":{"widgetUrl":"https:\/\/gifted.co\/wix\/card","widgetId":"2b0423db-abfa-45fb-8d1e-284fed57c195","refreshOnWidthChange":true,"mobileUrl":"https:\/\/gifted.co\/wix\/card","appPage":{"id":"Gift Card","name":"Gift Card","defaultPage":"","hidden":false,"multiInstanceEnabled":false,"order":1,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":false,"shouldBeStretchedByDefault":true,"shouldBeStretchedByDefaultMobile":true,"componentFields":{},"tpaWidgetId":"2b0423db-abfa-45fb-8d1e-284fed57c195","default":false}},"appRequirements":{"requireSiteMembers":false},"isWixTPA":false,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":{}},"24":{"type":"public","applicationId":24,"appDefinitionId":"36c09775-5ced-4ae9-9ba9-0c3119fbd7c1","appDefinitionName":"Gift Card Proxy","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":{}},"1703":{"type":"public","applicationId":1703,"appDefinitionId":"1380b703-ce81-ff05-f115-39571d94dfcd","appDefinitionName":"Wix Stores","instance":"","instanceId":"","sectionUrl":"https:\/\/ecom.wix.com\/storefront\/gallery","sectionMobileUrl":"https:\/\/ecom.wix.com\/storefront\/gallery","sectionPublished":true,"sectionMobilePublished":true,"sectionSeoEnabled":true,"sectionDefaultPage":"","sectionRefreshOnWidthChange":true,"widgets":{"1380bba0-253e-a800-a235-88821cf3f8a4":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/gallery","widgetId":"1380bba0-253e-a800-a235-88821cf3f8a4","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/gallery","appPage":{"id":"product_gallery","name":"Shop","defaultPage":"","hidden":false,"multiInstanceEnabled":true,"order":1,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"useSsrSeo":true,"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/gallery.bundle.min.js","controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/galleryController.bundle.min.js","minHeightInMobile":340,"mobileSettingsEnabled":true,"controllerUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/<%=serviceVersion('wixstores-client-gallery')%>\/galleryController.bundle.min.js","componentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/<%=serviceVersion('wixstores-client-gallery')%>\/gallery.bundle.min.js"},"default":true},"14e121c8-00a3-f7cc-6156-2c82a2ba8fcb":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/order-history","widgetId":"14e121c8-00a3-f7cc-6156-2c82a2ba8fcb","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/order-history","appPage":{"id":"order_history","name":"My Orders","defaultPage":"","hidden":true,"multiInstanceEnabled":false,"order":5,"indexable":false,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":false,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":true,"componentFields":{},"default":false},"1380bbc4-1485-9d44-4616-92e36b1ead6b":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/cartwidget","widgetId":"1380bbc4-1485-9d44-4616-92e36b1ead6b","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/cartwidget","published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-icon\/1.924.0\/cartIcon.bundle.min.js","componentName":"cartWidget","controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-icon\/1.924.0\/cartIconController.bundle.min.js","controllerUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-icon\/<%=serviceVersion('wixstores-client-cart-icon')%>\/cartIconController.bundle.min.js","componentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-icon\/<%=serviceVersion('wixstores-client-cart-icon')%>\/cartIcon.bundle.min.js","noCssComponentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-icon\/<%=serviceVersion('wixstores-client-cart-icon')%>\/cartIconNoCss.bundle.min.js"},"tpaWidgetId":"shopping_cart_icon","default":false},"13a94f09-2766-3c40-4a32-8edb5acdd8bc":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/product","widgetId":"13a94f09-2766-3c40-4a32-8edb5acdd8bc","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/product","appPage":{"id":"product_page","name":"Product Page","defaultPage":"","hidden":true,"multiInstanceEnabled":false,"order":2,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"useSsrSeo":true,"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-page\/1.1877.0\/productPage.bundle.min.js","controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-page\/1.1877.0\/productPageController.bundle.min.js","controllerUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-page\/<%=serviceVersion('wixstores-client-product-page')%>\/productPageController.bundle.min.js","componentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-page\/<%=serviceVersion('wixstores-client-product-page')%>\/productPage.bundle.min.js","noCssComponentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-page\/<%=serviceVersion('wixstores-client-product-page')%>\/productPageNoCss.bundle.min.js"},"default":false},"14fd5970-8072-c276-1246-058b79e70c1a":{"widgetUrl":"https:\/\/ecom.wixapps.net\/storefront\/checkout","widgetId":"14fd5970-8072-c276-1246-058b79e70c1a","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wixapps.net\/storefront\/checkout","appPage":{"id":"checkout","name":"Checkout","defaultPage":"","hidden":true,"multiInstanceEnabled":false,"order":6,"indexable":false,"fullPage":false,"landingPageInMobile":true,"hideFromMenu":true},"published":true,"mobilePublished":true,"seoEnabled":false,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":true,"componentFields":{"minHeightInMobile":480,"fullPageDesktopOnly":true},"default":false},"13ec3e79-e668-cc0c-2d48-e99d53a213dd":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/product-widget-view","widgetId":"13ec3e79-e668-cc0c-2d48-e99d53a213dd","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/product-widget-view","published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"useSsrSeo":true,"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-widget\/1.1031.0\/productWidget.bundle.min.js","controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-widget\/1.1031.0\/productWidgetController.bundle.min.js","minHeightInMobile":354,"controllerUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-widget\/<%=serviceVersion('wixstores-client-product-widget')%>\/productWidgetController.bundle.min.js","componentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-widget\/<%=serviceVersion('wixstores-client-product-widget')%>\/productWidget.bundle.min.js","noCssComponentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-widget\/<%=serviceVersion('wixstores-client-product-widget')%>\/productWidgetNoCss.bundle.min.js"},"tpaWidgetId":"product_widget","default":false},"14666402-0bc7-b763-e875-e99840d131bd":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/add-to-cart","widgetId":"14666402-0bc7-b763-e875-e99840d131bd","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/add-to-cart","published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-add-to-cart\/1.518.0\/addToCartController.bundle.min.js","componentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-add-to-cart\/<%=serviceVersion('wixstores-client-add-to-cart')%>\/addToCart.bundle.min.js","componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-add-to-cart\/1.518.0\/addToCart.bundle.min.js","controllerUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-add-to-cart\/<%=serviceVersion('wixstores-client-add-to-cart')%>\/addToCartController.bundle.min.js","viewer":{"errorReporting":{"url":"https:\/\/8c4075d5481d476e945486754f783364@sentry.io\/1865790"}}},"tpaWidgetId":"add_to_cart_button","default":false},"a63a5215-8aa6-42af-96b1-583bfd74cff5":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/wishlist","widgetId":"a63a5215-8aa6-42af-96b1-583bfd74cff5","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/wishlist","appPage":{"id":"wishlist","name":"My Wishlist","defaultPage":"","hidden":true,"multiInstanceEnabled":false,"order":7,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":false,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-wishlist\/1.978.0\/wishlist.bundle.min.js","controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-wishlist\/1.978.0\/wishlistController.bundle.min.js","controllerUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-wishlist\/<%=serviceVersion('wixstores-client-wishlist')%>\/wishlistController.bundle.min.js","componentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-wishlist\/<%=serviceVersion('wixstores-client-wishlist')%>\/wishlist.bundle.min.js"},"default":false},"1380bbab-4da3-36b0-efb4-2e0599971d14":{"widgetUrl":"https:\/\/editor-flow.wixapps.net\/render\/wixstores-client-cart-ooi\/1.527.0\/editor\/cart.html","widgetId":"1380bbab-4da3-36b0-efb4-2e0599971d14","refreshOnWidthChange":true,"mobileUrl":"https:\/\/editor-flow.wixapps.net\/render\/wixstores-client-cart-ooi\/1.527.0\/editor\/cart.html","appPage":{"id":"shopping_cart","name":"Cart Page","defaultPage":"","hidden":true,"multiInstanceEnabled":false,"order":3,"indexable":false,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-ooi\/1.527.0\/cartViewerWidget.bundle.min.js","controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-ooi\/1.527.0\/cartController.bundle.min.js","controllerUrlTemplate":"<%= serviceUrl('wixstores-client-cart-ooi', 'cartController.bundle.min.js') %>","componentUrlTemplate":"<%= serviceUrl('wixstores-client-cart-ooi', 'cartViewerWidget.bundle.min.js') %>"},"default":false},"13afb094-84f9-739f-44fd-78d036adb028":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/gallery","widgetId":"13afb094-84f9-739f-44fd-78d036adb028","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/gallery","published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"useSsrSeo":true,"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/gallery.bundle.min.js","controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/galleryController.bundle.min.js","mobileSettingsEnabled":true,"controllerUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/<%=serviceVersion('wixstores-client-gallery')%>\/galleryController.bundle.min.js","componentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/<%=serviceVersion('wixstores-client-gallery')%>\/gallery.bundle.min.js"},"tpaWidgetId":"grid_gallery","default":false},"139a41fd-0b1d-975f-6f67-e8cbdf8ccc82":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/minigallery","widgetId":"139a41fd-0b1d-975f-6f67-e8cbdf8ccc82","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/minigallery","published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"componentUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/sliderGallery.bundle.min.js","controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/sliderGalleryController.bundle.min.js","controllerUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/<%=serviceVersion('wixstores-client-gallery')%>\/sliderGalleryController.bundle.min.js","componentUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/<%=serviceVersion('wixstores-client-gallery')%>\/sliderGallery.bundle.min.js"},"tpaWidgetId":"slider_gallery","default":false},"1380bbb4-8df0-fd38-a235-88821cf3f8a4":{"widgetUrl":"https:\/\/ecom.wix.com\/storefront\/success","widgetId":"1380bbb4-8df0-fd38-a235-88821cf3f8a4","refreshOnWidthChange":true,"mobileUrl":"https:\/\/ecom.wix.com\/storefront\/success","appPage":{"id":"thank_you_page","name":"Thank You Page","defaultPage":"","hidden":true,"multiInstanceEnabled":false,"order":4,"indexable":false,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":true,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":false,"componentFields":{"controllerUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-worker\/1.1257.0\/thankYouPageController.bundle.min.js","iframeWithPlatform":true},"default":false}},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":false,"permissions":{"revoked":true},"appFields":{"platform":{"baseUrls":{"galleryBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/1.2087.0\/","cartIconBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-icon\/1.924.0\/","addToCartBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-add-to-cart\/1.518.0\/","productPageBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-page\/1.1877.0\/","productWidgetBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-widget\/1.1031.0\/","staticsBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-ooi\/1.527.0","wishlistBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-wishlist\/1.978.0\/"},"editorScriptUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-worker\/1.1489.0\/editor.bundle.min.js","viewerScriptUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-worker\/1.1489.0\/viewerScript.bundle.min.js","baseUrlsTemplate":{"staticsBaseUrl":"<%= serviceUrl('wixstores-client-cart-ooi', '\/') %>","addToCartBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-add-to-cart\/<%=serviceVersion('wixstores-client-add-to-cart')%>\/","cartIconBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-cart-icon\/<%=serviceVersion('wixstores-client-cart-icon')%>\/","productWidgetBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-widget\/<%=serviceVersion('wixstores-client-product-widget')%>\/","galleryBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-gallery\/<%=serviceVersion('wixstores-client-gallery')%>\/","wishlistBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-wishlist\/<%=serviceVersion('wixstores-client-wishlist')%>\/","productPageBaseUrl":"https:\/\/static.parastorage.com\/services\/wixstores-client-product-page\/<%=serviceVersion('wixstores-client-product-page')%>\/"},"margins":{"desktop":{"top":{"type":"PX","value":0},"right":{"type":"PX","value":0},"bottom":{"type":"PX","value":0},"left":{"type":"PX","value":0}}},"viewerScriptUrlTemplate":"https:\/\/static.parastorage.com\/services\/wixstores-client-worker\/<%=serviceVersion('wixstores-client-worker')%>\/viewerScript.bundle.min.js","isStretched":{"desktop":false,"tablet":false,"mobile":false},"docking":{"desktop":{"horizontal":"HCENTER","vertical":"TOP_DOCKING"}}},"appConfig":{"siteConfig":{"siteStructureApi":"wixArtifactId:com.wixpress.serverless.serverless-wixstores-tpa-site-ss"}}}},"2147":{"type":"public","applicationId":2147,"appDefinitionId":"14cc59bc-f0b7-15b8-e1c7-89ce41d0e0c9","appDefinitionName":"Members Area","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":true,"permissions":{"revoked":false},"appFields":{"platform":{"editorScriptUrl":"https:\/\/static.parastorage.com\/services\/santa-members-editor-app\/1.1234.0\/editorAppModule.bundle.min.js","viewerScriptUrl":"https:\/\/static.parastorage.com\/services\/santa-members-viewer-app\/1.762.0\/app.bundle.min.js","routerServiceUrl":"\/_api\/santa-members-server","viewerScriptUrlTemplate":""}}},"2633":{"type":"public","applicationId":2633,"appDefinitionId":"14ce28f7-7eb0-3745-22f8-074b0e2401fb","appDefinitionName":"Profile Card","instance":"","instanceId":"","sectionPublished":true,"sectionMobilePublished":false,"sectionSeoEnabled":true,"widgets":{"14cefc05-d163-dbb7-e4ec-cd4f2c4d6ddd":{"widgetUrl":"https:\/\/editor-flow.wixapps.net\/render\/profile-card-tpa-ooi\/1.248.0\/editor\/ProfileCard.html","widgetId":"14cefc05-d163-dbb7-e4ec-cd4f2c4d6ddd","refreshOnWidthChange":true,"mobileUrl":"https:\/\/editor-flow.wixapps.net\/render\/profile-card-tpa-ooi\/1.248.0\/editor\/ProfileCard.html","published":true,"mobilePublished":true,"seoEnabled":false,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":true,"componentFields":{"mobileSettingsEnabled":true,"controllerUrl":"https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0\/ProfileCardController.bundle.min.js","componentUrlTemplate":"<%= serviceUrl('profile-card-tpa-ooi', 'ProfileCardViewerWidget.bundle.min.js') %>","componentUrl":"https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0\/ProfileCardViewerWidget.bundle.min.js","controllerUrlTemplate":"<%= serviceUrl('profile-card-tpa-ooi', 'ProfileCardController.bundle.min.js') %>"},"tpaWidgetId":"profile","default":true}},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":false,"permissions":{"revoked":false},"appFields":{"platform":{"editorScriptUrl":"https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0\/editorScript.bundle.min.js","baseUrls":{"staticsBaseUrl":"https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0","staticsEditorBaseUrl":"https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0"},"baseUrlsTemplate":{"staticsBaseUrl":"<%= serviceUrl('profile-card-tpa-ooi', '\/') %>"},"margins":{"desktop":{"top":{"type":"PX","value":0},"right":{"type":"PX","value":0},"bottom":{"type":"PX","value":0},"left":{"type":"PX","value":0}},"tablet":{"top":{},"right":{},"bottom":{},"left":{}},"mobile":{"top":{},"right":{},"bottom":{},"left":{}}},"height":{"desktop":{},"tablet":{},"mobile":{}},"viewerScriptUrlTemplate":"<%= serviceUrl('profile-card-tpa-ooi', 'viewerScript.bundle.min.js') %>","isStretched":{},"docking":{"desktop":{"horizontal":"HCENTER","vertical":"TOP_DOCKING"},"tablet":{},"mobile":{}},"viewerScriptUrl":"https:\/\/static.parastorage.com\/services\/profile-card-tpa-ooi\/1.248.0\/viewerScript.bundle.min.js","errorReporting":{},"width":{"desktop":{},"tablet":{},"mobile":{}},"viewer":{"errorReporting":{}}}}},"3202":{"type":"public","applicationId":3202,"appDefinitionId":"14cffd81-5215-0a7f-22f8-074b0e2401fb","appDefinitionName":"Member Account Info","instance":"","instanceId":"","sectionUrl":"https:\/\/members.wixapps.net\/member-info\/view","sectionMobileUrl":"https:\/\/members.wixapps.net\/member-info\/view","sectionPublished":true,"sectionMobilePublished":true,"sectionSeoEnabled":true,"sectionDefaultPage":"","sectionRefreshOnWidthChange":true,"widgets":{"14dd1af6-3e02-63db-0ef2-72fbc7cc3136":{"widgetUrl":"https:\/\/members.wixapps.net\/member-info\/view","widgetId":"14dd1af6-3e02-63db-0ef2-72fbc7cc3136","refreshOnWidthChange":true,"mobileUrl":"https:\/\/members.wixapps.net\/member-info\/view","appPage":{"id":"member_info","name":"My Account","defaultPage":"","hidden":false,"multiInstanceEnabled":false,"order":1,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":false,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":true,"componentFields":{},"default":true}},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":false,"permissions":{"revoked":false},"appFields":{}},"3609":{"type":"public","applicationId":3609,"appDefinitionId":"1505b775-e885-eb1b-b665-1e485d9bf90e","appDefinitionName":"My Addresses","instance":"","instanceId":"","sectionUrl":"https:\/\/addresses.wixapps.net\/addresses\/address-book","sectionMobileUrl":"https:\/\/addresses.wixapps.net\/addresses\/address-book","sectionPublished":true,"sectionMobilePublished":true,"sectionSeoEnabled":false,"sectionDefaultPage":"","sectionRefreshOnWidthChange":true,"widgets":{"151290e1-62a2-0775-6fbc-02182fad5dec":{"widgetUrl":"https:\/\/addresses.wixapps.net\/addresses\/address-book","widgetId":"151290e1-62a2-0775-6fbc-02182fad5dec","refreshOnWidthChange":true,"mobileUrl":"https:\/\/addresses.wixapps.net\/addresses\/address-book","appPage":{"id":"my_addresses","name":"My Addresses","defaultPage":"","hidden":false,"multiInstanceEnabled":false,"order":1,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":false,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":true,"componentFields":{},"default":true}},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":false,"permissions":{"revoked":true},"appFields":{}},"4433":{"type":"public","applicationId":4433,"appDefinitionId":"4aebd0cb-fbdb-4da7-b5d1-d05660a30172","appDefinitionName":"My Wallet","instance":"","instanceId":"","sectionUrl":"https:\/\/cashier.wixapps.net\/wallet","sectionMobileUrl":"https:\/\/cashier.wixapps.net\/wallet","sectionPublished":true,"sectionMobilePublished":true,"sectionSeoEnabled":false,"sectionDefaultPage":"","sectionRefreshOnWidthChange":true,"widgets":{"6467c15e-af3c-4e8d-b167-41bfb8efc32a":{"widgetUrl":"https:\/\/cashier.wixapps.net\/wallet","widgetId":"6467c15e-af3c-4e8d-b167-41bfb8efc32a","refreshOnWidthChange":true,"mobileUrl":"https:\/\/cashier.wixapps.net\/wallet","appPage":{"id":"my_wallet","name":"My Wallet","defaultPage":"","hidden":false,"multiInstanceEnabled":false,"order":1,"indexable":true,"fullPage":false,"landingPageInMobile":false,"hideFromMenu":false},"published":true,"mobilePublished":true,"seoEnabled":false,"preFetch":false,"shouldBeStretchedByDefault":false,"shouldBeStretchedByDefaultMobile":true,"componentFields":{},"default":true}},"appRequirements":{"requireSiteMembers":false},"isWixTPA":true,"installedAtDashboard":false,"permissions":{"revoked":true},"appFields":{}},"-666":{"type":"metasite","metaSiteId":"449452eb-9160-401f-a8e7-73181281adef","appDefId":"22bef345-3c5b-4c18-b782-74d4085112ff","instance":"","appDefinitionId":"22bef345-3c5b-4c18-b782-74d4085112ff","applicationId":-666,"instanceId":""}},"isPremiumDomain":false,"tbElementsSiteAssets":"siteAssets.e448a59d.bundle.min.js","disableSiteAssetsCache":false,"migratingToOoiWidgetIds":"","widgetsToPageJsonFilenames":{},"siteRevisionConfig":{},"registryLibrariesTopology":[{"artifactId":"editor-elements","url":"https:\/\/static.parastorage.com\/services\/editor-elements\/1.5781.0","manifestName":"library-manifest","namespace":"wixui"},{"artifactId":"editor-elements-design-systems","url":"https:\/\/static.parastorage.com\/services\/editor-elements\/1.5781.0","manifestName":"design-systems-manifest","namespace":"dsgnsys"}],"isInSeo":false,"language":"ru","originalLanguage":"en"},"beckyExperiments":{"specs.thunderbolt.stylableCssPerComponent":true,"specs.thunderbolt.addressInputAtlasProvider":true,"specs.thunderbolt.seoFriendlyDropDownMenu":true,"specs.thunderbolt.image_placeholder":true,"specs.thunderbolt.tb_omitInlineContent":true,"tb_UploadButtonFixValidationNotRequired":true,"specs.thunderbolt.tb_pinLayerDockedBottom":true,"specs.thunderbolt.tb_media_layout_by_effect":true},"manifests":{"node":{"modulesToHashes":{"thunderbolt-css":"299e17dd.bundle.min","thunderbolt-features":"c4324d7e.bundle.min","thunderbolt-platform":"e61e2930.bundle.min"}},"web":{"modulesToHashes":{"webpack-runtime":"29425a48.bundle.min","thunderbolt-css":"9f6694a8.chunk.min","thunderbolt-features":"94e8f292.chunk.min","thunderbolt-platform":"85f6a7d1.chunk.min"},"webpackRuntimeBundle":"29425a48.bundle.min"},"webWorker":{"modulesToHashes":{"thunderbolt-css":"a9810ac5.bundle.min","thunderbolt-features":"ea431625.bundle.min","thunderbolt-platform":"5c1b51ed.bundle.min"}}},"tbElementsManifests":{"web":{"modulesToHashes":{"siteAssets":"05020ce4.chunk.min","webpack-runtime":"d721250b.bundle.min","thunderbolt-elements.03a8805908245ab59e0a22760130ac4e1740f1c4.metadata":"json"},"webpackRuntimeBundle":"d721250b.bundle.min"},"node":{"modulesToHashes":{"siteAssets":"e448a59d.bundle.min"}},"webWorker":{"modulesToHashes":{"siteAssets":"663e5bf1.bundle.min"}}},"staticHTMLComponentUrl":"https:\/\/albertkeshev-wixsite-com.filesusr.com\/","remoteWidgetStructureBuilderVersion":"1.226.0"},"experiments":{"storeSanpshotOnRedis":true,"specs.thunderbolt.sm_redirectToResetPasswordLinkOnTokenExpired":true,"dm_fixMobileHoverBoxDesign":true,"specs.thunderbolt.stylableCssPerComponent":true,"specs.thunderbolt.addressInputAtlasProvider":true,"specs.thunderbolt.seoFriendlyDropDownMenu":true,"specs.thunderbolt.RenderMultilingualInSEOFeature":true,"specs.thunderbolt.stylableInteractions":true,"specs.thunderbolt.encode_redirect_url":true,"specs.thunderbolt.addUtmParamsToBiEvents":true,"bv_removeMenuDataFromPageJson":true,"specs.thunderbolt.sm_platformizedLogin":true,"specs.thunderbolt.sm_displayLoginAsAPopup":true,"specs.thunderbolt.image_placeholder":true,"specs.thunderbolt.inject_namespaces_to_wix_code":true,"specs.thunderbolt.wixCodeUseGlobalsObject":true,"specs.promote.ar.reportRestOfEventsToFacebook":true,"bv_migrateResponsiveLayoutToSingleLayoutData":true,"specs.thunderbolt.tb_omitInlineContent":true,"specs.thunderbolt.enableSsrChunkedStreaming":true,"specs.thunderbolt.safari_sticky_fix":true,"specs.promote.ar.capiExtendedFields":true,"tb_UploadButtonFixValidationNotRequired":true,"specs.promote.ar.reportLeadToFacebook":true,"specs.thunderbolt.tb_pinLayerDockedBottom":true,"specs.thunderbolt.prefetch_instead_script":true,"specs.thunderbolt.oldBrowsersDeprecation":true,"specs.thunderbolt.editor_elements_site_assets":true,"specs.thunderbolt.do_not_handle_tpa_messages_from_different_origin":true,"specs.thunderbolt.reducedMotion":true,"displayWixAdsNewVersion":true,"specs.thunderbolt.shouldEnableSACFallbackForClientWorker":true,"specs.thunderbolt.ooi_css_optimization":true,"oneAppWixAds":true,"specs.thunderbolt.enableClientSideRenderTrailingHeader":true,"specs.promote.ar.useStoresPurchaseFBServerEvent":true,"specs.promote.ar.capiIdentifyAdvancedSource":true,"specs.thunderbolt.tb_media_layout_by_effect":true,"specs.thunderbolt.removeCookieFromLanguageDetection":true,"specs.thunderbolt.seoAsNewPageFalse":true,"bv_migrateResponsiveToVariantsModels":true,"specs.thunderbolt.newAuthorizedPagesFlow":true,"bv_cartPageResponsiveLayoutFixer":true,"specs.thunderbolt.platformWebVitals":true,"specs.promote.ar.capiUseFacebookSetupCache":true,"specs.thunderbolt.resourceFetcherConformToFetchApi":true},"fleetConfig":{"fleetName":"thunderbolt-renderer-light","type":"GA","code":0},"dynamicModelUrl":"https:\/\/albertkeshev.wixsite.com\/my-site\/_api\/v2\/dynamicmodel","rollout":{"siteAssetsVersionsRollout":false,"isDACRollout":0,"isTBRollout":false},"commonConfig":{"brand":"wix","bsi":"","consentPolicy":{},"consentPolicyHeader":{}}}
        </script>
        <script>
            window.viewerModel = JSON.parse(document.getElementById('wix-viewer-model').textContent)
            window.fetchDynamicModel = fetch(window.viewerModel.dynamicModelUrl, {
                credentials: 'same-origin'
            }).then(function(r) {
                return r.ok ? r.json() : "[" + r.status + "] " + r.statusText
            }).catch(function(e) {
                return e.message;
            });
            window.commonConfig = viewerModel.commonConfig
        </script>
        <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/externals-registry.inline.351fb32a.chunk.min.js">
            (window.webpackJsonp__wix_thunderbolt_app = window.webpackJsonp__wix_thunderbolt_app || []).push([[54], {
                130: function(e, n, o) {
                    "use strict";
                    var a = window.externalsRegistry = {
                        lodash: {},
                        react: {},
                        reactDOM: {}
                    }
                      , d = a.lodash
                      , w = a.react
                      , i = a.reactDOM;
                    d.loaded = new Promise((function(e) {
                        d.onload = e
                    }
                    )),
                    window.reactDOMReference = window.ReactDOM = {
                        loading: !0
                    },
                    i.loaded = new Promise((function(e) {
                        i.onload = function() {
                            Object.assign(window.reactDOMReference, window.ReactDOM),
                            e()
                        }
                    }
                    )),
                    window.reactReference = window.React = {
                        loading: !0
                    },
                    w.loaded = new Promise((function(e) {
                        w.onload = function() {
                            Object.assign(window.reactReference, window.React),
                            e()
                        }
                    }
                    )),
                    window.reactAndReactDOMLoaded = Promise.all([w.loaded, i.loaded])
                }
            }, [[130, 2]]]);
            //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/externals-registry.inline.351fb32a.chunk.min.js.map
        </script>
        <!-- thunderbolt elements promise -->
        <script>
            window.ThunderboltElementsLoaded = new Promise(function(r) {
                window.ThunderboltElementsLoadedResolve = r
            }
            )
        </script>
        <!-- bi -->
        <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/tslib.inline.16efbe29.chunk.min.js">
            (window.webpackJsonp__wix_thunderbolt_app = window.webpackJsonp__wix_thunderbolt_app || []).push([[5], [function(t, n, r) {
                "use strict";
                r.d(n, "c", (function() {
                    return o
                }
                )),
                r.d(n, "a", (function() {
                    return u
                }
                )),
                r.d(n, "f", (function() {
                    return c
                }
                )),
                r.d(n, "b", (function() {
                    return i
                }
                )),
                r.d(n, "d", (function() {
                    return a
                }
                )),
                r.d(n, "i", (function() {
                    return l
                }
                )),
                r.d(n, "e", (function() {
                    return f
                }
                )),
                r.d(n, "g", (function() {
                    return p
                }
                )),
                r.d(n, "h", (function() {
                    return y
                }
                ));
                var e = function(t, n) {
                    return (e = Object.setPrototypeOf || {
                        __proto__: []
                    }instanceof Array && function(t, n) {
                        t.__proto__ = n
                    }
                    || function(t, n) {
                        for (var r in n)
                            Object.prototype.hasOwnProperty.call(n, r) && (t[r] = n[r])
                    }
                    )(t, n)
                };
                function o(t, n) {
                    if ("function" != typeof n && null !== n)
                        throw new TypeError("Class extends value " + String(n) + " is not a constructor or null");
                    function r() {
                        this.constructor = t
                    }
                    e(t, n),
                    t.prototype = null === n ? Object.create(n) : (r.prototype = n.prototype,
                    new r)
                }
                var u = function() {
                    return (u = Object.assign || function(t) {
                        for (var n, r = 1, e = arguments.length; r < e; r++)
                            for (var o in n = arguments[r])
                                Object.prototype.hasOwnProperty.call(n, o) && (t[o] = n[o]);
                        return t
                    }
                    ).apply(this, arguments)
                };
                function c(t, n) {
                    var r = {};
                    for (var e in t)
                        Object.prototype.hasOwnProperty.call(t, e) && n.indexOf(e) < 0 && (r[e] = t[e]);
                    if (null != t && "function" == typeof Object.getOwnPropertySymbols) {
                        var o = 0;
                        for (e = Object.getOwnPropertySymbols(t); o < e.length; o++)
                            n.indexOf(e[o]) < 0 && Object.prototype.propertyIsEnumerable.call(t, e[o]) && (r[e[o]] = t[e[o]])
                    }
                    return r
                }
                function i(t, n, r, e) {
                    return new (r || (r = Promise))((function(o, u) {
                        function c(t) {
                            try {
                                a(e.next(t))
                            } catch (t) {
                                u(t)
                            }
                        }
                        function i(t) {
                            try {
                                a(e.throw(t))
                            } catch (t) {
                                u(t)
                            }
                        }
                        function a(t) {
                            var n;
                            t.done ? o(t.value) : (n = t.value,
                            n instanceof r ? n : new r((function(t) {
                                t(n)
                            }
                            ))).then(c, i)
                        }
                        a((e = e.apply(t, n || [])).next())
                    }
                    ))
                }
                function a(t, n) {
                    var r, e, o, u, c = {
                        label: 0,
                        sent: function() {
                            if (1 & o[0])
                                throw o[1];
                            return o[1]
                        },
                        trys: [],
                        ops: []
                    };
                    return u = {
                        next: i(0),
                        throw: i(1),
                        return: i(2)
                    },
                    "function" == typeof Symbol && (u[Symbol.iterator] = function() {
                        return this
                    }
                    ),
                    u;
                    function i(u) {
                        return function(i) {
                            return function(u) {
                                if (r)
                                    throw new TypeError("Generator is already executing.");
                                for (; c; )
                                    try {
                                        if (r = 1,
                                        e && (o = 2 & u[0] ? e.return : u[0] ? e.throw || ((o = e.return) && o.call(e),
                                        0) : e.next) && !(o = o.call(e, u[1])).done)
                                            return o;
                                        switch (e = 0,
                                        o && (u = [2 & u[0], o.value]),
                                        u[0]) {
                                        case 0:
                                        case 1:
                                            o = u;
                                            break;
                                        case 4:
                                            return c.label++,
                                            {
                                                value: u[1],
                                                done: !1
                                            };
                                        case 5:
                                            c.label++,
                                            e = u[1],
                                            u = [0];
                                            continue;
                                        case 7:
                                            u = c.ops.pop(),
                                            c.trys.pop();
                                            continue;
                                        default:
                                            if (!(o = c.trys,
                                            (o = o.length > 0 && o[o.length - 1]) || 6 !== u[0] && 2 !== u[0])) {
                                                c = 0;
                                                continue
                                            }
                                            if (3 === u[0] && (!o || u[1] > o[0] && u[1] < o[3])) {
                                                c.label = u[1];
                                                break
                                            }
                                            if (6 === u[0] && c.label < o[1]) {
                                                c.label = o[1],
                                                o = u;
                                                break
                                            }
                                            if (o && c.label < o[2]) {
                                                c.label = o[2],
                                                c.ops.push(u);
                                                break
                                            }
                                            o[2] && c.ops.pop(),
                                            c.trys.pop();
                                            continue
                                        }
                                        u = n.call(t, c)
                                    } catch (t) {
                                        u = [6, t],
                                        e = 0
                                    } finally {
                                        r = o = 0
                                    }
                                if (5 & u[0])
                                    throw u[1];
                                return {
                                    value: u[0] ? u[1] : void 0,
                                    done: !0
                                }
                            }([u, i])
                        }
                    }
                }
                Object.create;
                function l(t) {
                    var n = "function" == typeof Symbol && Symbol.iterator
                      , r = n && t[n]
                      , e = 0;
                    if (r)
                        return r.call(t);
                    if (t && "number" == typeof t.length)
                        return {
                            next: function() {
                                return t && e >= t.length && (t = void 0),
                                {
                                    value: t && t[e++],
                                    done: !t
                                }
                            }
                        };
                    throw new TypeError(n ? "Object is not iterable." : "Symbol.iterator is not defined.")
                }
                function f(t, n) {
                    var r = "function" == typeof Symbol && t[Symbol.iterator];
                    if (!r)
                        return t;
                    var e, o, u = r.call(t), c = [];
                    try {
                        for (; (void 0 === n || n-- > 0) && !(e = u.next()).done; )
                            c.push(e.value)
                    } catch (t) {
                        o = {
                            error: t
                        }
                    } finally {
                        try {
                            e && !e.done && (r = u.return) && r.call(u)
                        } finally {
                            if (o)
                                throw o.error
                        }
                    }
                    return c
                }
                function p() {
                    for (var t = [], n = 0; n < arguments.length; n++)
                        t = t.concat(f(arguments[n]));
                    return t
                }
                function y(t, n) {
                    for (var r = 0, e = n.length, o = t.length; r < e; r++,
                    o++)
                        t[o] = n[r];
                    return t
                }
                Object.create
            }
            ]]);
            //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/tslib.inline.16efbe29.chunk.min.js.map
        </script>
        <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/bi.inline.9872fcd4.chunk.min.js">
            (window.webpackJsonp__wix_thunderbolt_app = window.webpackJsonp__wix_thunderbolt_app || []).push([[24], {
                74: function(n, I, N) {
                    "use strict";
                    var A, E;
                    N.d(I, "a", (function() {
                        return A
                    }
                    )),
                    N.d(I, "b", (function() {
                        return E
                    }
                    )),
                    N.d(I, "c", (function() {
                        return _
                    }
                    )),
                    function(n) {
                        n[n.START = 1] = "START",
                        n[n.VISIBLE = 2] = "VISIBLE",
                        n[n.PAGE_FINISH = 33] = "PAGE_FINISH",
                        n[n.FIRST_CDN_RESPONSE = 4] = "FIRST_CDN_RESPONSE",
                        n[n.TBD = -1] = "TBD",
                        n[n.PAGE_NAVIGATION = 101] = "PAGE_NAVIGATION",
                        n[n.PAGE_NAVIGATION_DONE = 103] = "PAGE_NAVIGATION_DONE"
                    }(A || (A = {})),
                    function(n) {
                        n[n.NAVIGATION = 1] = "NAVIGATION",
                        n[n.DYNAMIC_REDIRECT = 2] = "DYNAMIC_REDIRECT",
                        n[n.INNER_ROUTE = 3] = "INNER_ROUTE",
                        n[n.NAVIGATION_ERROR = 4] = "NAVIGATION_ERROR",
                        n[n.CANCELED = 5] = "CANCELED"
                    }(E || (E = {}));
                    var _ = {
                        1: "page-navigation",
                        2: "page-navigation-redirect",
                        3: "page-navigation-inner-route",
                        4: "navigation-error",
                        5: "navigation-canceled"
                    }
                }
            }, [[12, 2, 5, 6]]]);
            //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/bi.inline.9872fcd4.chunk.min.js.map
        </script>
        <script>
            window.bi.sendBeat(1, 'Init')
        </script>
        <!-- preloading pre-scripts -->
        <!-- renderIndicator -->
        <!-- initial scripts -->
        <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/createPlatformWorker.inline.a232993f.chunk.min.js">
            (window.webpackJsonp__wix_thunderbolt_app = window.webpackJsonp__wix_thunderbolt_app || []).push([[44], {
                98: function(e, r, t) {
                    "use strict";
                    t.r(r),
                    t.d(r, "platformWorkerPromise", (function() {
                        return l
                    }
                    ));
                    var a = t(0)
                      , o = window.viewerModel
                      , n = o.siteAssets.clientTopology
                      , s = o.siteFeatures
                      , i = o.siteFeaturesConfigs.platform
                      , c = o.experiments
                      , p = s.includes("platform");
                    var l = p ? function() {
                        return Object(a.b)(this, void 0, void 0, (function() {
                            var e, r, t, o, s, p;
                            return Object(a.d)(this, (function(a) {
                                switch (a.label) {
                                case 0:
                                    return e = "platform_create-worker started",
                                    performance.mark(e),
                                    (r = i.clientWorkerUrl).startsWith("http://localhost:4200/") || r.startsWith("https://bo.wix.com/suricate/") ? [4, (l = i.clientWorkerUrl,
                                    u = new Blob(["importScripts('" + l + "');"],{
                                        type: "application/javascript"
                                    }),
                                    URL.createObjectURL(u))] : [3, 2];
                                case 1:
                                    return o = a.sent(),
                                    [3, 3];
                                case 2:
                                    o = r.replace(n.fileRepoUrl, "/_partials"),
                                    a.label = 3;
                                case 3:
                                    return t = o,
                                    c["specs.thunderbolt.platform_worker_on_dom_interactive"] ? [4, new Promise((function(e) {
                                        document.addEventListener("readystatechange", (function() {
                                            "interactive" === document.readyState && e()
                                        }
                                        ), {
                                            once: !0
                                        })
                                    }
                                    ))] : [3, 5];
                                case 4:
                                    a.sent(),
                                    a.label = 5;
                                case 5:
                                    return (s = new Worker(t)).postMessage({
                                        type: "platformScriptsOnPage",
                                        appsOnPageScriptsUrls: i.appsOnPageScriptsUrls
                                    }),
                                    p = "platform_create-worker ended",
                                    performance.mark(p),
                                    performance.measure("Create Platform Web Worker", e, p),
                                    [2, s]
                                }
                                var l, u
                            }
                            ))
                        }
                        ))
                    }() : Promise.resolve()
                }
            }, [[98, 2, 5]]]);
            //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/createPlatformWorker.inline.a232993f.chunk.min.js.map
        </script>
        <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/windowMessageRegister.inline.390f3824.chunk.min.js">
            (window.webpackJsonp__wix_thunderbolt_app = window.webpackJsonp__wix_thunderbolt_app || []).push([[156], {
                178: function(n, e, a) {
                    "use strict";
                    a.r(e),
                    function(n) {
                        var e = new Set
                          , a = []
                          , t = function(n) {
                            var a = [];
                            e.forEach((function(e) {
                                n.canHandleEvent(e) && a.push(e)
                            }
                            )),
                            a.forEach((function(a) {
                                e.delete(a),
                                n.handleEvent(a)
                            }
                            ))
                        };
                        n.addEventListener("message", (function(n) {
                            var o = {
                                source: n.source,
                                data: n.data,
                                origin: n.origin
                            }
                              , d = a.find((function(n) {
                                return n.canHandleEvent(o)
                            }
                            ));
                            d ? (t(d),
                            d.handleEvent(o)) : e.add(o)
                        }
                        )),
                        n._addWindowMessageHandler = function(n) {
                            a.push(n),
                            t(n)
                        }
                    }(window)
                }
            }, [[178, 2]]]);
            //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/windowMessageRegister.inline.390f3824.chunk.min.js.map
        </script>
        <script src="https://static.parastorage.com/services/wix-thunderbolt/dist/bootstrap-features.3fc05d6d.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/wix-thunderbolt/dist/main.d7c292fe.chunk.min.js" async=""></script>
        <!-- lodash script -->
        <script async="" onload="externalsRegistry.lodash.onload()" src="https://static.parastorage.com/unpkg/lodash@4.17.15/lodash.min.js"></script>
        <!-- react -->
        <script crossorigin src="https://static.parastorage.com/unpkg/react@16.13.1/umd/react.production.min.js" onload="externalsRegistry.react.onload()" defer=""></script>
        <!-- siteFeatureChunks -->
        <script async="" src="https://static.parastorage.com/services/wix-thunderbolt/dist/wix-code-sdk-providers.31bdeb35.chunk.min.js"></script>
        <script async="" src="https://static.parastorage.com/services/wix-thunderbolt/dist/dynamicPages.9b452069.chunk.min.js"></script>
        <script async="" src="https://static.parastorage.com/services/wix-thunderbolt/dist/page-features.4bf20dc4.chunk.min.js"></script>
        <script async="" src="https://static.parastorage.com/services/wix-thunderbolt/dist/ooi.b29aa2e0.chunk.min.js"></script>
        <script async="" src="https://static.parastorage.com/services/wix-thunderbolt/dist/popups.137437b2.chunk.min.js"></script>
        <script async="" src="https://static.parastorage.com/services/wix-thunderbolt/dist/protectedPages.74a7e435.chunk.min.js"></script>
        <script async="" src="https://static.parastorage.com/services/wix-thunderbolt/dist/siteMembers.02ecf8c9.chunk.min.js"></script>
        <script async="" src="https://static.parastorage.com/services/wix-thunderbolt/dist/tpaCommons.635c4163.chunk.min.js"></script>
        <script async="" src="https://static.parastorage.com/services/wix-thunderbolt/dist/windowMessageRegistrar.b866bae7.chunk.min.js"></script>
        <script async="" src="https://static.parastorage.com/services/wix-thunderbolt/dist/platform.87784f29.chunk.min.js"></script>
        <!-- preloading post-scripts -->
        <link rel="preload" crossorigin="anonymous" as="fetch" href="https://siteassets.parastorage.com/pages/pages/thunderbolt?beckyExperiments=specs.thunderbolt.stylableCssPerComponent%3Atrue%2Cspecs.thunderbolt.addressInputAtlasProvider%3Atrue%2Cspecs.thunderbolt.seoFriendlyDropDownMenu%3Atrue%2Cspecs.thunderbolt.image_placeholder%3Atrue%2Cspecs.thunderbolt.tb_omitInlineContent%3Atrue%2Ctb_UploadButtonFixValidationNotRequired%3Atrue%2Cspecs.thunderbolt.tb_pinLayerDockedBottom%3Atrue%2Cspecs.thunderbolt.tb_media_layout_by_effect%3Atrue&amp;contentType=application%2Fjson&amp;dfCk=6&amp;dfVersion=1.1273.0&amp;experiments=bv_cartPageResponsiveLayoutFixer%2Cbv_migrateResponsiveLayoutToSingleLayoutData%2Cbv_migrateResponsiveToVariantsModels%2Cbv_removeMenuDataFromPageJson%2Cbv_remove_add_chat_viewer_fixer%2Cdm_fixMobileHoverBoxDesign&amp;externalBaseUrl=https%3A%2F%2Falbertkeshev.wixsite.com%2Fmy-site&amp;fileId=e61e2930.bundle.min&amp;freemiumBanner=true&amp;hasTPAWorkerOnSite=false&amp;isHttps=true&amp;isInSeo=false&amp;isUrlMigrated=true&amp;isWixCodeOnPage=false&amp;isWixCodeOnSite=false&amp;language=ru&amp;metaSiteId=449452eb-9160-401f-a8e7-73181281adef&amp;module=thunderbolt-platform&amp;originalLanguage=en&amp;pageId=427fa1_688aa459a4c5ad817788c570cda819e2_9.json&amp;quickActionsMenuEnabled=false&amp;registryLibrariesTopology=%5B%7B%22artifactId%22%3A%22editor-elements%22%2C%22url%22%3A%22https%3A%2F%2Fstatic.parastorage.com%2Fservices%2Feditor-elements%2F1.5781.0%22%2C%22manifestName%22%3A%22library-manifest%22%2C%22namespace%22%3A%22wixui%22%7D%2C%7B%22artifactId%22%3A%22editor-elements-design-systems%22%2C%22url%22%3A%22https%3A%2F%2Fstatic.parastorage.com%2Fservices%2Feditor-elements%2F1.5781.0%22%2C%22manifestName%22%3A%22design-systems-manifest%22%2C%22namespace%22%3A%22dsgnsys%22%7D%5D&amp;remoteWidgetStructureBuilderVersion=1.226.0&amp;siteId=b97500a3-1350-45b0-bf57-d85911cfaba2&amp;siteRevision=9&amp;tbElementsSiteAssets=siteAssets.e448a59d.bundle.min.js&amp;viewMode=desktop" id="platform_masterPage">
        <link rel="preload" crossorigin="anonymous" as="fetch" href="https://siteassets.parastorage.com/pages/pages/thunderbolt?beckyExperiments=specs.thunderbolt.stylableCssPerComponent%3Atrue%2Cspecs.thunderbolt.addressInputAtlasProvider%3Atrue%2Cspecs.thunderbolt.seoFriendlyDropDownMenu%3Atrue%2Cspecs.thunderbolt.image_placeholder%3Atrue%2Cspecs.thunderbolt.tb_omitInlineContent%3Atrue%2Ctb_UploadButtonFixValidationNotRequired%3Atrue%2Cspecs.thunderbolt.tb_pinLayerDockedBottom%3Atrue%2Cspecs.thunderbolt.tb_media_layout_by_effect%3Atrue&amp;contentType=application%2Fjson&amp;dfCk=6&amp;dfVersion=1.1273.0&amp;experiments=bv_cartPageResponsiveLayoutFixer%2Cbv_migrateResponsiveLayoutToSingleLayoutData%2Cbv_migrateResponsiveToVariantsModels%2Cbv_removeMenuDataFromPageJson%2Cbv_remove_add_chat_viewer_fixer%2Cdm_fixMobileHoverBoxDesign&amp;externalBaseUrl=https%3A%2F%2Falbertkeshev.wixsite.com%2Fmy-site&amp;fileId=e61e2930.bundle.min&amp;freemiumBanner=true&amp;hasTPAWorkerOnSite=false&amp;isHttps=true&amp;isInSeo=false&amp;isUrlMigrated=true&amp;isWixCodeOnPage=false&amp;isWixCodeOnSite=false&amp;language=ru&amp;metaSiteId=449452eb-9160-401f-a8e7-73181281adef&amp;module=thunderbolt-platform&amp;originalLanguage=en&amp;pageId=427fa1_ed82a8b7efcf3cde6463246d6c8b865a_9.json&amp;quickActionsMenuEnabled=false&amp;registryLibrariesTopology=%5B%7B%22artifactId%22%3A%22editor-elements%22%2C%22url%22%3A%22https%3A%2F%2Fstatic.parastorage.com%2Fservices%2Feditor-elements%2F1.5781.0%22%2C%22manifestName%22%3A%22library-manifest%22%2C%22namespace%22%3A%22wixui%22%7D%2C%7B%22artifactId%22%3A%22editor-elements-design-systems%22%2C%22url%22%3A%22https%3A%2F%2Fstatic.parastorage.com%2Fservices%2Feditor-elements%2F1.5781.0%22%2C%22manifestName%22%3A%22design-systems-manifest%22%2C%22namespace%22%3A%22dsgnsys%22%7D%5D&amp;remoteWidgetStructureBuilderVersion=1.226.0&amp;siteId=b97500a3-1350-45b0-bf57-d85911cfaba2&amp;siteRevision=9&amp;tbElementsSiteAssets=siteAssets.e448a59d.bundle.min.js&amp;viewMode=desktop" id="platform_b5oae">
        <link rel="preload" crossorigin="anonymous" as="script" href="https://static.parastorage.com/services/editor-elements/dist/componentSdks.fbf38484.bundle.min.js" id="componentSdks">
        <link rel="preload" crossorigin="anonymous" as="fetch" href="https://siteassets.parastorage.com/pages/pages/thunderbolt?beckyExperiments=specs.thunderbolt.stylableCssPerComponent%3Atrue%2Cspecs.thunderbolt.addressInputAtlasProvider%3Atrue%2Cspecs.thunderbolt.seoFriendlyDropDownMenu%3Atrue%2Cspecs.thunderbolt.image_placeholder%3Atrue%2Cspecs.thunderbolt.tb_omitInlineContent%3Atrue%2Ctb_UploadButtonFixValidationNotRequired%3Atrue%2Cspecs.thunderbolt.tb_pinLayerDockedBottom%3Atrue%2Cspecs.thunderbolt.tb_media_layout_by_effect%3Atrue&amp;contentType=application%2Fjson&amp;deviceType=Desktop&amp;dfCk=6&amp;dfVersion=1.1273.0&amp;experiments=bv_cartPageResponsiveLayoutFixer%2Cbv_migrateResponsiveLayoutToSingleLayoutData%2Cbv_migrateResponsiveToVariantsModels%2Cbv_removeMenuDataFromPageJson%2Cbv_remove_add_chat_viewer_fixer%2Cdm_fixMobileHoverBoxDesign&amp;externalBaseUrl=https%3A%2F%2Falbertkeshev.wixsite.com%2Fmy-site&amp;fileId=c4324d7e.bundle.min&amp;freemiumBanner=true&amp;hasTPAWorkerOnSite=false&amp;isHttps=true&amp;isInSeo=false&amp;isMultilingualEnabled=false&amp;isUrlMigrated=true&amp;isWixCodeOnPage=false&amp;isWixCodeOnSite=false&amp;language=ru&amp;languageResolutionMethod=QueryParam&amp;metaSiteId=449452eb-9160-401f-a8e7-73181281adef&amp;module=thunderbolt-features&amp;originalLanguage=en&amp;pageId=427fa1_688aa459a4c5ad817788c570cda819e2_9.json&amp;quickActionsMenuEnabled=false&amp;registryLibrariesTopology=%5B%7B%22artifactId%22%3A%22editor-elements%22%2C%22url%22%3A%22https%3A%2F%2Fstatic.parastorage.com%2Fservices%2Feditor-elements%2F1.5781.0%22%2C%22manifestName%22%3A%22library-manifest%22%2C%22namespace%22%3A%22wixui%22%7D%2C%7B%22artifactId%22%3A%22editor-elements-design-systems%22%2C%22url%22%3A%22https%3A%2F%2Fstatic.parastorage.com%2Fservices%2Feditor-elements%2F1.5781.0%22%2C%22manifestName%22%3A%22design-systems-manifest%22%2C%22namespace%22%3A%22dsgnsys%22%7D%5D&amp;remoteWidgetStructureBuilderVersion=1.226.0&amp;siteId=b97500a3-1350-45b0-bf57-d85911cfaba2&amp;siteRevision=9&amp;staticHTMLComponentUrl=https%3A%2F%2Falbertkeshev-wixsite-com.filesusr.com%2F&amp;tbElementsSiteAssets=siteAssets.e448a59d.bundle.min.js&amp;useSandboxInHTMLComp=true&amp;viewMode=desktop" id="features_masterPage">
        <link rel="preload" crossorigin="anonymous" as="fetch" href="https://siteassets.parastorage.com/pages/pages/thunderbolt?beckyExperiments=specs.thunderbolt.stylableCssPerComponent%3Atrue%2Cspecs.thunderbolt.addressInputAtlasProvider%3Atrue%2Cspecs.thunderbolt.seoFriendlyDropDownMenu%3Atrue%2Cspecs.thunderbolt.image_placeholder%3Atrue%2Cspecs.thunderbolt.tb_omitInlineContent%3Atrue%2Ctb_UploadButtonFixValidationNotRequired%3Atrue%2Cspecs.thunderbolt.tb_pinLayerDockedBottom%3Atrue%2Cspecs.thunderbolt.tb_media_layout_by_effect%3Atrue&amp;contentType=application%2Fjson&amp;deviceType=Desktop&amp;dfCk=6&amp;dfVersion=1.1273.0&amp;experiments=bv_cartPageResponsiveLayoutFixer%2Cbv_migrateResponsiveLayoutToSingleLayoutData%2Cbv_migrateResponsiveToVariantsModels%2Cbv_removeMenuDataFromPageJson%2Cbv_remove_add_chat_viewer_fixer%2Cdm_fixMobileHoverBoxDesign&amp;externalBaseUrl=https%3A%2F%2Falbertkeshev.wixsite.com%2Fmy-site&amp;fileId=c4324d7e.bundle.min&amp;freemiumBanner=true&amp;hasTPAWorkerOnSite=false&amp;isHttps=true&amp;isInSeo=false&amp;isMultilingualEnabled=false&amp;isUrlMigrated=true&amp;isWixCodeOnPage=false&amp;isWixCodeOnSite=false&amp;language=ru&amp;languageResolutionMethod=QueryParam&amp;metaSiteId=449452eb-9160-401f-a8e7-73181281adef&amp;module=thunderbolt-features&amp;originalLanguage=en&amp;pageId=427fa1_ed82a8b7efcf3cde6463246d6c8b865a_9.json&amp;quickActionsMenuEnabled=false&amp;registryLibrariesTopology=%5B%7B%22artifactId%22%3A%22editor-elements%22%2C%22url%22%3A%22https%3A%2F%2Fstatic.parastorage.com%2Fservices%2Feditor-elements%2F1.5781.0%22%2C%22manifestName%22%3A%22library-manifest%22%2C%22namespace%22%3A%22wixui%22%7D%2C%7B%22artifactId%22%3A%22editor-elements-design-systems%22%2C%22url%22%3A%22https%3A%2F%2Fstatic.parastorage.com%2Fservices%2Feditor-elements%2F1.5781.0%22%2C%22manifestName%22%3A%22design-systems-manifest%22%2C%22namespace%22%3A%22dsgnsys%22%7D%5D&amp;remoteWidgetStructureBuilderVersion=1.226.0&amp;siteId=b97500a3-1350-45b0-bf57-d85911cfaba2&amp;siteRevision=9&amp;staticHTMLComponentUrl=https%3A%2F%2Falbertkeshev-wixsite-com.filesusr.com%2F&amp;tbElementsSiteAssets=siteAssets.e448a59d.bundle.min.js&amp;useSandboxInHTMLComp=true&amp;viewMode=desktop" id="features_b5oae">
        <!-- tbElements css -->
        <!-- Initial CSS -->
        <style data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/main.9395f539.chunk.min.css">
            a,abbr,acronym,address,applet,b,big,blockquote,body,button,caption,center,cite,code,dd,del,dfn,div,dl,dt,em,fieldset,font,footer,form,h1,h2,h3,h4,h5,h6,header,html,i,iframe,img,ins,kbd,label,legend,li,nav,object,ol,p,pre,q,s,samp,section,small,span,strike,strong,sub,sup,table,tbody,td,tfoot,th,thead,title,tr,tt,u,ul,var {
                margin: 0;
                padding: 0;
                border: 0;
                outline: 0;
                vertical-align: baseline;
                background: transparent
            }

            body {
                font-size: 10px;
                font-family: Arial,Helvetica,sans-serif
            }

            input,select,textarea {
                font-family: Helvetica,Arial,sans-serif;
                box-sizing: border-box
            }

            ol,ul {
                list-style: none
            }

            blockquote,q {
                quotes: none
            }

            ins {
                text-decoration: none
            }

            del {
                text-decoration: line-through
            }

            table {
                border-collapse: collapse;
                border-spacing: 0
            }

            a {
                cursor: pointer;
                text-decoration: none
            }

            body,html {
                height: 100%
            }

            body {
                overflow-x: auto;
                overflow-y: scroll
            }

            body.overflowHidden {
                overflow: hidden
            }

            .testStyles {
                overflow-y: hidden
            }

            .reset-button {
                background: none;
                border: 0;
                outline: 0;
                color: inherit;
                font: inherit;
                line-height: normal;
                overflow: visible;
                padding: 0;
                -webkit-appearance: none;
                -webkit-user-select: none;
                -moz-user-select: none;
                -ms-user-select: none
            }

            :focus {
                outline: none
            }

            body.device-mobile-optimized {
                overflow-x: hidden;
                overflow-y: scroll
            }

            body.device-mobile-optimized:not(.responsive) #SITE_CONTAINER {
                width: 320px;
                overflow-x: visible;
                position: relative
            }

            body.device-mobile-optimized:not(.responsive):not(.blockSiteScrolling) #SITE_CONTAINER {
                margin: 0 auto
            }

            body.device-mobile-optimized>* {
                max-width: 100%!important
            }

            body.device-mobile-optimized #site-root {
                overflow-x: hidden;
                overflow-y: hidden
            }

            body.device-mobile-non-optimized #SITE_CONTAINER #site-root {
                overflow-x: hidden;
                overflow-y: auto
            }

            body.device-mobile-non-optimized.fullScreenMode {
                background-color: #5f6360
            }

            body.device-mobile-non-optimized.fullScreenMode #MOBILE_ACTIONS_MENU,body.device-mobile-non-optimized.fullScreenMode #site-root,body.device-mobile-non-optimized.fullScreenMode #SITE_BACKGROUND,body.fullScreenMode #WIX_ADS {
                visibility: hidden
            }

            body.fullScreenMode {
                overflow-x: hidden!important;
                overflow-y: hidden!important
            }

            body.fullScreenMode.device-mobile-optimized #TINY_MENU {
                opacity: 0;
                pointer-events: none
            }

            body.fullScreenMode-scrollable.device-mobile-optimized {
                overflow-x: hidden!important;
                overflow-y: auto!important
            }

            body.fullScreenMode-scrollable.device-mobile-optimized #masterPage,body.fullScreenMode-scrollable.device-mobile-optimized #site-root {
                overflow-x: hidden!important;
                overflow-y: hidden!important
            }

            body.fullScreenMode-scrollable.device-mobile-optimized #masterPage,body.fullScreenMode-scrollable.device-mobile-optimized #SITE_BACKGROUND {
                height: auto!important
            }

            body.fullScreenMode-scrollable.device-mobile-optimized #masterPage.mesh-layout {
                height: 0!important
            }

            body.blockSiteScrolling {
                position: fixed;
                width: 100%;
                overflow: hidden
            }

            body.blockSiteScrolling #SITE_CONTAINER {
                margin-top: calc(var(--blocked-site-scroll-margin-top) * -1)
            }

            body.blockSiteScrolling:not(.responsive) #WIX_ADS {
                margin-top: var(--blocked-site-scroll-margin-top)
            }

            .fullScreenOverlay {
                z-index: 1005;
                position: fixed;
                left: 0;
                top: -60px;
                right: 0;
                bottom: 0;
                display: flex;
                justify-content: center;
                overflow-y: hidden
            }

            .fullScreenOverlay>.fullScreenOverlayContent {
                margin: 0 auto;
                position: absolute;
                right: 0;
                top: 60px;
                left: 0;
                bottom: 0;
                overflow: hidden;
                transform: translateZ(0)
            }

            [data-mesh-id$=centeredContent],[data-mesh-id$=form],[data-mesh-id$=inlineContent] {
                position: relative;
                pointer-events: none
            }

            [data-mesh-id$=-gridWrapper],[data-mesh-id$=-rotated-wrapper] {
                pointer-events: none
            }

            [data-mesh-id$=-gridContainer]>*,[data-mesh-id$=-rotated-wrapper]>*,[data-mesh-id$=inlineContent]>:not([data-mesh-id$=-gridContainer]) {
                pointer-events: auto
            }

            .device-mobile-optimized #masterPage.mesh-layout #SOSP_CONTAINER_CUSTOM_ID {
                -ms-grid-row: 2;
                grid-area: 2/1/3/2;
                position: relative
            }

            #masterPage.mesh-layout {
                display: -ms-grid;
                display: grid;
                -ms-grid-rows: max-content max-content min-content max-content;
                grid-template-rows: -webkit-max-content -webkit-max-content -webkit-min-content -webkit-max-content;
                grid-template-rows: max-content max-content min-content max-content;
                -ms-grid-columns: 100%;
                grid-template-columns: 100%;
                align-items: start;
                justify-content: stretch
            }

            #masterPage.mesh-layout #PAGES_CONTAINER,#masterPage.mesh-layout #SITE_FOOTER-placeholder,#masterPage.mesh-layout #SITE_FOOTER_WRAPPER,#masterPage.mesh-layout #SITE_HEADER-placeholder,#masterPage.mesh-layout #SITE_HEADER_WRAPPER,#masterPage.mesh-layout #soapAfterPagesContainer,#masterPage.mesh-layout #soapBeforePagesContainer,#masterPage.mesh-layout #SOSP_CONTAINER_CUSTOM_ID[data-state~=mobileView] {
                -ms-grid-column: 1;
                -ms-grid-row-align: start;
                -ms-grid-column-align: start
            }

            #masterPage.mesh-layout #SITE_HEADER-placeholder,#masterPage.mesh-layout #SITE_HEADER_WRAPPER {
                -ms-grid-row: 1;
                grid-area: 1/1/2/2
            }

            #masterPage.mesh-layout #PAGES_CONTAINER,#masterPage.mesh-layout #soapAfterPagesContainer,#masterPage.mesh-layout #soapBeforePagesContainer {
                -ms-grid-row: 3;
                grid-area: 3/1/4/2
            }

            #masterPage.mesh-layout #soapAfterPagesContainer,#masterPage.mesh-layout #soapBeforePagesContainer {
                width: 100%
            }

            #masterPage.mesh-layout #PAGES_CONTAINER {
                align-self: stretch
            }

            #masterPage.mesh-layout main#PAGES_CONTAINER {
                display: block
            }

            #masterPage.mesh-layout #SITE_FOOTER-placeholder,#masterPage.mesh-layout #SITE_FOOTER_WRAPPER {
                -ms-grid-row: 4;
                grid-area: 4/1/5/2
            }

            #masterPage.mesh-layout #SITE_PAGES,#masterPage.mesh-layout [data-mesh-id=PAGES_CONTAINERcenteredContent],#masterPage.mesh-layout [data-mesh-id=PAGES_CONTAINERinlineContent] {
                height: 100%
            }

            #masterPage.mesh-layout.desktop>* {
                width: 100%
            }

            #masterPage.mesh-layout #masterPageinlineContent,#masterPage.mesh-layout #PAGES_CONTAINER,#masterPage.mesh-layout #SITE_FOOTER,#masterPage.mesh-layout #SITE_FOOTER_WRAPPER,#masterPage.mesh-layout #SITE_HEADER,#masterPage.mesh-layout #SITE_HEADER_WRAPPER,#masterPage.mesh-layout #SITE_PAGES,#site-root {
                position: relative
            }

            #site-root {
                top: var(--wix-ads-top-height);
                min-height: 100%;
                margin: 0 auto
            }

            #site-root img:not([src]) {
                visibility: hidden
            }

            #site-root svg img:not([src]) {
                visibility: visible
            }

            body:not(.responsive) #site-root {
                width: 100%;
                min-width: var(--site-width)
            }

            #SITE_CONTAINER {
                position: relative
            }

            .auto-generated-link {
                color: inherit
            }

            body:not([data-js-loaded]) [data-hide-prejs] {
                visibility: hidden
            }

            #SCROLL_TO_BOTTOM,#SCROLL_TO_TOP {
                height: 0
            }

            [data-z-counter] {
                z-index: 0
            }

            [data-z-counter="0"] {
                z-index: auto
            }

            .wixSiteProperties {
                -webkit-font-smoothing: antialiased;
                -moz-osx-font-smoothing: grayscale
            }
        </style>
        <script defer src="https://static.parastorage.com/services/tag-manager-client/1.423.0/siteTags.bundle.min.js"></script>
        <meta name="format-detection" content="telephone=no">
        <meta name="skype_toolbar" content="skype_toolbar_parser_compatible">
        <!--pageHtmlEmbeds.head start-->
        <script type="wix/htmlEmbeds" id="pageHtmlEmbeds.head start"></script>
        <script type="wix/htmlEmbeds" id="pageHtmlEmbeds.head end"></script>
        <!--pageHtmlEmbeds.head end-->
        <!-- initCustomElements -->
        <meta name="wix-dynamic-custom-elements" content="DropDownMenu">
        <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/initCustomElements.inline.891d7f64.chunk.min.js">
            (window.webpackJsonp__wix_thunderbolt_app = window.webpackJsonp__wix_thunderbolt_app || []).push([[65, 24], {
                127: function(e, t) {
                    !function() {
                        if (void 0 !== window.Reflect && void 0 !== window.customElements && !window.customElements.hasOwnProperty("polyfillWrapFlushCallback")) {
                            var e = HTMLElement;
                            window.HTMLElement = function() {
                                return Reflect.construct(e, [], this.constructor)
                            }
                            ,
                            HTMLElement.prototype = e.prototype,
                            HTMLElement.prototype.constructor = HTMLElement,
                            Object.setPrototypeOf(HTMLElement, e)
                        }
                    }()
                },
                169: function(e, t, i) {
                    "use strict";
                    i.r(t);
                    var r = i(0)
                      , n = i(41)
                      , a = i.n(n)
                      , o = i(12)
                      , s = i(33)
                      , c = i(90)
                      , u = i.n(c)
                      , l = i(19)
                      , h = i.n(l)
                      , d = function(e, t, i) {
                        var r = (Array.isArray(t) ? t : t.split(".")).reduce((function(e, t) {
                            return e && void 0 !== e[t] ? e[t] : null
                        }
                        ), e);
                        return null !== r ? r : i
                    }
                      , f = function(e, t) {
                        return (Array.isArray(t) ? t : [t]).reduce((function(t, i) {
                            var r, n = d(e, i);
                            return void 0 !== n ? Object.assign(t, ((r = {})[i] = n,
                            r)) : t
                        }
                        ), {})
                    };
                    function p() {
                        for (var e = arguments.length, t = new Array(e), i = 0; i < e; i++)
                            t[i] = arguments[i];
                        for (var r = t[0], n = 1; n < t.length; ++n)
                            r = r.replace(/\/$/, "") + "/" + t[n].replace(/^\//, "");
                        return r
                    }
                    var g = function(e, t, i) {
                        if (!e.containerWidth || !e.containerHeight || !e.imageData.uri)
                            return {
                                uri: "",
                                css: {}
                            };
                        var r = e.imageData
                          , n = e.displayMode || h.a.fittingTypes.SCALE_TO_FILL
                          , a = Object.assign(f(r, "upscaleMethod"), f(e, "filters"), e.quality || r.quality)
                          , o = d(e.imageData, "devicePixelRatio", t.devicePixelRatio)
                          , s = b(o)
                          , c = Object.assign(f(r, ["width", "height", "crop", "name", "focalPoint"]), {
                            id: r.uri
                        })
                          , u = {
                            width: e.containerWidth,
                            height: e.containerHeight,
                            htmlTag: i || "img",
                            pixelAspectRatio: s,
                            alignment: e.alignType || h.a.alignTypes.CENTER
                        }
                          , l = h.a.getData(n, c, u, a);
                        return l.uri = m(l.uri, t.staticMediaUrl, t.mediaRootUrl),
                        l
                    }
                      , m = function(e, t, i) {
                        if (/(^https?)|(^data)|(^blob)|(^\/\/)/.test(e))
                            return e;
                        var r = t + "/";
                        return e && (/^micons\//.test(e) ? r = i : "ico" === /[^.]+$/.exec(e)[0] && (r = r.replace("media", "ficons"))),
                        r + e
                    }
                      , b = function(e) {
                        var t = window.location.search.split("&").map((function(e) {
                            return e.split("=")
                        }
                        )).find((function(e) {
                            return e[0].toLowerCase().includes("devicepixelratio")
                        }
                        ));
                        return (t ? Number(t[1]) : null) || e || 1
                    }
                      , v = function(e, t) {
                        return e.getAttribute(t ? "xlink:href" : "src")
                    };
                    var T = {
                        columnCount: 1,
                        columns: 1,
                        fontWeight: 1,
                        lineHeight: 1,
                        opacity: 1,
                        zIndex: 1,
                        zoom: 1
                    }
                      , _ = function(e, t) {
                        return e && t && Object.keys(t).forEach((function(i) {
                            return e.setAttribute(i, t[i])
                        }
                        ))
                    }
                      , y = function(e, t) {
                        return e && t && Object.keys(t).forEach((function(i) {
                            var r = t[i];
                            void 0 !== r ? e.style[i] = function(e, t) {
                                return "number" != typeof t || T[e] ? t : t + "px"
                            }(i, r) : e.style.removeProperty(i)
                        }
                        ))
                    }
                      , I = function(e, t) {
                        return e && t && Object.keys(t).forEach((function(i) {
                            e.style.setProperty(i, t[i])
                        }
                        ))
                    }
                      , E = function(e, t, i) {
                        return void 0 === i && (i = !0),
                        e && i ? (r = e.dataset[t]) ? "true" === r || "false" !== r && ("null" === r ? null : "" + +r === r ? +r : r) : r : e.dataset[t];
                        var r
                    }
                      , A = function(e, t) {
                        return e && t && Object.assign(e.dataset, t)
                    }
                      , w = function() {
                        return window ? window.innerHeight || document.documentElement.clientHeight : 0
                    };
                    var O = {
                        measure: function(e, t, i, r, n) {
                            var a = r.containerId
                              , o = r.bgEffectName
                              , s = i[e]
                              , c = i[a]
                              , u = n.getMediaDimensionsByEffect(o, c.offsetWidth, c.offsetHeight, w())
                              , l = u.width
                              , h = u.height;
                            t.width = l,
                            t.height = h,
                            t.currentSrc = s.style.backgroundImage,
                            t.bgEffectName = s.dataset.bgEffectName
                        },
                        patch: function(e, t, i, r, n) {
                            var a = i[e];
                            r.containerWidth = t.width,
                            r.containerHeight = t.height;
                            var o, s, c = g(r, n, "bg");
                            o = t.currentSrc,
                            s = c.uri,
                            void 0 === o && (o = ""),
                            o.includes(s) && !!o == !!s ? y(a, c.css.container) : function(e, t) {
                                var i = Object.assign({
                                    backgroundImage: 'url("' + t.uri + '")'
                                }, t.css.container)
                                  , r = new Image;
                                r.onload = y.bind(null, e, i),
                                r.src = t.uri
                            }(a, c)
                        }
                    };
                    function S(e, t) {
                        for (var i = 0; i < t.length; i++) {
                            var r = t[i];
                            r.enumerable = r.enumerable || !1,
                            r.configurable = !0,
                            "value"in r && (r.writable = !0),
                            Object.defineProperty(e, r.key, r)
                        }
                    }
                    function L(e, t) {
                        return (L = Object.setPrototypeOf || function(e, t) {
                            return e.__proto__ = t,
                            e
                        }
                        )(e, t)
                    }
                    var M = function(e, t, i) {
                        return function(e) {
                            var r, n;
                            function a() {
                                return e.call(this) || this
                            }
                            n = e,
                            (r = a).prototype = Object.create(n.prototype),
                            r.prototype.constructor = r,
                            L(r, n);
                            var o, s, c, u = a.prototype;
                            return u.reLayout = function() {
                                if (!t.isExperimentOpen("specs.thunderbolt.tb_stop_client_images")) {
                                    var e = {}
                                      , r = {}
                                      , n = this.getAttribute("id")
                                      , a = JSON.parse(this.dataset.tiledImageInfo)
                                      , o = this.dataset.bgEffectName
                                      , s = a.containerId
                                      , c = document.getElementById(s);
                                    e[n] = this,
                                    e[s] = c,
                                    a.displayMode = a.imageData.displayMode,
                                    t.mutationService.measure((function() {
                                        O.measure(n, r, e, {
                                            containerId: s,
                                            bgEffectName: o
                                        }, t)
                                    }
                                    )),
                                    t.mutationService.mutate((function() {
                                        O.patch(n, r, e, a, i)
                                    }
                                    ))
                                }
                            }
                            ,
                            u.attributeChangedCallback = function(e, t) {
                                t && this.reLayout()
                            }
                            ,
                            u.disconnectedCallback = function() {
                                e.prototype.disconnectedCallback.call(this)
                            }
                            ,
                            o = a,
                            c = [{
                                key: "observedAttributes",
                                get: function() {
                                    return ["data-tiled-image-info"]
                                }
                            }],
                            (s = null) && S(o.prototype, s),
                            c && S(o, c),
                            a
                        }(e)
                    };
                    function R(e, t) {
                        for (var i = 0; i < t.length; i++) {
                            var r = t[i];
                            r.enumerable = r.enumerable || !1,
                            r.configurable = !0,
                            "value"in r && (r.writable = !0),
                            Object.defineProperty(e, r.key, r)
                        }
                    }
                    function x(e, t) {
                        return (x = Object.setPrototypeOf || function(e, t) {
                            return e.__proto__ = t,
                            e
                        }
                        )(e, t)
                    }
                    var P = function(e, t) {
                        var i = {
                            width: void 0,
                            height: void 0,
                            left: void 0
                        };
                        return function(e) {
                            var r, n;
                            function a() {
                                return e.call(this) || this
                            }
                            n = e,
                            (r = a).prototype = Object.create(n.prototype),
                            r.prototype.constructor = r,
                            x(r, n);
                            var o, s, c, u = a.prototype;
                            return u.reLayout = function() {
                                var e = this
                                  , r = this.dataset
                                  , n = r.containerId
                                  , a = r.pageId
                                  , o = r.useCssVars
                                  , s = r.bgEffectName
                                  , c = document.getElementById("" + n)
                                  , u = document.getElementById("" + a)
                                  , l = {};
                                t.mutationService.measure((function() {
                                    var i = "fixed" === window.getComputedStyle(e).position
                                      , r = document.documentElement.clientHeight
                                      , n = c.getBoundingClientRect()
                                      , a = u.getBoundingClientRect()
                                      , h = t.getMediaDimensionsByEffect(s, n.width, n.height, r)
                                      , d = h.hasParallax
                                      , f = h.width
                                      , p = h.height
                                      , g = f + "px"
                                      , m = p + "px"
                                      , b = i ? n.left - a.left + "px" : (n.width - f) / 2 + "px"
                                      , v = i || d ? 0 : (n.height - p) / 2 + "px"
                                      , T = o ? {
                                        "--containerW": g,
                                        "--containerH": m,
                                        "--containerL": b,
                                        "--screenH_val": "" + r
                                    } : {
                                        width: g,
                                        height: m,
                                        left: b,
                                        top: v
                                    };
                                    Object.assign(l, T)
                                }
                                )),
                                t.mutationService.mutate((function() {
                                    o ? (y(e, i),
                                    I(e, l)) : y(e, l)
                                }
                                ))
                            }
                            ,
                            u.connectedCallback = function() {
                                e.prototype.connectedCallback.call(this),
                                t.windowResizeService.observe(this)
                            }
                            ,
                            u.disconnectedCallback = function() {
                                e.prototype.disconnectedCallback.call(this),
                                t.windowResizeService.unobserve(this)
                            }
                            ,
                            u.attributeChangedCallback = function(e, t) {
                                t && this.reLayout()
                            }
                            ,
                            o = a,
                            c = [{
                                key: "observedAttributes",
                                get: function() {
                                    return ["data-is-full-height", "data-container-size"]
                                }
                            }],
                            (s = null) && R(o.prototype, s),
                            c && R(o, c),
                            a
                        }(e)
                    }
                      , C = function(e, t, i, r, n, a, o, s) {
                        if (e -= n * (o ? r.length : r.length - 1),
                        e -= s.left + s.right,
                        t && (r = r.map((function() {
                            return a
                        }
                        ))),
                        r.some((function(e) {
                            return 0 === e
                        }
                        )))
                            return null;
                        var c = 0
                          , u = r.reduce((function(e, t) {
                            return e + t
                        }
                        ), 0);
                        if (u > e)
                            return null;
                        if (t) {
                            if (i) {
                                var l = Math.floor(e / r.length)
                                  , h = r.map((function() {
                                    return l
                                }
                                ));
                                if ((c = l * r.length) < e) {
                                    var d = Math.floor(e - c);
                                    r.forEach((function(e, t) {
                                        t <= d - 1 && h[t]++
                                    }
                                    ))
                                }
                                return h
                            }
                            return r
                        }
                        if (i) {
                            var f = Math.floor((e - u) / r.length);
                            c = 0;
                            var p = r.map((function(e) {
                                return c += e + f,
                                e + f
                            }
                            ));
                            if (c < e) {
                                var g = Math.floor(e - c);
                                r.forEach((function(e, t) {
                                    t <= g - 1 && p[t]++
                                }
                                ))
                            }
                            return p
                        }
                        return r
                    }
                      , F = function(e) {
                        var t = parseFloat(e);
                        return isFinite(t) ? t : 0
                    }
                      , G = function(e) {
                        return e.getBoundingClientRect().top > window.innerHeight / 2
                    }
                      , B = function(e, t, i, r) {
                        var n = t.width
                          , a = t.height
                          , o = t.alignButtons
                          , s = t.hoverListPosition
                          , c = t.menuItemContainerExtraPixels
                          , u = t.absoluteLeft
                          , l = function(e, t, i, r, n, a, o, s, c) {
                            var u = "0px"
                              , l = "auto"
                              , h = a.left
                              , d = a.width;
                            ("left" === t ? u = "left" === n ? 0 : h + e.left + "px" : "right" === t ? (l = "right" === n ? 0 : r - h - d - e.right + "px",
                            u = "auto") : "left" === n ? u = h + (d + e.left - i) / 2 + "px" : "right" === n ? (u = "auto",
                            l = (d + e.right - (i + e.width)) / 2 + "px") : u = e.left + h + (d - (i + e.width)) / 2 + "px",
                            "auto" !== u) && (u = o + parseInt(u, 10) < 0 ? 0 : u);
                            "auto" !== l && (l = s - parseInt(l, 10) > c ? 0 : l);
                            return {
                                moreContainerLeft: u,
                                moreContainerRight: l
                            }
                        }(c, o, r, n, s, i, u, u + n, t.bodyClientWidth);
                        return {
                            left: l.moreContainerLeft,
                            right: l.moreContainerRight,
                            top: t.needToOpenMenuUp ? "auto" : a + "px",
                            bottom: t.needToOpenMenuUp ? a + "px" : "auto"
                        }
                    }
                      , k = function(e) {
                        return !isNaN(parseFloat(e)) && isFinite(e)
                    }
                      , N = function(e) {
                        var t = {}
                          , i = {};
                        i[e] = document.getElementById("" + e);
                        var r, n, a = (r = i[e],
                        (n = +E(r, "numItems")) <= 0 || n > Number.MAX_SAFE_INTEGER ? [] : new Array(n).fill(0).map((function(e, t) {
                            return String(t)
                        }
                        ))), o = function(e) {
                            return ["moreContainer", "itemsContainer", "dropWrapper"].concat(e, ["__more__"])
                        }(a);
                        o.forEach((function(t) {
                            var r = "" + e + t;
                            i[r] = document.getElementById("" + r)
                        }
                        )),
                        t.children = function(e, t, i, r) {
                            var n = {};
                            return r.forEach((function(t) {
                                var r = "" + e + t
                                  , a = i[r];
                                a && (n[r] = {
                                    width: a.offsetWidth,
                                    boundingClientRectWidth: a.getBoundingClientRect().width,
                                    height: a.offsetHeight
                                })
                            }
                            )),
                            n
                        }(e, 0, i, o);
                        var s = i[e]
                          , c = i[e + "itemsContainer"]
                          , u = c.childNodes
                          , l = i[e + "moreContainer"]
                          , h = l.childNodes
                          , d = E(s, "stretchButtonsToMenuWidth")
                          , f = E(s, "sameWidthButtons")
                          , p = s.getBoundingClientRect();
                        t.absoluteLeft = p.left,
                        t.bodyClientWidth = document.body.clientWidth,
                        t.alignButtons = E(s, "dropalign"),
                        t.hoverListPosition = E(s, "drophposition"),
                        t.menuBorderY = parseInt(E(s, "menuborderY"), 10),
                        t.ribbonExtra = parseInt(E(s, "ribbonExtra"), 10),
                        t.ribbonEls = parseInt(E(s, "ribbonEls"), 10),
                        t.labelPad = parseInt(E(s, "labelPad"), 10),
                        t.menuButtonBorder = parseInt(E(s, "menubtnBorder"), 10),
                        t.menuItemContainerMargins = function(e) {
                            var t = e.lastChild
                              , i = window.getComputedStyle(t);
                            return (parseInt(i.marginLeft, 10) || 0) + (parseInt(i.marginRight, 10) || 0)
                        }(c),
                        t.menuItemContainerExtraPixels = function(e, t) {
                            var i = window.getComputedStyle(e)
                              , r = F(i.borderTopWidth) + F(i.paddingTop)
                              , n = F(i.borderBottomWidth) + F(i.paddingBottom)
                              , a = F(i.borderLeftWidth) + F(i.paddingLeft)
                              , o = F(i.borderRightWidth) + F(i.paddingRight);
                            return t && (r += F(i.marginTop),
                            n += F(i.marginBottom),
                            a += F(i.marginLeft),
                            o += F(i.marginRight)),
                            {
                                top: r,
                                bottom: n,
                                left: a,
                                right: o,
                                height: r + n,
                                width: a + o
                            }
                        }(c, !0),
                        t.needToOpenMenuUp = G(s),
                        t.menuItemMarginForAllChildren = !d || "false" !== c.getAttribute("data-marginAllChildren"),
                        t.moreSubItem = [],
                        t.labelWidths = {},
                        t.linkIds = {},
                        t.parentId = {},
                        t.menuItems = {},
                        t.labels = {},
                        h.forEach((function(e, r) {
                            t.parentId[e.id] = E(e, "parentId");
                            var n = E(e, "dataId");
                            t.menuItems[n] = {
                                dataId: n,
                                parentId: E(e, "parentId"),
                                moreDOMid: e.id,
                                moreIndex: r
                            },
                            i[e.id] = e;
                            var a = e.querySelector("p");
                            i[a.id] = a,
                            t.labels[a.id] = {
                                width: a.offsetWidth,
                                height: a.offsetHeight,
                                left: a.offsetLeft,
                                lineHeight: parseInt(window.getComputedStyle(a).fontSize, 10)
                            },
                            t.moreSubItem.push(e.id)
                        }
                        )),
                        u.forEach((function(e, r) {
                            var n = E(e, "dataId");
                            t.menuItems[n] = t.menuItems[n] || {},
                            t.menuItems[n].menuIndex = r,
                            t.menuItems[n].menuDOMid = e.id,
                            t.children[e.id].left = e.offsetLeft;
                            var a = e.querySelector("p");
                            i[a.id] = a,
                            t.labelWidths[a.id] = function(e) {
                                return e.getBoundingClientRect().width
                            }(a);
                            var o = e.querySelector("p");
                            i[o.id] = o,
                            t.linkIds[e.id] = o.id
                        }
                        ));
                        var g = s.offsetHeight;
                        t.height = g,
                        t.width = s.offsetWidth,
                        t.lineHeight = function(e, t) {
                            return e - t.menuBorderY - t.labelPad - t.ribbonEls - t.menuButtonBorder - t.ribbonExtra + "px"
                        }(g, t);
                        var m = function(e, t, i, r, n) {
                            var a = t.width;
                            t.hasOriginalGapData = {},
                            t.originalGapBetweenTextAndBtn = {};
                            var o = n.map((function(i) {
                                var n, a = r[e + i], o = E(a, "originalGapBetweenTextAndBtn");
                                return void 0 === o ? (t.hasOriginalGapData[i] = !1,
                                n = t.children[e + i].boundingClientRectWidth - t.labelWidths[e + i + "label"],
                                t.originalGapBetweenTextAndBtn[e + i] = n) : (t.hasOriginalGapData[i] = !0,
                                n = parseFloat(o)),
                                t.children[e + i].width > 0 ? Math.floor(t.labelWidths[e + i + "label"] + n) : 0
                            }
                            ))
                              , s = o.pop()
                              , c = i.sameWidthButtons
                              , u = i.stretchButtonsToMenuWidth
                              , l = !1
                              , h = t.menuItemContainerMargins
                              , d = t.menuItemMarginForAllChildren
                              , f = t.menuItemContainerExtraPixels
                              , p = function(e) {
                                return e.reduce((function(e, t) {
                                    return e > t ? e : t
                                }
                                ), -1 / 0)
                            }(o)
                              , g = C(a, c, u, o, h, p, d, f);
                            if (!g) {
                                for (var m = 1; m <= o.length; m++)
                                    if (g = C(a, c, u, o.slice(0, -1 * m).concat(s), h, p, d, f)) {
                                        l = !0;
                                        break
                                    }
                                g || (l = !0,
                                g = [s])
                            }
                            if (l) {
                                var b = g[g.length - 1];
                                for (g = g.slice(0, -1); g.length < n.length; )
                                    g.push(0);
                                g[g.length - 1] = b
                            }
                            return {
                                realWidths: g,
                                moreShown: l
                            }
                        }(e, t, {
                            sameWidthButtons: f,
                            stretchButtonsToMenuWidth: d
                        }, i, a.concat("__more__"));
                        return t.realWidths = m.realWidths,
                        t.isMoreShown = m.moreShown,
                        t.menuItemIds = a,
                        t.hoverState = E(l, "hover", !1),
                        {
                            measures: t,
                            domNodes: i
                        }
                    }
                      , D = function(e, t, i) {
                        y(i[e], {
                            overflowX: "visible"
                        });
                        var r, n = t.menuItemIds, a = t.needToOpenMenuUp, o = n.concat("__more__");
                        r = i[e],
                        A(r, {
                            dropmode: a ? "dropUp" : "dropDown"
                        });
                        var s, c, u = 0;
                        if ("__more__" === t.hoverState) {
                            var l = t.realWidths.indexOf(0)
                              , h = t.menuItems[(s = t.menuItems,
                            c = function(e) {
                                return e.menuIndex === l
                            }
                            ,
                            Object.keys(s).find((function(e) {
                                return c(s[e], e)
                            }
                            )))]
                              , d = h.moreIndex
                              , f = d === n.length - 1;
                            h.moreDOMid && _(i[h.moreDOMid], {
                                "data-listposition": f ? "dropLonely" : "top"
                            }),
                            Object.values(t.menuItems).filter((function(e) {
                                return !!e.moreDOMid
                            }
                            )).forEach((function(e) {
                                if (e.moreIndex < d)
                                    y(i[e.moreDOMid], {
                                        display: "none"
                                    });
                                else {
                                    var r = e.moreDOMid + "label";
                                    u = Math.max(t.labels[r].width, u)
                                }
                            }
                            ))
                        } else
                            t.hoverState && t.moreSubItem.forEach((function(i, r) {
                                var n = e + "moreContainer" + r + "label";
                                u = Math.max(t.labels[n].width, u)
                            }
                            ));
                        !function(e, t, i, r) {
                            var n = t.hoverState;
                            if ("-1" !== n) {
                                var a = t.menuItemIds.indexOf(n);
                                if (k(t.hoverState) || "__more__" === n) {
                                    if (!t.realWidths)
                                        return;
                                    var o = Math.max(r, t.children[-1 !== a ? e + a : e + "__more__"].width)
                                      , s = function(e, t) {
                                        return e + 15 + t.menuBorderY + t.labelPad + t.menuButtonBorder
                                    }(0 !== t.moreSubItem.length ? t.labels[t.moreSubItem[0] + "label"].lineHeight : 0, t);
                                    t.moreSubItem.forEach((function(e) {
                                        y(i[e], {
                                            minWidth: o + "px"
                                        }),
                                        y(i[e + "label"], {
                                            minWidth: "0px",
                                            lineHeight: s + "px"
                                        })
                                    }
                                    ));
                                    var c = k(t.hoverState) ? t.hoverState : "__more__"
                                      , u = {
                                        width: t.children[e + c].width,
                                        left: t.children[e + c].left
                                    }
                                      , l = B(0, t, u, o);
                                    y(i[e + "moreContainer"], {
                                        left: l.left,
                                        right: l.right
                                    }),
                                    y(i[e + "dropWrapper"], {
                                        left: l.left,
                                        right: l.right,
                                        top: l.top,
                                        bottom: l.bottom
                                    })
                                }
                            }
                        }(e, t, i, u),
                        t.originalGapBetweenTextAndBtn && o.forEach((function(r) {
                            t.hasOriginalGapData[r] || A(i["" + e + r], {
                                originalGapBetweenTextAndBtn: t.originalGapBetweenTextAndBtn["" + e + r]
                            })
                        }
                        )),
                        function(e, t, i, r) {
                            for (var n = i.realWidths, a = i.height, o = i.menuItemContainerExtraPixels, s = 0, c = null, u = null, l = i.lineHeight, h = a - o.height, d = 0; d < r.length; d++) {
                                var f = n[d]
                                  , p = f > 0
                                  , g = e + r[d];
                                u = i.linkIds[g],
                                p ? (s++,
                                c = g,
                                y(t[g], {
                                    width: f + "px",
                                    height: h + "px",
                                    position: "relative",
                                    "box-sizing": "border-box",
                                    overflow: "visible",
                                    visibility: "inherit"
                                }),
                                y(t[g + "label"], {
                                    "line-height": l
                                }),
                                _(t[g], {
                                    "aria-hidden": !1
                                })) : (y(t[g], {
                                    height: "0px",
                                    overflow: "hidden",
                                    position: "absolute",
                                    visibility: "hidden"
                                }),
                                _(t[g], {
                                    "aria-hidden": !0
                                }),
                                _(t[u], {
                                    tabIndex: -1
                                }))
                            }
                            1 === s && (A(t[e + "moreContainer"], {
                                listposition: "lonely"
                            }),
                            A(t[c], {
                                listposition: "lonely"
                            }))
                        }(e, i, t, o)
                    };
                    function H(e, t) {
                        for (var i = 0; i < t.length; i++) {
                            var r = t[i];
                            r.enumerable = r.enumerable || !1,
                            r.configurable = !0,
                            "value"in r && (r.writable = !0),
                            Object.defineProperty(e, r.key, r)
                        }
                    }
                    function j(e) {
                        if (void 0 === e)
                            throw new ReferenceError("this hasn't been initialised - super() hasn't been called");
                        return e
                    }
                    function U(e, t) {
                        return (U = Object.setPrototypeOf || function(e, t) {
                            return e.__proto__ = t,
                            e
                        }
                        )(e, t)
                    }
                    function W(e, t, i) {
                        return t in e ? Object.defineProperty(e, t, {
                            value: i,
                            enumerable: !0,
                            configurable: !0,
                            writable: !0
                        }) : e[t] = i,
                        e
                    }
                    var Y = function(e, t) {
                        return function(e) {
                            var i, r;
                            function n() {
                                for (var t, i = arguments.length, r = new Array(i), n = 0; n < i; n++)
                                    r[n] = arguments[n];
                                return W(j(t = e.call.apply(e, [this].concat(r)) || this), "_visible", !1),
                                W(j(t), "_mutationIds", {
                                    read: null,
                                    write: null
                                }),
                                W(j(t), "_itemsContainer", null),
                                W(j(t), "_dropContainer", null),
                                W(j(t), "_labelItems", []),
                                t
                            }
                            r = e,
                            (i = n).prototype = Object.create(r.prototype),
                            i.prototype.constructor = i,
                            U(i, r);
                            var a, o, s, c = n.prototype;
                            return c.attributeChangedCallback = function() {
                                this._isVisible() && this.reLayout()
                            }
                            ,
                            c.connectedCallback = function() {
                                var t = this;
                                this._id = this.getAttribute("id"),
                                this._hideElement(),
                                this._waitForDomLoad().then((function() {
                                    e.prototype.observeResize.call(t),
                                    t._observeChildrenResize(),
                                    t.reLayout()
                                }
                                ))
                            }
                            ,
                            c.disconnectedCallback = function() {
                                t.mutationService.clear(this._mutationIds.read),
                                t.mutationService.clear(this._mutationIds.write),
                                e.prototype.disconnectedCallback.call(this)
                            }
                            ,
                            c._waitForDomLoad = function() {
                                var e, t = this, i = new Promise((function(t) {
                                    e = t
                                }
                                ));
                                return this._isDomReady() ? e() : (this._waitForDomReadyObserver = new MutationObserver((function() {
                                    return t._onRootMutate(e)
                                }
                                )),
                                this._waitForDomReadyObserver.observe(this, {
                                    childList: !0,
                                    subtree: !0
                                })),
                                i
                            }
                            ,
                            c._isDomReady = function() {
                                return this._itemsContainer = document.getElementById(this._id + "itemsContainer"),
                                this._dropContainer = document.getElementById(this._id + "dropWrapper"),
                                this._itemsContainer && this._dropContainer
                            }
                            ,
                            c._onRootMutate = function(e) {
                                this._isDomReady() && (this._waitForDomReadyObserver.disconnect(),
                                e())
                            }
                            ,
                            c._observeChildrenResize = function() {
                                var t = this
                                  , i = Array.from(this._itemsContainer.childNodes);
                                this._labelItems = i.map((function(e) {
                                    return document.getElementById(e.getAttribute("id") + "label")
                                }
                                )),
                                this._labelItems.forEach((function(i) {
                                    return e.prototype.observeChildResize.call(t, i)
                                }
                                ))
                            }
                            ,
                            c._setVisibility = function(e) {
                                this._visible = e,
                                this.style.visibility = e ? "inherit" : "hidden"
                            }
                            ,
                            c._isVisible = function() {
                                return this._visible
                            }
                            ,
                            c._hideElement = function() {
                                this._setVisibility(!1)
                            }
                            ,
                            c._showElement = function() {
                                this._setVisibility(!0)
                            }
                            ,
                            c.reLayout = function() {
                                var e, i, r = this;
                                t.mutationService.clear(this._mutationIds.read),
                                t.mutationService.clear(this._mutationIds.write),
                                this._mutationIds.read = t.mutationService.measure((function() {
                                    var t = N(r._id);
                                    e = t.measures,
                                    i = t.domNodes
                                }
                                )),
                                this._mutationIds.write = t.mutationService.mutate((function() {
                                    D(r._id, e, i),
                                    r._showElement()
                                }
                                ))
                            }
                            ,
                            a = n,
                            s = [{
                                key: "observedAttributes",
                                get: function() {
                                    return ["data-hovered-item"]
                                }
                            }],
                            (o = null) && H(a.prototype, o),
                            s && H(a, s),
                            n
                        }(e)
                    };
                    function z(e, t) {
                        var i = "undefined" != typeof Symbol && e[Symbol.iterator] || e["@@iterator"];
                        if (i)
                            return (i = i.call(e)).next.bind(i);
                        if (Array.isArray(e) || (i = function(e, t) {
                            if (!e)
                                return;
                            if ("string" == typeof e)
                                return V(e, t);
                            var i = Object.prototype.toString.call(e).slice(8, -1);
                            "Object" === i && e.constructor && (i = e.constructor.name);
                            if ("Map" === i || "Set" === i)
                                return Array.from(e);
                            if ("Arguments" === i || /^(?:Ui|I)nt(?:8|16|32)(?:Clamped)?Array$/.test(i))
                                return V(e, t)
                        }(e)) || t && e && "number" == typeof e.length) {
                            i && (e = i);
                            var r = 0;
                            return function() {
                                return r >= e.length ? {
                                    done: !0
                                } : {
                                    done: !1,
                                    value: e[r++]
                                }
                            }
                        }
                        throw new TypeError("Invalid attempt to iterate non-iterable instance.\nIn order to be iterable, non-array objects must have a [Symbol.iterator]() method.")
                    }
                    function V(e, t) {
                        (null == t || t > e.length) && (t = e.length);
                        for (var i = 0, r = new Array(t); i < t; i++)
                            r[i] = e[i];
                        return r
                    }
                    function q(e) {
                        var t = "function" == typeof Map ? new Map : void 0;
                        return (q = function(e) {
                            if (null === e || (i = e,
                            -1 === Function.toString.call(i).indexOf("[native code]")))
                                return e;
                            var i;
                            if ("function" != typeof e)
                                throw new TypeError("Super expression must either be null or a function");
                            if (void 0 !== t) {
                                if (t.has(e))
                                    return t.get(e);
                                t.set(e, r)
                            }
                            function r() {
                                return Z(e, arguments, Q(this).constructor)
                            }
                            return r.prototype = Object.create(e.prototype, {
                                constructor: {
                                    value: r,
                                    enumerable: !1,
                                    writable: !0,
                                    configurable: !0
                                }
                            }),
                            J(r, e)
                        }
                        )(e)
                    }
                    function Z(e, t, i) {
                        return (Z = $() ? Reflect.construct : function(e, t, i) {
                            var r = [null];
                            r.push.apply(r, t);
                            var n = new (Function.bind.apply(e, r));
                            return i && J(n, i.prototype),
                            n
                        }
                        ).apply(null, arguments)
                    }
                    function $() {
                        if ("undefined" == typeof Reflect || !Reflect.construct)
                            return !1;
                        if (Reflect.construct.sham)
                            return !1;
                        if ("function" == typeof Proxy)
                            return !0;
                        try {
                            return Boolean.prototype.valueOf.call(Reflect.construct(Boolean, [], (function() {}
                            ))),
                            !0
                        } catch (e) {
                            return !1
                        }
                    }
                    function J(e, t) {
                        return (J = Object.setPrototypeOf || function(e, t) {
                            return e.__proto__ = t,
                            e
                        }
                        )(e, t)
                    }
                    function Q(e) {
                        return (Q = Object.setPrototypeOf ? Object.getPrototypeOf : function(e) {
                            return e.__proto__ || Object.getPrototypeOf(e)
                        }
                        )(e)
                    }
                    var X = function(e) {
                        return function(t) {
                            var i, r;
                            function n() {
                                return t.call(this) || this
                            }
                            r = t,
                            (i = n).prototype = Object.create(r.prototype),
                            i.prototype.constructor = i,
                            J(i, r);
                            var a = n.prototype;
                            return a.reLayout = function() {}
                            ,
                            a.connectedCallback = function() {
                                this.observeResize(),
                                this.reLayout()
                            }
                            ,
                            a.disconnectedCallback = function() {
                                this.unobserveResize(),
                                this.unobserveChildren()
                            }
                            ,
                            a.observeResize = function() {
                                e.resizeService.observe(this)
                            }
                            ,
                            a.unobserveResize = function() {
                                e.resizeService.unobserve(this)
                            }
                            ,
                            a.observeChildren = function(e) {
                                var t = this;
                                this.childListObserver || (this.childListObserver = new MutationObserver((function() {
                                    return t.reLayout()
                                }
                                ))),
                                this.childListObserver.observe(e, {
                                    childList: !0
                                })
                            }
                            ,
                            a.observeChildAttributes = function(e, t) {
                                var i = this;
                                void 0 === t && (t = []),
                                this.childrenAttributesObservers || (this.childrenAttributesObservers = []);
                                var r = new MutationObserver((function() {
                                    return i.reLayout()
                                }
                                ));
                                r.observe(e, {
                                    attributeFilter: t
                                }),
                                this.childrenAttributesObservers.push(r)
                            }
                            ,
                            a.observeChildResize = function(t) {
                                this.childrenResizeObservers || (this.childrenResizeObservers = []),
                                e.resizeService.observeChild(t, this),
                                this.childrenResizeObservers.push(t)
                            }
                            ,
                            a.unobserveChildrenResize = function() {
                                this.childrenResizeObservers && (this.childrenResizeObservers.forEach((function(t) {
                                    e.resizeService.unobserveChild(t)
                                }
                                )),
                                this.childrenResizeObservers = null)
                            }
                            ,
                            a.unobserveChildren = function() {
                                if (this.childListObserver && (this.childListObserver.disconnect(),
                                this.childListObserver = null),
                                this.childrenAttributesObservers) {
                                    for (var e, t = z(this.childrenAttributesObservers); !(e = t()).done; ) {
                                        var i = e.value;
                                        i.disconnect(),
                                        i = null
                                    }
                                    this.childrenAttributesObservers = null
                                }
                                this.unobserveChildrenResize()
                            }
                            ,
                            n
                        }(q(HTMLElement))
                    }
                      , K = {
                        APP_IFRAME_START_LOADING: {
                            eventId: 642,
                            src: 42,
                            params: {
                                widget_id: "widgetId",
                                widget_name: "widgetName",
                                instance_id: "compId",
                                appId: "appDefinitionId",
                                loading_time: "loadingTime",
                                pid: "pageId",
                                pn: "pageNo",
                                iss: "ssr",
                                tts: "totalLoadingTime",
                                external_app_id: "externalAppDefinitionId",
                                external_widget_id: "externalWidgetId",
                                lazy_load: "lazyLoad"
                            }
                        }
                    };
                    function ee(e, t) {
                        for (var i = 0; i < t.length; i++) {
                            var r = t[i];
                            r.enumerable = r.enumerable || !1,
                            r.configurable = !0,
                            "value"in r && (r.writable = !0),
                            Object.defineProperty(e, r.key, r)
                        }
                    }
                    function te(e, t) {
                        return (te = Object.setPrototypeOf || function(e, t) {
                            return e.__proto__ = t,
                            e
                        }
                        )(e, t)
                    }
                    var ie = function(e, t) {
                        return function(e) {
                            var i, r;
                            function n() {
                                return e.call(this) || this
                            }
                            r = e,
                            (i = n).prototype = Object.create(r.prototype),
                            i.prototype.constructor = i,
                            te(i, r);
                            var a, o, s, c = n.prototype;
                            return c.reportIframeStartLoading = function(e) {
                                var i = this.dataset
                                  , r = i.isTpa
                                  , n = i.widgetId
                                  , a = i.appDefinitionId;
                                t && t.biService && "true" === r && t.biService.reportTpaBiEvent({
                                    reportDef: K.APP_IFRAME_START_LOADING,
                                    params: {},
                                    compId: e.getAttribute("name"),
                                    isWixTPA: !0,
                                    widgetId: n,
                                    appDefinitionId: a
                                })
                            }
                            ,
                            c.reLayout = function() {
                                var e = this.querySelector("iframe");
                                if (e) {
                                    var t = e.dataset.src;
                                    t && e.src !== t && (e.src = t,
                                    e.dataset.src = "",
                                    this.dataset.src = "",
                                    this.reportIframeStartLoading(e))
                                }
                            }
                            ,
                            c.attributeChangedCallback = function(e, t, i) {
                                i && this.reLayout()
                            }
                            ,
                            a = n,
                            s = [{
                                key: "observedAttributes",
                                get: function() {
                                    return ["data-src"]
                                }
                            }],
                            (o = null) && ee(a.prototype, o),
                            s && ee(a, s),
                            n
                        }(e)
                    }
                      , re = function() {
                        function e(e) {
                            var t;
                            this.mutationService = e,
                            window && "IntersectionObserver"in window && "IntersectionObserverEntry"in window && "intersectionRatio"in window.IntersectionObserverEntry.prototype && "isIntersecting"in window.IntersectionObserverEntry.prototype && (t = window,
                            !/Edge\/18/.test(t.navigator.userAgent)) && (this.intersectionObserver = new IntersectionObserver(this.getViewPortIntersectionHandler(),{
                                rootMargin: "50% 0px"
                            }),
                            this.scrollEffectsIntersectionObserver = new IntersectionObserver(this.getScrollEffectsIntersectionHandler(),{
                                rootMargin: "10% 0px"
                            }))
                        }
                        var t = e.prototype;
                        return t.isImageInViewPort = function(e, t) {
                            return e.top + e.height >= 0 && e.bottom - e.height <= t
                        }
                        ,
                        t.loadImage = function(e, t) {
                            var i = t.screenHeight
                              , r = t.boundingRect
                              , n = t.withScrollEffectVars;
                            !this.intersectionObserver || this.isImageInViewPort(r, i) ? this.setImageSource(e) : (this.intersectionObserver.unobserve(e),
                            this.intersectionObserver.observe(e)),
                            n && this.scrollEffectsIntersectionObserver && (this.scrollEffectsIntersectionObserver.unobserve(e),
                            this.scrollEffectsIntersectionObserver.observe(e))
                        }
                        ,
                        t.onImageDisconnected = function(e) {
                            this.intersectionObserver && this.intersectionObserver.unobserve(e),
                            this.scrollEffectsIntersectionObserver && this.scrollEffectsIntersectionObserver.unobserve(e)
                        }
                        ,
                        t.setSrcAttribute = function(e, t, i) {
                            v(e, t) !== i && (t ? e.setAttributeNS("http://www.w3.org/1999/xlink", "xlink:href", i) : e.src = i)
                        }
                        ,
                        t.setSourceSetAttribute = function(e, t) {
                            e.srcset !== t && (e.srcset = t)
                        }
                        ,
                        t.setImageSource = function(e) {
                            var t = this
                              , i = "true" === e.dataset.isSvg
                              , r = e.querySelector(i ? "image" : "img")
                              , n = e.querySelector("picture");
                            this.setSrcAttribute(r, i, e.dataset.src),
                            n && Array.from(n.querySelectorAll("source")).forEach((function(e) {
                                t.setSourceSetAttribute(e, e.dataset.srcset)
                            }
                            ))
                        }
                        ,
                        t.getViewPortIntersectionHandler = function() {
                            var e = this;
                            return function(t, i) {
                                t.filter((function(e) {
                                    return e.isIntersecting
                                }
                                )).forEach((function(t) {
                                    var r = t.target;
                                    e.setImageSource(r),
                                    i.unobserve(r)
                                }
                                ))
                            }
                        }
                        ,
                        t.getScrollEffectsIntersectionHandler = function() {
                            var e = this;
                            return function(t) {
                                return t.forEach((function(t) {
                                    var i = t.target;
                                    t.isIntersecting ? e.mutationService.mutate((function() {
                                        return i.classList.add("scroll-css-var--scrollEffect")
                                    }
                                    )) : e.mutationService.mutate((function() {
                                        return i.classList.remove("scroll-css-var--scrollEffect")
                                    }
                                    ))
                                }
                                ))
                            }
                        }
                        ,
                        e
                    }()
                      , ne = {
                        eventId: 348,
                        adapter: "ugc-viewer",
                        params: {
                            ow: "originalWidth",
                            oh: "originalHeight",
                            tw: "targetWidth",
                            th: "targetHeight",
                            dpr: "devicePixelRatio",
                            um: "upscaleMethod",
                            url: "url"
                        }
                    };
                    function ae(e) {
                        var t = e
                          , i = (t.width,
                        t.height,
                        function(e, t) {
                            if (null == e)
                                return {};
                            var i, r, n = {}, a = Object.keys(e);
                            for (r = 0; r < a.length; r++)
                                i = a[r],
                                t.indexOf(i) >= 0 || (n[i] = e[i]);
                            return n
                        }(t, ["width", "height"]))
                          , r = {};
                        for (e in i)
                            "" !== i[e] && (r[e] = i[e]);
                        return r
                    }
                    var oe = {
                        measure: function(e, t, i, r, n) {
                            var a = r.containerElm
                              , o = r.isSvgImage
                              , s = r.isSvgMask
                              , c = r.mediaHeightOverrideType
                              , u = r.bgEffectName
                              , l = i.image
                              , h = i[e]
                              , d = w()
                              , f = a && u ? a : h
                              , p = n.getMediaDimensionsByEffect(u, f.offsetWidth, f.offsetHeight, d)
                              , g = p.width
                              , m = p.height;
                            if (l) {
                                var b = v(l, o);
                                t.width = g,
                                t.screenHeight = d,
                                t.height = c ? d : m,
                                t.isZoomed = h.getAttribute("data-image-zoomed"),
                                t.isSvgImage = o,
                                t.imgSrc = b,
                                t.renderedStyles = h.getAttribute("data-style"),
                                t.boundingRect = h.getBoundingClientRect(),
                                t.mediaHeightOverrideType = c,
                                s && (t.bBox = function(e) {
                                    if (e) {
                                        var t = e.dataset.type;
                                        if (t && "ugc" !== t)
                                            if (!e.dataset.bbox) {
                                                var i = e.getBBox();
                                                return i.x + " " + i.y + " " + i.width + " " + i.height
                                            }
                                    }
                                    return null
                                }(i.maskSvg))
                            }
                        },
                        patch: function(e, t, i, r, n, a, o, s) {
                            var c, u = (c = t.renderedStyles) && c.split ? c.split(";").reduce((function(e, t) {
                                var i = t.split(":");
                                return i[0] && i[1] && (e[i[0].trim()] = i[1].trim()),
                                e
                            }
                            ), {}) : {}, l = r.imageData;
                            s && (l.devicePixelRatio = 1);
                            var h, f = Object.assign({}, r, {
                                containerWidth: t.isZoomed ? l.width : t.width,
                                containerHeight: t.isZoomed ? l.height : t.height,
                                displayMode: l.displayMode
                            });
                            if (t.isSvgImage)
                                h = g(f, a, "svg"),
                                _(i.svg, t.isZoomed ? h.attr.container : {});
                            else {
                                h = g(f, a, "img");
                                var p = d(h, ["css", "img"]) || {}
                                  , m = function(e, t, i) {
                                    if (!e)
                                        return t;
                                    var r = Object.assign({}, t);
                                    return "fill" === i && (r.position = "absolute",
                                    r.top = 0),
                                    "fixed" === e && (r.height = "100%",
                                    r["will-change"] = "transform"),
                                    r.objectPosition && (r.objectPosition = t.objectPosition.replace(/(center|bottom)$/, "top")),
                                    r
                                }(t.mediaHeightOverrideType, p, l.displayMode);
                                y(i.image, m)
                            }
                            t.bBox && i.maskSvg && _(i.maskSvg, {
                                viewBox: t.bBox
                            });
                            var b = function(e, t) {
                                var i = ae(e);
                                return "number" == typeof t && (i.opacity = t),
                                i
                            }(u, l.opacity);
                            y(i[e], b);
                            var v = d(h, "uri")
                              , T = t.imgSrc;
                            _(i[e], {
                                "data-src": v
                            }),
                            _(i[e], {
                                "data-has-ssr-src": ""
                            }),
                            o && (!function(e, t, i, r, n) {
                                var a = n.uri.match(/,lg_(\d)/);
                                t.isViewerMode && n.uri !== r.currentSrc && a && e.reportBI(ne, {
                                    originalWidth: i.imageData.width,
                                    originalHeight: i.imageData.height,
                                    targetWidth: Math.round(i.containerWidth),
                                    targetHeight: Math.round(i.containerHeight),
                                    upscaleMethod: "1" === a[1] ? "classic" : "super",
                                    devicePixelRatio: Math.floor(100 * t.devicePixelRatio),
                                    url: r.src
                                })
                            }(n.biService, a, f, {
                                src: v,
                                currentSrc: T
                            }, h),
                            n.imageLoader.loadImage(i[e], {
                                screenHeight: t.screenHeight,
                                boundingRect: t.boundingRect
                            }))
                        }
                    };
                    function se(e, t, i) {
                        return void 0 === i && (i = 1.5),
                        {
                            parallax: e.height * i,
                            fixed: e.screenHeight
                        }[t] || e.height
                    }
                    var ce = {
                        measure: function(e, t, i) {
                            var r = i.image;
                            if (r) {
                                var n = v(r);
                                t.width = i[e].offsetWidth,
                                t.height = i[e].offsetHeight,
                                t.imgSrc = n,
                                t.screenHeight = w(),
                                t.boundingRect = i[e].getBoundingClientRect(),
                                t.documentScroll = window ? window.pageYOffset || document.documentElement.scrollTop : 0
                            }
                        },
                        patch: function(e, t, i, r, n, a, o) {
                            var s, c, u = r.imageData, l = r.parallaxSpeed, h = Object.assign({}, r, {
                                containerWidth: t.width,
                                containerHeight: se(t, u.scrollEffect, l),
                                displayMode: u.displayMode
                            }), f = (s = u.opacity,
                            c = {},
                            "number" == typeof s && (c.opacity = s),
                            c);
                            y(i[e], f);
                            var p = g(h, a, "img")
                              , m = d(p, "uri");
                            _(i[e], {
                                "data-src": m
                            });
                            var b, v, T = (b = u.scrollEffect,
                            void 0 === (v = r.sourceSets) && (v = []),
                            "parallax" === b || v.some((function(e) {
                                return "parallax" === e.scrollEffect
                            }
                            )));
                            T && I(i[e], function(e) {
                                var t;
                                return (t = {})["--compH"] = e.height,
                                t["--top"] = Math.ceil(e.boundingRect.top) + e.documentScroll,
                                t["--scroll"] = e.documentScroll,
                                t
                            }(t));
                            var E = function(e) {
                                var t = d(e, ["css", "img"]);
                                return {
                                    width: "100%",
                                    objectFit: t ? t.objectFit : void 0
                                }
                            }(p);
                            y(i.image, E),
                            i.picture && function(e, t, i, r) {
                                var n = t.sourceSets;
                                if (n && n.length) {
                                    var a = JSON.parse(JSON.stringify(t))
                                      , o = a.parallaxSpeed;
                                    n.forEach((function(t) {
                                        var n = r.querySelector("source[media='" + t.mediaQuery + "']");
                                        a.imageData.crop = t.crop,
                                        a.imageData.displayMode = t.displayMode,
                                        a.imageData.focalPoint = t.focalPoint,
                                        a.containerHeight = se(e, t.scrollEffect, o);
                                        var s = g(a, i, "img");
                                        _(n, {
                                            "data-srcset": d(s, "uri")
                                        })
                                    }
                                    ))
                                }
                            }(t, h, a, i.picture),
                            _(i[e], {
                                "data-has-ssr-src": ""
                            }),
                            o && n.imageLoader.loadImage(i[e], {
                                screenHeight: t.screenHeight,
                                boundingRect: t.boundingRect,
                                withScrollEffectVars: T
                            })
                        }
                    };
                    function ue(e, t) {
                        for (var i = 0; i < t.length; i++) {
                            var r = t[i];
                            r.enumerable = r.enumerable || !1,
                            r.configurable = !0,
                            "value"in r && (r.writable = !0),
                            Object.defineProperty(e, r.key, r)
                        }
                    }
                    function le(e, t) {
                        return (le = Object.setPrototypeOf || function(e, t) {
                            return e.__proto__ = t,
                            e
                        }
                        )(e, t)
                    }
                    var he, de = function(e, t, i) {
                        return t.imageLoader || (t.imageLoader = new re(t.mutationService)),
                        function(e) {
                            var r, n;
                            function a() {
                                var t;
                                return (t = e.call(this) || this).childListObserver = null,
                                t.timeoutId = null,
                                t
                            }
                            n = e,
                            (r = a).prototype = Object.create(n.prototype),
                            r.prototype.constructor = r,
                            le(r, n);
                            var o, s, c, u = a.prototype;
                            return u.reLayout = function() {
                                if (!t.isExperimentOpen("specs.thunderbolt.tb_stop_client_images")) {
                                    var e = {}
                                      , r = {}
                                      , n = this.getAttribute("id")
                                      , a = JSON.parse(this.dataset.imageInfo)
                                      , o = "true" === this.dataset.isSvg
                                      , s = "true" === this.dataset.isSvgMask
                                      , c = "true" === this.dataset.isResponsive
                                      , u = this.dataset.bgEffectName;
                                    e[n] = this,
                                    a.containerId && (e[a.containerId] = document.getElementById("" + a.containerId)),
                                    e.image = this.querySelector(o ? "image" : "img"),
                                    e.svg = o ? this.querySelector("svg") : null,
                                    e.picture = this.querySelector("picture");
                                    var l = a.containerId && e[a.containerId]
                                      , h = l && l.dataset.mediaHeightOverrideType;
                                    if (s && (e.maskSvg = e.svg && e.svg.querySelector("svg")),
                                    e.image) {
                                        this.unobserveChildren(),
                                        this.observeChildren(this);
                                        var d = c || e.picture ? ce : oe;
                                        t.mutationService.measure((function() {
                                            d.measure(n, r, e, {
                                                containerElm: l,
                                                isSvg: o,
                                                isSvgMask: s,
                                                mediaHeightOverrideType: h,
                                                bgEffectName: u
                                            }, t)
                                        }
                                        ));
                                        var f = function(o) {
                                            t.mutationService.mutate((function() {
                                                d.patch(n, r, e, a, t, i, o, u)
                                            }
                                            ))
                                        };
                                        !v(e.image, o) || this.dataset.hasSsrSrc ? f(!0) : this.debounceImageLoad(f)
                                    } else {
                                        var p = o && e.svg || this;
                                        this.observeChildren(p)
                                    }
                                }
                            }
                            ,
                            u.debounceImageLoad = function(e) {
                                clearTimeout(this.timeoutId),
                                this.timeoutId = setTimeout((function() {
                                    e(!0)
                                }
                                ), 250),
                                e(!1)
                            }
                            ,
                            u.attributeChangedCallback = function(e, t) {
                                t && this.reLayout()
                            }
                            ,
                            u.disconnectedCallback = function() {
                                e.prototype.disconnectedCallback.call(this),
                                t.imageLoader.onImageDisconnected(this),
                                this.unobserveChildren()
                            }
                            ,
                            o = a,
                            c = [{
                                key: "observedAttributes",
                                get: function() {
                                    return ["data-image-info"]
                                }
                            }],
                            (s = null) && ue(o.prototype, s),
                            c && ue(o, c),
                            a
                        }(e)
                    }, fe = function(e, t, i, r, n, a, o, s, c, u, l) {
                        var d = i ? t.offsetWidth : e.parentElement.offsetWidth
                          , f = e.parentElement.offsetHeight
                          , g = parseInt(r, 10)
                          , m = parseInt(n, 10)
                          , b = function(e, t, i, r) {
                            var n;
                            n = e === h.a.fittingTypes.SCALE_TO_FIT ? Math.min(t.wScale, t.hScale) : Math.max(t.wScale, t.hScale);
                            return {
                                width: Math.round(i * n),
                                height: Math.round(r * n)
                            }
                        }(a, function(e, t, i, r) {
                            return {
                                wScale: e / i,
                                hScale: t / r
                            }
                        }(d, f, g, m), g, m)
                          , v = function(e, t, i) {
                            var r = i.width
                              , n = i.height
                              , a = t.width
                              , o = t.height
                              , s = r - a
                              , c = n - o;
                            return me[e || h.a.alignTypes.CENTER]({
                                verticalMiddle: Math.round(c / 2),
                                horizontalMiddle: Math.round(s / 2),
                                top: c,
                                left: s
                            })
                        }(o, b, {
                            width: d,
                            height: f
                        })
                          , T = function(e, t, i, r) {
                            if ("mp4" === r)
                                return e.url ? p(t, e.url) : p(t, i, e.quality, r, "file.mp4");
                            return ""
                        }(function(e, t) {
                            var i = t.width
                              , r = t.height;
                            return (n = e,
                            a = function(e) {
                                return e.size
                            }
                            ,
                            o = n.reduce((function(e, t) {
                                return e[a(t)] = t,
                                e
                            }
                            ), {}),
                            Object.values(o)).find((function(e) {
                                return e.size > i * r
                            }
                            )) || e[e.length - 1];
                            var n, a, o
                        }(s, b), c, u, l);
                        return {
                            videoSourceUrl: T,
                            needsSrcUpdate: function(e, t) {
                                var i = e.networkState === e.NETWORK_NO_SOURCE
                                  , r = !e.currentSrc.endsWith(t);
                                return t && (r || i)
                            }(e, T),
                            videoStyle: {
                                width: b.width,
                                height: b.height,
                                left: v.left,
                                top: v.top
                            }
                        }
                    }, pe = function(e, t, i, r, n, a, o, s, c, u, l) {
                        _(i, {
                            width: r.width,
                            height: r.height
                        }),
                        t ? y(t, r) : (!function(e, t, i, r, n, a) {
                            a && t.paused && (i.style.opacity = "1",
                            t.style.opacity = "0");
                            if (t.paused && (e || a))
                                if (t.ontimeupdate = null,
                                t.onseeked = null,
                                t.onplay = null,
                                !a && n) {
                                    var o = t.muted;
                                    t.muted = !0,
                                    t.ontimeupdate = function() {
                                        t.currentTime > 0 && (t.ontimeupdate = null,
                                        t.onseeked = function() {
                                            t.onseeked = null,
                                            t.muted = o,
                                            be(t, i, r)
                                        }
                                        ,
                                        t.currentTime = 0)
                                    }
                                } else
                                    t.onplay = function() {
                                        t.onplay = null,
                                        be(t, i, r)
                                    }
                        }(o, i, e, s, n, l),
                        n ? i.setAttribute("autoplay", "") : i.removeAttribute("autoplay"),
                        y(i, r)),
                        function(e, t, i) {
                            e && (t.src = i,
                            t.load())
                        }(o, i, a),
                        i.playbackRate = u
                    }, ge = h.a.alignTypes, me = ((he = {})[ge.CENTER] = function(e) {
                        return {
                            left: e.horizontalMiddle,
                            top: e.verticalMiddle
                        }
                    }
                    ,
                    he[ge.LEFT] = function(e) {
                        return {
                            left: 0,
                            top: e.verticalMiddle
                        }
                    }
                    ,
                    he[ge.RIGHT] = function(e) {
                        return {
                            left: e.left,
                            top: e.verticalMiddle
                        }
                    }
                    ,
                    he[ge.TOP] = function(e) {
                        return {
                            left: e.horizontalMiddle,
                            top: 0
                        }
                    }
                    ,
                    he[ge.BOTTOM] = function(e) {
                        return {
                            left: e.horizontalMiddle,
                            top: e.top
                        }
                    }
                    ,
                    he[ge.TOP_LEFT] = function() {
                        return {
                            left: 0,
                            top: 0
                        }
                    }
                    ,
                    he[ge.TOP_RIGHT] = function(e) {
                        return {
                            left: e.left,
                            top: 0
                        }
                    }
                    ,
                    he[ge.BOTTOM_LEFT] = function(e) {
                        return {
                            left: 0,
                            top: e.top
                        }
                    }
                    ,
                    he[ge.BOTTOM_RIGHT] = function(e) {
                        return {
                            left: e.left,
                            top: e.top
                        }
                    }
                    ,
                    he);
                    function be(e, t, i) {
                        "fade" === i && (t.style.transition = "opacity 1.6s ease-out"),
                        t.style.opacity = "0",
                        e.style.opacity = "1"
                    }
                    function ve(e, t) {
                        for (var i = 0; i < t.length; i++) {
                            var r = t[i];
                            r.enumerable = r.enumerable || !1,
                            r.configurable = !0,
                            "value"in r && (r.writable = !0),
                            Object.defineProperty(e, r.key, r)
                        }
                    }
                    function Te(e, t) {
                        return (Te = Object.setPrototypeOf || function(e, t) {
                            return e.__proto__ = t,
                            e
                        }
                        )(e, t)
                    }
                    var _e = function(e, t, i) {
                        return function(e) {
                            var r, n;
                            function a() {
                                return e.call(this) || this
                            }
                            n = e,
                            (r = a).prototype = Object.create(n.prototype),
                            r.prototype.constructor = r,
                            Te(r, n);
                            var o, s, c, u = a.prototype;
                            return u.reLayout = function() {
                                var e = this
                                  , r = JSON.parse(this.dataset.videoInfo)
                                  , n = r.isVideoDataExists
                                  , a = r.videoWidth
                                  , o = r.videoHeight
                                  , s = r.qualities
                                  , c = r.videoId
                                  , u = r.videoFormat
                                  , l = r.alignType
                                  , h = r.fittingType
                                  , d = r.hasBgScrollEffect
                                  , f = r.autoPlay
                                  , p = r.animatePoster
                                  , g = r.containerId
                                  , m = r.isEditorMode
                                  , b = r.playbackRate
                                  , v = r.hasAlpha;
                                if (n) {
                                    var T = !i.prefersReducedMotion && f
                                      , _ = this.querySelector('video[id^="' + g + '"]')
                                      , y = this.querySelector('.bgVideoposter[id^="' + g + '"]');
                                    if (this.unobserveChildren(),
                                    _ && y) {
                                        var I = document.getElementById("" + g)
                                          , E = I.querySelector('.webglcanvas[id^="' + g + '"]');
                                        !(v || "true" === I.dataset.hasAlpha) || E ? t.mutationService.measure((function() {
                                            var e = fe(_, I, d, a, o, h, l, s, i.staticVideoUrl, c, u)
                                              , r = e.videoSourceUrl
                                              , n = e.needsSrcUpdate
                                              , f = e.videoStyle;
                                            t.mutationService.mutate((function() {
                                                pe(y, E, _, f, T, r, n, p, u, b, m)
                                            }
                                            ))
                                        }
                                        )) : requestAnimationFrame((function() {
                                            return e.reLayout()
                                        }
                                        ))
                                    } else
                                        this.observeChildren(this)
                                }
                            }
                            ,
                            u.attributeChangedCallback = function(e, t) {
                                t && this.reLayout()
                            }
                            ,
                            o = a,
                            c = [{
                                key: "observedAttributes",
                                get: function() {
                                    return ["data-video-info"]
                                }
                            }],
                            (s = null) && ve(o.prototype, s),
                            c && ve(o, c),
                            a
                        }(e)
                    };
                    function ye(e, t) {
                        var i = Object.keys(e);
                        if (Object.getOwnPropertySymbols) {
                            var r = Object.getOwnPropertySymbols(e);
                            t && (r = r.filter((function(t) {
                                return Object.getOwnPropertyDescriptor(e, t).enumerable
                            }
                            ))),
                            i.push.apply(i, r)
                        }
                        return i
                    }
                    function Ie(e, t, i) {
                        return t in e ? Object.defineProperty(e, t, {
                            value: i,
                            enumerable: !0,
                            configurable: !0,
                            writable: !0
                        }) : e[t] = i,
                        e
                    }
                    function Ee(e, t) {
                        void 0 === customElements.get(e) && customElements.define(e, t)
                    }
                    function Ae(e, t, i) {
                        Ee("wix-image", de(e, t, i))
                    }
                    function we(e, t, i) {
                        Ee("wix-bg-image", M(e, t, i))
                    }
                    function Oe(e, t, i, r) {
                        Ee("wix-bg-media", P(e, function(e) {
                            for (var t = 1; t < arguments.length; t++) {
                                var i = null != arguments[t] ? arguments[t] : {};
                                t % 2 ? ye(Object(i), !0).forEach((function(t) {
                                    Ie(e, t, i[t])
                                }
                                )) : Object.getOwnPropertyDescriptors ? Object.defineProperties(e, Object.getOwnPropertyDescriptors(i)) : ye(Object(i)).forEach((function(t) {
                                    Object.defineProperty(e, t, Object.getOwnPropertyDescriptor(i, t))
                                }
                                ))
                            }
                            return e
                        }({
                            windowResizeService: t
                        }, i), r))
                    }
                    function Se(e, t) {
                        Ee("wix-dropdown-menu", Y(e, t))
                    }
                    function Le(e, t, i) {
                        Ee("wix-video", _e(e, t, i))
                    }
                    function Me(e, t) {
                        Ee("wix-iframe", ie(e, t))
                    }
                    var Re = {
                        init: function(e) {
                            i(127);
                            var t, r, n = e.resizeService.init((function(e) {
                                o.getLayoutTargets(e.map((function(e) {
                                    return e.target
                                }
                                ))).forEach((function(e) {
                                    return e.reLayout()
                                }
                                ))
                            }
                            )), a = {
                                registry: new Set,
                                observe: function(e) {
                                    a.registry.add(e)
                                },
                                unobserve: function(e) {
                                    a.registry.delete(e)
                                }
                            };
                            e.windowResizeService.init((t = function() {
                                return a.registry.forEach((function(e) {
                                    return e.reLayout()
                                }
                                ))
                            }
                            ,
                            r = !1,
                            function() {
                                for (var e = arguments.length, i = new Array(e), n = 0; n < e; n++)
                                    i[n] = arguments[n];
                                r || (r = !0,
                                requestAnimationFrame((function() {
                                    r = !1,
                                    t.apply(void 0, i)
                                }
                                )))
                            }
                            ));
                            var o = {
                                observedElementToRelayoutTarget: new Map,
                                getLayoutTargets: function(e) {
                                    var t = new Set;
                                    return e.forEach((function(e) {
                                        return t.add(o.observedElementToRelayoutTarget.get(e))
                                    }
                                    )),
                                    t
                                },
                                observe: function(e) {
                                    o.observedElementToRelayoutTarget.set(e, e),
                                    n.observe(e)
                                },
                                unobserve: function(e) {
                                    o.observedElementToRelayoutTarget.delete(e),
                                    n.unobserve(e)
                                },
                                observeChild: function(e, t) {
                                    o.observedElementToRelayoutTarget.set(e, t),
                                    n.observe(e)
                                },
                                unobserveChild: function(e) {
                                    o.observedElementToRelayoutTarget.delete(e),
                                    n.unobserve(e)
                                }
                            }
                              , s = X({
                                resizeService: o
                            });
                            return Ee("wix-element", s),
                            {
                                defineWixImage: Ae.bind(null, s),
                                defineWixBgImage: we.bind(null, s),
                                defineWixBgMedia: Oe.bind(null, s, a),
                                defineWixDropdownMenu: Se.bind(null, s),
                                defineWixVideo: Le.bind(null, s),
                                defineWixIframe: Me.bind(null, s)
                            }
                        }
                    };
                    function xe(e, t) {
                        var i = Object.keys(e);
                        if (Object.getOwnPropertySymbols) {
                            var r = Object.getOwnPropertySymbols(e);
                            t && (r = r.filter((function(t) {
                                return Object.getOwnPropertyDescriptor(e, t).enumerable
                            }
                            ))),
                            i.push.apply(i, r)
                        }
                        return i
                    }
                    function Pe(e, t, i) {
                        return t in e ? Object.defineProperty(e, t, {
                            value: i,
                            enumerable: !0,
                            configurable: !0,
                            writable: !0
                        }) : e[t] = i,
                        e
                    }
                    var Ce, Fe, Ge, Be, ke = function(e) {
                        for (var t = 1; t < arguments.length; t++) {
                            var i = null != arguments[t] ? arguments[t] : {};
                            t % 2 ? xe(Object(i), !0).forEach((function(t) {
                                Pe(e, t, i[t])
                            }
                            )) : Object.getOwnPropertyDescriptors ? Object.defineProperties(e, Object.getOwnPropertyDescriptors(i)) : xe(Object(i)).forEach((function(t) {
                                Object.defineProperty(e, t, Object.getOwnPropertyDescriptor(i, t))
                            }
                            ))
                        }
                        return e
                    }({
                        imageClientApi: h.a
                    }, Re), Ne = window.viewerModel, De = Ne.experiments, He = Ne.media, je = Ne.requestUrl;
                    Ce = {
                        experiments: De,
                        media: He,
                        requestUrl: je
                    },
                    Ge = Promise.all([!("customElements"in window) && i.e(46).then(i.t.bind(null, 779, 7)), !("IntersectionObserver"in window) && i.e(66).then(i.t.bind(null, 780, 7)), !("ResizeObserver"in window) && i.e(154).then(i.bind(null, 781)).then((function(e) {
                        return window.ResizeObserver = e.default
                    }
                    ))]).then((function() {
                        return t = Fe,
                        s = {
                            staticMediaUrl: (e = Ce).media.staticMediaUrl,
                            mediaRootUrl: e.media.mediaRootUrl,
                            experiments: {},
                            isViewerMode: !0,
                            devicePixelRatio: /iemobile/i.test(navigator.userAgent) ? Math.round(window.screen.availWidth / (window.screen.width || window.document.documentElement.clientWidth)) : window.devicePixelRatio
                        },
                        c = {
                            mutationService: a.a,
                            biService: o.instance,
                            isExperimentOpen: function(t) {
                                return Boolean(e.experiments[t])
                            }
                        },
                        l = Object(r.a)({
                            getMediaDimensionsByEffect: function(e, t, i, n) {
                                var a = u.a[e] || {}
                                  , o = a.getMediaDimensions
                                  , s = Object(r.f)(a, ["getMediaDimensions"]);
                                return o ? Object(r.a)(Object(r.a)({}, o(t, i, n)), s) : Object(r.a)({
                                    width: t,
                                    height: i
                                }, s)
                            }
                        }, c),
                        Object(r.a)(Object(r.a)({}, e), {
                            wixCustomElements: t || (i = {
                                init: function(e) {
                                    return new ResizeObserver(e)
                                }
                            },
                            n = {
                                init: function(e) {
                                    return window.addEventListener("resize", e)
                                }
                            },
                            ke.init({
                                resizeService: i,
                                windowResizeService: n
                            })),
                            services: c,
                            environmentConsts: s,
                            mediaServices: l
                        });
                        var e, t, i, n, s, c, l
                    }
                    )),
                    Be = new Promise((function(e) {
                        "complete" === document.readyState || "interactive" === document.readyState ? e() : document.addEventListener("readystatechange", (function() {
                            return e()
                        }
                        ), {
                            once: !0
                        })
                    }
                    )),
                    Promise.all([Ge, Be]).then((function(e) {
                        var t = Object(r.e)(e, 1)[0]
                          , i = t.services
                          , n = t.environmentConsts
                          , a = t.wixCustomElements
                          , o = t.experiments
                          , c = t.media
                          , u = t.requestUrl
                          , l = t.mediaServices;
                        a.defineWixImage(l, n),
                        a.defineWixBgImage(l, n),
                        a.defineWixBgMedia(l, n),
                        a.defineWixVideo(l, Object(r.a)(Object(r.a)({}, n), {
                            staticVideoUrl: c.staticVideoUrl,
                            prefersReducedMotion: Object(s.a)(window, o, u)
                        })),
                        a.defineWixDropdownMenu(i, n),
                        a.defineWixIframe(i, n)
                    }
                    )),
                    window.__imageClientApi__ = ke.imageClientApi
                },
                19: function(e, t, i) {
                    e.exports = function(e) {
                        var t = {};
                        function i(r) {
                            if (t[r])
                                return t[r].exports;
                            var n = t[r] = {
                                i: r,
                                l: !1,
                                exports: {}
                            };
                            return e[r].call(n.exports, n, n.exports, i),
                            n.l = !0,
                            n.exports
                        }
                        return i.m = e,
                        i.c = t,
                        i.d = function(e, t, r) {
                            i.o(e, t) || Object.defineProperty(e, t, {
                                enumerable: !0,
                                get: r
                            })
                        }
                        ,
                        i.r = function(e) {
                            "undefined" != typeof Symbol && Symbol.toStringTag && Object.defineProperty(e, Symbol.toStringTag, {
                                value: "Module"
                            }),
                            Object.defineProperty(e, "__esModule", {
                                value: !0
                            })
                        }
                        ,
                        i.t = function(e, t) {
                            if (1 & t && (e = i(e)),
                            8 & t)
                                return e;
                            if (4 & t && "object" == typeof e && e && e.__esModule)
                                return e;
                            var r = Object.create(null);
                            if (i.r(r),
                            Object.defineProperty(r, "default", {
                                enumerable: !0,
                                value: e
                            }),
                            2 & t && "string" != typeof e)
                                for (var n in e)
                                    i.d(r, n, function(t) {
                                        return e[t]
                                    }
                                    .bind(null, n));
                            return r
                        }
                        ,
                        i.n = function(e) {
                            var t = e && e.__esModule ? function() {
                                return e.default
                            }
                            : function() {
                                return e
                            }
                            ;
                            return i.d(t, "a", t),
                            t
                        }
                        ,
                        i.o = function(e, t) {
                            return Object.prototype.hasOwnProperty.call(e, t)
                        }
                        ,
                        i.p = "",
                        i(i.s = 15)
                    }([function(e, t, i) {
                        "use strict";
                        var r = {
                            JPG: "jpg",
                            JPEG: "jpeg",
                            JPE: "jpe",
                            PNG: "png",
                            WEBP: "webp",
                            WIX_ICO_MP: "wix_ico_mp",
                            WIX_MP: "wix_mp",
                            GIF: "gif",
                            SVG: "svg",
                            UNRECOGNIZED: "unrecognized"
                        }
                          , n = [r.JPG, r.JPEG, r.JPE, r.PNG, r.GIF, r.WEBP];
                        e.exports = {
                            alignTypes: {
                                CENTER: "center",
                                TOP: "top",
                                TOP_LEFT: "top_left",
                                TOP_RIGHT: "top_right",
                                BOTTOM: "bottom",
                                BOTTOM_LEFT: "bottom_left",
                                BOTTOM_RIGHT: "bottom_right",
                                LEFT: "left",
                                RIGHT: "right"
                            },
                            alignTypesMap: {
                                center: "c",
                                top: "t",
                                top_left: "tl",
                                top_right: "tr",
                                bottom: "b",
                                bottom_left: "bl",
                                bottom_right: "br",
                                left: "l",
                                right: "r"
                            },
                            transformTypes: {
                                FIT: "fit",
                                FILL: "fill",
                                FILL_FOCAL: "fill_focal",
                                CROP: "crop",
                                LEGACY_CROP: "legacy_crop",
                                LEGACY_FILL: "legacy_fill"
                            },
                            fittingTypes: {
                                SCALE_TO_FILL: "fill",
                                SCALE_TO_FIT: "fit",
                                STRETCH: "stretch",
                                ORIGINAL_SIZE: "original_size",
                                TILE: "tile",
                                TILE_HORIZONTAL: "tile_horizontal",
                                TILE_VERTICAL: "tile_vertical",
                                FIT_AND_TILE: "fit_and_tile",
                                LEGACY_STRIP_TILE: "legacy_strip_tile",
                                LEGACY_STRIP_TILE_HORIZONTAL: "legacy_strip_tile_horizontal",
                                LEGACY_STRIP_TILE_VERTICAL: "legacy_strip_tile_vertical",
                                LEGACY_STRIP_SCALE_TO_FILL: "legacy_strip_fill",
                                LEGACY_STRIP_SCALE_TO_FIT: "legacy_strip_fit",
                                LEGACY_STRIP_FIT_AND_TILE: "legacy_strip_fit_and_tile",
                                LEGACY_STRIP_ORIGINAL_SIZE: "legacy_strip_original_size",
                                LEGACY_ORIGINAL_SIZE: "actual_size",
                                LEGACY_FIT_WIDTH: "fitWidth",
                                LEGACY_FIT_HEIGHT: "fitHeight",
                                LEGACY_FULL: "full",
                                LEGACY_BG_FIT_AND_TILE: "legacy_tile",
                                LEGACY_BG_FIT_AND_TILE_HORIZONTAL: "legacy_tile_horizontal",
                                LEGACY_BG_FIT_AND_TILE_VERTICAL: "legacy_tile_vertical",
                                LEGACY_BG_NORMAL: "legacy_normal"
                            },
                            htmlTag: {
                                BG: "bg",
                                IMG: "img",
                                SVG: "svg"
                            },
                            upscaleMethods: {
                                AUTO: "auto",
                                CLASSIC: "classic",
                                SUPER: "super"
                            },
                            upscaleMethodsValues: {
                                classic: 1,
                                super: 2
                            },
                            defaultUSM: {
                                radius: .66,
                                amount: 1,
                                threshold: .01
                            },
                            emptyData: {
                                uri: "",
                                css: {
                                    img: {},
                                    container: {}
                                },
                                attr: {
                                    img: {},
                                    container: {}
                                }
                            },
                            imageQuality: {
                                HIGH: "HIGH",
                                MEDIUM: "MEDIUM",
                                LOW: "LOW",
                                TINY: "TINY"
                            },
                            imageFilters: {
                                CONTRAST: "contrast",
                                BRIGHTNESS: "brightness",
                                SATURATION: "saturation",
                                HUE: "hue",
                                BLUR: "blur"
                            },
                            imageScaleDefaults: {
                                HIGH: {
                                    size: 196e4,
                                    quality: 90,
                                    maxUpscale: 1
                                },
                                MEDIUM: {
                                    size: 36e4,
                                    quality: 85,
                                    maxUpscale: 1
                                },
                                LOW: {
                                    size: 16e4,
                                    quality: 80,
                                    maxUpscale: 1.2
                                },
                                TINY: {
                                    size: 0,
                                    quality: 80,
                                    maxUpscale: 1.4
                                }
                            },
                            fileType: r,
                            supportedExtensions: n,
                            webp: {
                                LOSSLESS: "lossless",
                                LOSSY: "lossy",
                                ALPHA: "alpha",
                                ANIMATION: "animation"
                            },
                            noWEBP: {
                                lossless: !1,
                                lossy: !1,
                                alpha: !1,
                                animation: !1
                            },
                            DSKTP_MAX_BG_SITE_LEGACY_WIDTH: 1920,
                            MOBILE_MAX_BG_SITE_LEGACY_WIDTH: 1e3,
                            DSKTP_MAX_BG_SITE_LEGACY_HEIGHT: 1920,
                            MOBILE_MAX_BG_SITE_LEGACY_HEIGHT: 1e3,
                            SAFE_TRANSFORMED_AREA: 25e6,
                            SUPER_UPSCALE_MODELS: [1.5, 2, 4],
                            MAX_DEVICE_PIXEL_RATIO: 2,
                            API_VERSION: "v1"
                        }
                    }
                    , function(e, t, i) {
                        "use strict";
                        var r = i(3)
                          , n = i(0);
                        function a(e) {
                            var t = [n.fileType.PNG, n.fileType.JPEG, n.fileType.JPG, n.fileType.JPE, n.fileType.WIX_ICO_MP, n.fileType.WIX_MP];
                            return r.includes(t, c(e))
                        }
                        function o(e) {
                            return r.includes(["webp"], c(e))
                        }
                        function s(e) {
                            return /(^https?)|(^data)|(^\/\/)/.test(e)
                        }
                        function c(e) {
                            return (/[.]([^.]+)$/.exec(e) && /[.]([^.]+)$/.exec(e)[1] || "").toLowerCase()
                        }
                        function u(e, t, i, r, a) {
                            return a === n.transformTypes.FILL ? function(e, t, i, r) {
                                return Math.max(i / e, r / t)
                            }(e, t, i, r) : a === n.transformTypes.FIT ? function(e, t, i, r) {
                                return Math.min(i / e, r / t)
                            }(e, t, i, r) : 1
                        }
                        function l(e, t) {
                            var i = f(e, t);
                            return {
                                optimizedScaleFactor: n.imageScaleDefaults[i].maxUpscale,
                                upscaleMethodValue: n.upscaleMethodsValues.classic,
                                forceUSM: !1
                            }
                        }
                        function h(e, t) {
                            var i = f(e, t);
                            return {
                                optimizedScaleFactor: n.imageScaleDefaults[i].maxUpscale,
                                upscaleMethodValue: n.upscaleMethodsValues.classic,
                                forceUSM: !1
                            }
                        }
                        function d(e, t, i) {
                            return {
                                optimizedScaleFactor: r.last(n.SUPER_UPSCALE_MODELS),
                                upscaleMethodValue: n.upscaleMethodsValues.super,
                                forceUSM: !(n.SUPER_UPSCALE_MODELS.includes(i) || i > r.last(n.SUPER_UPSCALE_MODELS))
                            }
                        }
                        function f(e, t) {
                            var i = e * t;
                            return i > n.imageScaleDefaults[n.imageQuality.HIGH].size ? n.imageQuality.HIGH : i > n.imageScaleDefaults[n.imageQuality.MEDIUM].size ? n.imageQuality.MEDIUM : i > n.imageScaleDefaults[n.imageQuality.LOW].size ? n.imageQuality.LOW : n.imageQuality.TINY
                        }
                        function p(e, t) {
                            var i = Math.pow(10, t || 0);
                            return (e * i / i).toFixed(parseInt(t, 10))
                        }
                        e.exports.isImageTransformApplicable = function(e) {
                            return a(e) && !s(e)
                        }
                        ,
                        e.exports.isValidRequest = function(e, t, i) {
                            return i && t && !(!(a = t.id) || !a.trim() || "none" === a.toLowerCase()) && r.includes(n.fittingTypes, e);
                            var a
                        }
                        ,
                        e.exports.isImageTypeSupported = a,
                        e.exports.isExternalUrl = s,
                        e.exports.isWEBP = o,
                        e.exports.isSEOBot = function(e) {
                            return e && e.isSEOBot || !1
                        }
                        ,
                        e.exports.getFileType = function(e) {
                            return function(e) {
                                return r.includes([n.fileType.JPEG, n.fileType.JPG, n.fileType.JPE], c(e))
                            }(e) ? n.fileType.JPG : function(e) {
                                return r.includes(["png"], c(e))
                            }(e) ? n.fileType.PNG : o(e) ? n.fileType.WEBP : n.fileType.UNRECOGNIZED
                        }
                        ,
                        e.exports.getFileExtension = c,
                        e.exports.getFileName = function(e, t) {
                            var i = /\.([^.]*)$/;
                            if ("string" == typeof t && t.length) {
                                var a = ["/", "\\", "?", "<", ">", "|", "\u201c", ":", '"'].map(encodeURIComponent)
                                  , o = new RegExp("(" + a.concat(["\\.", "\\*"]).join("|") + ")","g")
                                  , s = t
                                  , c = t.match(i);
                                return c && r.includes(n.supportedExtensions, c[1]) && (s = t.replace(i, "")),
                                encodeURIComponent(s).replace(o, "_")
                            }
                            var u = e.match(/\/(.*?)$/);
                            return (u ? u[1] : e).replace(i, "")
                        }
                        ,
                        e.exports.getAlignedRect = function(e, t, i) {
                            var r, a;
                            switch (i) {
                            case n.alignTypes.CENTER:
                                r = Math.max(0, (e.width - t.width) / 2),
                                a = Math.max(0, (e.height - t.height) / 2);
                                break;
                            case n.alignTypes.TOP:
                                r = Math.max(0, (e.width - t.width) / 2),
                                a = 0;
                                break;
                            case n.alignTypes.TOP_LEFT:
                                r = 0,
                                a = 0;
                                break;
                            case n.alignTypes.TOP_RIGHT:
                                r = Math.max(0, e.width - t.width),
                                a = 0;
                                break;
                            case n.alignTypes.BOTTOM:
                                r = Math.max(0, (e.width - t.width) / 2),
                                a = Math.max(0, e.height - t.height);
                                break;
                            case n.alignTypes.BOTTOM_LEFT:
                                r = 0,
                                a = Math.max(0, e.height - t.height);
                                break;
                            case n.alignTypes.BOTTOM_RIGHT:
                                r = Math.max(0, e.width - t.width),
                                a = Math.max(0, e.height - t.height);
                                break;
                            case n.alignTypes.LEFT:
                                r = 0,
                                a = Math.max(0, (e.height - t.height) / 2);
                                break;
                            case n.alignTypes.RIGHT:
                                r = Math.max(0, e.width - t.width),
                                a = Math.max(0, (e.height - t.height) / 2)
                            }
                            return {
                                x: e.x ? e.x + r : r,
                                y: e.y ? e.y + a : a,
                                width: Math.min(e.width, t.width),
                                height: Math.min(e.height, t.height)
                            }
                        }
                        ,
                        e.exports.getOverlappingRect = function(e, t) {
                            var i = Math.max(0, Math.min(e.width, t.x + t.width) - Math.max(0, t.x))
                              , r = Math.max(0, Math.min(e.height, t.y + t.height) - Math.max(0, t.y));
                            return i && r && (e.width !== i || e.height !== r) ? {
                                x: Math.max(0, t.x),
                                y: Math.max(0, t.y),
                                width: i,
                                height: r
                            } : null
                        }
                        ,
                        e.exports.getScaleFactor = u,
                        e.exports.getTransformData = function(e, t, i, r, a, o) {
                            var s = function(e, t, i, r, a) {
                                var o, s, c;
                                if (o = u(e, t, i, r, a),
                                a === n.transformTypes.FILL ? (s = i,
                                c = r) : a === n.transformTypes.FIT && (s = e * o,
                                c = t * o),
                                s * c > n.SAFE_TRANSFORMED_AREA) {
                                    var l = Math.sqrt(n.SAFE_TRANSFORMED_AREA / (s * c));
                                    o = u(e, t, s *= l, c *= l, a)
                                }
                                return {
                                    scaleFactor: o,
                                    width: s,
                                    height: c
                                }
                            }(e = e || i.width, t = t || i.height, i.width * r, i.height * r, a)
                              , c = s.scaleFactor;
                            return function(e, t, i, r, a, o, s) {
                                var c, u, f = function(e, t, i, r) {
                                    return {
                                        classic: l,
                                        auto: h,
                                        super: d
                                    }[r](e, t, i)
                                }(e, t, o, a), p = f.optimizedScaleFactor, g = f.upscaleMethodValue, m = f.forceUSM;
                                if (o <= p)
                                    return {
                                        width: i,
                                        height: r,
                                        scaleFactor: o,
                                        upscaleMethodValue: g,
                                        forceUSM: m,
                                        cssUpscaleNeeded: !1
                                    };
                                switch (s) {
                                case n.transformTypes.FILL:
                                    c = i * (p / o),
                                    u = r * (p / o);
                                    break;
                                case n.transformTypes.FIT:
                                    c = e * p,
                                    u = t * p
                                }
                                return {
                                    width: c,
                                    height: u,
                                    scaleFactor: p,
                                    upscaleMethodValue: g,
                                    forceUSM: m,
                                    cssUpscaleNeeded: !0
                                }
                            }(e, t, s.width, s.height, o, c, a)
                        }
                        ,
                        e.exports.getDevicePixelRatio = function(e) {
                            return Math.min(e.pixelAspectRatio || 1, n.MAX_DEVICE_PIXEL_RATIO)
                        }
                        ,
                        e.exports.getAlignment = function(e) {
                            return n.alignTypesMap[e.alignment] || n.alignTypesMap[n.alignTypes.CENTER]
                        }
                        ,
                        e.exports.getPreferredImageQuality = function(e, t) {
                            return n.imageScaleDefaults[f(e, t)].quality
                        }
                        ,
                        e.exports.getDimension = function(e, t, i, r, n) {
                            var a = u(e, t, i, r, n);
                            return {
                                width: Math.round(e * a),
                                height: Math.round(t * a)
                            }
                        }
                        ,
                        e.exports.getFocalPoint = function(e) {
                            var t = null;
                            return "number" != typeof e.x || isNaN(e.x) || "number" != typeof e.y || isNaN(e.y) || (t = {
                                x: p(Math.max(0, Math.min(100, e.x)) / 100, 2),
                                y: p(Math.max(0, Math.min(100, e.y)) / 100, 2)
                            }),
                            t
                        }
                        ,
                        e.exports.getUpscaleString = function(e) {
                            return e && e.upscaleMethod && "string" == typeof e.upscaleMethod && n.upscaleMethods[e.upscaleMethod.toUpperCase()] || n.upscaleMethods.AUTO
                        }
                        ,
                        e.exports.roundToFixed = p
                    }
                    , function(e, t, i) {
                        "use strict";
                        var r = {
                            isWEBP: i(0).noWEBP,
                            isObjectFitBrowser: !0
                        };
                        e.exports.getFeature = function(e) {
                            return r[e]
                        }
                        ,
                        e.exports.setFeature = function(e, t) {
                            r[e] = t
                        }
                    }
                    , function(e, t, i) {
                        "use strict";
                        function r(e) {
                            return (r = "function" == typeof Symbol && "symbol" == typeof Symbol.iterator ? function(e) {
                                return typeof e
                            }
                            : function(e) {
                                return e && "function" == typeof Symbol && e.constructor === Symbol && e !== Symbol.prototype ? "symbol" : typeof e
                            }
                            )(e)
                        }
                        e.exports.includes = function(e, t) {
                            return e.indexOf ? e.indexOf(t) > -1 : !(!e || "object" !== r(e)) && Object.keys(e).some((function(i) {
                                return e[i] === t
                            }
                            ))
                        }
                        ,
                        e.exports.last = function(e) {
                            return e[e.length - 1]
                        }
                        ,
                        e.exports.template = function(e) {
                            return function(t) {
                                var i = e;
                                for (var r in t)
                                    t.hasOwnProperty(r) && (i = i.replace(new RegExp("\\${" + r + "}","g"), t[r]));
                                return i
                            }
                        }
                    }
                    , function(e, t, i) {
                        "use strict";
                        function r(e, t) {
                            var i = Object.keys(e);
                            if (Object.getOwnPropertySymbols) {
                                var r = Object.getOwnPropertySymbols(e);
                                t && (r = r.filter((function(t) {
                                    return Object.getOwnPropertyDescriptor(e, t).enumerable
                                }
                                ))),
                                i.push.apply(i, r)
                            }
                            return i
                        }
                        function n(e, t, i) {
                            return t in e ? Object.defineProperty(e, t, {
                                value: i,
                                enumerable: !0,
                                configurable: !0,
                                writable: !0
                            }) : e[t] = i,
                            e
                        }
                        var a = i(1)
                          , o = a.isSEOBot
                          , s = a.getFileType
                          , c = a.getFileName
                          , u = a.getFileExtension
                          , l = a.getDevicePixelRatio
                          , h = a.getUpscaleString
                          , d = a.isImageTransformApplicable
                          , f = i(7)
                          , p = f.isMobile
                          , g = f.isWEBPBrowserSupport
                          , m = i(10)
                          , b = i(11)
                          , v = i(0);
                        e.exports.getTransform = function(e, t, i, r) {
                            var n = o(r)
                              , a = s(t.id)
                              , f = c(t.id, t.name)
                              , p = u(t.id)
                              , v = !n && g(a)
                              , T = n ? 1 : l(i)
                              , _ = {
                                fileName: f,
                                fileExtension: p,
                                fileType: a,
                                isWEBPSupport: v,
                                fittingType: e,
                                preferredExtension: v ? "webp" : p,
                                src: {
                                    id: t.id,
                                    width: t.width,
                                    height: t.height,
                                    isCropped: !1
                                },
                                focalPoint: {
                                    x: t.focalPoint && t.focalPoint.x,
                                    y: t.focalPoint && t.focalPoint.y
                                },
                                parts: [],
                                devicePixelRatio: T,
                                quality: 0,
                                upscaleMethod: h(r),
                                progressive: !0,
                                watermark: "",
                                unsharpMask: {},
                                filters: {}
                            };
                            return d(t.id) && (m.setTransformParts(_, t, i),
                            b.setTransformOptions(_, r)),
                            _
                        }
                        ,
                        e.exports.getTarget = function(e, t, i) {
                            var a = function(e) {
                                for (var t = 1; t < arguments.length; t++) {
                                    var i = null != arguments[t] ? arguments[t] : {};
                                    t % 2 ? r(Object(i), !0).forEach((function(t) {
                                        n(e, t, i[t])
                                    }
                                    )) : Object.getOwnPropertyDescriptors ? Object.defineProperties(e, Object.getOwnPropertyDescriptors(i)) : r(Object(i)).forEach((function(t) {
                                        Object.defineProperty(e, t, Object.getOwnPropertyDescriptor(i, t))
                                    }
                                    ))
                                }
                                return e
                            }({}, i)
                              , o = p();
                            switch (e) {
                            case v.fittingTypes.LEGACY_BG_FIT_AND_TILE:
                            case v.fittingTypes.LEGACY_BG_FIT_AND_TILE_HORIZONTAL:
                            case v.fittingTypes.LEGACY_BG_FIT_AND_TILE_VERTICAL:
                            case v.fittingTypes.LEGACY_BG_NORMAL:
                                var s = o ? v.MOBILE_MAX_BG_SITE_LEGACY_WIDTH : v.DSKTP_MAX_BG_SITE_LEGACY_WIDTH
                                  , c = o ? v.MOBILE_MAX_BG_SITE_LEGACY_HEIGHT : v.DSKTP_MAX_BG_SITE_LEGACY_HEIGHT;
                                a.width = Math.min(s, t.width),
                                a.height = Math.min(c, Math.round(a.width / (t.width / t.height))),
                                a.pixelAspectRatio = 1
                            }
                            return a
                        }
                    }
                    , function(e, t, i) {
                        "use strict";
                        var r = i(2)
                          , n = i(0);
                        function a(e) {
                            var t = r.getFeature("isWEBP")
                              , i = new window.Image;
                            i.onload = function() {
                                t[e] = i.width > 0 && i.height > 0,
                                r.setFeature("isWEBP", t)
                            }
                            ,
                            i.onerror = function() {
                                t[e] = !1,
                                r.setFeature("isWEBP", t)
                            }
                            ,
                            i.src = "data:image/webp;base64," + {
                                lossy: "UklGRiIAAABXRUJQVlA4IBYAAAAwAQCdASoBAAEADsD+JaQAA3AAAAAA",
                                lossless: "UklGRhoAAABXRUJQVlA4TA0AAAAvAAAAEAcQERGIiP4HAA==",
                                alpha: "UklGRkoAAABXRUJQVlA4WAoAAAAQAAAAAAAAAAAAQUxQSAwAAAARBxAR/Q9ERP8DAABWUDggGAAAABQBAJ0BKgEAAQAAAP4AAA3AAP7mtQAAAA==",
                                animation: "UklGRlIAAABXRUJQVlA4WAoAAAASAAAAAAAAAAAAQU5JTQYAAAD/////AABBTk1GJgAAAAAAAAAAAAAAAAAAAGQAAABWUDhMDQAAAC8AAAAQBxAREYiI/gcA"
                            }[e]
                        }
                        e.exports.checkSupportByUserAgent = function(e, t) {
                            var i = t.browser
                              , a = t.os;
                            if (e) {
                                var o, s = parseFloat(i.version), c = parseFloat(a.version), u = new RegExp(/AppleWebKit\/([\d.]+)/), l = null === u.exec(e) ? null : parseFloat(u.exec(e)[1]), h = function(e, t, i, r, n) {
                                    var a = !e.phone && !e.tablet && i.chrome && r >= 23
                                      , o = e.android && (e.phone || e.tablet) && i.webkit && i.chrome && r >= 25
                                      , s = e.android && n < 535 && (e.phone || e.tablet) && t >= 4.2 && i.webkit && !i.safari
                                      , c = i.edge && r >= 18
                                      , u = !e.firefoxos && i.firefox && !i.webkit && r >= 65;
                                    return !!(a || o || s || c || u)
                                }(a, c, i, s, l);
                                r.setFeature("isWEBP", ((o = {})[n.webp.LOSSY] = function(e, t, i, r, n) {
                                    var a = !e.phone && !e.tablet && i.chrome && r >= 17
                                      , o = e.android && (e.phone || e.tablet) && i.webkit && i.chrome && r >= 25
                                      , s = e.android && n < 535 && (e.phone || e.tablet) && t >= 4 && i.webkit
                                      , c = i.edge && r >= 18
                                      , u = !e.firefoxos && i.firefox && !i.webkit && r >= 65;
                                    return !!(a || o || s || c || u)
                                }(a, c, i, s, l),
                                o[n.webp.LOSSLESS] = h,
                                o[n.webp.ALPHA] = h,
                                o[n.webp.ANIMATION] = function(e, t, i, r) {
                                    var n = !e.ios && i.chrome && r >= 32
                                      , a = i.edge && r >= 18
                                      , o = !e.firefoxos && i.firefox && !i.webkit && r >= 65;
                                    return !!(n || a || o)
                                }(a, 0, i, s),
                                o))
                            }
                        }
                        ,
                        e.exports.checkSupportByFeatureDetection = function() {
                            a(n.webp.LOSSY),
                            a(n.webp.LOSSLESS),
                            a(n.webp.ALPHA),
                            a(n.webp.ANIMATION)
                        }
                        ,
                        e.exports.isWEBPBrowserSupport = function(e) {
                            var t = r.getFeature("isWEBP")
                              , i = e === n.fileType.JPG && t[n.webp.LOSSY]
                              , a = e === n.fileType.PNG && t[n.webp.LOSSLESS]
                              , o = e === n.fileType.PNG && t[n.webp.ALPHA];
                            return i || a && o
                        }
                    }
                    , function(e, t, i) {
                        "use strict";
                        var r = i(0).noWEBP
                          , n = i(9)
                          , a = i(5)
                          , o = i(2);
                        e.exports.populateGlobalFeatureSupport = function(e) {
                            var t;
                            void 0 === e && (e = ""),
                            "undefined" != typeof window && "undefined" != typeof navigator ? ((t = n(navigator.userAgent)).browser.safari || t.os.iphone || t.os.ipad ? o.setFeature("isWEBP", r) : (a.checkSupportByUserAgent(navigator.userAgent, t),
                            a.checkSupportByFeatureDetection()),
                            o.setFeature("isObjectFitBrowser", "objectFit"in window.document.documentElement.style),
                            o.setFeature("isMobile", t.os.phone)) : (t = n(e),
                            a.checkSupportByUserAgent(e, t),
                            o.setFeature("isMobile", t.os.phone))
                        }
                    }
                    , function(e, t, i) {
                        "use strict";
                        var r = i(5)
                          , n = i(2);
                        e.exports.isWEBPBrowserSupport = r.isWEBPBrowserSupport,
                        e.exports.isObjectFitBrowserSupport = function() {
                            return n.getFeature("isObjectFitBrowser")
                        }
                        ,
                        e.exports.isMobile = function() {
                            return n.getFeature("isMobile")
                        }
                    }
                    , function(e, t, i) {
                        "use strict";
                        var r = i(0)
                          , n = i(1).isImageTransformApplicable
                          , a = i(12)
                          , o = i(4);
                        e.exports.getURI = function(e, t, i, s, c) {
                            var u = r.emptyData.uri;
                            return n(t.id) ? (c = c || o.getTransform(e, t, i, s, c),
                            u = a.getImageURI(c)) : u = t.id,
                            u
                        }
                    }
                    , function(e, t, i) {
                        e.exports = function() {
                            "use strict";
                            return function(e) {
                                var t = {}
                                  , i = {};
                                if (!e)
                                    return {
                                        browser: i,
                                        os: t
                                    };
                                var r = e.match(/Web[kK]it[\/]{0,1}([\d.]+)/)
                                  , n = e.match(/(Android);?[\s\/]+([\d.]+)?/)
                                  , a = !!e.match(/\(Macintosh\; Intel /)
                                  , o = e.match(/(iPad).*OS\s([\d_]+)/)
                                  , s = e.match(/(iPod)(.*OS\s([\d_]+))?/)
                                  , c = !o && e.match(/(iPhone\sOS)\s([\d_]+)/)
                                  , u = e.match(/(webOS|hpwOS)[\s\/]([\d.]+)/)
                                  , l = e.match(/Windows Phone ([\d.]+)/)
                                  , h = u && e.match(/TouchPad/)
                                  , d = e.match(/Kindle\/([\d.]+)/)
                                  , f = e.match(/Silk\/([\d._]+)/)
                                  , p = e.match(/(BlackBerry).*Version\/([\d.]+)/)
                                  , g = e.match(/(BB10).*Version\/([\d.]+)/)
                                  , m = e.match(/(RIM\sTablet\sOS)\s([\d.]+)/)
                                  , b = e.match(/PlayBook/)
                                  , v = e.match(/Chrome\/([\d.]+)/) || e.match(/CriOS\/([\d.]+)/)
                                  , T = e.match(/Firefox\/([\d.]+)/)
                                  , _ = e.match(/MSIE\s([\d.]+)/) || e.match(/Trident\/[\d](?=[^\?]+).*rv:([0-9.].)/)
                                  , y = !v && e.match(/(iPhone|iPod|iPad).*AppleWebKit(?!.*Safari)/)
                                  , I = y || e.match(/Version\/([\d.]+)([^S](Safari)|[^M]*(Mobile)[^S]*(Safari))/)
                                  , E = e.match(/Edge\/(\d{2,}\.[\d\w]+)$/)
                                  , A = e.match(/Opera Mini/);
                                return i.webkit = r && !E,
                                i.webkit && (i.version = r[1]),
                                n && (t.android = !0,
                                t.version = n[2]),
                                c && !s && (t.ios = t.iphone = !0,
                                t.version = c[2].replace(/_/g, ".")),
                                o && (t.ios = t.ipad = !0,
                                t.version = o[2].replace(/_/g, ".")),
                                s && (t.ios = t.ipod = !0,
                                t.version = s[3] ? s[3].replace(/_/g, ".") : null),
                                l && (t.wp = !0,
                                t.version = l[1]),
                                u && (t.webos = !0,
                                t.version = u[2]),
                                h && (t.touchpad = !0),
                                p && (t.blackberry = !0,
                                t.version = p[2]),
                                g && (t.bb10 = !0,
                                t.version = g[2]),
                                m && (t.rimtabletos = !0,
                                t.version = m[2]),
                                b && (i.playbook = !0),
                                d && (t.kindle = !0,
                                t.version = d[1]),
                                f && (i.silk = !0,
                                i.version = f[1]),
                                !f && t.android && e.match(/Kindle Fire/) && (i.silk = !0),
                                v && !E && (i.chrome = !0,
                                i.version = v[1]),
                                T && !E && (i.firefox = !0,
                                i.version = T[1]),
                                _ && (i.ie = !0,
                                i.version = _[1]),
                                I && (a || t.ios) && (i.safari = !0,
                                a && (i.version = I[1])),
                                y && (i.webview = !0),
                                E && (i.edge = !0,
                                i.version = E[1]),
                                A && (i.operaMini = !0),
                                t.tablet = !!(o || b || n && !e.match(/Mobile/) || T && e.match(/Tablet/) || (_ || E) && !e.match(/Phone/) && e.match(/Touch/)),
                                t.phone = !(t.tablet || t.ipod || !(n || c || u || p || g || v && e.match(/Android/) || v && e.match(/CriOS\/([\d.]+)/) || T && e.match(/Mobile/) || _ && e.match(/Touch/))),
                                t.mac = a,
                                t.googleBot = !!e.match(/Googlebot\/2.1/),
                                {
                                    browser: i,
                                    os: t
                                }
                            }
                        }()
                    }
                    , function(e, t, i) {
                        "use strict";
                        var r = i(0)
                          , n = i(1)
                          , a = n.getAlignment
                          , o = n.getScaleFactor
                          , s = n.getOverlappingRect
                          , c = n.getAlignedRect
                          , u = n.getTransformData
                          , l = n.getFocalPoint;
                        function h(e, t) {
                            var i = u(e.src.width, e.src.height, t, e.devicePixelRatio, r.transformTypes.FIT, e.upscaleMethod);
                            return {
                                transformType: r.transformTypes.FILL,
                                width: Math.round(i.width),
                                height: Math.round(i.height),
                                alignment: r.alignTypesMap.center,
                                upscale: i.scaleFactor > 1,
                                forceUSM: i.forceUSM,
                                scaleFactor: i.scaleFactor,
                                cssUpscaleNeeded: i.cssUpscaleNeeded,
                                upscaleMethodValue: i.upscaleMethodValue
                            }
                        }
                        function d(e) {
                            return {
                                transformType: r.transformTypes.CROP,
                                x: Math.round(e.x),
                                y: Math.round(e.y),
                                width: Math.round(e.width),
                                height: Math.round(e.height),
                                upscale: !1,
                                forceUSM: !1,
                                scaleFactor: 1,
                                cssUpscaleNeeded: !1
                            }
                        }
                        e.exports.setTransformParts = function(e, t, i) {
                            var n;
                            switch (t.crop && (n = s(t, t.crop)) && (e.src.width = n.width,
                            e.src.height = n.height,
                            e.src.cropped = !0,
                            e.parts.push(d(n))),
                            e.fittingType) {
                            case r.fittingTypes.SCALE_TO_FIT:
                            case r.fittingTypes.LEGACY_FIT_WIDTH:
                            case r.fittingTypes.LEGACY_FIT_HEIGHT:
                            case r.fittingTypes.LEGACY_FULL:
                            case r.fittingTypes.FIT_AND_TILE:
                            case r.fittingTypes.LEGACY_BG_FIT_AND_TILE:
                            case r.fittingTypes.LEGACY_BG_FIT_AND_TILE_HORIZONTAL:
                            case r.fittingTypes.LEGACY_BG_FIT_AND_TILE_VERTICAL:
                            case r.fittingTypes.LEGACY_BG_NORMAL:
                                e.parts.push(h(e, i));
                                break;
                            case r.fittingTypes.SCALE_TO_FILL:
                                e.parts.push(function(e, t) {
                                    var i = u(e.src.width, e.src.height, t, e.devicePixelRatio, r.transformTypes.FILL, e.upscaleMethod)
                                      , n = l(e.focalPoint);
                                    return {
                                        transformType: n ? r.transformTypes.FILL_FOCAL : r.transformTypes.FILL,
                                        width: Math.round(i.width),
                                        height: Math.round(i.height),
                                        alignment: a(t),
                                        focalPointX: n && n.x,
                                        focalPointY: n && n.y,
                                        upscale: i.scaleFactor > 1,
                                        forceUSM: i.forceUSM,
                                        scaleFactor: i.scaleFactor,
                                        cssUpscaleNeeded: i.cssUpscaleNeeded,
                                        upscaleMethodValue: i.upscaleMethodValue
                                    }
                                }(e, i));
                                break;
                            case r.fittingTypes.STRETCH:
                                e.parts.push(function(e, t) {
                                    var i = o(e.src.width, e.src.height, t.width, t.height, r.transformTypes.FILL)
                                      , n = Object.assign({}, t);
                                    return n.width = e.src.width * i,
                                    n.height = e.src.height * i,
                                    h(e, n)
                                }(e, i));
                                break;
                            case r.fittingTypes.TILE_HORIZONTAL:
                            case r.fittingTypes.TILE_VERTICAL:
                            case r.fittingTypes.TILE:
                            case r.fittingTypes.LEGACY_ORIGINAL_SIZE:
                            case r.fittingTypes.ORIGINAL_SIZE:
                                n = c(e.src, i, i.alignment),
                                e.src.isCropped ? (Object.assign(e.parts[0], n),
                                e.src.width = n.width,
                                e.src.height = n.height) : e.parts.push(d(n));
                                break;
                            case r.fittingTypes.LEGACY_STRIP_TILE_HORIZONTAL:
                            case r.fittingTypes.LEGACY_STRIP_TILE_VERTICAL:
                            case r.fittingTypes.LEGACY_STRIP_TILE:
                            case r.fittingTypes.LEGACY_STRIP_ORIGINAL_SIZE:
                                e.parts.push(function(e) {
                                    return {
                                        transformType: r.transformTypes.LEGACY_CROP,
                                        width: Math.round(e.width),
                                        height: Math.round(e.height),
                                        alignment: a(e),
                                        upscale: !1,
                                        forceUSM: !1,
                                        scaleFactor: 1,
                                        cssUpscaleNeeded: !1
                                    }
                                }(i));
                                break;
                            case r.fittingTypes.LEGACY_STRIP_SCALE_TO_FIT:
                            case r.fittingTypes.LEGACY_STRIP_FIT_AND_TILE:
                                e.parts.push(function(e) {
                                    return {
                                        transformType: r.transformTypes.FIT,
                                        width: Math.round(e.width),
                                        height: Math.round(e.height),
                                        upscale: !1,
                                        forceUSM: !0,
                                        scaleFactor: 1,
                                        cssUpscaleNeeded: !1
                                    }
                                }(i));
                                break;
                            case r.fittingTypes.LEGACY_STRIP_SCALE_TO_FILL:
                                e.parts.push(function(e) {
                                    return {
                                        transformType: r.transformTypes.LEGACY_FILL,
                                        width: Math.round(e.width),
                                        height: Math.round(e.height),
                                        alignment: a(e),
                                        upscale: !1,
                                        forceUSM: !0,
                                        scaleFactor: 1,
                                        cssUpscaleNeeded: !1
                                    }
                                }(i))
                            }
                        }
                    }
                    , function(e, t, i) {
                        "use strict";
                        var r = i(3)
                          , n = i(0)
                          , a = i(1)
                          , o = a.getPreferredImageQuality
                          , s = a.roundToFixed;
                        function c(e, t, i) {
                            return !isNaN(e) && "number" == typeof e && 0 !== e && e >= t && e <= i
                        }
                        e.exports.setTransformOptions = function(e, t) {
                            t = t || {},
                            e.quality = function(e, t) {
                                var i = e.fileType === n.fileType.PNG && e.isWEBPSupport;
                                if (e.fileType === n.fileType.JPG || i) {
                                    var a = r.last(e.parts)
                                      , s = o(a.width, a.height)
                                      , c = t.quality && t.quality >= 5 && t.quality <= 90 ? t.quality : s;
                                    return c = i ? c + 5 : c,
                                    parseInt(c, 10)
                                }
                                return 0
                            }(e, t),
                            e.progressive = function(e) {
                                return !1 !== e.progressive
                            }(t),
                            e.watermark = function(e) {
                                return e.watermark
                            }(t),
                            e.unsharpMask = function(e, t) {
                                var i;
                                return function(e) {
                                    e = e || {};
                                    var t = !isNaN(e.radius) && "number" == typeof e.radius && e.radius >= .1 && e.radius <= 500
                                      , i = !isNaN(e.amount) && "number" == typeof e.amount && e.amount >= 0 && e.amount <= 10
                                      , r = !isNaN(e.threshold) && "number" == typeof e.threshold && e.threshold >= 0 && e.threshold <= 255;
                                    return t && i && r
                                }(t.unsharpMask) ? i = {
                                    radius: t.unsharpMask.radius,
                                    amount: t.unsharpMask.amount,
                                    threshold: t.unsharpMask.threshold
                                } : function(e) {
                                    return e = e || {},
                                    !isNaN(e.radius) && "number" == typeof e.radius && 0 === e.radius && !isNaN(e.amount) && "number" == typeof e.amount && 0 === e.amount && !isNaN(e.threshold) && "number" == typeof e.threshold && 0 === e.threshold
                                }(t.unsharpMask) || function(e) {
                                    var t = r.last(e.parts);
                                    return !(t.scaleFactor >= 1) || t.forceUSM
                                }(e) && (i = n.defaultUSM),
                                i && (i.radius = s(i.radius, 2),
                                i.amount = s(i.amount, 2),
                                i.threshold = s(i.threshold, 2)),
                                i
                            }(e, t),
                            e.filters = function(e) {
                                var t = e.filters || {}
                                  , i = {};
                                return c(t[n.imageFilters.CONTRAST], -100, 100) && (i[n.imageFilters.CONTRAST] = t[n.imageFilters.CONTRAST]),
                                c(t[n.imageFilters.BRIGHTNESS], -100, 100) && (i[n.imageFilters.BRIGHTNESS] = t[n.imageFilters.BRIGHTNESS]),
                                c(t[n.imageFilters.SATURATION], -100, 100) && (i[n.imageFilters.SATURATION] = t[n.imageFilters.SATURATION]),
                                c(t[n.imageFilters.HUE], -180, 180) && (i[n.imageFilters.HUE] = t[n.imageFilters.HUE]),
                                c(t[n.imageFilters.BLUR], 0, 100) && (i[n.imageFilters.BLUR] = t[n.imageFilters.BLUR]),
                                i
                            }(t)
                        }
                    }
                    , function(e, t, i) {
                        "use strict";
                        var r, n = i(3), a = i(0), o = a.imageFilters, s = a.transformTypes, c = a.API_VERSION, u = n.template("fit/w_${width},h_${height}"), l = n.template("fill/w_${width},h_${height},al_${alignment}"), h = n.template("fill/w_${width},h_${height},fp_${focalPointX}_${focalPointY}"), d = n.template("crop/x_${x},y_${y},w_${width},h_${height}"), f = n.template("crop/w_${width},h_${height},al_${alignment}"), p = n.template("fill/w_${width},h_${height},al_${alignment}"), g = n.template(",lg_${upscaleMethodValue}"), m = n.template(",q_${quality}"), b = n.template(",usm_${radius}_${amount}_${threshold}"), v = n.template(",bl"), T = n.template(",wm_${watermark}"), _ = ((r = {})[o.CONTRAST] = n.template(",con_${contrast}"),
                        r[o.BRIGHTNESS] = n.template(",br_${brightness}"),
                        r[o.SATURATION] = n.template(",sat_${saturation}"),
                        r[o.HUE] = n.template(",hue_${hue}"),
                        r[o.BLUR] = n.template(",blur_${blur}"),
                        r);
                        e.exports.getImageURI = function(e) {
                            var t = [];
                            e.parts.forEach((function(e) {
                                switch (e.transformType) {
                                case s.CROP:
                                    t.push(d(e));
                                    break;
                                case s.LEGACY_CROP:
                                    t.push(f(e));
                                    break;
                                case s.LEGACY_FILL:
                                    var i = p(e);
                                    e.upscale && (i += g(e)),
                                    t.push(i);
                                    break;
                                case s.FIT:
                                    var r = u(e);
                                    e.upscale && (r += g(e)),
                                    t.push(r);
                                    break;
                                case s.FILL:
                                    var n = l(e);
                                    e.upscale && (n += g(e)),
                                    t.push(n);
                                    break;
                                case s.FILL_FOCAL:
                                    var a = h(e);
                                    e.upscale && (a += g(e)),
                                    t.push(a)
                                }
                            }
                            ));
                            var i = t.join("/");
                            return e.quality && (i += m(e)),
                            e.unsharpMask && (i += b(e.unsharpMask)),
                            e.progressive || (i += v(e)),
                            e.watermark && (i += T(e)),
                            e.filters && (i += Object.keys(e.filters).map((function(t) {
                                return _[t](e.filters)
                            }
                            )).join("")),
                            e.src.id + "/" + c + "/" + i + "/" + e.fileName + "." + e.preferredExtension
                        }
                    }
                    , function(e, t, i) {
                        "use strict";
                        var r = i(14)
                          , n = i(0)
                          , a = /^media\//i
                          , o = "undefined" != typeof window ? window.devicePixelRatio : 1
                          , s = function(e, t) {
                            var i = (void 0 === t ? {} : t).baseHostURL;
                            return i ? "" + i + e : function(e) {
                                return a.test(e) ? "https://static.wixstatic.com/" + e : "https://static.wixstatic.com/media/" + e
                            }(e)
                        };
                        e.exports.populateGlobalFeatureSupport = r.populateGlobalFeatureSupport,
                        e.exports.getScaleToFitImageURL = function(e, t, i, a, c, u) {
                            var l = r.getData(n.fittingTypes.SCALE_TO_FIT, {
                                id: e,
                                width: t,
                                height: i,
                                name: u && u.name
                            }, {
                                width: a,
                                height: c,
                                htmlTag: r.htmlTag.IMG,
                                alignment: r.alignTypes.CENTER,
                                pixelAspectRatio: o
                            }, u);
                            return s(l.uri, u)
                        }
                        ,
                        e.exports.getScaleToFillImageURL = function(e, t, i, a, c, u) {
                            var l = r.getData(n.fittingTypes.SCALE_TO_FILL, {
                                id: e,
                                width: t,
                                height: i,
                                name: u && u.name,
                                focalPoint: {
                                    x: u && u.focalPoint && u.focalPoint.x,
                                    y: u && u.focalPoint && u.focalPoint.y
                                }
                            }, {
                                width: a,
                                height: c,
                                htmlTag: r.htmlTag.IMG,
                                alignment: r.alignTypes.CENTER,
                                pixelAspectRatio: o
                            }, u);
                            return s(l.uri, u)
                        }
                        ,
                        e.exports.getCropImageURL = function(e, t, i, a, c, u, l, h, d, f) {
                            var p = r.getData(n.fittingTypes.SCALE_TO_FILL, {
                                id: e,
                                width: t,
                                height: i,
                                name: f && f.name,
                                crop: {
                                    x: a,
                                    y: c,
                                    width: u,
                                    height: l
                                }
                            }, {
                                width: h,
                                height: d,
                                htmlTag: r.htmlTag.IMG,
                                alignment: r.alignTypes.CENTER,
                                pixelAspectRatio: o
                            }, f);
                            return s(p.uri, f)
                        }
                    }
                    , function(e, t, i) {
                        "use strict";
                        var r = i(0)
                          , n = i(1).isValidRequest
                          , a = i(6).populateGlobalFeatureSupport
                          , o = i(4)
                          , s = i(8).getURI;
                        e.exports.populateGlobalFeatureSupport = a,
                        e.exports.getData = function(e, t, i, a) {
                            var c = r.emptyData.uri;
                            if (n(e, t, i)) {
                                var u = o.getTarget(e, t, i)
                                  , l = o.getTransform(e, t, u, a);
                                c = s(e, t, u, a, l)
                            }
                            return {
                                uri: c
                            }
                        }
                        ,
                        e.exports.fittingTypes = r.fittingTypes,
                        e.exports.alignTypes = r.alignTypes,
                        e.exports.htmlTag = r.htmlTag,
                        e.exports.upscaleMethods = r.upscaleMethods
                    }
                    , function(e, t, i) {
                        "use strict";
                        var r = i(0)
                          , n = i(6).populateGlobalFeatureSupport
                          , a = i(16)
                          , o = a.getData
                          , s = a.getPlaceholder
                          , c = i(13)
                          , u = c.getScaleToFitImageURL
                          , l = c.getScaleToFillImageURL
                          , h = c.getCropImageURL;
                        n(),
                        e.exports.populateGlobalFeatureSupport = n,
                        e.exports.getData = o,
                        e.exports.getPlaceholder = s,
                        e.exports.fittingTypes = r.fittingTypes,
                        e.exports.alignTypes = r.alignTypes,
                        e.exports.htmlTag = r.htmlTag,
                        e.exports.upscaleMethods = r.upscaleMethods,
                        e.exports.sdk = {
                            getScaleToFitImageURL: u,
                            getScaleToFillImageURL: l,
                            getCropImageURL: h
                        }
                    }
                    , function(e, t, i) {
                        "use strict";
                        function r(e, t) {
                            var i = Object.keys(e);
                            if (Object.getOwnPropertySymbols) {
                                var r = Object.getOwnPropertySymbols(e);
                                t && (r = r.filter((function(t) {
                                    return Object.getOwnPropertyDescriptor(e, t).enumerable
                                }
                                ))),
                                i.push.apply(i, r)
                            }
                            return i
                        }
                        function n(e) {
                            for (var t = 1; t < arguments.length; t++) {
                                var i = null != arguments[t] ? arguments[t] : {};
                                t % 2 ? r(Object(i), !0).forEach((function(t) {
                                    a(e, t, i[t])
                                }
                                )) : Object.getOwnPropertyDescriptors ? Object.defineProperties(e, Object.getOwnPropertyDescriptors(i)) : r(Object(i)).forEach((function(t) {
                                    Object.defineProperty(e, t, Object.getOwnPropertyDescriptor(i, t))
                                }
                                ))
                            }
                            return e
                        }
                        function a(e, t, i) {
                            return t in e ? Object.defineProperty(e, t, {
                                value: i,
                                enumerable: !0,
                                configurable: !0,
                                writable: !0
                            }) : e[t] = i,
                            e
                        }
                        var o = i(0)
                          , s = i(1).isValidRequest
                          , c = i(17)
                          , u = i(4)
                          , l = i(8).getURI
                          , h = i(22)
                          , d = h.getScaledDimensions
                          , f = h.getBlurValue
                          , p = h.getCSSOverrides
                          , g = h.validateTargetDimensions
                          , m = h.getIsFakeTile
                          , b = h.getConvertedFitting;
                        function v(e, t, i, r) {
                            var n = {};
                            if (s(e, t, i)) {
                                var a = u.getTarget(e, t, i)
                                  , h = u.getTransform(e, t, a, r);
                                n.uri = l(e, t, a, r, h),
                                Object.assign(n, c.getAttributes(h, a))
                            } else
                                n = o.emptyData;
                            return n
                        }
                        e.exports.getData = v,
                        e.exports.getPlaceholder = function(e, t, i, r) {
                            if (void 0 === r && (r = {}),
                            !s(e, t, i))
                                return o.emptyData;
                            var a = n(n({}, i), g(t, i))
                              , c = i.alignment
                              , u = i.htmlTag
                              , l = r.isSEOBot
                              , h = m(e, t, a)
                              , T = d(e, t, a, l)
                              , _ = f(a.width, e, l)
                              , y = b(e, h)
                              , I = p(e, t, i, c)
                              , E = v(y, t, n(n({}, T), {}, {
                                alignment: c,
                                htmlTag: u
                            }), {
                                filters: {
                                    blur: _
                                }
                            }).uri
                              , A = v(e, t, n(n({}, a), {}, {
                                alignment: c,
                                htmlTag: u
                            }))
                              , w = A.attr
                              , O = void 0 === w ? {} : w
                              , S = A.css;
                            return S.img = S.img || {},
                            S.container = S.container || {},
                            Object.assign(S.img, I.img),
                            Object.assign(S.container, I.container),
                            {
                                uri: E,
                                css: S,
                                attr: O
                            }
                        }
                    }
                    , function(e, t, i) {
                        "use strict";
                        var r = i(0).htmlTag
                          , n = i(7).isObjectFitBrowserSupport
                          , a = i(18)
                          , o = i(19)
                          , s = i(20)
                          , c = i(21);
                        e.exports.getAttributes = function(e, t) {
                            return (t.htmlTag === r.BG ? a : t.htmlTag === r.SVG ? s : n() ? o : c).get(e, t)
                        }
                    }
                    , function(e, t, i) {
                        "use strict";
                        var r = i(0)
                          , n = r.alignTypes
                          , a = r.fittingTypes;
                        e.exports.get = function(e, t) {
                            var i = {
                                css: {
                                    container: {}
                                }
                            }
                              , r = i.css;
                            switch (e.fittingType) {
                            case a.ORIGINAL_SIZE:
                            case a.LEGACY_ORIGINAL_SIZE:
                            case a.LEGACY_STRIP_ORIGINAL_SIZE:
                                r.container.backgroundSize = "auto",
                                r.container.backgroundRepeat = "no-repeat";
                                break;
                            case a.SCALE_TO_FIT:
                            case a.LEGACY_STRIP_SCALE_TO_FIT:
                                r.container.backgroundSize = "contain",
                                r.container.backgroundRepeat = "no-repeat";
                                break;
                            case a.STRETCH:
                                r.container.backgroundSize = "100% 100%",
                                r.container.backgroundRepeat = "no-repeat";
                                break;
                            case a.SCALE_TO_FILL:
                            case a.LEGACY_STRIP_SCALE_TO_FILL:
                                r.container.backgroundSize = "cover",
                                r.container.backgroundRepeat = "no-repeat";
                                break;
                            case a.TILE_HORIZONTAL:
                            case a.LEGACY_STRIP_TILE_HORIZONTAL:
                                r.container.backgroundSize = "auto",
                                r.container.backgroundRepeat = "repeat-x";
                                break;
                            case a.TILE_VERTICAL:
                            case a.LEGACY_STRIP_TILE_VERTICAL:
                                r.container.backgroundSize = "auto",
                                r.container.backgroundRepeat = "repeat-y";
                                break;
                            case a.TILE:
                            case a.LEGACY_STRIP_TILE:
                                r.container.backgroundSize = "auto",
                                r.container.backgroundRepeat = "repeat";
                                break;
                            case a.FIT_AND_TILE:
                            case a.LEGACY_STRIP_FIT_AND_TILE:
                                r.container.backgroundSize = "contain",
                                r.container.backgroundRepeat = "repeat";
                                break;
                            case a.LEGACY_BG_FIT_AND_TILE:
                                r.container.backgroundSize = "auto",
                                r.container.backgroundRepeat = "repeat";
                                break;
                            case a.LEGACY_BG_FIT_AND_TILE_HORIZONTAL:
                                r.container.backgroundSize = "auto",
                                r.container.backgroundRepeat = "repeat-x";
                                break;
                            case a.LEGACY_BG_FIT_AND_TILE_VERTICAL:
                                r.container.backgroundSize = "auto",
                                r.container.backgroundRepeat = "repeat-y";
                                break;
                            case a.LEGACY_BG_NORMAL:
                                r.container.backgroundSize = "auto",
                                r.container.backgroundRepeat = "no-repeat"
                            }
                            switch (t.alignment) {
                            case n.CENTER:
                                r.container.backgroundPosition = "center center";
                                break;
                            case n.LEFT:
                                r.container.backgroundPosition = "left center";
                                break;
                            case n.RIGHT:
                                r.container.backgroundPosition = "right center";
                                break;
                            case n.TOP:
                                r.container.backgroundPosition = "center top";
                                break;
                            case n.BOTTOM:
                                r.container.backgroundPosition = "center bottom";
                                break;
                            case n.TOP_RIGHT:
                                r.container.backgroundPosition = "right top";
                                break;
                            case n.TOP_LEFT:
                                r.container.backgroundPosition = "left top";
                                break;
                            case n.BOTTOM_RIGHT:
                                r.container.backgroundPosition = "right bottom";
                                break;
                            case n.BOTTOM_LEFT:
                                r.container.backgroundPosition = "left bottom"
                            }
                            return i
                        }
                    }
                    , function(e, t, i) {
                        "use strict";
                        var r, n = i(0), a = n.alignTypes, o = n.fittingTypes, s = ((r = {})[a.CENTER] = "center",
                        r[a.TOP] = "top",
                        r[a.TOP_LEFT] = "top left",
                        r[a.TOP_RIGHT] = "top right",
                        r[a.BOTTOM] = "bottom",
                        r[a.BOTTOM_LEFT] = "bottom left",
                        r[a.BOTTOM_RIGHT] = "bottom right",
                        r[a.LEFT] = "left",
                        r[a.RIGHT] = "right",
                        r), c = {
                            position: "absolute",
                            top: "auto",
                            right: "auto",
                            bottom: "auto",
                            left: "auto"
                        };
                        e.exports = {
                            get: function(e, t) {
                                var i = {
                                    css: {
                                        container: {},
                                        img: {}
                                    }
                                }
                                  , r = i.css
                                  , n = e.fittingType
                                  , u = t.alignment;
                                switch (r.container.position = "relative",
                                n) {
                                case o.ORIGINAL_SIZE:
                                case o.LEGACY_ORIGINAL_SIZE:
                                    e.parts && e.parts.length ? (r.img.width = e.parts[0].width,
                                    r.img.height = e.parts[0].height) : (r.img.width = e.src.width,
                                    r.img.height = e.src.height);
                                    break;
                                case o.SCALE_TO_FIT:
                                case o.LEGACY_FIT_WIDTH:
                                case o.LEGACY_FIT_HEIGHT:
                                case o.LEGACY_FULL:
                                    r.img.width = t.width,
                                    r.img.height = t.height,
                                    r.img.objectFit = "contain",
                                    r.img.objectPosition = s[u] || "unset";
                                    break;
                                case o.LEGACY_BG_NORMAL:
                                    r.img.width = "100%",
                                    r.img.height = "100%",
                                    r.img.objectFit = "none",
                                    r.img.objectPosition = s[u] || "unset";
                                    break;
                                case o.STRETCH:
                                    r.img.width = t.width,
                                    r.img.height = t.height,
                                    r.img.objectFit = "fill";
                                    break;
                                case o.SCALE_TO_FILL:
                                    r.img.width = t.width,
                                    r.img.height = t.height,
                                    r.img.objectFit = "cover"
                                }
                                if ("number" == typeof r.img.width && (r.img.width !== t.width || r.img.height !== t.height)) {
                                    var l = Math.round((t.height - r.img.height) / 2)
                                      , h = Math.round((t.width - r.img.width) / 2);
                                    Object.assign(r.img, c, function(e, t, i) {
                                        var r;
                                        return (r = {})[a.TOP_LEFT] = {
                                            top: 0,
                                            left: 0
                                        },
                                        r[a.TOP_RIGHT] = {
                                            top: 0,
                                            right: 0
                                        },
                                        r[a.TOP] = {
                                            top: 0,
                                            left: t
                                        },
                                        r[a.BOTTOM_LEFT] = {
                                            top: 0,
                                            left: 0
                                        },
                                        r[a.BOTTOM_RIGHT] = {
                                            bottom: 0,
                                            right: 0
                                        },
                                        r[a.BOTTOM] = {
                                            bottom: 0,
                                            left: t
                                        },
                                        r[a.RIGHT] = {
                                            top: e,
                                            right: 0
                                        },
                                        r[a.LEFT] = {
                                            top: e,
                                            left: 0
                                        },
                                        r[a.CENTER] = {
                                            width: i.width,
                                            height: i.height,
                                            objectFit: "none"
                                        },
                                        r
                                    }(l, h, t)[u])
                                }
                                return i
                            }
                        }
                    }
                    , function(e, t, i) {
                        "use strict";
                        var r = i(0)
                          , n = r.fittingTypes
                          , a = r.alignTypes
                          , o = r.transformTypes
                          , s = i(1)
                          , c = s.getDimension
                          , u = s.isImageTransformApplicable;
                        e.exports = {
                            get: function(e, t) {
                                var i, r = {
                                    css: {
                                        container: {}
                                    },
                                    attr: {
                                        container: {},
                                        img: {}
                                    }
                                }, s = r.css, l = r.attr, h = e.fittingType, d = t.alignment, f = e.src, p = f.width, g = f.height;
                                switch (s.container.position = "relative",
                                h) {
                                case n.ORIGINAL_SIZE:
                                case n.LEGACY_ORIGINAL_SIZE:
                                case n.TILE:
                                    e.parts && e.parts.length ? (l.img.width = e.parts[0].width,
                                    l.img.height = e.parts[0].height) : (l.img.width = p,
                                    l.img.height = g),
                                    l.img.preserveAspectRatio = "xMidYMid slice";
                                    break;
                                case n.SCALE_TO_FIT:
                                case n.LEGACY_FIT_WIDTH:
                                case n.LEGACY_FIT_HEIGHT:
                                case n.LEGACY_FULL:
                                    l.img.width = "100%",
                                    l.img.height = "100%",
                                    l.img.transform = "",
                                    l.img.preserveAspectRatio = "";
                                    break;
                                case n.STRETCH:
                                    l.img.width = t.width,
                                    l.img.height = t.height,
                                    l.img.x = 0,
                                    l.img.y = 0,
                                    l.img.transform = "",
                                    l.img.preserveAspectRatio = "none";
                                    break;
                                case n.SCALE_TO_FILL:
                                    u(e.src.id) ? (l.img.width = t.width,
                                    l.img.height = t.height) : (i = c(p, g, t.width, t.height, o.FILL),
                                    l.img.width = i.width,
                                    l.img.height = i.height),
                                    l.img.x = 0,
                                    l.img.y = 0,
                                    l.img.transform = "",
                                    l.img.preserveAspectRatio = "xMidYMid slice"
                                }
                                if ("number" == typeof l.img.width && (l.img.width !== t.width || l.img.height !== t.height)) {
                                    var m, b, v = 0, T = 0;
                                    h === n.TILE ? (m = t.width % l.img.width,
                                    b = t.height % l.img.height) : (m = t.width - l.img.width,
                                    b = t.height - l.img.height);
                                    var _ = Math.round(m / 2)
                                      , y = Math.round(b / 2);
                                    switch (d) {
                                    case a.TOP_LEFT:
                                        v = 0,
                                        T = 0;
                                        break;
                                    case a.TOP:
                                        v = _,
                                        T = 0;
                                        break;
                                    case a.TOP_RIGHT:
                                        v = m,
                                        T = 0;
                                        break;
                                    case a.LEFT:
                                        v = 0,
                                        T = y;
                                        break;
                                    case a.CENTER:
                                        v = _,
                                        T = y;
                                        break;
                                    case a.RIGHT:
                                        v = m,
                                        T = y;
                                        break;
                                    case a.BOTTOM_LEFT:
                                        v = 0,
                                        T = b;
                                        break;
                                    case a.BOTTOM:
                                        v = _,
                                        T = b;
                                        break;
                                    case a.BOTTOM_RIGHT:
                                        v = m,
                                        T = b
                                    }
                                    l.img.x = v,
                                    l.img.y = T
                                }
                                return l.container.width = t.width,
                                l.container.height = t.height,
                                l.container.viewBox = [0, 0, t.width, t.height].join(" "),
                                r
                            }
                        }
                    }
                    , function(e, t, i) {
                        "use strict";
                        var r = i(0)
                          , n = r.fittingTypes
                          , a = r.alignTypes
                          , o = r.transformTypes
                          , s = i(1)
                          , c = s.getDimension
                          , u = s.isImageTypeSupported
                          , l = s.isExternalUrl;
                        e.exports = {
                            get: function(e, t) {
                                var i, r, s, h = {
                                    css: {
                                        container: {},
                                        img: {}
                                    }
                                }, d = h.css, f = e.fittingType, p = t.alignment;
                                switch (e.parts && e.parts.length ? (i = e.parts[0].width,
                                r = e.parts[0].height) : (i = e.src.width,
                                r = e.src.height),
                                d.img.display = "block",
                                d.container.position = "relative",
                                d.img.position = "absolute",
                                d.img.top = "auto",
                                d.img.right = "auto",
                                d.img.bottom = "auto",
                                d.img.left = "auto",
                                f) {
                                case n.ORIGINAL_SIZE:
                                case n.LEGACY_ORIGINAL_SIZE:
                                    d.img.width = i,
                                    d.img.height = r;
                                    break;
                                case n.SCALE_TO_FIT:
                                case n.LEGACY_FIT_WIDTH:
                                case n.LEGACY_FIT_HEIGHT:
                                case n.LEGACY_FULL:
                                    s = c(i, r, t.width, t.height, o.FIT),
                                    Object.assign(d.img, s);
                                    break;
                                case n.STRETCH:
                                    d.img.width = t.width,
                                    d.img.height = t.height;
                                    break;
                                case n.SCALE_TO_FILL:
                                    var g = e.src.id;
                                    u(g) || l(g) ? (d.img.width = t.width,
                                    d.img.height = t.height) : (s = c(i, r, t.width, t.height, o.FILL),
                                    Object.assign(d.img, s),
                                    d.container.overflow = "hidden")
                                }
                                if (d.img.width !== t.width || d.img.height !== t.height) {
                                    var m = Math.round((t.height - d.img.height) / 2)
                                      , b = Math.round((t.width - d.img.width) / 2);
                                    switch (p) {
                                    default:
                                    case a.CENTER:
                                        d.img.top = m,
                                        d.img.left = b;
                                        break;
                                    case a.LEFT:
                                        d.img.left = 0,
                                        d.img.top = m;
                                        break;
                                    case a.RIGHT:
                                        d.img.right = 0,
                                        d.img.top = m;
                                        break;
                                    case a.TOP:
                                        d.img.left = b,
                                        d.img.top = 0;
                                        break;
                                    case a.BOTTOM:
                                        d.img.left = b,
                                        d.img.bottom = 0;
                                        break;
                                    case a.TOP_RIGHT:
                                        d.img.right = 0,
                                        d.img.top = 0;
                                        break;
                                    case a.TOP_LEFT:
                                        d.img.left = 0,
                                        d.img.top = 0;
                                        break;
                                    case a.BOTTOM_RIGHT:
                                        d.img.right = 0,
                                        d.img.bottom = 0;
                                        break;
                                    case a.BOTTOM_LEFT:
                                        d.img.left = 0,
                                        d.img.bottom = 0
                                    }
                                }
                                return h
                            }
                        }
                    }
                    , function(e, t, i) {
                        "use strict";
                        var r, n = i(0), a = n.alignTypes, o = n.fittingTypes, s = ((r = {})[a.CENTER] = "50% 50%",
                        r[a.TOP_LEFT] = "0% 0%",
                        r[a.TOP_RIGHT] = "100% 0%",
                        r[a.TOP] = "50% 0%",
                        r[a.BOTTOM_LEFT] = "0% 100%",
                        r[a.BOTTOM_RIGHT] = "100% 100%",
                        r[a.BOTTOM] = "50% 100%",
                        r[a.RIGHT] = "100% 50%",
                        r[a.LEFT] = "0% 50%",
                        r), c = Object.entries(s).reduce((function(e, t) {
                            var i = t[0];
                            return e[t[1]] = i,
                            e
                        }
                        ), {}), u = [o.TILE, o.TILE_HORIZONTAL, o.TILE_VERTICAL, o.LEGACY_BG_FIT_AND_TILE, o.LEGACY_BG_FIT_AND_TILE_HORIZONTAL, o.LEGACY_BG_FIT_AND_TILE_VERTICAL], l = [o.LEGACY_ORIGINAL_SIZE, o.ORIGINAL_SIZE, o.LEGACY_BG_NORMAL];
                        function h(e, t, i) {
                            var r = i.width
                              , n = i.height;
                            return e === o.TILE && t.width > r && t.height > n
                        }
                        function d(e, t, i) {
                            var r = e.width
                              , n = e.height
                              , a = t.width
                              , o = t.height
                              , s = i.x
                              , c = i.y;
                            if (!a || !o)
                                return s + "% " + c + "%";
                            var u = Math.max(a / r, o / n)
                              , l = r * u
                              , h = n * u
                              , d = Math.max(0, Math.min(l - a, l * (s / 100) - a / 2))
                              , f = Math.max(0, Math.min(h - o, h * (c / 100) - o / 2));
                            return (d && Math.floor(d / (l - a) * 100)) + "% " + (f && Math.floor(f / (h - o) * 100)) + "%"
                        }
                        e.exports.validateTargetDimensions = function(e, t) {
                            var i = t.width
                              , r = t.height;
                            if (!i || !r) {
                                var n = i || Math.min(980, e.width)
                                  , a = n / e.width;
                                return {
                                    width: n,
                                    height: r || e.height * a
                                }
                            }
                            return {
                                width: i,
                                height: r
                            }
                        }
                        ,
                        e.exports.getScaledDimensions = function(e, t, i, r) {
                            var n = i.width
                              , a = i.height;
                            if (void 0 === r && (r = !1),
                            r)
                                return {
                                    width: n,
                                    height: a
                                };
                            var o = !l.includes(e)
                              , s = h(e, t, {
                                width: n,
                                height: a
                            })
                              , c = !s && u.includes(e)
                              , d = c ? t.width : n
                              , f = c ? t.height : a
                              , p = o ? function(e) {
                                return e > 900 ? .25 : e > 500 ? .3 : e > 200 ? .4 : 1
                            }(d) : 1;
                            return {
                                width: s ? 1920 : d * p,
                                height: f * p
                            }
                        }
                        ,
                        e.exports.getConvertedFitting = function(e, t) {
                            var i = u.includes(e) && !t;
                            return e === o.SCALE_TO_FILL || i ? o.SCALE_TO_FIT : e
                        }
                        ,
                        e.exports.getIsFakeTile = h,
                        e.exports.getBlurValue = function(e, t, i) {
                            return i ? 0 : u.includes(t) ? 1 : e > 200 ? 2 : 3
                        }
                        ,
                        e.exports.getCSSOverrides = function(e, t, i, r) {
                            void 0 === r && (r = "center");
                            var n, a, l = {
                                img: {},
                                container: {}
                            };
                            if (e === o.SCALE_TO_FILL) {
                                var h = t.focalPoint && (a = (n = t.focalPoint).x + "% " + n.y + "%",
                                c[a] || "")
                                  , f = h || r;
                                t.focalPoint && !h ? l.img = {
                                    objectPosition: d(t, i, t.focalPoint)
                                } : l.img = {
                                    objectPosition: s[f]
                                }
                            } else
                                [o.LEGACY_ORIGINAL_SIZE, o.ORIGINAL_SIZE].includes(e) ? l.img = {
                                    objectFit: "none",
                                    top: "auto",
                                    left: "auto",
                                    right: "auto",
                                    bottom: "auto"
                                } : u.includes(e) && (l.container = {
                                    backgroundSize: t.width + "px " + t.height + "px"
                                });
                            return l
                        }
                    }
                    ])
                },
                32: function(e, t, i) {
                    "use strict";
                    i.d(t, "e", (function() {
                        return r
                    }
                    )),
                    i.d(t, "c", (function() {
                        return n
                    }
                    )),
                    i.d(t, "d", (function() {
                        return a
                    }
                    )),
                    i.d(t, "h", (function() {
                        return o
                    }
                    )),
                    i.d(t, "a", (function() {
                        return s
                    }
                    )),
                    i.d(t, "b", (function() {
                        return c
                    }
                    )),
                    i.d(t, "g", (function() {
                        return l
                    }
                    )),
                    i.d(t, "f", (function() {
                        return h
                    }
                    )),
                    i.d(t, "i", (function() {
                        return d
                    }
                    ));
                    var r = function(e) {
                        return !!e && !!e.document && !!e.document.documentMode
                    }
                      , n = function(e) {
                        return u(e).indexOf("edg") > -1
                    }
                      , a = function(e) {
                        return u(e).indexOf("firefox") > -1
                    }
                      , o = function(e) {
                        var t = u(e);
                        return t.indexOf("safari") > -1 && t.indexOf("version") > -1
                    }
                      , s = function(e) {
                        if (o(e)) {
                            var t = u(e).split(" ");
                            return t = (t = t.find((function(e) {
                                return e.startsWith("version/")
                            }
                            ))).split("/")[1],
                            parseInt(t, 10)
                        }
                        return -1
                    }
                      , c = function(e) {
                        var t = u(e);
                        return t.indexOf("safari") > -1 && t.indexOf("crios") > -1
                    }
                      , u = function(e) {
                        return e && e.navigator && e.navigator.userAgent ? e.navigator.userAgent.toLowerCase() : ""
                    }
                      , l = function(e) {
                        var t = u(e);
                        return /ip(hone|od|ad).*os 11/.test(t)
                    }
                      , h = function(e) {
                        var t = function(e) {
                            return e && e.navigator && e.navigator.platform || ""
                        }(e);
                        return !!t && /iPad|iPhone|iPod/.test(t)
                    }
                      , d = function(e) {
                        var t = u(e);
                        return !!t && /.*\(win.*\).*/i.test(t)
                    }
                },
                33: function(e, t, i) {
                    "use strict";
                    i.d(t, "a", (function() {
                        return n
                    }
                    ));
                    var r = i(32)
                      , n = function(e, t, i) {
                        void 0 === i && (i = "");
                        var n = t["specs.thunderbolt.reducedMotion"]
                          , a = Object(r.i)(e);
                        return i.toLowerCase().includes("forcereducedmotion") || !(!e || !n || a) && e.matchMedia("(prefers-reduced-motion: reduce)").matches
                    }
                },
                74: function(e, t, i) {
                    "use strict";
                    var r, n;
                    i.d(t, "a", (function() {
                        return r
                    }
                    )),
                    i.d(t, "b", (function() {
                        return n
                    }
                    )),
                    i.d(t, "c", (function() {
                        return a
                    }
                    )),
                    function(e) {
                        e[e.START = 1] = "START",
                        e[e.VISIBLE = 2] = "VISIBLE",
                        e[e.PAGE_FINISH = 33] = "PAGE_FINISH",
                        e[e.FIRST_CDN_RESPONSE = 4] = "FIRST_CDN_RESPONSE",
                        e[e.TBD = -1] = "TBD",
                        e[e.PAGE_NAVIGATION = 101] = "PAGE_NAVIGATION",
                        e[e.PAGE_NAVIGATION_DONE = 103] = "PAGE_NAVIGATION_DONE"
                    }(r || (r = {})),
                    function(e) {
                        e[e.NAVIGATION = 1] = "NAVIGATION",
                        e[e.DYNAMIC_REDIRECT = 2] = "DYNAMIC_REDIRECT",
                        e[e.INNER_ROUTE = 3] = "INNER_ROUTE",
                        e[e.NAVIGATION_ERROR = 4] = "NAVIGATION_ERROR",
                        e[e.CANCELED = 5] = "CANCELED"
                    }(n || (n = {}));
                    var a = {
                        1: "page-navigation",
                        2: "page-navigation-redirect",
                        3: "page-navigation-inner-route",
                        4: "navigation-error",
                        5: "navigation-canceled"
                    }
                },
                90: function(e, t, i) {
                    "use strict";
                    var r = function(e) {
                        return e * Math.PI / 180
                    }
                      , n = function(e, t) {
                        return {
                            width: e,
                            height: t
                        }
                    }
                      , a = function(e, t, i) {
                        return {
                            width: e,
                            height: Math.max(t, i)
                        }
                    };
                    e.exports = {
                        BackgroundParallax: {
                            hasParallax: !0,
                            getMediaDimensions: a
                        },
                        BackgroundParallaxZoom: {
                            hasParallax: !0,
                            getMediaDimensions: a
                        },
                        BackgroundReveal: {
                            hasParallax: !0,
                            getMediaDimensions: a
                        },
                        BgCloseUp: {
                            getMediaDimensions: n
                        },
                        BgExpand: {
                            getMediaDimensions: n
                        },
                        BgFabeBack: {
                            getMediaDimensions: n
                        },
                        BgFadeIn: {
                            getMediaDimensions: n
                        },
                        BgFadeOut: {
                            getMediaDimensions: n
                        },
                        BgFake3D: {
                            hasParallax: !0,
                            getMediaDimensions: a
                        },
                        BgPanLeft: {
                            getMediaDimensions: function(e, t) {
                                return {
                                    width: 1.2 * e,
                                    height: t
                                }
                            }
                        },
                        BgPanRight: {
                            getMediaDimensions: function(e, t) {
                                return {
                                    width: 1.2 * e,
                                    height: t
                                }
                            }
                        },
                        BgParallax: {
                            hasParallax: !0,
                            getMediaDimensions: a
                        },
                        BgPullBack: {
                            getMediaDimensions: n
                        },
                        BgReveal: {
                            hasParallax: !0,
                            getMediaDimensions: a
                        },
                        BgRotate: {
                            getMediaDimensions: function(e, t) {
                                return function(e, t, i) {
                                    var n = r(i)
                                      , a = Math.hypot(e, t) / 2
                                      , o = Math.acos(e / 2 / a)
                                      , s = e * Math.abs(Math.cos(n)) + t * Math.abs(Math.sin(n))
                                      , c = e * Math.abs(Math.sin(n)) + t * Math.abs(Math.cos(n));
                                    return {
                                        width: Math.ceil(n < o ? s : 2 * a),
                                        height: Math.ceil(n < r(90) - o ? c : 2 * a)
                                    }
                                }(e, t, 22)
                            }
                        },
                        BgShrink: {
                            getMediaDimensions: n
                        },
                        BgSkew: {
                            getMediaDimensions: function(e, t) {
                                return function(e, t, i) {
                                    var n = r(i);
                                    return {
                                        width: e,
                                        height: e * Math.tan(n) + t
                                    }
                                }(e, t, 20)
                            }
                        },
                        BgUnwind: {
                            getMediaDimensions: n
                        },
                        BgZoomIn: {
                            hasParallax: !0,
                            getMediaDimensions: a
                        },
                        BgZoomOut: {
                            getMediaDimensions: function(e, t) {
                                return {
                                    width: 1.15 * e,
                                    height: 1.15 * t
                                }
                            }
                        }
                    }
                }
            }, [[169, 2, 0, 5, 6]]]);
            //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/initCustomElements.inline.891d7f64.chunk.min.js.map
        </script>
        <!-- tbElements js -->
        <script src="https://static.parastorage.com/services/editor-elements/dist/thunderboltElements.31b92ac5.bundle.min.js" defer="" onload="window.ThunderboltElementsLoadedResolve()"></script>
        <script async id="wix-perf-measure" src="https://static.parastorage.com/services/wix-perf-measure/1.466.0/wix-perf-measure.bundle.min.js"></script>
        <!-- react-dom -->
        <script crossorigin src="https://static.parastorage.com/unpkg/react-dom@16.13.1/umd/react-dom.production.min.js" onload="externalsRegistry.reactDOM.onload()" defer=""></script>
        <meta http-equiv="X-Wix-Meta-Site-Id" content="449452eb-9160-401f-a8e7-73181281adef">
        <meta http-equiv="X-Wix-Application-Instance-Id" content="b97500a3-1350-45b0-bf57-d85911cfaba2">
        <meta http-equiv="X-Wix-Published-Version" content="9"/>
        <meta http-equiv="etag" content="bug"/>
        <!-- render-head end -->
        <script src="https://static.parastorage.com/services/wix-thunderbolt/dist/page-features.4bf20dc4.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/wix-thunderbolt/dist/activePopup.c4f95473.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/wix-thunderbolt/dist/wix-code-sdk-providers.31bdeb35.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/wix-thunderbolt/dist/loginSocialBar.ae595ce9.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/wix-thunderbolt/dist/ooiTpaSharedConfig.c0f65fc9.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/wix-thunderbolt/dist/ooi.b29aa2e0.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/wix-thunderbolt/dist/platformPubsub.53f75229.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/wix-thunderbolt/dist/protectedPages.74a7e435.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/wix-thunderbolt/dist/siteMembers.02ecf8c9.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/wix-thunderbolt/dist/sosp.0e2cb91f.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/wix-thunderbolt/dist/tpa.5b946007.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/wix-thunderbolt/dist/platform.87784f29.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/wix-thunderbolt/dist/pageTransitions.19a2e879.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/editor-elements/dist/bootstrap-components-common.298f32be.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/editor-elements/dist/Container_DefaultAreaSkin.32265d95.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/editor-elements/dist/bootstrap-components-classic.eed27cba.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/editor-elements/dist/LoginSocialBar.21dafa7b.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/editor-elements/dist/bootstrap-components-responsive.45771a1f.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/editor-elements/dist/DropDownMenu_OverlineMenuButtonSkin.fe9d41d8.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/editor-elements/dist/MeshGroup.fceb4749.chunk.min.js" async=""></script>
        <script src="https://static.parastorage.com/services/editor-elements/dist/FreemiumBannerDesktop.b64b233d.chunk.min.js" async=""></script>
        <style data-href="https://static.parastorage.com/services/editor-elements/dist/bootstrap-components-common.2e48afc7.chunk.min.css">
            ._2_Pya {
                position: absolute;
                top: 0;
                right: 0;
                bottom: 0;
                width: 100%;
                left: 0
            }

            ._1s0Ge {
                transition: .2s ease-in;
                transform: translateY(-100%)
            }

            ._3-JNd {
                transition: .2s;
                transform: translateY(0)
            }

            .FxFZJ {
                transition: .2s ease-in;
                opacity: 0;
                visibility: hidden
            }

            .lSyDa {
                transition: .2s;
                opacity: 1
            }

            ._1jI8r {
                height: auto
            }

            ._1jI8r,._2qN73 {
                position: relative;
                width: 100%
            }

            body:not(.device-mobile-optimized) ._1M8CM {
                margin-left: calc((100% - var(--site-width)) / 2);
                width: var(--site-width)
            }

            ._17W7D,.UZpZM ._1M8CM {
                position: absolute;
                top: 0;
                right: 0;
                bottom: 0;
                left: 0
            }

            .s0eeT {
                cursor: pointer
            }

            .TG-Zk {
                -webkit-tap-highlight-color: rgba(0,0,0,0);
                opacity: var(--opacity);
                fill: var(--fill);
                fill-opacity: var(--fill-opacity);
                stroke: var(--stroke);
                stroke-opacity: var(--stroke-opacity);
                stroke-width: var(--stroke-width);
                transform: var(--flip);
                filter: var(--drop-shadow,none)
            }

            .TG-Zk,.TG-Zk svg {
                position: absolute;
                top: 0;
                right: 0;
                bottom: 0;
                left: 0
            }

            .TG-Zk svg {
                width: var(--svg-calculated-width,100%);
                height: var(--svg-calculated-height,100%);
                padding: var(--svg-calculated-padding,0);
                margin: auto
            }

            ._1UnNA * {
                vector-effect: non-scaling-stroke
            }

            ._27iav svg,._37OKp svg {
                overflow: visible!important
            }

            @media not all and (min-resolution: 0.001dpcm) {
                @supports (-webkit-appearance:none) {
                    .TG-Zk._37OKp {
                        will-change:filter
                    }
                }
            }

            ._2HrZd {
                opacity: 0
            }

            ._2fuJI {
                transition: opacity var(--transition-duration) cubic-bezier(.37,0,.63,1)
            }

            ._2fuJI,.g0xNe {
                opacity: 1
            }

            .PeTAs {
                transition: opacity var(--transition-duration) cubic-bezier(.37,0,.63,1)
            }

            ._1IGjY,.PeTAs {
                opacity: 0
            }

            .Ic0Mb {
                transition: opacity var(--transition-duration) cubic-bezier(.64,0,.78,0)
            }

            .Ic0Mb,.WjNI2 {
                opacity: 1
            }

            .Y5LuX {
                opacity: 0;
                transition: opacity var(--transition-duration) cubic-bezier(.22,1,.36,1)
            }

            ._3P3IS {
                transform: translateX(100%)
            }

            ._1vZD6 {
                transition: transform var(--transition-duration) cubic-bezier(.87,0,.13,1)
            }

            ._1vZD6,.AM-g_ {
                transform: translateX(0)
            }

            ._1MVJv {
                transition: transform var(--transition-duration) cubic-bezier(.87,0,.13,1)
            }

            ._1MVJv,._2uVRM {
                transform: translateX(-100%)
            }

            ._2kt-u {
                transition: transform var(--transition-duration) cubic-bezier(.87,0,.13,1)
            }

            ._2kt-u,._3f6Db {
                transform: translateX(0)
            }

            ._3u3Qg {
                transform: translateX(100%);
                transition: transform var(--transition-duration) cubic-bezier(.87,0,.13,1)
            }

            ._2LoMk {
                transform: translateY(100%)
            }

            ._3VRRq {
                transition: transform var(--transition-duration) cubic-bezier(.87,0,.13,1)
            }

            ._3VRRq,._8b5uM {
                transform: translateY(0)
            }

            ._1c8N5 {
                transition: transform var(--transition-duration) cubic-bezier(.87,0,.13,1)
            }

            ._1c8N5,._1SRt2 {
                transform: translateY(-100%)
            }

            .mMep- {
                transition: transform var(--transition-duration) cubic-bezier(.87,0,.13,1)
            }

            ._3jOkM,.mMep- {
                transform: translateY(0)
            }

            ._1hGK7 {
                transform: translateY(100%);
                transition: transform var(--transition-duration) cubic-bezier(.87,0,.13,1)
            }

            .StylableButton1872886392__root {
                -archetype: box;
                cursor: pointer;
                border: none;
                display: block;
                min-width: 10px;
                min-height: 10px;
                width: 100%;
                height: 100%;
                box-sizing: border-box;
                padding: 0
            }

            .StylableButton1872886392__root[disabled] {
                pointer-events: none
            }

            .StylableButton1872886392__root.StylableButton1872886392--hasBackgroundColor {
                background-color: var(--corvid-background-color)!important
            }

            .StylableButton1872886392__root.StylableButton1872886392--hasBorderColor {
                border-color: var(--corvid-border-color)!important
            }

            .StylableButton1872886392__root.StylableButton1872886392--hasBorderRadius {
                border-radius: var(--corvid-border-radius)!important
            }

            .StylableButton1872886392__root.StylableButton1872886392--hasBorderWidth {
                border-width: var(--corvid-border-width)!important
            }

            .StylableButton1872886392__root.StylableButton1872886392--hasColor,.StylableButton1872886392__root.StylableButton1872886392--hasColor .StylableButton1872886392__label {
                color: var(--corvid-color)!important
            }

            .StylableButton1872886392__link {
                -archetype: box;
                text-decoration: none;
                box-sizing: border-box;
                color: #000
            }

            .StylableButton1872886392__container {
                display: flex;
                flex-basis: auto;
                justify-content: center;
                flex-direction: row;
                flex-grow: 1;
                align-items: center;
                overflow: hidden;
                height: 100%;
                width: 100%;
                transition: all .2s ease,visibility 0s
            }

            .StylableButton1872886392__label {
                -archetype: text;
                -controller-part-type: LayoutChildDisplayDropdown,LayoutFlexChildSpacing(first);
                overflow: hidden;
                text-overflow: ellipsis;
                white-space: nowrap;
                min-width: 1.8em;
                max-width: 100%;
                transition: inherit
            }

            .StylableButton1872886392__icon {
                -archetype: icon;
                -controller-part-type: LayoutChildDisplayDropdown,LayoutFlexChildSpacing(last);
                min-width: 1px;
                height: 50px;
                transition: inherit;
                flex-shrink: 0
            }

            .StylableButton1872886392__icon>div,.StylableButton1872886392__icon svg {
                display: flex;
                width: inherit;
                height: inherit
            }

            .GFY_- {
                pointer-events: none;
                overflow: hidden;
                padding: 0;
                white-space: nowrap
            }

            ._2Yk_Z {
                cursor: pointer
            }

            ol.font_100,ul.font_100 {
                color: #080808;
                font-family: "Arial, Helvetica, sans-serif",serif;
                font-size: 10px;
                font-style: normal;
                font-variant: normal;
                font-weight: 400;
                margin: 0;
                text-decoration: none;
                line-height: normal;
                letter-spacing: normal
            }

            ol.font_100 li,ul.font_100 li {
                margin-bottom: 12px
            }

            ol.wix-list-text-align,ul.wix-list-text-align {
                list-style-position: inside
            }

            ol.wix-list-text-align h1,ol.wix-list-text-align h2,ol.wix-list-text-align h3,ol.wix-list-text-align h4,ol.wix-list-text-align h5,ol.wix-list-text-align h6,ol.wix-list-text-align p,ul.wix-list-text-align h1,ul.wix-list-text-align h2,ul.wix-list-text-align h3,ul.wix-list-text-align h4,ul.wix-list-text-align h5,ul.wix-list-text-align h6,ul.wix-list-text-align p {
                display: inline
            }

            ._2tuyK {
                cursor: pointer
            }

            .XcBF6 ._1cEyW {
                position: relative;
                width: 100%;
                height: 100%;
                word-wrap: break-word;
                overflow-wrap: break-word
            }

            .XcBF6 ._1cEyW ul {
                list-style: disc inside
            }

            .XcBF6 ._1cEyW li {
                margin-bottom: 12px
            }

            ._2bafp {
                word-wrap: break-word;
                overflow-wrap: break-word;
                text-align: start;
                pointer-events: none
            }

            ._2bafp>* {
                pointer-events: auto
            }

            ._2bafp li {
                font-style: inherit;
                font-weight: inherit;
                line-height: inherit;
                letter-spacing: normal
            }

            ._2bafp ol,._2bafp ul {
                padding-left: 1.3em;
                padding-right: 0;
                margin-left: .5em;
                margin-right: 0;
                line-height: normal;
                letter-spacing: normal
            }

            ._2bafp ul {
                list-style-type: disc
            }

            ._2bafp ol {
                list-style-type: decimal
            }

            ._2bafp ol ul,._2bafp ul ul {
                list-style-type: circle
            }

            ._2bafp ol ol ul,._2bafp ol ul ul,._2bafp ul ol ul,._2bafp ul ul ul {
                list-style-type: square
            }

            ._2bafp ol[dir=rtl],._2bafp ol[dir=rtl] ol,._2bafp ol[dir=rtl] ul,._2bafp ul[dir=rtl],._2bafp ul[dir=rtl] ol,._2bafp ul[dir=rtl] ul {
                padding-left: 0;
                padding-right: 1.3em;
                margin-left: 0;
                margin-right: .5em
            }

            ._2bafp blockquote,._2bafp h1,._2bafp h2,._2bafp h3,._2bafp h4,._2bafp h5,._2bafp h6,._2bafp p {
                margin: 0;
                line-height: normal;
                letter-spacing: normal
            }

            ._2bafp a {
                color: inherit
            }

            .lJm9X ._1cEyW {
                position: relative;
                width: 100%;
                height: 100%;
                word-wrap: break-word;
                overflow-wrap: break-word
            }

            .lJm9X ._1cEyW ol,.lJm9X ._1cEyW ul {
                padding-left: 1.3em;
                margin-left: .5em;
                line-height: normal;
                letter-spacing: normal
            }

            .lJm9X ._1cEyW ol[dir=rtl],.lJm9X ._1cEyW ul[dir=rtl] {
                padding-right: 1.3em;
                margin-right: .5em
            }

            .lJm9X ._1cEyW ul {
                list-style-type: disc
            }

            .lJm9X ._1cEyW ol {
                list-style-type: decimal
            }

            .lJm9X ._1cEyW ol[dir=rtl],.lJm9X ._1cEyW ul[dir=rtl] {
                padding-right: 1.3em;
                margin-right: .5em
            }

            .lJm9X ._1cEyW ol ul,.lJm9X ._1cEyW ul ul {
                list-style-type: circle;
                line-height: normal
            }

            .lJm9X ._1cEyW ol ol ul,.lJm9X ._1cEyW ol ul ul,.lJm9X ._1cEyW ul ol ul,.lJm9X ._1cEyW ul ul ul {
                list-style-type: square;
                line-height: normal
            }

            .lJm9X ._1cEyW li {
                font-style: inherit;
                font-weight: inherit;
                line-height: inherit;
                letter-spacing: normal
            }

            .lJm9X ._1cEyW h1,.lJm9X ._1cEyW h2,.lJm9X ._1cEyW h3,.lJm9X ._1cEyW h4,.lJm9X ._1cEyW h5,.lJm9X ._1cEyW h6,.lJm9X ._1cEyW p {
                margin: 0;
                line-height: normal;
                letter-spacing: normal
            }

            .lJm9X ._1cEyW a {
                color: inherit
            }

            ._3tDhR {
                display: grid;
                grid-template-rows: 1fr;
                grid-template-columns: 1fr
            }

            ._3tDhR>div {
                justify-self: stretch!important;
                align-self: stretch!important
            }

            ._2oJTp {
                top: 0;
                left: 0;
                position: fixed;
                width: 100%;
                height: calc(100% - var(--wix-ads-height));
                margin-top: var(--wix-ads-height);
                display: grid;
                grid-template-columns: 1fr;
                grid-template-rows: 1fr
            }

            ._1PGFM,._2oJTp {
                pointer-events: none;
                z-index: var(--pinned-layer-in-container,var(--above-all-in-container))
            }
        </style>
        <style data-href="https://static.parastorage.com/services/editor-elements/dist/Container_DefaultAreaSkin.0b1317f3.chunk.min.css">
            ._3ucik {
                --container-corvid-border-color:rgba(var(--brd,var(--color_15)),var(--alpha-brd,1));--container-corvid-border-size:var(--brw,1px);--container-corvid-background-color:rgba(var(--bg,var(--color_11)),var(--alpha-bg,1))}

            ._15Xjo {
                border: var(--container-corvid-border-width,var(--brw,1px)) solid var(--container-corvid-border-color,rgba(var(--brd,var(--color_15)),var(--alpha-brd,1)));
                background-color: var(--container-corvid-background-color,rgba(var(--bg,var(--color_11)),var(--alpha-bg,1)));
                border-radius: var(--rd,5px);
                box-shadow: var(--shd,0 1px 4px rgba(0,0,0,.6));
                position: absolute;
                top: 0;
                right: 0;
                bottom: 0;
                left: 0
            }
        </style>
        <style data-href="https://static.parastorage.com/services/editor-elements/dist/bootstrap-components-classic.77073ea7.chunk.min.css">
            .dmysR {
                position: absolute;
                top: 0;
                right: 0;
                bottom: 0;
                width: 100%;
                left: 0
            }

            ._1veUs {
                transition: .2s ease-in;
                transform: translateY(-100%)
            }

            ._3FGUd {
                transition: .2s;
                transform: translateY(0)
            }

            ._2JCUO {
                transition: .2s ease-in;
                opacity: 0;
                visibility: hidden
            }

            ._2qLBX {
                transition: .2s;
                opacity: 1
            }

            ._1MBwI {
                height: auto
            }

            ._1MBwI,._2_pp6 {
                position: relative;
                width: 100%
            }

            body:not(.device-mobile-optimized) ._1DMOb {
                margin-left: calc((100% - var(--site-width)) / 2);
                width: var(--site-width)
            }

            ._26XlU .kvZ7q {
                top: 0;
                bottom: 0;
                box-shadow: var(--shd,0 0 5px rgba(0,0,0,.7));
                background-color: var(--screenwidth-corvid-background-color,rgba(var(--bg,var(--color_11)),var(--alpha-bg,1)));
                border-top: var(--brwt,0) solid var(--screenwidth-corvid-border-color,rgba(var(--brd,var(--color_15)),var(--alpha-brd,1)));
                border-bottom: var(--brwb,0) solid var(--screenwidth-corvid-border-color,rgba(var(--brd,var(--color_15)),var(--alpha-brd,1)))
            }

            ._26XlU .kvZ7q,._26XlU .mtROD {
                position: absolute;
                right: 0;
                left: 0
            }

            ._26XlU .mtROD {
                top: var(--brwt,0);
                bottom: var(--brwb,0);
                border-radius: var(--rd,0);
                background-color: rgba(var(--bgctr,var(--color_11)),var(--alpha-bgctr,1))
            }

            ._26XlU ._1DMOb {
                position: absolute;
                top: 0;
                right: 0;
                bottom: 0;
                left: 0
            }

            body.device-mobile-optimized ._26XlU ._1DMOb {
                left: 10px;
                right: 10px
            }

            ._31Ne5 {
                position: relative
            }

            ._1XT8x {
                -webkit-backface-visibility: hidden;
                backface-visibility: hidden
            }

            ._2US5Z {
                cursor: pointer
            }

            .cs8rE {
                border-color: var(--hover-box-border-color);
                border-radius: var(--hover-box-border-radius);
                border-style: var(--hover-box-border-style);
                border-width: var(--hover-box-border-width);
                box-shadow: var(--hover-box-box-shadow);
                transform: var(--hover-box-transform);
                margin: var(--hover-box-margin);
                overflow: var(--hover-box-overflow);
                position: relative
            }

            ._2k7xj {
                text-align: initial;
                display: flex;
                align-items: center;
                box-sizing: border-box;
                width: -webkit-max-content;
                width: -moz-max-content;
                width: max-content;
                justify-content: var(--label-align);
                min-width: 100%
            }

            ._2k7xj:before {
                max-width: var(--margin-left,0)
            }

            ._2k7xj:after,._2k7xj:before {
                content: "";
                flex-grow: 1;
                align-self: stretch
            }

            ._2k7xj:after {
                max-width: var(--margin-right,0)
            }

            ._2btH0 {
                height: 100%
            }

            ._2btH0 ._2k7xj {
                border-radius: var(--corvid-border-radius,var(--rd,0));
                position: absolute;
                top: 0;
                right: 0;
                bottom: 0;
                left: 0;
                transition: var(--trans1,border-color .4s ease 0s,background-color .4s ease 0s);
                box-shadow: var(--shd,0 1px 4px rgba(0,0,0,.6))
            }

            ._2btH0 ._2k7xj:link,._2btH0 ._2k7xj:visited {
                border-color: transparent
            }

            ._2btH0 .nr31w {
                font: var(--fnt,var(--font_5));
                transition: var(--trans2,color .4s ease 0s);
                color: var(--corvid-color,rgb(var(--txt,var(--color_15))));
                position: relative;
                white-space: nowrap;
                margin: 0
            }

            ._2btH0[aria-disabled=false] ._2k7xj {
                background-color: var(--corvid-background-color,rgba(var(--bg,var(--color_17)),var(--alpha-bg,1)));
                border: solid var(--corvid-border-color,rgba(var(--brd,var(--color_15)),var(--alpha-brd,1))) var(--corvid-border-width,var(--brw,0));
                cursor: pointer!important
            }

            body.device-mobile-optimized ._2btH0[aria-disabled=false]:active ._2k7xj {
                background-color: rgba(var(--bgh,var(--color_18)),var(--alpha-bgh,1));
                border-color: rgba(var(--brdh,var(--color_15)),var(--alpha-brdh,1))
            }

            body.device-mobile-optimized ._2btH0[aria-disabled=false]:active .nr31w {
                color: rgb(var(--txth,var(--color_15)))
            }

            body:not(.device-mobile-optimized) ._2btH0[aria-disabled=false]:hover ._2k7xj {
                background-color: rgba(var(--bgh,var(--color_18)),var(--alpha-bgh,1));
                border-color: rgba(var(--brdh,var(--color_15)),var(--alpha-brdh,1))
            }

            body:not(.device-mobile-optimized) ._2btH0[aria-disabled=false]:hover .nr31w {
                color: rgb(var(--txth,var(--color_15)))
            }

            ._2btH0[aria-disabled=true] ._2k7xj {
                background-color: rgba(var(--bgd,204,204,204),var(--alpha-bgd,1));
                border-color: rgba(var(--brdd,204,204,204),var(--alpha-brdd,1));
                border-width: var(--corvid-border-width,var(--brw,0));
                border-style: solid
            }

            ._2btH0[aria-disabled=true] .nr31w {
                color: rgb(var(--txtd,255,255,255))
            }

            .e3SAW {
                width: 100%;
                height: 100%;
                overflow: hidden
            }

            .e3SAW._3qUQs:hover {
                cursor: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAYAAAH6ji2bAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAA3FpVFh0WE1MOmNvbS5hZG9iZS54bXAAAAAAADw/eHBhY2tldCBiZWdpbj0i77u/IiBpZD0iVzVNME1wQ2VoaUh6cmVTek5UY3prYzlkIj8+IDx4OnhtcG1ldGEgeG1sbnM6eD0iYWRvYmU6bnM6bWV0YS8iIHg6eG1wdGs9IkFkb2JlIFhNUCBDb3JlIDUuNS1jMDE0IDc5LjE1MTQ4MSwgMjAxMy8wMy8xMy0xMjowOToxNSAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wTU09Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9tbS8iIHhtbG5zOnN0UmVmPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvc1R5cGUvUmVzb3VyY2VSZWYjIiB4bWxuczp4bXA9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC8iIHhtcE1NOk9yaWdpbmFsRG9jdW1lbnRJRD0ieG1wLmRpZDpmMWUzNTlkMS1hYjZhLTNkNDctYmM0ZC03MWMyZDYyMWNmNDgiIHhtcE1NOkRvY3VtZW50SUQ9InhtcC5kaWQ6ODM3MEUzMUU4OTAyMTFFMzk3Q0FCMkFEODdDNzUzMjQiIHhtcE1NOkluc3RhbmNlSUQ9InhtcC5paWQ6ODM3MEUzMUQ4OTAyMTFFMzk3Q0FCMkFEODdDNzUzMjQiIHhtcDpDcmVhdG9yVG9vbD0iQWRvYmUgUGhvdG9zaG9wIENDIChXaW5kb3dzKSI+IDx4bXBNTTpEZXJpdmVkRnJvbSBzdFJlZjppbnN0YW5jZUlEPSJ4bXAuaWlkOjk0ZTkyMTRlLThiNDQtNjc0My04MWZiLTZlYjIzYTA2ZjcwNCIgc3RSZWY6ZG9jdW1lbnRJRD0ieG1wLmRpZDpmMWUzNTlkMS1hYjZhLTNkNDctYmM0ZC03MWMyZDYyMWNmNDgiLz4gPC9yZGY6RGVzY3JpcHRpb24+IDwvcmRmOlJERj4gPC94OnhtcG1ldGE+IDw/eHBhY2tldCBlbmQ9InIiPz4bqsJgAAACF0lEQVR42mJgQAd8fHz/gdRvRigfxGEACCA4YvwPBMgCbgABBGOAJP6LiooiZBUUFMCC7969Awk6AQQQA1bAxMTUOnXq1P8/f/78j2zdf5BDQDgoKAgiyMgItv0/1AkozlgJlHwPpDWB+AhAACFL1EJVwvBPIGZHd8P/OXPmgI0F2YdmxXQUhX///sVQqK2tDVL4DFkhF8zK2NjY/4aGhshOOMJAJAB5ZjdAADGQCpiB4Cear3uwKQR74vv372BPLFq0CKZ4GnLcdMGiFtnXmzZtQo0Bdnb2r/b29nBFMIwUjkxghby8vHfFxMQwTMQWp0YggZcvX/5HBpqamhgKQdafAQnq6en9j4+P/4/me150nzsCPfYOKrkWKvYCymcjJozPgqIYIMAYcUjKAnEcELsDbVECOpkNiO8B+buAeCEQ3yUqFllYWNYh+4Obm/u/ubn5f0tLy//QPIqM90ATHVagDHTJH5BCfn7+/xcvXvyPC9y7d+8/KHqghv4FYj0M04BxeAOkQEhI6P+vX79QDECOeBj49+/ffzk5OZih91FyP4gAGiIDooH5hIGVlRUsAXQpGMMAMh+Y1xksLCzg5QxGrAFzwAxY2GzYsIGgC48cOYIclsuwBiIbG9sCmCJFRcX/+/fvxwi/EydOwIoDGH6JLQEiA26ga1egxSY2vAUpkcKKEV5iCwVOIObBU8w8RzLYgYHaAAACg5CxaxSLgwAAAABJRU5ErkJggg==),auto
            }

            .e3SAW.UKJJk:hover {
                cursor: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAYAAAH6ji2bAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAA3FpVFh0WE1MOmNvbS5hZG9iZS54bXAAAAAAADw/eHBhY2tldCBiZWdpbj0i77u/IiBpZD0iVzVNME1wQ2VoaUh6cmVTek5UY3prYzlkIj8+IDx4OnhtcG1ldGEgeG1sbnM6eD0iYWRvYmU6bnM6bWV0YS8iIHg6eG1wdGs9IkFkb2JlIFhNUCBDb3JlIDUuNS1jMDE0IDc5LjE1MTQ4MSwgMjAxMy8wMy8xMy0xMjowOToxNSAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wTU09Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9tbS8iIHhtbG5zOnN0UmVmPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvc1R5cGUvUmVzb3VyY2VSZWYjIiB4bWxuczp4bXA9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC8iIHhtcE1NOk9yaWdpbmFsRG9jdW1lbnRJRD0ieG1wLmRpZDpmMWUzNTlkMS1hYjZhLTNkNDctYmM0ZC03MWMyZDYyMWNmNDgiIHhtcE1NOkRvY3VtZW50SUQ9InhtcC5kaWQ6N0I4QkNGQTI4OTAyMTFFMzg0RDlBRkM5NDA5QjczRTEiIHhtcE1NOkluc3RhbmNlSUQ9InhtcC5paWQ6N0I4QkNGQTE4OTAyMTFFMzg0RDlBRkM5NDA5QjczRTEiIHhtcDpDcmVhdG9yVG9vbD0iQWRvYmUgUGhvdG9zaG9wIENDIChXaW5kb3dzKSI+IDx4bXBNTTpEZXJpdmVkRnJvbSBzdFJlZjppbnN0YW5jZUlEPSJ4bXAuaWlkOjk0ZTkyMTRlLThiNDQtNjc0My04MWZiLTZlYjIzYTA2ZjcwNCIgc3RSZWY6ZG9jdW1lbnRJRD0ieG1wLmRpZDpmMWUzNTlkMS1hYjZhLTNkNDctYmM0ZC03MWMyZDYyMWNmNDgiLz4gPC9yZGY6RGVzY3JpcHRpb24+IDwvcmRmOlJERj4gPC94OnhtcG1ldGE+IDw/eHBhY2tldCBlbmQ9InIiPz7hiSPZAAACGklEQVR42mJgQAd8fHz/gdRvRigfxGEACCA4YvwPBMgCbgABBGOAJP6LiooiZBUUFMCC7969Awk6AQQQA1bAxMTUOnXq1P8/f/78j2zdf5BDQDgoKAgiyMgItv0/1AkozlgJlHwPpDWB+AhAACFL1EJVwvBPIGZHd8P/OXPm/EcHUA3TURT+/fsXQ6G2tjZI4TNkhVwwK2NjY/8bGhoiO+EIA5EA5JndAAHEQCpgBoKfaL7uwaYQHLrfv38He2LRokUwxdOQ46YLFrXIYNOmTagxwM7O/tXe3h4sCYs3EEYKRyawQl5e3rtiYmL/sQH0ODUCCbx8+RJFkaamJoZCkPVnQIJ6enr/4+Pj/6P5nhfd545Aj72DSq6Fir2A8tmICeOzoCgGCDBGHJKyQBwHxO5AW5SATmYD4ntA/i4gXgjEd4mKRRYWlnXI/uDm5v5vbm7+39LS8j80jyLjPdBEhxUoA13yB6SQn5///8WLF//jAvfu3fsPih6ooX+BWA/DNGAc3gApEBIS+v/r16//hMC/f//+y8nJwQy9j2wWC4gAGiIDooH5hIGVlRUsAXQpVq98/PgRVBAwWFhYMDx69AhczkBj7RdyFpgBC5sNGzYQdOGRI0eQw3IZVpvZ2NgWwBQpKir+379/P4ZBJ06cgBUHMPwSWwJEBtxA165Ai01seAtSIoUVI7zEFgqcQMyDp5h5jmSwAwO1AQBU5q033XYWQwAAAABJRU5ErkJggg==),auto
            }

            ._3oqF5 {
                text-align: initial;
                display: flex;
                align-items: center;
                box-sizing: border-box;
                width: -webkit-max-content;
                width: -moz-max-content;
                width: max-content;
                justify-content: var(--label-align);
                min-width: 100%
            }

            ._3oqF5:before {
                max-width: var(--margin-left,0)
            }

            ._3oqF5:after,._3oqF5:before {
                content: "";
                flex-grow: 1;
                align-self: stretch
            }

            ._3oqF5:after {
                max-width: var(--margin-right,0)
            }

            ._1P1ro[aria-disabled=false] ._3oqF5 {
                cursor: pointer
            }

            body.device-mobile-optimized ._1P1ro[aria-disabled=false]:active ._22ngm,body:not(.device-mobile-optimized) ._1P1ro[aria-disabled=false]:hover ._22ngm {
                color: rgb(var(--txth,var(--color_15)));
                transition: var(--trans,color .4s ease 0s)
            }

            ._1P1ro ._3oqF5 {
                position: absolute;
                top: 0;
                right: 0;
                bottom: 0;
                left: 0
            }

            ._1P1ro ._22ngm {
                font: var(--fnt,var(--font_5));
                transition: var(--trans,color .4s ease 0s);
                color: var(--corvid-color,rgb(var(--txt,var(--color_15))));
                white-space: nowrap
            }

            ._1P1ro[aria-disabled=true] ._22ngm {
                color: rgb(var(--txtd,255,255,255))
            }

            ._2AO2a {
                position: var(--bg-position);
                top: var(--wix-ads-height);
                min-height: calc(100vh - var(--wix-ads-height));
                height: 100%;
                width: 100%;
                min-width: var(--site-width)
            }

            body:not(.device-mobile-optimized) .JSM9k {
                display: flex
            }

            body:not(.device-mobile-optimized) ._2EoGw {
                display: flex;
                position: relative;
                width: calc(100% - var(--padding) * 2);
                margin: 0 auto
            }

            body:not(.device-mobile-optimized) ._2EoGw>* {
                flex: var(--column-flex);
                min-width: var(--column-width);
                margin-top: var(--padding);
                margin-bottom: var(--padding);
                position: relative;
                left: 0;
                top: 0;
                margin-left: var(--margin)
            }

            body:not(.device-mobile-optimized) ._2EoGw>:first-child {
                margin-left: 0
            }

            body.device-mobile-optimized ._2EoGw {
                display: block;
                position: relative;
                padding: var(--padding) 0
            }

            body.device-mobile-optimized ._2EoGw>* {
                margin-bottom: var(--margin);
                position: relative
            }

            body.device-mobile-optimized ._2EoGw>:first-child {
                margin-top: -1px
            }

            body.device-mobile-optimized ._2EoGw>:last-child {
                margin-bottom: -1px
            }

            ._1NovW {
                -webkit-backface-visibility: hidden;
                backface-visibility: hidden
            }

            .rca7A {
                width: 100%;
                height: 100%;
                display: block
            }

            .rca7A svg._1eMqj {
                width: 0;
                height: 0;
                left: 0;
                top: 0;
                overflow: hidden;
                position: absolute
            }

            ._1K4Go,._1K4Go svg {
                width: 100%;
                height: 100%
            }

            ._22Lsw,.X-jRX {
                position: absolute;
                top: 0;
                width: 100%;
                height: 100%;
                overflow: hidden
            }

            .X-jRX {
                left: 0;
                -webkit-mask-image: var(--mask-image,none);
                mask-image: var(--mask-image,none);
                -webkit-mask-position: var(--mask-position,0);
                mask-position: var(--mask-position,0);
                -webkit-mask-size: var(--mask-size,100%);
                mask-size: var(--mask-size,100%);
                -webkit-mask-repeat: var(--mask-repeat,no-repeat);
                mask-repeat: var(--mask-repeat,no-repeat);
                pointer-events: var(--fill-layer-background-media-pointer-events)
            }

            .X-jRX._2AZ6T {
                clip: rect(0,auto,auto,0)
            }

            @media not all and (min-resolution: 0.001dpcm) {
                @supports (-webkit-appearance:none) {
                    .X-jRX._2AZ6T {
                        clip:auto;
                        -webkit-clip-path: inset(0)
                    }
                }
            }

            ._1J6n9 {
                height: 100%
            }

            .mlsxv {
                background-color: var(--bg-overlay-color)
            }

            ._1-b-O {
                opacity: var(--fill-layer-image-opacity);
                height: var(--fill-layer-image-height,100%)
            }

            ._1-b-O img {
                width: 100%;
                height: 100%
            }

            ._2kjIP {
                position: absolute;
                width: 100%;
                height: var(--media-padding-height);
                top: var(--media-padding-top);
                bottom: var(--media-padding-bottom)
            }

            .ysaOK {
                transform: scale(var(--scale,1));
                transition: var(--transform-duration,transform 0s)
            }

            .kBelp {
                position: relative;
                width: 100%;
                height: 100%
            }

            ._1n_5u {
                -webkit-clip-path: var(--fill-layer-clip);
                clip-path: var(--fill-layer-clip)
            }

            ._1n_5u,._3UHRA {
                position: absolute;
                top: 0
            }

            ._1n_5u,._1ytkV img,._3UHRA {
                width: 100%;
                height: 100%
            }

            ._1BP2G {
                position: absolute;
                top: 0
            }

            ._3nV6U {
                position: var(--fill-layer-background-media-position);
                pointer-events: var(--fill-layer-background-media-pointer-events);
                left: 0
            }

            ._1qeol,._3nV6U,.YhHhy {
                width: 100%;
                height: 100%;
                top: 0
            }

            .YhHhy {
                position: absolute
            }

            ._1qeol {
                background-color: var(--fill-layer-background-overlay-color);
                position: var(--fill-layer-background-overlay-position);
                opacity: var(--fill-layer-background-overlay-blend-opacity-fallback,1);
                transform: var(--fill-layer-background-overlay-transform)
            }

            @supports (mix-blend-mode: overlay) {
                ._1qeol {
                    mix-blend-mode:var(--fill-layer-background-overlay-blend-mode);
                    opacity: var(--fill-layer-background-overlay-blend-opacity,1)
                }
            }

            ._2ws69 {
                cursor: pointer
            }

            ._2edl5 {
                width: 100%;
                height: 100%;
                box-sizing: border-box
            }

            ._2ztx1 {
                min-height: var(--image-min-height);
                min-width: var(--image-min-width)
            }

            ._2ztx1 img {
                -o-object-position: var(--object-position);
                object-position: var(--object-position);
                filter: var(--filter-effect-svg-url)
            }

            .Ued3M {
                position: var(--position-fixed,static);
                left: var(--left,auto);
                top: var(--top,auto);
                z-index: var(--z-index,auto)
            }

            .Ued3M ._2ztx1 img {
                position: static;
                box-shadow: 0 0 0 #000;
                -webkit-user-select: none;
                -moz-user-select: none;
                -ms-user-select: none;
                user-select: none
            }

            .Ued3M ._2edl5 {
                display: block
            }

            .Ued3M ._2edl5,.Ued3M ._2ztx1 {
                overflow: hidden
            }

            ._1m93a .PE8t5 ._2-pBe {
                display: var(--item-display);
                width: var(--item-size);
                height: var(--item-size)
            }

            ._1m93a .PE8t5 ._2-pBe:not(:last-child) {
                margin: var(--item-margin)
            }

            ._1m93a .PE8t5 ._2-pBe .fNVUF {
                display: block
            }

            ._1m93a .PE8t5 ._2-pBe .fNVUF ._21zrA {
                width: var(--item-size);
                height: var(--item-size)
            }

            ._1m93a .PE8t5 {
                position: absolute;
                width: 100%;
                height: 100%;
                white-space: nowrap
            }

            body.device-mobile-optimized ._1m93a .PE8t5 {
                white-space: normal
            }

            ._3XkhD {
                position: absolute;
                top: 0;
                right: 0;
                bottom: 0;
                left: 0
            }

            ._3UCvU {
                height: auto;
                width: 100%;
                position: relative
            }

            body:not(.responsive) ._3V_xK {
                height: 100%;
                position: relative;
                left: 0;
                grid-area: 1/1/1/1;
                align-self: start;
                justify-self: stretch
            }

            body:not(.device-mobile-optimized) ._3XkhD {
                margin-left: calc((100% - var(--site-width)) / 2);
                width: var(--site-width)
            }

            ._4INfd ._3XkhD {
                overflow: hidden;
                background-color: rgba(var(--bg,var(--color_11)),var(--alpha-bg,1))
            }

            body.device-mobile-optimized ._3XkhD {
                left: 10px;
                right: 10px
            }

            ._1vnzj {
                position: absolute;
                top: 0;
                right: 0;
                bottom: 0;
                left: 0
            }

            ._2egft {
                height: auto;
                width: 100%;
                position: relative
            }

            body:not(.responsive) ._3akMP {
                height: 100%;
                position: relative;
                left: 0;
                grid-area: 1/1/1/1;
                align-self: start;
                justify-self: stretch
            }

            body:not(.device-mobile-optimized) ._1vnzj {
                margin-left: calc((100% - var(--site-width)) / 2);
                width: var(--site-width)
            }

            body.device-mobile-optimized ._1vnzj {
                left: 10px;
                right: 10px
            }

            ._1Cfot {
                pointer-events: none
            }
        </style>
        <style data-href="https://static.parastorage.com/services/editor-elements/dist/LoginSocialBar.afc6547d.chunk.min.css">
            ._1NSXQ {
                display: flex;
                align-items: center;
                box-sizing: border-box;
                background-color: rgba(var(--bg,0,0,0),var(--alpha-bg,0));
                border: var(--brw,0) solid rgba(var(--brd,var(--color_15)),var(--alpha-brd,1));
                border-radius: var(--rd,0);
                box-shadow: var(--shd,0 0 0 transparent)
            }

            ._27KJ3 {
                display: block;
                overflow: hidden;
                flex-shrink: 0;
                padding-left: 7px;
                padding-right: 7px;
                fill: rgba(var(--fillcolor,var(--color_0)),var(--alpha-fillcolor,1));
                fill-opacity: var(--alpha-fillcolor)
            }

            ._27KJ3,._27KJ3 .c0mZI,._27KJ3 svg {
                width: var(--icon-size,26px);
                height: var(--icon-size,26px)
            }

            ._27KJ3 .c0mZI,._27KJ3 svg {
                position: static
            }

            ._27KJ3 img {
                border-radius: 50%
            }

            ._2PFxe,._345YM {
                cursor: pointer;
                display: flex;
                align-items: center;
                white-space: nowrap;
                padding-top: 6px;
                padding-bottom: 6px;
                position: relative;
                min-width: 0
            }

            ._2PFxe,._345YM,._345YM ._11T5N {
                padding-left: 7px;
                padding-right: 7px;
                color: rgb(var(--txt,var(--color_18)));
                font: var(--fnt,var(--font_8))
            }

            ._345YM ._11T5N {
                overflow: hidden;
                text-overflow: ellipsis;
                min-width: 60px
            }

            ._345YM ._1-aWG {
                padding-left: 7px;
                padding-right: 7px
            }

            ._345YM ._1-aWG path {
                fill: rgb(var(--txt,var(--color_18)))
            }

            ._345YM:hover ._11T5N {
                color: rgb(var(--txth,var(--color_17)))
            }

            ._345YM:hover ._1-aWG path {
                fill: rgb(var(--txth,var(--color_17)))
            }

            ._2PFxe {
                border-radius: var(--rd,0)
            }

            ._2PFxe span {
                padding-left: 7px;
                padding-right: 7px
            }

            ._2PFxe:hover span {
                opacity: .7
            }

            ._3c5D0.N-2-- ._345YM {
                padding-left: 0
            }

            ._3c5D0._1rJBD ._345YM {
                padding-right: 0
            }

            .o_DnN {
                display: flex;
                flex-shrink: 0;
                padding-top: 6px;
                padding-bottom: 6px
            }

            .o_DnN ._3DxZO {
                position: relative
            }

            .o_DnN ._3DxZO,.o_DnN ._3DxZO svg {
                width: var(--icon-size,26px);
                height: var(--icon-size,26px)
            }

            .o_DnN ._3DxZO svg {
                fill: rgba(var(--fillcolor,var(--color_0)),var(--alpha-fillcolor,1));
                fill-opacity: var(--alpha-fillcolor)
            }

            .o_DnN.ElWPB {
                padding-left: 14px;
                padding-right: 3px
            }

            .o_DnN.ElWPB ._3DxZO:not(:last-child) {
                margin-right: 10px
            }

            .o_DnN.ElWPB ._2z7UX {
                left: 50%
            }

            .o_DnN._3BPVB {
                padding-left: 3px;
                padding-right: 14px
            }

            .o_DnN._3BPVB ._3DxZO:not(:last-child) {
                margin-left: 10px
            }

            .o_DnN._3BPVB ._2z7UX {
                right: 50%
            }

            ._2z7UX {
                display: block;
                background-color: rgba(var(--badge-bg,226,28,33),var(--alpha-badge-bg,1));
                color: rgb(var(--badge-txt,var(--color_11)));
                border-radius: 10px;
                position: absolute;
                top: 0;
                pointer-events: none;
                text-align: center;
                height: 18px;
                line-height: 18px;
                letter-spacing: 1px;
                padding-left: 6px;
                padding-right: 6px
            }

            ._1Bnqh {
                opacity: 0;
                cursor: pointer;
                width: 100%;
                height: 100%;
                left: 0;
                font-size: var(--fnt-size-dd,15px)
            }

            ._1Bnqh,.w4_Uk {
                position: absolute
            }

            .w4_Uk {
                display: none;
                top: calc(100% + var(--brw, 0px));
                padding: 10px 0;
                z-index: 99999;
                background-color: rgba(var(--bg-dd,var(--color_11)),var(--alpha-bg-dd,1));
                border: var(--brw-dd,1px) solid rgba(var(--brd-dd,var(--color_15)),var(--alpha-brd-dd,1));
                box-sizing: border-box;
                border-radius: var(--rd-dd,0);
                box-shadow: var(--shd-dd,0 0 0 transparent);
                font: var(--fnt,var(--font_8));
                font-size: var(--fnt-size-dd,15px);
                min-width: 100px;
                max-width: 300px
            }

            .w4_Uk.Gcvfr {
                display: block
            }

            .w4_Uk hr {
                margin: 5px 20px;
                opacity: .4
            }

            ._1SdeY {
                --force-state-metadata:selected}

            ._29xft {
                color: rgb(var(--txt-dd,var(--color_15)));
                cursor: pointer;
                padding: 0 20px;
                display: flex;
                line-height: 260%;
                border-radius: var(--rd-dd,0)
            }

            ._29xft._1SdeY {
                color: rgb(var(--txt-slct-dd,var(--color_18)))
            }

            ._29xft:hover {
                color: rgb(var(--txth-dd,var(--color_14)))
            }

            ._29xft ._1g7pK {
                overflow: hidden;
                text-overflow: ellipsis;
                white-space: nowrap
            }

            ._29xft ._3niRF {
                opacity: .6
            }

            ._1mEpJ {
                right: 14px
            }

            ._1mEpJ ._3niRF {
                padding-left: 12px
            }

            ._1_l7F {
                left: 14px
            }

            ._1_l7F ._3niRF {
                padding-right: 12px
            }
        </style>
        <style data-href="https://static.parastorage.com/services/editor-elements/dist/bootstrap-components-responsive.5813065d.chunk.min.css">
            ._1BLK_ {
                overflow-x: hidden
            }

            ._1BLK_ ._3mdqs {
                display: flex;
                flex-direction: column;
                height: 100%;
                width: 100%
            }

            ._1BLK_ ._3mdqs ._151Fq {
                flex: 1
            }

            ._1BLK_ ._3mdqs ._2qN6d {
                width: calc(100% - (var(--menuTotalBordersX, 0px)));
                height: calc(100% - (var(--menuTotalBordersY, 0px)));
                white-space: nowrap;
                overflow: visible
            }

            ._1BLK_ ._3mdqs ._2qN6d .AEGjP {
                display: inline-block
            }

            ._1BLK_ ._3mdqs ._2qN6d ._3c4V9 {
                display: block;
                width: 100%
            }

            ._1BLK_ ._3FVLO {
                z-index: 99999;
                display: block;
                opacity: 1
            }

            ._1BLK_ ._3FVLO ._37sAS {
                overflow: visible;
                display: inherit;
                white-space: nowrap;
                width: auto;
                visibility: inherit
            }

            ._1BLK_ ._3FVLO._3Pev9 {
                transition: visibility;
                transition-delay: .2s;
                visibility: visible
            }

            ._1BLK_ ._3FVLO .hfpL0 {
                display: inline-block
            }

            ._1BLK_ ._2FZTJ {
                display: none
            }

            ._3w6CQ>nav {
                top: 0;
                right: 0;
                bottom: 0;
                left: 0
            }

            ._3w6CQ ._2qN6d,._3w6CQ ._3FVLO,._3w6CQ>nav {
                position: absolute
            }

            ._3w6CQ ._3FVLO {
                visibility: hidden;
                margin-top: 7px
            }

            ._3w6CQ ._3FVLO[data-dropMode=dropUp] {
                margin-top: 0;
                margin-bottom: 7px
            }

            ._3w6CQ ._37sAS {
                background-color: rgba(var(--bgDrop,var(--color_11)),var(--alpha-bgDrop,1));
                border-radius: var(--rd,0);
                box-shadow: var(--shd,0 1px 4px rgba(0,0,0,.6))
            }

            ._1VAYf,._14VId {
                height: 100%;
                width: auto;
                position: relative;
                box-sizing: border-box;
                overflow: visible
            }

            ._1VAYf[data-state~=header] a,._1VAYf[data-state~=header] div,._14VId[data-state~=header] a,._14VId[data-state~=header] div {
                cursor: default!important
            }

            ._1VAYf ._35v05,._14VId ._35v05 {
                display: inline-block;
                height: 100%;
                width: 100%
            }

            ._14VId {
                display: inline-block;
                cursor: pointer;
                font: var(--fnt,var(--font_1))
            }

            ._14VId ._1Szr4 {
                padding: 0 var(--pad,5px)
            }

            ._14VId .ccDUc {
                display: inline-block;
                padding: 0 10px;
                color: rgb(var(--txt,var(--color_15)));
                transition: var(--trans,color .4s ease 0s)
            }

            ._14VId[data-state~=drop] {
                width: 100%;
                display: block
            }

            ._14VId[data-state~=drop] .ccDUc {
                padding: 0 .5em
            }

            ._14VId[data-state~=link]:hover .ccDUc,._14VId[data-state~=over] .ccDUc {
                color: rgb(var(--txth,var(--color_14)));
                transition: var(--trans,color .4s ease 0s)
            }

            ._14VId[data-state~=selected] .ccDUc {
                color: rgb(var(--txts,var(--color_14)));
                transition: var(--trans,color .4s ease 0s)
            }

            /*! remove when this file is updated or https://github.com/wix/yoshi/issues/2689 is resolved */
            ._3WQKx {
                overflow: hidden;
                background-color: rgba(var(--backgroundColor,var(--color_8)),var(--alpha-backgroundColor,1));
                border-color: rgba(var(--borderColor,var(--color_8)),var(--alpha-borderColor,1));
                border-width: var(--borderWidth,0);
                border-style: solid;
                border-radius: var(--cornerRadius,0);
                box-shadow: var(--boxShadow,none)
            }

            ._3WQKx wix-image {
                position: absolute;
                top: 0;
                bottom: 0;
                left: 0;
                right: 0;
                opacity: var(--mediaOpacity,1)
            }

            ._3WQKx img {
                width: 100%;
                height: 100%
            }

            ._7STJN .PpEzW .TlAtT {
                display: var(--item-display);
                width: var(--item-size);
                height: var(--item-size)
            }

            ._7STJN .PpEzW .TlAtT:not(:last-child) {
                margin: var(--item-margin)
            }

            ._7STJN .PpEzW .TlAtT .I0LrY {
                display: block
            }

            ._7STJN .PpEzW .TlAtT .I0LrY ._3YBJ2 {
                width: var(--item-size);
                height: var(--item-size)
            }

            ._7STJN {
                display: table
            }

            ._7STJN .PpEzW {
                display: flex;
                flex-direction: var(--flex-direction)
            }

            ._3QVX_ {
                background-color: rgba(var(--bg,var(--color_11)),var(--alpha-bg,1))
            }

            .b2Sfd {
                transition-delay: var(--transition-delay);
                transition-duration: var(--transition-duration);
                transition-timing-function: var(--transition-timing-function);
                transition-property: var(--transition-property)
            }

            .b2Sfd._3kfn- {
                transform: var(--scrolled-transform)
            }

            .b2Sfd._13h-i {
                opacity: var(--scrolled-opacity)
            }

            .b2Sfd._30mX3 {
                transition-delay: 0s
            }

            ._2mKjd {
                background-color: rgba(var(--bg,var(--color_11)),var(--alpha-bg,1));
                transition-delay: var(--transition-delay);
                transition-duration: var(--transition-duration);
                transition-timing-function: var(--transition-timing-function);
                transition-property: var(--transition-property)
            }

            ._192ST._2mKjd {
                background-color: rgba(var(--bg-scrl,var(--color_11)),var(--alpha-bg-scrl,1))
            }

            ._30GbI {
                pointer-events: none!important
            }

            ._30GbI._3HaDB>*,._30GbI:not(._3HaDB)>:first-child>* {
                pointer-events: auto
            }

            ._1xBzm {
                --container-corvid-border-color:rgba(var(--brd,var(--color_15)),var(--alpha-brd,1));--container-corvid-border-size:var(--brw,1px);--container-corvid-background-color:rgba(var(--bg,var(--color_11)),var(--alpha-bg,1))}

            ._3NuDC {
                border: var(--container-corvid-border-width,var(--brw,1px)) solid var(--container-corvid-border-color,rgba(var(--brd,var(--color_15)),var(--alpha-brd,1)));
                background-color: var(--container-corvid-background-color,rgba(var(--bg,var(--color_11)),var(--alpha-bg,1)));
                border-radius: var(--rd,5px);
                box-shadow: var(--shd,0 1px 4px rgba(0,0,0,.6));
                position: absolute;
                top: 0;
                right: 0;
                bottom: 0;
                left: 0
            }

            ._2wjTQ {
                -webkit-tap-highlight-color: rgba(0,0,0,0);
                opacity: 0;
                visibility: hidden
            }

            ._2wjTQ._3bPEB {
                opacity: 1;
                visibility: visible
            }

            ._2wjTQ[data-undisplayed=true] {
                display: none
            }

            ._2wjTQ:not([data-is-mesh]) .-r5tc,._2wjTQ:not([data-is-mesh]) ._3KPTS {
                position: absolute;
                top: 0;
                right: 0;
                bottom: 0;
                left: 0
            }

            ._1ACUw {
                height: 100%;
                width: 100%;
                position: fixed;
                top: 0;
                left: 0;
                background-color: rgba(var(--bg,var(--color_15)),var(--alpha-bg,1));
                display: initial;
                opacity: 0
            }

            ._1ACUw._11nYb {
                display: none
            }

            body.device-mobile-optimized ._1ACUw {
                height: 100vh;
                width: var(--screen-width)
            }

            body.device-mobile-optimized ._1ACUw,body.device-mobile-optimized ._2wjTQ._11nYb {
                left: calc((100% - var(--screen-width)) / 2)
            }

            body.device-mobile-optimized ._2wjTQ.tPkHi,body:not(.device-mobile-optimized) ._2wjTQ.tPkHi {
                height: 100vh
            }

            ._1KE0E.tPkHi,._1KE0E.tPkHi>:first-child {
                height: calc(var(--menu-height) - var(--wix-ads-height))
            }

            ._1KE0E.tPkHi>:first-child {
                margin-top: var(--wix-ads-height)
            }

            ._2wjTQ.tPkHi {
                top: 0
            }

            ._2wjTQ._2RcFC {
                z-index: calc(var(--above-all-z-index) - 1)
            }

            ._3bezk {
                -webkit-tap-highlight-color: rgba(0,0,0,0);
                opacity: 0;
                visibility: hidden
            }

            ._3bezk.bwoU- {
                opacity: 1;
                visibility: visible
            }

            ._3bezk[data-undisplayed=true] {
                display: none
            }

            ._3bezk:not([data-is-mesh]) ._1tsjP,._3bezk:not([data-is-mesh]) ._2eYka {
                position: absolute;
                top: 0;
                right: 0;
                bottom: 0;
                left: 0
            }

            .CcDeJ {
                height: 100%;
                width: 100%;
                position: fixed;
                top: 0;
                left: 0;
                background-color: rgba(var(--bg,var(--color_15)),var(--alpha-bg,1));
                display: initial;
                opacity: 0
            }

            .CcDeJ.d1eWu {
                display: none
            }

            body.device-mobile-optimized .CcDeJ {
                height: 100vh;
                width: var(--screen-width)
            }

            body.device-mobile-optimized ._3bezk.d1eWu,body.device-mobile-optimized .CcDeJ {
                left: calc((100% - var(--screen-width)) / 2)
            }

            body.device-mobile-optimized ._3bezk._3o_Lz,body:not(.device-mobile-optimized) ._3bezk._3o_Lz {
                height: 100vh
            }

            ._2iV2q._3o_Lz,._2iV2q._3o_Lz>:first-child {
                height: calc(var(--menu-height) - var(--wix-ads-height))
            }

            ._2iV2q._3o_Lz>:first-child {
                margin-top: var(--wix-ads-height)
            }

            ._3bezk._3o_Lz {
                top: 0
            }

            .cf8n_ {
                position: absolute;
                top: 0;
                right: 0;
                bottom: 0;
                left: 0;
                background-color: rgba(var(--containerBackground,var(--color_11)),var(--alpha-containerBackground,1))
            }

            ._2iV2q {
                height: 100%
            }

            .AgPkq ._1htNC {
                position: absolute;
                top: 0;
                right: 0;
                bottom: 0;
                left: 0;
                overflow: hidden;
                background-color: rgba(var(--bg,var(--color_11)),var(--alpha-bg,1))
            }

            ._7b77h {
                display: contents
            }
        </style>
        <style data-href="https://static.parastorage.com/services/editor-elements/dist/DropDownMenu_OverlineMenuButtonSkin.9c677e50.chunk.min.css">
            ._3vJLl {
                overflow-x: hidden
            }

            ._3vJLl ._137Lb {
                display: flex;
                flex-direction: column;
                height: 100%;
                width: 100%
            }

            ._3vJLl ._137Lb ._23fYY {
                flex: 1
            }

            ._3vJLl ._137Lb ._vEk9 {
                width: calc(100% - (var(--menuTotalBordersX, 0px)));
                height: calc(100% - (var(--menuTotalBordersY, 0px)));
                white-space: nowrap;
                overflow: visible
            }

            ._3vJLl ._137Lb ._vEk9 ._3_vJA {
                display: inline-block
            }

            ._3vJLl ._137Lb ._vEk9 ._1gysk {
                display: block;
                width: 100%
            }

            ._3vJLl ._3p0kk {
                z-index: 99999;
                display: block;
                opacity: 1
            }

            ._3vJLl ._3p0kk ._1BUV6 {
                overflow: visible;
                display: inherit;
                white-space: nowrap;
                width: auto;
                visibility: inherit
            }

            ._3vJLl ._3p0kk._3ptCd {
                transition: visibility;
                transition-delay: .2s;
                visibility: visible
            }

            ._3vJLl ._3p0kk ._2bW8Z {
                display: inline-block
            }

            ._3vJLl ._2XgPb {
                display: none
            }

            ._2CaQE>nav {
                top: 0;
                right: 0;
                bottom: 0;
                left: 0
            }

            ._2CaQE ._3p0kk,._2CaQE ._vEk9,._2CaQE>nav {
                position: absolute
            }

            ._2CaQE ._3p0kk {
                visibility: hidden;
                margin-top: 7px;
                padding: 15px 5px 0 5px;
                background-color: rgba(var(--bgDrop,var(--color_11)),var(--alpha-bgDrop,1));
                border-radius: var(--rd,10px);
                box-shadow: var(--shd,0 1px 4px rgba(0,0,0,.6))
            }

            ._2CaQE [data-dropmode=dropUp] ._3p0kk {
                margin-top: 0;
                margin-bottom: 7px
            }

            ._2NSlE,.SjMSg {
                height: 100%;
                width: auto;
                position: relative;
                box-sizing: border-box;
                overflow: visible
            }

            ._2NSlE[data-state~=header] a,._2NSlE[data-state~=header] div,.SjMSg[data-state~=header] a,.SjMSg[data-state~=header] div {
                cursor: default!important
            }

            ._2NSlE ._1FF4t,.SjMSg ._1FF4t {
                display: inline-block;
                height: 100%;
                width: 100%
            }

            .SjMSg {
                display: inline-block
            }

            .SjMSg ._1__h7 {
                padding: 0 var(--pad,5px)
            }

            .SjMSg ._3vUm_ {
                cursor: pointer;
                font: var(--fnt,var(--font_1));
                border-top: 1px solid rgba(var(--brd,var(--color_15)),var(--alpha-brd,1))
            }

            .SjMSg ._1o_X5 {
                color: rgb(var(--txt,var(--color_15)));
                display: inline-block;
                padding: 8px
            }

            .SjMSg[data-listposition=left] {
                padding-left: 0
            }

            .SjMSg[data-listposition=right] {
                padding-right: 0
            }

            .SjMSg[data-state~=drop] {
                width: 100%;
                display: block
            }

            .SjMSg[data-state~=link]:hover ._3vUm_,.SjMSg[data-state~=over] ._3vUm_ {
                border-top-width: 4px;
                border-top-color: rgba(var(--brdh,var(--color_15)),var(--alpha-brdh,1))
            }

            .SjMSg[data-state~=link]:hover ._1o_X5,.SjMSg[data-state~=over] ._1o_X5 {
                color: rgb(var(--txth,var(--color_15)));
                display: inline-block;
                padding-top: 5px
            }

            .SjMSg[data-state~=selected] ._3vUm_ {
                border-top-width: 4px;
                border-top-color: rgba(var(--brds,var(--color_15)),var(--alpha-brds,1))
            }

            .SjMSg[data-state~=selected] ._1o_X5 {
                color: rgb(var(--txts,var(--color_15)));
                display: inline-block;
                padding-top: 5px
            }
        </style>
        <style data-href="https://static.parastorage.com/services/editor-elements/dist/FreemiumBannerDesktop.08fe5004.chunk.min.css">
            @font-face {
                font-display:swap;font-family: wixFreemiumFontW01-35Thin;
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/56be84de-9d60-4089-8df0-0ea6ec786b84.eot#iefix);
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/56be84de-9d60-4089-8df0-0ea6ec786b84.eot#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/50d35bbc-dfd4-48f1-af16-cf058f69421d.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/278bef59-6be1-4800-b5ac-1f769ab47430.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/2e309b1b-08b8-477f-bc9e-7067cf0af0b3.svg#2e309b1b-08b8-477f-bc9e-7067cf0af0b3) format("svg")
            }

            @font-face {
                font-display:swap;font-family: wixFreemiumFontW01-45Ligh;
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/ae1656aa-5f8f-4905-aed0-93e667bd6e4a.eot#iefix);
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/ae1656aa-5f8f-4905-aed0-93e667bd6e4a.eot#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/530dee22-e3c1-4e9f-bf62-c31d510d9656.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/688ab72b-4deb-4e15-a088-89166978d469.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/7816f72f-f47e-4715-8cd7-960e3723846a.svg#7816f72f-f47e-4715-8cd7-960e3723846a) format("svg")
            }

            @font-face {
                font-display:swap;font-family: wixFreemiumFontW01-55Roma;
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/b7693a83-b861-4aa6-85e0-9ecf676bc4d6.eot#iefix);
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/b7693a83-b861-4aa6-85e0-9ecf676bc4d6.eot#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/bcf54343-d033-41ee-bbd7-2b77df3fe7ba.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/b0ffdcf0-26da-47fd-8485-20e4a40d4b7d.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/da09f1f1-062a-45af-86e1-2bbdb3dd94f9.svg#da09f1f1-062a-45af-86e1-2bbdb3dd94f9) format("svg")
            }

            @font-face {
                font-display:swap;font-family: wixFreemiumFontW01-65Medi;
                font-weight: 700;
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/07fe0fec-b63f-4963-8ee1-535528b67fdb.eot#iefix);
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/07fe0fec-b63f-4963-8ee1-535528b67fdb.eot#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/60be5c39-863e-40cb-9434-6ebafb62ab2b.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/4c6503c9-859b-4d3b-a1d5-2d42e1222415.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/36c182c6-ef98-4021-9b0d-d63122c2bbf5.svg#36c182c6-ef98-4021-9b0d-d63122c2bbf5) format("svg")
            }

            @font-face {
                font-display:swap;font-family: wixFreemiumFontW02-35Thin;
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/30b6ffc3-3b64-40dd-9ff8-a3a850daf535.eot#iefix);
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/30b6ffc3-3b64-40dd-9ff8-a3a850daf535.eot#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/775a65da-14aa-4634-be95-6724c05fd522.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/988eaaa7-5565-4f65-bb17-146b650ce9e9.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/3503a1a6-91c3-4c42-8e66-2ea7b2b57541.svg#3503a1a6-91c3-4c42-8e66-2ea7b2b57541) format("svg")
            }

            @font-face {
                font-display:swap;font-family: wixFreemiumFontW02-45Ligh;
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/88fcd49a-13c7-4d0c-86b1-ad1e258bd75d.eot#iefix);
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/88fcd49a-13c7-4d0c-86b1-ad1e258bd75d.eot#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/9a2e4855-380f-477f-950e-d98e8db54eac.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/fa82d0ee-4fbd-4cc9-bf9f-226ad1fcbae2.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/48d599a6-92b5-4d43-a4ac-8959f6971853.svg#48d599a6-92b5-4d43-a4ac-8959f6971853) format("svg")
            }

            @font-face {
                font-display:swap;font-family: wixFreemiumFontW02-55Roma;
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/0b3a3fca-0fad-402b-bd38-fdcbad1ef776.eot#iefix);
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/0b3a3fca-0fad-402b-bd38-fdcbad1ef776.eot#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/d5af76d8-a90b-4527-b3a3-182207cc3250.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/1d238354-d156-4dde-89ea-4770ef04b9f9.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/b68875cb-14a9-472e-8177-0247605124d7.svg#b68875cb-14a9-472e-8177-0247605124d7) format("svg")
            }

            @font-face {
                font-display:swap;font-family: wixFreemiumFontW02-65Medi;
                font-weight: 700;
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/55f60419-09c3-42bd-b81f-1983ff093852.eot#iefix);
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/55f60419-09c3-42bd-b81f-1983ff093852.eot#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/5b4a262e-3342-44e2-8ad7-719998a68134.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/4a3ef5d8-cfd9-4b96-bd67-90215512f1e5.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/58ab5075-53ea-46e6-9783-cbb335665f88.svg#58ab5075-53ea-46e6-9783-cbb335665f88) format("svg")
            }

            @font-face {
                font-display:swap;font-family: wixFreemiumFontW10-35Thin;
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/93b6bf6a-418e-4a8f-8f79-cb9c99ef3e32.eot#iefix);
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/93b6bf6a-418e-4a8f-8f79-cb9c99ef3e32.eot#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/c881c21b-4148-4a11-a65d-f35e42999bc8.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/03634cf1-a9c9-4e13-b049-c90d830423d4.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/1bc99c0a-298b-46f9-b325-18b5e5169795.svg#1bc99c0a-298b-46f9-b325-18b5e5169795) format("svg")
            }

            @font-face {
                font-display:swap;font-family: wixFreemiumFontW10-45Ligh;
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/5b85c7cc-6ad4-4226-83f5-9d19e2974123.eot#iefix);
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/5b85c7cc-6ad4-4226-83f5-9d19e2974123.eot#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/835e7b4f-b524-4374-b57b-9a8fc555fd4e.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/2c694ef6-9615-473e-8cf4-d8d00c6bd973.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/3fc84193-a13f-4fe8-87f7-238748a4ac54.svg#3fc84193-a13f-4fe8-87f7-238748a4ac54) format("svg")
            }

            @font-face {
                font-display:swap;font-family: wixFreemiumFontW10-65Medi;
                font-weight: 700;
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/7092fdcc-7036-48ce-ae23-cfbc9be2e3b0.eot#iefix);
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/7092fdcc-7036-48ce-ae23-cfbc9be2e3b0.eot#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/5b29e833-1b7a-40ab-82a5-cfd69c8650f4.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/b0298148-2d59-44d1-9ec9-1ca6bb097603.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/ae1dea8c-a953-4845-b616-74a257ba72e6.svg#ae1dea8c-a953-4845-b616-74a257ba72e6) format("svg")
            }

            @font-face {
                font-display:swap;font-family: wixFreemiumFontW10-55Roma;
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/f1feaed7-6bce-400a-a07e-a893ae43a680.eot#iefix);
                src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/f1feaed7-6bce-400a-a07e-a893ae43a680.eot#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/8ac9e38d-29c6-41ea-8e47-4ae4d2b1a4e1.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/4bd09087-655e-4abb-844c-dccdeb68003d.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/df234d87-eada-4058-aa80-5871e7fbe1c3.svg#df234d87-eada-4058-aa80-5871e7fbe1c3) format("svg")
            }

            ._2ny4c {
                width: 100%
            }

            ._2ny4c._3cP_8 {
                display: none
            }

            ._2ny4c._2NZB- {
                display: block;
                visibility: visible
            }

            ._2ny4c .zzFVa {
                direction: rtl
            }

            ._2ny4c ._3Dqvk {
                direction: ltr
            }

            ._2ny4c._3jGoI {
                z-index: var(--above-all-z-index);
                position: fixed;
                top: 0
            }

            ._2ny4c ._3hdQ6 {
                box-sizing: border-box;
                background: #eff1f2;
                display: flex;
                justify-content: center;
                align-items: center;
                border-bottom: 3px solid #a0138e;
                width: 100%;
                height: 50px
            }

            ._2ny4c ._3hdQ6._1ID94 {
                background-color: red;
                border: none
            }

            ._2ny4c ._3hdQ6>._1UBiC {
                display: flex;
                align-items: center
            }

            ._2ny4c ._3hdQ6>._1UBiC ._17VLG {
                font-family: wixFreemiumFontW01-65Medi,wixFreemiumFontW02-65Medi,wixFreemiumFontW10-65Medi,Helvetica Neue,Helvetica,Arial,メイリオ,meiryo,ヒラギノ角ゴ pro w3,hiragino kaku gothic pro,sans-serif;
                font-size: 14px;
                color: #20303c;
                line-height: 24px;
                flex-shrink: 0
            }

            ._2ny4c ._3hdQ6>._1UBiC ._17VLG ._3Qu-W {
                fill: #20303c;
                width: 36px;
                vertical-align: middle;
                padding-bottom: 6px;
                height: 16px
            }

            ._2ny4c ._3hdQ6>._1UBiC ._17VLG ._3Qu-W>._2TY8E {
                fill: #fc0
            }

            ._2ny4c ._3hdQ6>._1UBiC ._17VLG ._3DZA8 {
                color: #20303c
            }

            ._2ny4c ._3hdQ6>._1UBiC ._3VwOd {
                font-family: wixFreemiumFontW01-65Medi,wixFreemiumFontW02-65Medi,wixFreemiumFontW10-65Medi,Helvetica Neue,Helvetica,Arial,メイリオ,meiryo,ヒラギノ角ゴ pro w3,hiragino kaku gothic pro,sans-serif;
                font-size: 14px;
                color: #a0138e;
                border: 1px solid #a0138e;
                display: inline-flex;
                width: 112px;
                height: 35px;
                justify-content: center;
                align-items: center;
                border-radius: 17px;
                flex-shrink: 0;
                text-align: center
            }

            ._2ny4c ._3hdQ6>._1UBiC ._3VwOd._3Dqvk {
                margin-left: 6px
            }

            ._2ny4c ._3hdQ6>._1UBiC ._3VwOd.zzFVa {
                margin-right: 6px
            }

            ._2ny4c ._3hdQ6:not(._1ID94):hover {
                cursor: pointer;
                background: #fff
            }

            ._2ny4c ._3hdQ6:not(._1ID94):hover ._3VwOd {
                color: #fff;
                background-color: #a0138e
            }
        </style>
        <title>4 | My Site</title>
        <link rel="canonical" href="https://albertkeshev.wixsite.com/my-site"/>
        <meta name="robots" content="noindex"/>
        <meta property="og:title" content="4 | My Site"/>
        <meta property="og:url" content="https://albertkeshev.wixsite.com/my-site"/>
        <meta property="og:site_name" content="My Site"/>
        <meta property="og:type" content="website"/>
        <meta name="twitter:card" content="summary_large_image"/>
        <meta name="twitter:title" content="4 | My Site"/>
    </head>
    <body class=''>
        <script type="text/javascript">
            var bodyCacheable = true;

            var exclusionReason = {
                "shouldRender": true,
                "forced": false
            };
            var ssrInfo = {
                "renderBodyTime": 188,
                "renderTimeStamp": 1621773672667
            }
        </script>
        <!-- react-dom -->
        <script>
            window.clientSideRender = false;
        </script>
        <!--pageHtmlEmbeds.bodyStart start-->
        <script type="wix/htmlEmbeds" id="pageHtmlEmbeds.bodyStart start"></script>
        <script type="wix/htmlEmbeds" id="pageHtmlEmbeds.bodyStart end"></script>
        <!--pageHtmlEmbeds.bodyStart end-->
        <script id="wix-first-paint">
            if (window.ResizeObserver && (!window.PerformanceObserver || !PerformanceObserver.supportedEntryTypes || PerformanceObserver.supportedEntryTypes.indexOf('paint') === -1)) {
                new ResizeObserver(function(entries, observer) {
                    entries.some(function(entry) {
                        var contentRect = entry.contentRect;
                        if (contentRect.width > 0 && contentRect.height > 0) {
                            requestAnimationFrame(function(now) {
                                window.wixFirstPaint = now;
                                dispatchEvent(new CustomEvent('wixFirstPaint'));
                            });
                            observer.disconnect();
                            return true;
                        }
                    });
                }
                ).observe(document.body);
            }
        </script>
        <pages-css id="pages-css">
            <style id="css_masterPage">
                :root {
                    --color_0:255,255,255;--color_1:255,255,255;--color_2:0,0,0;--color_3:237,28,36;--color_4:0,136,203;--color_5:255,203,5;--color_6:114,114,114;--color_7:176,176,176;--color_8:255,255,255;--color_9:114,114,114;--color_10:176,176,176;--color_11:255,255,255;--color_12:232,230,230;--color_13:199,199,199;--color_14:153,153,151;--color_15:65,65,65;--color_16:181,188,240;--color_17:143,152,226;--color_18:56,74,211;--color_19:37,49,141;--color_20:19,25,70;--color_21:249,197,180;--color_22:243,167,143;--color_23:237,88,41;--color_24:158,59,27;--color_25:79,29,14;--color_26:210,172,247;--color_27:186,131,240;--color_28:128,21,232;--color_29:85,14,155;--color_30:43,7,77;--color_31:177,211,187;--color_32:127,168,139;--color_33:64,124,81;--color_34:43,83,54;--color_35:21,41,27;--font_0:normal normal normal 40px/1.4em proxima-n-w01-reg,sans-serif;--font_1:normal normal normal 16px/1.4em din-next-w01-light,din-next-w02-light,din-next-w10-light,sans-serif;--font_2:normal normal normal 28px/1.4em proxima-n-w01-reg,sans-serif;--font_3:normal normal normal 60px/1.4em proxima-n-w01-reg,sans-serif;--font_4:normal normal normal 40px/1.4em proxima-n-w01-reg,sans-serif;--font_5:normal normal normal 25px/1.4em proxima-n-w01-reg,sans-serif;--font_6:normal normal normal 22px/1.4em proxima-n-w01-reg,sans-serif;--font_7:normal normal normal 17px/1.4em proxima-n-w01-reg,sans-serif;--font_8:normal normal normal 15px/1.4em proxima-n-w01-reg,sans-serif;--font_9:normal normal normal 14px/1.4em proxima-n-w01-reg,sans-serif;--font_10:normal normal normal 12px/1.4em din-next-w01-light,din-next-w02-light,din-next-w10-light,sans-serif;--wix-ads-height:50px;--wix-ads-top-height:50px;--site-width:980px;--above-all-z-index:100000;--minViewportSize:320;--maxViewportSize:1920}

                .font_0 {
                    font: var(--font_0);
                    color: rgb(var(--color_15))
                }

                .font_1 {
                    font: var(--font_1);
                    color: rgb(var(--color_14))
                }

                .font_2 {
                    font: var(--font_2);
                    color: rgb(var(--color_15))
                }

                .font_3 {
                    font: var(--font_3);
                    color: rgb(var(--color_15))
                }

                .font_4 {
                    font: var(--font_4);
                    color: rgb(var(--color_15))
                }

                .font_5 {
                    font: var(--font_5);
                    color: rgb(var(--color_15))
                }

                .font_6 {
                    font: var(--font_6);
                    color: rgb(var(--color_15))
                }

                .font_7 {
                    font: var(--font_7);
                    color: rgb(var(--color_15))
                }

                .font_8 {
                    font: var(--font_8);
                    color: rgb(var(--color_15))
                }

                .font_9 {
                    font: var(--font_9);
                    color: rgb(var(--color_15))
                }

                .font_10 {
                    font: var(--font_10);
                    color: rgb(var(--color_14))
                }

                .color_0 {
                    color: rgb(var(--color_0))
                }

                .color_1 {
                    color: rgb(var(--color_1))
                }

                .color_2 {
                    color: rgb(var(--color_2))
                }

                .color_3 {
                    color: rgb(var(--color_3))
                }

                .color_4 {
                    color: rgb(var(--color_4))
                }

                .color_5 {
                    color: rgb(var(--color_5))
                }

                .color_6 {
                    color: rgb(var(--color_6))
                }

                .color_7 {
                    color: rgb(var(--color_7))
                }

                .color_8 {
                    color: rgb(var(--color_8))
                }

                .color_9 {
                    color: rgb(var(--color_9))
                }

                .color_10 {
                    color: rgb(var(--color_10))
                }

                .color_11 {
                    color: rgb(var(--color_11))
                }

                .color_12 {
                    color: rgb(var(--color_12))
                }

                .color_13 {
                    color: rgb(var(--color_13))
                }

                .color_14 {
                    color: rgb(var(--color_14))
                }

                .color_15 {
                    color: rgb(var(--color_15))
                }

                .color_16 {
                    color: rgb(var(--color_16))
                }

                .color_17 {
                    color: rgb(var(--color_17))
                }

                .color_18 {
                    color: rgb(var(--color_18))
                }

                .color_19 {
                    color: rgb(var(--color_19))
                }

                .color_20 {
                    color: rgb(var(--color_20))
                }

                .color_21 {
                    color: rgb(var(--color_21))
                }

                .color_22 {
                    color: rgb(var(--color_22))
                }

                .color_23 {
                    color: rgb(var(--color_23))
                }

                .color_24 {
                    color: rgb(var(--color_24))
                }

                .color_25 {
                    color: rgb(var(--color_25))
                }

                .color_26 {
                    color: rgb(var(--color_26))
                }

                .color_27 {
                    color: rgb(var(--color_27))
                }

                .color_28 {
                    color: rgb(var(--color_28))
                }

                .color_29 {
                    color: rgb(var(--color_29))
                }

                .color_30 {
                    color: rgb(var(--color_30))
                }

                .color_31 {
                    color: rgb(var(--color_31))
                }

                .color_32 {
                    color: rgb(var(--color_32))
                }

                .color_33 {
                    color: rgb(var(--color_33))
                }

                .color_34 {
                    color: rgb(var(--color_34))
                }

                .color_35 {
                    color: rgb(var(--color_35))
                }

                .backcolor_0 {
                    background-color: rgb(var(--color_0))
                }

                .backcolor_1 {
                    background-color: rgb(var(--color_1))
                }

                .backcolor_2 {
                    background-color: rgb(var(--color_2))
                }

                .backcolor_3 {
                    background-color: rgb(var(--color_3))
                }

                .backcolor_4 {
                    background-color: rgb(var(--color_4))
                }

                .backcolor_5 {
                    background-color: rgb(var(--color_5))
                }

                .backcolor_6 {
                    background-color: rgb(var(--color_6))
                }

                .backcolor_7 {
                    background-color: rgb(var(--color_7))
                }

                .backcolor_8 {
                    background-color: rgb(var(--color_8))
                }

                .backcolor_9 {
                    background-color: rgb(var(--color_9))
                }

                .backcolor_10 {
                    background-color: rgb(var(--color_10))
                }

                .backcolor_11 {
                    background-color: rgb(var(--color_11))
                }

                .backcolor_12 {
                    background-color: rgb(var(--color_12))
                }

                .backcolor_13 {
                    background-color: rgb(var(--color_13))
                }

                .backcolor_14 {
                    background-color: rgb(var(--color_14))
                }

                .backcolor_15 {
                    background-color: rgb(var(--color_15))
                }

                .backcolor_16 {
                    background-color: rgb(var(--color_16))
                }

                .backcolor_17 {
                    background-color: rgb(var(--color_17))
                }

                .backcolor_18 {
                    background-color: rgb(var(--color_18))
                }

                .backcolor_19 {
                    background-color: rgb(var(--color_19))
                }

                .backcolor_20 {
                    background-color: rgb(var(--color_20))
                }

                .backcolor_21 {
                    background-color: rgb(var(--color_21))
                }

                .backcolor_22 {
                    background-color: rgb(var(--color_22))
                }

                .backcolor_23 {
                    background-color: rgb(var(--color_23))
                }

                .backcolor_24 {
                    background-color: rgb(var(--color_24))
                }

                .backcolor_25 {
                    background-color: rgb(var(--color_25))
                }

                .backcolor_26 {
                    background-color: rgb(var(--color_26))
                }

                .backcolor_27 {
                    background-color: rgb(var(--color_27))
                }

                .backcolor_28 {
                    background-color: rgb(var(--color_28))
                }

                .backcolor_29 {
                    background-color: rgb(var(--color_29))
                }

                .backcolor_30 {
                    background-color: rgb(var(--color_30))
                }

                .backcolor_31 {
                    background-color: rgb(var(--color_31))
                }

                .backcolor_32 {
                    background-color: rgb(var(--color_32))
                }

                .backcolor_33 {
                    background-color: rgb(var(--color_33))
                }

                .backcolor_34 {
                    background-color: rgb(var(--color_34))
                }

                .backcolor_35 {
                    background-color: rgb(var(--color_35))
                }

                #SITE_CONTAINER.focus-ring-active :not(.has-custom-focus):not(.ignore-focus):focus, #SITE_CONTAINER.focus-ring-active :not(.has-custom-focus):not(.ignore-focus):focus ~ .wixSdkShowFocusOnSibling {
                    box-shadow: 0 0 0 1px #ffffff, 0 0 0 3px #116dff !important;
                    z-index: 999
                }

                [data-mesh-id=SITE_HEADERinlineContent] {
                    height: auto;
                    width: 100%
                }

                [data-mesh-id=SITE_HEADERinlineContent-gridContainer] {
                    position: static;
                    display: grid;
                    height: auto;
                    width: 100%;
                    min-height: auto;
                    grid-template-rows: 1fr;
                    grid-template-columns: 100%
                }

                [data-mesh-id=SITE_HEADERinlineContent-gridContainer] > [id="comp-kp0uk529"] {
                    position: relative;
                    margin: 35px 0px 36px calc((100% - 980px) * 0.5);
                    left: 810px;
                    grid-area: 1 / 1 / 2 / 2;
                    justify-self: start;
                    align-self: start
                }

                [data-mesh-id=SITE_FOOTERinlineContent] {
                    height: auto;
                    width: 100%;
                    position: static;
                    min-height: 132px
                }

                [data-mesh-id=SOSP_CONTAINER_CUSTOM_IDinlineContent] {
                    height: auto;
                    width: 980px
                }

                [data-mesh-id=SOSP_CONTAINER_CUSTOM_IDinlineContent-gridContainer] {
                    position: static;
                    display: grid;
                    height: auto;
                    width: 100%;
                    min-height: auto;
                    grid-template-rows: min-content 1fr;
                    grid-template-columns: 100%
                }

                [data-mesh-id=SOSP_CONTAINER_CUSTOM_IDinlineContent-gridContainer] > [id="comp-kp0uk773"] {
                    position: relative;
                    margin: 0px 0px 0 0;
                    left: 0px;
                    grid-area: 1 / 1 / 2 / 2;
                    justify-self: start;
                    align-self: start
                }

                [data-mesh-id=SOSP_CONTAINER_CUSTOM_IDinlineContent-gridContainer] > [id="comp-kp0uk9ob"] {
                    position: relative;
                    margin: 0px 0px 0px 0;
                    left: 12px;
                    grid-area: 2 / 1 / 3 / 2;
                    justify-self: start;
                    align-self: start
                }

                [id="soapAfterPagesContainer"].page-without-sosp [data-mesh-id=soapAfterPagesContainerinlineContent] {
                    height: auto;
                    width: 100%;
                    position: static;
                    min-height: auto;
                    padding-bottom: 0px;
                    box-sizing: border-box
                }

                [id="soapAfterPagesContainer"].page-without-sosp [data-mesh-id=soapAfterPagesContainerinlineContent-gridContainer] > [id="CONTROLLER_COMP_CUSTOM_ID"] {
                    position: absolute;
                    top: -96px;
                    left: 20px
                }

                [id="soapAfterPagesContainer"].page-with-sosp [data-mesh-id=soapAfterPagesContainerinlineContent] {
                    height: auto;
                    width: 100%
                }

                [id="soapAfterPagesContainer"].page-with-sosp [data-mesh-id=soapAfterPagesContainerinlineContent-gridContainer] {
                    position: static;
                    display: grid;
                    height: auto;
                    width: 100%;
                    min-height: auto;
                    grid-template-rows: 1fr;
                    grid-template-columns: 100%;
                    padding-bottom: 0px;
                    box-sizing: border-box
                }

                [id="soapAfterPagesContainer"].page-with-sosp [data-mesh-id=soapAfterPagesContainerinlineContent-gridContainer] > [id="CONTROLLER_COMP_CUSTOM_ID"] {
                    position: absolute;
                    top: -96px;
                    left: 20px
                }

                [id="soapAfterPagesContainer"].page-with-sosp [data-mesh-id=soapAfterPagesContainerinlineContent-gridContainer] > [id="SOSP_CONTAINER_CUSTOM_ID"] {
                    position: relative;
                    margin: 0px 0px 0 calc((100% - 980px) * 0.5);
                    left: 0px;
                    grid-area: 1 / 1 / 2 / 2;
                    justify-self: start;
                    align-self: start
                }

                #masterPage {
                    left: 0;
                    margin-left: 0;
                    width: 100%;
                    min-width: 980px
                }

                #SITE_HEADER {
                    left: 0;
                    margin-left: 0;
                    width: 100%;
                    min-width: 980px;
                    --pinned-layer-in-container:50;--above-all-in-container:49}

                #SITE_FOOTER {
                    left: 0;
                    margin-left: 0;
                    width: 100%;
                    min-width: 980px;
                    --pinned-layer-in-container:51;--above-all-in-container:49}

                #PAGES_CONTAINER {
                    left: 0;
                    margin-left: 0;
                    width: 100%;
                    min-width: 980px;
                    --pinned-layer-in-container:52;--above-all-in-container:49}

                #SOSP_CONTAINER_CUSTOM_ID {
                    width: 980px;
                    --pinned-layer-in-container:54;--above-all-in-container:49}

                #comp-kp0uk529 {
                    width: 120px;
                    height: 40px
                }

                #SITE_PAGES {
                    left: 0;
                    margin-left: 0;
                    width: 100%;
                    min-width: 980px
                }

                #comp-kp0uk773 {
                    width: 980px;
                    height: 250px
                }

                #comp-kp0uk9ob {
                    width: 956px;
                    height: 40px
                }

                #masterPage.landingPage #SITE_HEADER {
                    display: none
                }

                #masterPage.landingPage #SITE_FOOTER {
                    display: none
                }

                #masterPage.landingPage #CONTROLLER_COMP_CUSTOM_ID {
                    display: none
                }

                #masterPage.landingPage #SOSP_CONTAINER_CUSTOM_ID {
                    display: none
                }

                #masterPage.landingPage #SITE_HEADER-placeholder {
                    display: none
                }

                #masterPage.landingPage #SITE_FOOTER-placeholder {
                    display: none
                }

                #masterPage:not(.landingPage) #PAGES_CONTAINER {
                    margin-top: 0px;
                    margin-bottom: 0px
                }

                #CONTROLLER_COMP_CUSTOM_ID {
                    --pinned-layer-in-container:53;--above-all-in-container:49}

                @font-face {
                    font-display: block; font-family: "Proxima-N-W01-Reg";
                    src: url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/7e90123f-e4a7-4689-b41f-6bcfe331c00a.eot?#iefix");
                    src: url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/7e90123f-e4a7-4689-b41f-6bcfe331c00a.eot?#iefix") format("eot"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/64017d81-9430-4cba-8219-8f5cc28b923e.woff2") format("woff2"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/e56ecb6d-da41-4bd9-982d-2d295bec9ab0.woff") format("woff"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/2aff4f81-3e97-4a83-9e6c-45e33c024796.ttf") format("truetype"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/ab9cd062-380f-4b53-b1a7-c0bec7402235.svg#ab9cd062-380f-4b53-b1a7-c0bec7402235") format("svg");
                }

                @font-face {
                    font-display: block; font-family: "DIN-Next-W01-Light";
                    src: url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/3e0b2cd7-9657-438b-b4af-e04122e8f1f7.eot?#iefix");
                    src: url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/3e0b2cd7-9657-438b-b4af-e04122e8f1f7.eot?#iefix") format("eot"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/bc176270-17fa-4c78-a343-9fe52824e501.woff") format("woff"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/3516f91d-ac48-42cd-acfe-1be691152cc4.ttf") format("truetype"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/d1b1e866-a411-42ba-8f75-72bf28e23694.svg#d1b1e866-a411-42ba-8f75-72bf28e23694") format("svg");
                }

                @font-face {
                    font-display: block; font-family: "DIN-Next-W02-Light";
                    src: url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/48e5a0e1-2d56-46e5-8fc4-3d6d5c973cbf.eot?#iefix");
                    src: url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/48e5a0e1-2d56-46e5-8fc4-3d6d5c973cbf.eot?#iefix") format("eot"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/07d62b21-8d7a-4c36-be86-d32ab1089972.woff") format("woff"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/c0050890-bbed-44b9-94df-2611d72dbb06.ttf") format("truetype"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/9f774d17-c03a-418e-a375-34f3beecbc7a.svg#9f774d17-c03a-418e-a375-34f3beecbc7a") format("svg");
                }

                @font-face {
                    font-display: block; font-family: "DIN-Next-W10-Light";
                    src: url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/3d009cd7-c8fe-40c0-93da-74f4ea8c530b.eot?#iefix");
                    src: url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/3d009cd7-c8fe-40c0-93da-74f4ea8c530b.eot?#iefix") format("eot"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/a9e95a29-98a7-404a-90ee-1929ad09c696.woff") format("woff"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/0a7663fd-eae8-4e50-a67a-225271f8cceb.ttf") format("truetype"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/58ae9be9-5d95-44b6-8b6c-e6da6a46822c.svg#58ae9be9-5d95-44b6-8b6c-e6da6a46822c") format("svg");
                }

                @font-face {
                    font-display: block; font-family: "Futura-LT-W01-Book";
                    src: url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/cf053eae-ba1f-44f3-940c-a34b68ccbbdf.eot?#iefix");
                    src: url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/cf053eae-ba1f-44f3-940c-a34b68ccbbdf.eot?#iefix") format("eot"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/8bf38806-3423-4080-b38f-d08542f7e4ac.woff2") format("woff2"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/e2b9cbeb-fa8e-41cd-8a6a-46044b29ba52.woff") format("woff"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/c2a69697-4f06-4764-abd4-625031a84e31.ttf") format("truetype"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/dc423cc1-bf86-415c-bc7d-ad7dde416a34.svg#dc423cc1-bf86-415c-bc7d-ad7dde416a34") format("svg");
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 400;
                    src: local('Montserrat Italic'), local('Montserrat-Italic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUQjIg1_i6t8kCHKm459WxRxC7m0dR9pBOi.woff2) format('woff2');
                    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 400;
                    src: local('Montserrat Italic'), local('Montserrat-Italic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUQjIg1_i6t8kCHKm459WxRzS7m0dR9pBOi.woff2) format('woff2');
                    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 400;
                    src: local('Montserrat Italic'), local('Montserrat-Italic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUQjIg1_i6t8kCHKm459WxRxi7m0dR9pBOi.woff2) format('woff2');
                    unicode-range: U+0102-0103, U+0110-0111, U+1EA0-1EF9, U+20AB;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 400;
                    src: local('Montserrat Italic'), local('Montserrat-Italic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUQjIg1_i6t8kCHKm459WxRxy7m0dR9pBOi.woff2) format('woff2');
                    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 400;
                    src: local('Montserrat Italic'), local('Montserrat-Italic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUQjIg1_i6t8kCHKm459WxRyS7m0dR9pA.woff2) format('woff2');
                    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 700;
                    src: local('Montserrat Bold Italic'), local('Montserrat-BoldItalic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUPjIg1_i6t8kCHKm459WxZcgvz8fZwjimrq1Q_.woff2) format('woff2');
                    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 700;
                    src: local('Montserrat Bold Italic'), local('Montserrat-BoldItalic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUPjIg1_i6t8kCHKm459WxZcgvz-PZwjimrq1Q_.woff2) format('woff2');
                    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 700;
                    src: local('Montserrat Bold Italic'), local('Montserrat-BoldItalic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUPjIg1_i6t8kCHKm459WxZcgvz8_Zwjimrq1Q_.woff2) format('woff2');
                    unicode-range: U+0102-0103, U+0110-0111, U+1EA0-1EF9, U+20AB;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 700;
                    src: local('Montserrat Bold Italic'), local('Montserrat-BoldItalic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUPjIg1_i6t8kCHKm459WxZcgvz8vZwjimrq1Q_.woff2) format('woff2');
                    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 700;
                    src: local('Montserrat Bold Italic'), local('Montserrat-BoldItalic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUPjIg1_i6t8kCHKm459WxZcgvz_PZwjimrqw.woff2) format('woff2');
                    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 400;
                    src: local('Montserrat Regular'), local('Montserrat-Regular'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUSjIg1_i6t8kCHKm459WRhyyTh89ZNpQ.woff2) format('woff2');
                    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 400;
                    src: local('Montserrat Regular'), local('Montserrat-Regular'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUSjIg1_i6t8kCHKm459W1hyyTh89ZNpQ.woff2) format('woff2');
                    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 400;
                    src: local('Montserrat Regular'), local('Montserrat-Regular'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUSjIg1_i6t8kCHKm459WZhyyTh89ZNpQ.woff2) format('woff2');
                    unicode-range: U+0102-0103, U+0110-0111, U+1EA0-1EF9, U+20AB;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 400;
                    src: local('Montserrat Regular'), local('Montserrat-Regular'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUSjIg1_i6t8kCHKm459WdhyyTh89ZNpQ.woff2) format('woff2');
                    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 400;
                    src: local('Montserrat Regular'), local('Montserrat-Regular'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUSjIg1_i6t8kCHKm459WlhyyTh89Y.woff2) format('woff2');
                    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 700;
                    src: local('Montserrat Bold'), local('Montserrat-Bold'), url(https://fonts.gstatic.com/s/montserrat/v14/JTURjIg1_i6t8kCHKm45_dJE3gTD_vx3rCubqg.woff2) format('woff2');
                    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 700;
                    src: local('Montserrat Bold'), local('Montserrat-Bold'), url(https://fonts.gstatic.com/s/montserrat/v14/JTURjIg1_i6t8kCHKm45_dJE3g3D_vx3rCubqg.woff2) format('woff2');
                    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 700;
                    src: local('Montserrat Bold'), local('Montserrat-Bold'), url(https://fonts.gstatic.com/s/montserrat/v14/JTURjIg1_i6t8kCHKm45_dJE3gbD_vx3rCubqg.woff2) format('woff2');
                    unicode-range: U+0102-0103, U+0110-0111, U+1EA0-1EF9, U+20AB;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 700;
                    src: local('Montserrat Bold'), local('Montserrat-Bold'), url(https://fonts.gstatic.com/s/montserrat/v14/JTURjIg1_i6t8kCHKm45_dJE3gfD_vx3rCubqg.woff2) format('woff2');
                    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 700;
                    src: local('Montserrat Bold'), local('Montserrat-Bold'), url(https://fonts.gstatic.com/s/montserrat/v14/JTURjIg1_i6t8kCHKm45_dJE3gnD_vx3rCs.woff2) format('woff2');
                    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
                }

                @font-face {
                    font-display: block; font-family: "Poppins-ExtraLight";
                    src: url("//fonts.gstatic.com/s/poppins/v5/h3r77AwDsldr1E_2g4qqGFQlYEbsez9cZjKsNMjLOwM.eot?#iefix");
                    src: url("//fonts.gstatic.com/s/poppins/v5/h3r77AwDsldr1E_2g4qqGFQlYEbsez9cZjKsNMjLOwM.eot?#iefix") format("eot"), url("//fonts.gstatic.com/s/poppins/v5/h3r77AwDsldr1E_2g4qqGPk_vArhqVIZ0nv9q090hN8.woff2") format("woff2"), url("//fonts.gstatic.com/s/poppins/v5/h3r77AwDsldr1E_2g4qqGBsxEYwM7FgeyaSgU71cLG0.woff") format("woff"), url("//fonts.gstatic.com/s/poppins/v5/h3r77AwDsldr1E_2g4qqGC3USBnSvpkopQaUR-2r7iU.ttf") format("truetype"), url("//fonts.gstatic.com/l/font?kit=h3r77AwDsldr1E_2g4qqGKWUboTb-jS2tyCOQMtm97g&skey=1bdc08fe61c3cc9e&v=v5#Poppins") format("svg");
                }

                @font-face {
                    font-display: block; font-family: "Poppins-ExtraLight";
                    font-weight: 700;
                    src: url("//fonts.gstatic.com/s/poppins/v5/2NBlOVek2HIa2EeuV_3Cbw.eot?#iefix");
                    src: url("//fonts.gstatic.com/s/poppins/v5/2NBlOVek2HIa2EeuV_3Cbw.eot?#iefix") format("eot"), url("//fonts.gstatic.com/s/poppins/v5/rijG6I_IOXJjsH07UEo2mw.woff2") format("woff2"), url("//fonts.gstatic.com/s/poppins/v5/p0A1C4_gK5NzKtuGSwNurQ.woff") format("woff"), url("//fonts.gstatic.com/s/poppins/v5/rATt6MpBkxjRr3sy5fMEDg.ttf") format("truetype"), url("//fonts.gstatic.com/l/font?kit=dvQ6luzB0ViWP07p6fisSw&skey=87759fb096548f6d&v=v5#Poppins") format("svg");
                }

                @font-face {
                    font-display: block; font-family: "Poppins-ExtraLight";
                    font-style: italic;
                    src: url("//fonts.gstatic.com/s/poppins/v5/-GlaWpWcSgdVagNuOGuFKalSqKUsDpiXlwfj-ZM2w_A.eot?#iefix");
                    src: url("//fonts.gstatic.com/s/poppins/v5/-GlaWpWcSgdVagNuOGuFKalSqKUsDpiXlwfj-ZM2w_A.eot?#iefix") format("eot"), url("//fonts.gstatic.com/s/poppins/v5/-GlaWpWcSgdVagNuOGuFKRUOjZSKWg4xBWp_C_qQx0o.woff2") format("woff2"), url("//fonts.gstatic.com/s/poppins/v5/-GlaWpWcSgdVagNuOGuFKRa1RVmPjeKy21_GQJaLlJI.woff") format("woff"), url("//fonts.gstatic.com/s/poppins/v5/-GlaWpWcSgdVagNuOGuFKdqQynqKV_9Plp7mupa0S4g.ttf") format("truetype"), url("//fonts.gstatic.com/l/font?kit=-GlaWpWcSgdVagNuOGuFKd1LKoZ82bBu2f46DhHcs3c&skey=e6f64e60fb8d9268&v=v5#Poppins") format("svg");
                }

                @font-face {
                    font-display: block; font-family: "Poppins-ExtraLight";
                    font-weight: 700;
                    font-style: italic;
                    src: url("//fonts.gstatic.com/s/poppins/v5/Fm41upUVp7KTKUZhL0PfQfY6323mHUZFJMgTvxaG2iE.eot?#iefix");
                    src: url("//fonts.gstatic.com/s/poppins/v5/Fm41upUVp7KTKUZhL0PfQfY6323mHUZFJMgTvxaG2iE.eot?#iefix") format("eot"), url("//fonts.gstatic.com/s/poppins/v5/Fm41upUVp7KTKUZhL0PfQVtXRa8TVwTICgirnJhmVJw.woff2") format("woff2"), url("//fonts.gstatic.com/s/poppins/v5/Fm41upUVp7KTKUZhL0PfQT8E0i7KZn-EPnyo3HZu7kw.woff") format("woff"), url("//fonts.gstatic.com/s/poppins/v5/Fm41upUVp7KTKUZhL0PfQaCWcynf_cDxXwCLxiixG1c.ttf") format("truetype"), url("//fonts.gstatic.com/l/font?kit=Fm41upUVp7KTKUZhL0PfQZbd9NUM7myrQQz30yPaGQ4&skey=f21d6e783fa43c88&v=v5#Poppins") format("svg");
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: italic;
                    font-weight: 400;
                    src: local('Poppins Italic'), local('Poppins-Italic'), url(https://fonts.gstatic.com/s/poppins/v9/pxiGyp8kv8JHgFVrJJLucXtAOvWDSHFF.woff2) format('woff2');
                    unicode-range: U+0900-097F, U+1CD0-1CF6, U+1CF8-1CF9, U+200C-200D, U+20A8, U+20B9, U+25CC, U+A830-A839, U+A8E0-A8FB;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: italic;
                    font-weight: 400;
                    src: local('Poppins Italic'), local('Poppins-Italic'), url(https://fonts.gstatic.com/s/poppins/v9/pxiGyp8kv8JHgFVrJJLufntAOvWDSHFF.woff2) format('woff2');
                    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: italic;
                    font-weight: 400;
                    src: local('Poppins Italic'), local('Poppins-Italic'), url(https://fonts.gstatic.com/s/poppins/v9/pxiGyp8kv8JHgFVrJJLucHtAOvWDSA.woff2) format('woff2');
                    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: italic;
                    font-weight: 700;
                    src: local('Poppins Bold Italic'), local('Poppins-BoldItalic'), url(https://fonts.gstatic.com/s/poppins/v9/pxiDyp8kv8JHgFVrJJLmy15VFteOYktMqlap.woff2) format('woff2');
                    unicode-range: U+0900-097F, U+1CD0-1CF6, U+1CF8-1CF9, U+200C-200D, U+20A8, U+20B9, U+25CC, U+A830-A839, U+A8E0-A8FB;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: italic;
                    font-weight: 700;
                    src: local('Poppins Bold Italic'), local('Poppins-BoldItalic'), url(https://fonts.gstatic.com/s/poppins/v9/pxiDyp8kv8JHgFVrJJLmy15VGdeOYktMqlap.woff2) format('woff2');
                    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: italic;
                    font-weight: 700;
                    src: local('Poppins Bold Italic'), local('Poppins-BoldItalic'), url(https://fonts.gstatic.com/s/poppins/v9/pxiDyp8kv8JHgFVrJJLmy15VF9eOYktMqg.woff2) format('woff2');
                    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: normal;
                    font-weight: 400;
                    src: local('Poppins Regular'), local('Poppins-Regular'), url(https://fonts.gstatic.com/s/poppins/v9/pxiEyp8kv8JHgFVrJJbecnFHGPezSQ.woff2) format('woff2');
                    unicode-range: U+0900-097F, U+1CD0-1CF6, U+1CF8-1CF9, U+200C-200D, U+20A8, U+20B9, U+25CC, U+A830-A839, U+A8E0-A8FB;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: normal;
                    font-weight: 400;
                    src: local('Poppins Regular'), local('Poppins-Regular'), url(https://fonts.gstatic.com/s/poppins/v9/pxiEyp8kv8JHgFVrJJnecnFHGPezSQ.woff2) format('woff2');
                    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: normal;
                    font-weight: 400;
                    src: local('Poppins Regular'), local('Poppins-Regular'), url(https://fonts.gstatic.com/s/poppins/v9/pxiEyp8kv8JHgFVrJJfecnFHGPc.woff2) format('woff2');
                    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: normal;
                    font-weight: 700;
                    src: local('Poppins Bold'), local('Poppins-Bold'), url(https://fonts.gstatic.com/s/poppins/v9/pxiByp8kv8JHgFVrLCz7Z11lFd2JQEl8qw.woff2) format('woff2');
                    unicode-range: U+0900-097F, U+1CD0-1CF6, U+1CF8-1CF9, U+200C-200D, U+20A8, U+20B9, U+25CC, U+A830-A839, U+A8E0-A8FB;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: normal;
                    font-weight: 700;
                    src: local('Poppins Bold'), local('Poppins-Bold'), url(https://fonts.gstatic.com/s/poppins/v9/pxiByp8kv8JHgFVrLCz7Z1JlFd2JQEl8qw.woff2) format('woff2');
                    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: normal;
                    font-weight: 700;
                    src: local('Poppins Bold'), local('Poppins-Bold'), url(https://fonts.gstatic.com/s/poppins/v9/pxiByp8kv8JHgFVrLCz7Z1xlFd2JQEk.woff2) format('woff2');
                    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
                }

                #CONTROLLER_COMP_CUSTOM_ID {
                    --alpha-bg:1;--alpha -bgh: 1;
                    --alpha - brd: 1;
                    --alpha - brdh: 1;
                    --alpha - txt: 1;
                    --alpha - txth: 1;
                    --bg:61,155,233;--bgh:43,104,156;--alpha-bgh:1;--boxShadowToggleOn -shd: none;
                    --brd:43,104,156;--alpha-brd:1;--brdh:61,155,233;--alpha-brdh:1;--brw:0px;--fnt:normal normal normal 14px/1.4em raleway;--rd:20px;--shd:0 1px 4px rgba(0, 0, 0, 0.6);;--txt:255,255,255;--alpha-txt:1;--txth:255,255,255;--alpha-txth:1 }

                #SOSP_CONTAINER_CUSTOM_ID {
                    --brw:0px;--brd:var(--color_15);--bg:var(--color_11);--rd:0px;--shd:none;--alpha-bg:1;--alpha-brd:1;--boxShadowToggleOn-shd:none;--shc-mutated-brightness:128,128,128 }

                #comp-kp0uk529 {
                    --bg:0,0,0;--alpha-bg:0;--brw:0px;--brd:var(--color_15);--rd:0px;--shd:none;--bg-dd:var(--color_11);--alpha-bg-dd:1;--brw-dd:1px;--brd-dd:var(--color_15);--rd-dd:0px;--shd-dd:none;--fnt:var(--font_8);--fnt-size-dd:15px;--txt-dd:var(--color_15);--alpha-txt-dd:1;--txt-slct-dd:var(--color_18);--alpha-txt-slct-dd:1;--txth-dd:var(--color_14);--alpha-txth-dd:1;--txth:var(--color_17);--alpha-txth:1;--txt:var(--color_18);--alpha-txt:1;--badge-bg:226,28,33;--alpha-badge-bg:1;--badge-txt:var(--color_11);--alpha-badge-txt:1;--fillcolor:var(--color_18);--alpha-fillcolor:1;--alpha-brd:1;--alpha-brd-dd:0.2;--boxShadowToggleOn-shd:none;--boxShadowToggleOn-shd-dd:none;justify-content: flex-end;
                    direction: ltr;
                    --icon-size:26px }

                #SITE_PAGES {
                    --transition-duration:700ms }

                #comp-kp0uk9ob {
                    --menuTotalBordersX:0px;--menuTotalBordersY:0px;--bgDrop:var(--color_11);--rd:0px;--shd:0px 1px 4px 0px rgba(0,0,0,0.2);--pad:10px;--fnt:var(--font_8);--brd:var(--color_15);--txt:var(--color_15);--alpha-txt:1;--brdh:var(--color_17);--txth:var(--color_17);--alpha-txth:1;--brds:var(--color_18);--txts:var(--color_18);--alpha-txts:1;--alpha-bgDrop:1;--alpha-brdh:1;--alpha-brd:0;--alpha-brds:1;--bg:var(--color_11);--alpha-bg:1 }

                #BACKGROUND_GROUP {
                    --transition-duration:700ms }
            </style>
            <style id="css_b5oae">
                [data-mesh-id=Containerb5oaeinlineContent] {
                    height: auto;
                    width: 100%
                }

                [data-mesh-id=Containerb5oaeinlineContent-gridContainer] {
                    position: static;
                    display: grid;
                    height: auto;
                    width: 100%;
                    min-height: 500px;
                    grid-template-rows: min-content min-content min-content min-content min-content 1fr;
                    grid-template-columns: 100%;
                    padding-bottom: 0px;
                    box-sizing: border-box
                }

                [data-mesh-id=Containerb5oaeinlineContent-gridContainer] > [id="comp-kp0y6g30"] {
                    position: relative;
                    margin: 335px 0px 0 calc((100% - 980px) * 0.5);
                    left: 132px;
                    grid-area: 1 / 1 / 2 / 2;
                    justify-self: start;
                    align-self: start
                }

                [data-mesh-id=Containerb5oaeinlineContent-gridContainer] > [id="comp-kp0y6opj"] {
                    position: relative;
                    margin: 0px 0px 1px calc((100% - 980px) * 0.5);
                    left: 132px;
                    grid-area: 2 / 1 / 3 / 2;
                    justify-self: start;
                    align-self: start
                }

                [data-mesh-id=Containerb5oaeinlineContent-gridContainer] > [id="comp-kp0y8x0p"] {
                    position: relative;
                    margin: 0px 0px 0 calc((100% - 980px) * 0.5);
                    left: 132px;
                    grid-area: 3 / 1 / 4 / 2;
                    justify-self: start;
                    align-self: start
                }

                [data-mesh-id=Containerb5oaeinlineContent-gridContainer] > [id="comp-kp0y8x17"] {
                    position: relative;
                    margin: 0px 0px 0 calc((100% - 980px) * 0.5);
                    left: 132px;
                    grid-area: 4 / 1 / 5 / 2;
                    justify-self: start;
                    align-self: start
                }

                [data-mesh-id=Containerb5oaeinlineContent-gridContainer] > [id="comp-kp0y94pd"] {
                    position: relative;
                    margin: 0px 0px 0 calc((100% - 980px) * 0.5);
                    left: 132px;
                    grid-area: 5 / 1 / 6 / 2;
                    justify-self: start;
                    align-self: start
                }

                [data-mesh-id=Containerb5oaeinlineContent-gridContainer] > [id="comp-kp0y94px"] {
                    position: relative;
                    margin: 0px 0px 0 calc((100% - 980px) * 0.5);
                    left: 132px;
                    grid-area: 6 / 1 / 7 / 2;
                    justify-self: start;
                    align-self: start
                }

                #b5oae {
                    left: 0;
                    margin-left: 0;
                    width: 100%;
                    min-width: 980px
                }

                #comp-kp0y6g30 {
                    width: 670px;
                    height: 76px
                }

                #comp-kp0y6opj {
                    width: 670px;
                    height: 76px
                }

                #comp-kp0y8x0p {
                    width: 670px;
                    height: 76px
                }

                #comp-kp0y8x17 {
                    width: 670px;
                    height: 76px
                }

                #comp-kp0y94pd {
                    width: 670px;
                    height: 76px
                }

                #comp-kp0y94px {
                    width: 670px;
                    height: 76px
                }

                #masterPage {
                    --pinned-layers-in-page:0}

                @font-face {
                    font-display: block; font-family: "Futura-LT-W01-Book";
                    src: url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/cf053eae-ba1f-44f3-940c-a34b68ccbbdf.eot?#iefix");
                    src: url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/cf053eae-ba1f-44f3-940c-a34b68ccbbdf.eot?#iefix") format("eot"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/8bf38806-3423-4080-b38f-d08542f7e4ac.woff2") format("woff2"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/e2b9cbeb-fa8e-41cd-8a6a-46044b29ba52.woff") format("woff"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/c2a69697-4f06-4764-abd4-625031a84e31.ttf") format("truetype"),url("//static.parastorage.com/services/third-party/fonts/user-site-fonts/fonts/dc423cc1-bf86-415c-bc7d-ad7dde416a34.svg#dc423cc1-bf86-415c-bc7d-ad7dde416a34") format("svg");
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 400;
                    src: local('Montserrat Italic'), local('Montserrat-Italic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUQjIg1_i6t8kCHKm459WxRxC7m0dR9pBOi.woff2) format('woff2');
                    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 400;
                    src: local('Montserrat Italic'), local('Montserrat-Italic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUQjIg1_i6t8kCHKm459WxRzS7m0dR9pBOi.woff2) format('woff2');
                    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 400;
                    src: local('Montserrat Italic'), local('Montserrat-Italic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUQjIg1_i6t8kCHKm459WxRxi7m0dR9pBOi.woff2) format('woff2');
                    unicode-range: U+0102-0103, U+0110-0111, U+1EA0-1EF9, U+20AB;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 400;
                    src: local('Montserrat Italic'), local('Montserrat-Italic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUQjIg1_i6t8kCHKm459WxRxy7m0dR9pBOi.woff2) format('woff2');
                    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 400;
                    src: local('Montserrat Italic'), local('Montserrat-Italic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUQjIg1_i6t8kCHKm459WxRyS7m0dR9pA.woff2) format('woff2');
                    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 700;
                    src: local('Montserrat Bold Italic'), local('Montserrat-BoldItalic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUPjIg1_i6t8kCHKm459WxZcgvz8fZwjimrq1Q_.woff2) format('woff2');
                    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 700;
                    src: local('Montserrat Bold Italic'), local('Montserrat-BoldItalic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUPjIg1_i6t8kCHKm459WxZcgvz-PZwjimrq1Q_.woff2) format('woff2');
                    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 700;
                    src: local('Montserrat Bold Italic'), local('Montserrat-BoldItalic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUPjIg1_i6t8kCHKm459WxZcgvz8_Zwjimrq1Q_.woff2) format('woff2');
                    unicode-range: U+0102-0103, U+0110-0111, U+1EA0-1EF9, U+20AB;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 700;
                    src: local('Montserrat Bold Italic'), local('Montserrat-BoldItalic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUPjIg1_i6t8kCHKm459WxZcgvz8vZwjimrq1Q_.woff2) format('woff2');
                    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: italic;
                    font-weight: 700;
                    src: local('Montserrat Bold Italic'), local('Montserrat-BoldItalic'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUPjIg1_i6t8kCHKm459WxZcgvz_PZwjimrqw.woff2) format('woff2');
                    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 400;
                    src: local('Montserrat Regular'), local('Montserrat-Regular'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUSjIg1_i6t8kCHKm459WRhyyTh89ZNpQ.woff2) format('woff2');
                    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 400;
                    src: local('Montserrat Regular'), local('Montserrat-Regular'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUSjIg1_i6t8kCHKm459W1hyyTh89ZNpQ.woff2) format('woff2');
                    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 400;
                    src: local('Montserrat Regular'), local('Montserrat-Regular'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUSjIg1_i6t8kCHKm459WZhyyTh89ZNpQ.woff2) format('woff2');
                    unicode-range: U+0102-0103, U+0110-0111, U+1EA0-1EF9, U+20AB;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 400;
                    src: local('Montserrat Regular'), local('Montserrat-Regular'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUSjIg1_i6t8kCHKm459WdhyyTh89ZNpQ.woff2) format('woff2');
                    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 400;
                    src: local('Montserrat Regular'), local('Montserrat-Regular'), url(https://fonts.gstatic.com/s/montserrat/v14/JTUSjIg1_i6t8kCHKm459WlhyyTh89Y.woff2) format('woff2');
                    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 700;
                    src: local('Montserrat Bold'), local('Montserrat-Bold'), url(https://fonts.gstatic.com/s/montserrat/v14/JTURjIg1_i6t8kCHKm45_dJE3gTD_vx3rCubqg.woff2) format('woff2');
                    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 700;
                    src: local('Montserrat Bold'), local('Montserrat-Bold'), url(https://fonts.gstatic.com/s/montserrat/v14/JTURjIg1_i6t8kCHKm45_dJE3g3D_vx3rCubqg.woff2) format('woff2');
                    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 700;
                    src: local('Montserrat Bold'), local('Montserrat-Bold'), url(https://fonts.gstatic.com/s/montserrat/v14/JTURjIg1_i6t8kCHKm45_dJE3gbD_vx3rCubqg.woff2) format('woff2');
                    unicode-range: U+0102-0103, U+0110-0111, U+1EA0-1EF9, U+20AB;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 700;
                    src: local('Montserrat Bold'), local('Montserrat-Bold'), url(https://fonts.gstatic.com/s/montserrat/v14/JTURjIg1_i6t8kCHKm45_dJE3gfD_vx3rCubqg.woff2) format('woff2');
                    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
                }

                @font-face {
                    font-display: block; font-family: 'Montserrat';
                    font-style: normal;
                    font-weight: 700;
                    src: local('Montserrat Bold'), local('Montserrat-Bold'), url(https://fonts.gstatic.com/s/montserrat/v14/JTURjIg1_i6t8kCHKm45_dJE3gnD_vx3rCs.woff2) format('woff2');
                    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
                }

                @font-face {
                    font-display: block; font-family: "Poppins-ExtraLight";
                    src: url("//fonts.gstatic.com/s/poppins/v5/h3r77AwDsldr1E_2g4qqGFQlYEbsez9cZjKsNMjLOwM.eot?#iefix");
                    src: url("//fonts.gstatic.com/s/poppins/v5/h3r77AwDsldr1E_2g4qqGFQlYEbsez9cZjKsNMjLOwM.eot?#iefix") format("eot"), url("//fonts.gstatic.com/s/poppins/v5/h3r77AwDsldr1E_2g4qqGPk_vArhqVIZ0nv9q090hN8.woff2") format("woff2"), url("//fonts.gstatic.com/s/poppins/v5/h3r77AwDsldr1E_2g4qqGBsxEYwM7FgeyaSgU71cLG0.woff") format("woff"), url("//fonts.gstatic.com/s/poppins/v5/h3r77AwDsldr1E_2g4qqGC3USBnSvpkopQaUR-2r7iU.ttf") format("truetype"), url("//fonts.gstatic.com/l/font?kit=h3r77AwDsldr1E_2g4qqGKWUboTb-jS2tyCOQMtm97g&skey=1bdc08fe61c3cc9e&v=v5#Poppins") format("svg");
                }

                @font-face {
                    font-display: block; font-family: "Poppins-ExtraLight";
                    font-weight: 700;
                    src: url("//fonts.gstatic.com/s/poppins/v5/2NBlOVek2HIa2EeuV_3Cbw.eot?#iefix");
                    src: url("//fonts.gstatic.com/s/poppins/v5/2NBlOVek2HIa2EeuV_3Cbw.eot?#iefix") format("eot"), url("//fonts.gstatic.com/s/poppins/v5/rijG6I_IOXJjsH07UEo2mw.woff2") format("woff2"), url("//fonts.gstatic.com/s/poppins/v5/p0A1C4_gK5NzKtuGSwNurQ.woff") format("woff"), url("//fonts.gstatic.com/s/poppins/v5/rATt6MpBkxjRr3sy5fMEDg.ttf") format("truetype"), url("//fonts.gstatic.com/l/font?kit=dvQ6luzB0ViWP07p6fisSw&skey=87759fb096548f6d&v=v5#Poppins") format("svg");
                }

                @font-face {
                    font-display: block; font-family: "Poppins-ExtraLight";
                    font-style: italic;
                    src: url("//fonts.gstatic.com/s/poppins/v5/-GlaWpWcSgdVagNuOGuFKalSqKUsDpiXlwfj-ZM2w_A.eot?#iefix");
                    src: url("//fonts.gstatic.com/s/poppins/v5/-GlaWpWcSgdVagNuOGuFKalSqKUsDpiXlwfj-ZM2w_A.eot?#iefix") format("eot"), url("//fonts.gstatic.com/s/poppins/v5/-GlaWpWcSgdVagNuOGuFKRUOjZSKWg4xBWp_C_qQx0o.woff2") format("woff2"), url("//fonts.gstatic.com/s/poppins/v5/-GlaWpWcSgdVagNuOGuFKRa1RVmPjeKy21_GQJaLlJI.woff") format("woff"), url("//fonts.gstatic.com/s/poppins/v5/-GlaWpWcSgdVagNuOGuFKdqQynqKV_9Plp7mupa0S4g.ttf") format("truetype"), url("//fonts.gstatic.com/l/font?kit=-GlaWpWcSgdVagNuOGuFKd1LKoZ82bBu2f46DhHcs3c&skey=e6f64e60fb8d9268&v=v5#Poppins") format("svg");
                }

                @font-face {
                    font-display: block; font-family: "Poppins-ExtraLight";
                    font-weight: 700;
                    font-style: italic;
                    src: url("//fonts.gstatic.com/s/poppins/v5/Fm41upUVp7KTKUZhL0PfQfY6323mHUZFJMgTvxaG2iE.eot?#iefix");
                    src: url("//fonts.gstatic.com/s/poppins/v5/Fm41upUVp7KTKUZhL0PfQfY6323mHUZFJMgTvxaG2iE.eot?#iefix") format("eot"), url("//fonts.gstatic.com/s/poppins/v5/Fm41upUVp7KTKUZhL0PfQVtXRa8TVwTICgirnJhmVJw.woff2") format("woff2"), url("//fonts.gstatic.com/s/poppins/v5/Fm41upUVp7KTKUZhL0PfQT8E0i7KZn-EPnyo3HZu7kw.woff") format("woff"), url("//fonts.gstatic.com/s/poppins/v5/Fm41upUVp7KTKUZhL0PfQaCWcynf_cDxXwCLxiixG1c.ttf") format("truetype"), url("//fonts.gstatic.com/l/font?kit=Fm41upUVp7KTKUZhL0PfQZbd9NUM7myrQQz30yPaGQ4&skey=f21d6e783fa43c88&v=v5#Poppins") format("svg");
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: italic;
                    font-weight: 400;
                    src: local('Poppins Italic'), local('Poppins-Italic'), url(https://fonts.gstatic.com/s/poppins/v9/pxiGyp8kv8JHgFVrJJLucXtAOvWDSHFF.woff2) format('woff2');
                    unicode-range: U+0900-097F, U+1CD0-1CF6, U+1CF8-1CF9, U+200C-200D, U+20A8, U+20B9, U+25CC, U+A830-A839, U+A8E0-A8FB;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: italic;
                    font-weight: 400;
                    src: local('Poppins Italic'), local('Poppins-Italic'), url(https://fonts.gstatic.com/s/poppins/v9/pxiGyp8kv8JHgFVrJJLufntAOvWDSHFF.woff2) format('woff2');
                    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: italic;
                    font-weight: 400;
                    src: local('Poppins Italic'), local('Poppins-Italic'), url(https://fonts.gstatic.com/s/poppins/v9/pxiGyp8kv8JHgFVrJJLucHtAOvWDSA.woff2) format('woff2');
                    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: italic;
                    font-weight: 700;
                    src: local('Poppins Bold Italic'), local('Poppins-BoldItalic'), url(https://fonts.gstatic.com/s/poppins/v9/pxiDyp8kv8JHgFVrJJLmy15VFteOYktMqlap.woff2) format('woff2');
                    unicode-range: U+0900-097F, U+1CD0-1CF6, U+1CF8-1CF9, U+200C-200D, U+20A8, U+20B9, U+25CC, U+A830-A839, U+A8E0-A8FB;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: italic;
                    font-weight: 700;
                    src: local('Poppins Bold Italic'), local('Poppins-BoldItalic'), url(https://fonts.gstatic.com/s/poppins/v9/pxiDyp8kv8JHgFVrJJLmy15VGdeOYktMqlap.woff2) format('woff2');
                    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: italic;
                    font-weight: 700;
                    src: local('Poppins Bold Italic'), local('Poppins-BoldItalic'), url(https://fonts.gstatic.com/s/poppins/v9/pxiDyp8kv8JHgFVrJJLmy15VF9eOYktMqg.woff2) format('woff2');
                    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: normal;
                    font-weight: 400;
                    src: local('Poppins Regular'), local('Poppins-Regular'), url(https://fonts.gstatic.com/s/poppins/v9/pxiEyp8kv8JHgFVrJJbecnFHGPezSQ.woff2) format('woff2');
                    unicode-range: U+0900-097F, U+1CD0-1CF6, U+1CF8-1CF9, U+200C-200D, U+20A8, U+20B9, U+25CC, U+A830-A839, U+A8E0-A8FB;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: normal;
                    font-weight: 400;
                    src: local('Poppins Regular'), local('Poppins-Regular'), url(https://fonts.gstatic.com/s/poppins/v9/pxiEyp8kv8JHgFVrJJnecnFHGPezSQ.woff2) format('woff2');
                    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: normal;
                    font-weight: 400;
                    src: local('Poppins Regular'), local('Poppins-Regular'), url(https://fonts.gstatic.com/s/poppins/v9/pxiEyp8kv8JHgFVrJJfecnFHGPc.woff2) format('woff2');
                    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: normal;
                    font-weight: 700;
                    src: local('Poppins Bold'), local('Poppins-Bold'), url(https://fonts.gstatic.com/s/poppins/v9/pxiByp8kv8JHgFVrLCz7Z11lFd2JQEl8qw.woff2) format('woff2');
                    unicode-range: U+0900-097F, U+1CD0-1CF6, U+1CF8-1CF9, U+200C-200D, U+20A8, U+20B9, U+25CC, U+A830-A839, U+A8E0-A8FB;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: normal;
                    font-weight: 700;
                    src: local('Poppins Bold'), local('Poppins-Bold'), url(https://fonts.gstatic.com/s/poppins/v9/pxiByp8kv8JHgFVrLCz7Z1JlFd2JQEl8qw.woff2) format('woff2');
                    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
                }

                @font-face {
                    font-display: block; font-family: 'Poppins';
                    font-style: normal;
                    font-weight: 700;
                    src: local('Poppins Bold'), local('Poppins-Bold'), url(https://fonts.gstatic.com/s/poppins/v9/pxiByp8kv8JHgFVrLCz7Z1xlFd2JQEk.woff2) format('woff2');
                    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
                }

                #b5oae {
                    width: auto;
                    min-height: 500px
                }

                #pageBackground_b5oae {
                    --bg-position:absolute;--bg-overlay-color:rgb(var(--color_35));--fill-layer-image-opacity:1 }

                /* END STYLABLE DIRECTIVE RULES */
                #comp-kp0y6g30 .style-kp0y6g40__root:hover .StylableButton1872886392__icon {
                    fill: #FFFFFF;
                }

                /* START STYLABLE DIRECTIVE RULES */
                #comp-kp0y6g30 .style-kp0y6g40__root {
                    -st-extends: StylableButton;
                    transition: all 0.2s ease, visibility 0s;
                    border: 1px solid #384AD3;
                    background: rgba(255, 255, 255, 0)
                }

                #comp-kp0y6g30 .style-kp0y6g40__root:hover {
                    background: #384AD3;
                }

                #comp-kp0y6g30 .style-kp0y6g40__root:hover .StylableButton1872886392__label {
                    color: #FFFFFF;
                }

                #comp-kp0y6g30 .style-kp0y6g40__root:disabled {
                    background: #E2E2E2
                }

                #comp-kp0y6g30 .style-kp0y6g40__root:disabled .StylableButton1872886392__label {
                    color: #8F8F8F
                }

                #comp-kp0y6g30 .style-kp0y6g40__root:disabled .StylableButton1872886392__icon {
                    fill: #8F8F8F
                }

                #comp-kp0y6g30 .style-kp0y6g40__root .StylableButton1872886392__container {
                    transition: inherit
                }

                #comp-kp0y6g30 .style-kp0y6g40__root .StylableButton1872886392__label {
                    transition: inherit;
                    font-size: 14px;
                    letter-spacing: 0.1em;
                    color: #384AD3;
                    font-family: poppins-extralight,poppins,sans-serif;
                    font-family: proxima-n-w01-reg,sans-serif;
                    font-size: 14px;
                    font-weight: normal;
                    font-style: normal;
                    margin: 0px 2px 0px 0px;
                    display: none
                }

                #comp-kp0y6g30 .style-kp0y6g40__root .StylableButton1872886392__icon {
                    transition: inherit;
                    display: initial;
                    fill: #384AD3;
                    margin: 0px 0px 0px 2px;
                    width: 12px;
                    height: 12px;
                }

                /* END STYLABLE DIRECTIVE RULES */
                #comp-kp0y6opj .style-kp0y6oqu__root:hover .StylableButton1872886392__icon {
                    fill: #FFFFFF;
                }

                /* START STYLABLE DIRECTIVE RULES */
                #comp-kp0y6opj .style-kp0y6oqu__root {
                    -st-extends: StylableButton;
                    transition: all 0.2s ease, visibility 0s;
                    border: 1px solid #384AD3;
                    background: rgba(255, 255, 255, 0)
                }

                #comp-kp0y6opj .style-kp0y6oqu__root:hover {
                    background: #384AD3;
                }

                #comp-kp0y6opj .style-kp0y6oqu__root:hover .StylableButton1872886392__label {
                    color: #FFFFFF;
                }

                #comp-kp0y6opj .style-kp0y6oqu__root:disabled {
                    background: #E2E2E2
                }

                #comp-kp0y6opj .style-kp0y6oqu__root:disabled .StylableButton1872886392__label {
                    color: #8F8F8F
                }

                #comp-kp0y6opj .style-kp0y6oqu__root:disabled .StylableButton1872886392__icon {
                    fill: #8F8F8F
                }

                #comp-kp0y6opj .style-kp0y6oqu__root .StylableButton1872886392__container {
                    transition: inherit
                }

                #comp-kp0y6opj .style-kp0y6oqu__root .StylableButton1872886392__label {
                    transition: inherit;
                    font-size: 14px;
                    letter-spacing: 0.1em;
                    color: #384AD3;
                    font-family: poppins-extralight,poppins,sans-serif;
                    font-family: proxima-n-w01-reg,sans-serif;
                    font-size: 14px;
                    font-weight: normal;
                    font-style: normal;
                    margin: 0px 2px 0px 0px;
                    display: none
                }

                #comp-kp0y6opj .style-kp0y6oqu__root .StylableButton1872886392__icon {
                    transition: inherit;
                    display: initial;
                    fill: #384AD3;
                    margin: 0px 0px 0px 2px;
                    width: 12px;
                    height: 12px;
                }

                /* END STYLABLE DIRECTIVE RULES */
                #comp-kp0y8x0p .style-kp0y8x3k__root:hover .StylableButton1872886392__icon {
                    fill: #FFFFFF;
                }

                /* START STYLABLE DIRECTIVE RULES */
                #comp-kp0y8x0p .style-kp0y8x3k__root {
                    -st-extends: StylableButton;
                    transition: all 0.2s ease, visibility 0s;
                    border: 1px solid #384AD3;
                    background: rgba(255, 255, 255, 0)
                }

                #comp-kp0y8x0p .style-kp0y8x3k__root:hover {
                    background: #384AD3;
                }

                #comp-kp0y8x0p .style-kp0y8x3k__root:hover .StylableButton1872886392__label {
                    color: #FFFFFF;
                }

                #comp-kp0y8x0p .style-kp0y8x3k__root:disabled {
                    background: #E2E2E2
                }

                #comp-kp0y8x0p .style-kp0y8x3k__root:disabled .StylableButton1872886392__label {
                    color: #8F8F8F
                }

                #comp-kp0y8x0p .style-kp0y8x3k__root:disabled .StylableButton1872886392__icon {
                    fill: #8F8F8F
                }

                #comp-kp0y8x0p .style-kp0y8x3k__root .StylableButton1872886392__container {
                    transition: inherit
                }

                #comp-kp0y8x0p .style-kp0y8x3k__root .StylableButton1872886392__label {
                    transition: inherit;
                    font-size: 14px;
                    letter-spacing: 0.1em;
                    color: #384AD3;
                    font-family: poppins-extralight,poppins,sans-serif;
                    font-family: proxima-n-w01-reg,sans-serif;
                    font-size: 14px;
                    font-weight: normal;
                    font-style: normal;
                    margin: 0px 2px 0px 0px;
                    display: none
                }

                #comp-kp0y8x0p .style-kp0y8x3k__root .StylableButton1872886392__icon {
                    transition: inherit;
                    display: initial;
                    fill: #384AD3;
                    margin: 0px 0px 0px 2px;
                    width: 12px;
                    height: 12px;
                }

                /* END STYLABLE DIRECTIVE RULES */
                #comp-kp0y8x17 .style-kp0y8x3v__root:hover .StylableButton1872886392__icon {
                    fill: #FFFFFF;
                }

                /* START STYLABLE DIRECTIVE RULES */
                #comp-kp0y8x17 .style-kp0y8x3v__root {
                    -st-extends: StylableButton;
                    transition: all 0.2s ease, visibility 0s;
                    border: 1px solid #384AD3;
                    background: rgba(255, 255, 255, 0)
                }

                #comp-kp0y8x17 .style-kp0y8x3v__root:hover {
                    background: #384AD3;
                }

                #comp-kp0y8x17 .style-kp0y8x3v__root:hover .StylableButton1872886392__label {
                    color: #FFFFFF;
                }

                #comp-kp0y8x17 .style-kp0y8x3v__root:disabled {
                    background: #E2E2E2
                }

                #comp-kp0y8x17 .style-kp0y8x3v__root:disabled .StylableButton1872886392__label {
                    color: #8F8F8F
                }

                #comp-kp0y8x17 .style-kp0y8x3v__root:disabled .StylableButton1872886392__icon {
                    fill: #8F8F8F
                }

                #comp-kp0y8x17 .style-kp0y8x3v__root .StylableButton1872886392__container {
                    transition: inherit
                }

                #comp-kp0y8x17 .style-kp0y8x3v__root .StylableButton1872886392__label {
                    transition: inherit;
                    font-size: 14px;
                    letter-spacing: 0.1em;
                    color: #384AD3;
                    font-family: poppins-extralight,poppins,sans-serif;
                    font-family: proxima-n-w01-reg,sans-serif;
                    font-size: 14px;
                    font-weight: normal;
                    font-style: normal;
                    margin: 0px 2px 0px 0px;
                    display: none
                }

                #comp-kp0y8x17 .style-kp0y8x3v__root .StylableButton1872886392__icon {
                    transition: inherit;
                    display: initial;
                    fill: #384AD3;
                    margin: 0px 0px 0px 2px;
                    width: 12px;
                    height: 12px;
                }

                /* END STYLABLE DIRECTIVE RULES */
                #comp-kp0y94pd .style-kp0y94sd__root:hover .StylableButton1872886392__icon {
                    fill: #FFFFFF;
                }

                /* START STYLABLE DIRECTIVE RULES */
                #comp-kp0y94pd .style-kp0y94sd__root {
                    -st-extends: StylableButton;
                    transition: all 0.2s ease, visibility 0s;
                    border: 1px solid #384AD3;
                    background: rgba(255, 255, 255, 0)
                }

                #comp-kp0y94pd .style-kp0y94sd__root:hover {
                    background: #384AD3;
                }

                #comp-kp0y94pd .style-kp0y94sd__root:hover .StylableButton1872886392__label {
                    color: #FFFFFF;
                }

                #comp-kp0y94pd .style-kp0y94sd__root:disabled {
                    background: #E2E2E2
                }

                #comp-kp0y94pd .style-kp0y94sd__root:disabled .StylableButton1872886392__label {
                    color: #8F8F8F
                }

                #comp-kp0y94pd .style-kp0y94sd__root:disabled .StylableButton1872886392__icon {
                    fill: #8F8F8F
                }

                #comp-kp0y94pd .style-kp0y94sd__root .StylableButton1872886392__container {
                    transition: inherit
                }

                #comp-kp0y94pd .style-kp0y94sd__root .StylableButton1872886392__label {
                    transition: inherit;
                    font-size: 14px;
                    letter-spacing: 0.1em;
                    color: #384AD3;
                    font-family: poppins-extralight,poppins,sans-serif;
                    font-family: proxima-n-w01-reg,sans-serif;
                    font-size: 14px;
                    font-weight: normal;
                    font-style: normal;
                    margin: 0px 2px 0px 0px;
                    display: none
                }

                #comp-kp0y94pd .style-kp0y94sd__root .StylableButton1872886392__icon {
                    transition: inherit;
                    display: initial;
                    fill: #384AD3;
                    margin: 0px 0px 0px 2px;
                    width: 12px;
                    height: 12px;
                }

                /* END STYLABLE DIRECTIVE RULES */
                #comp-kp0y94px .style-kp0y94so__root:hover .StylableButton1872886392__icon {
                    fill: #FFFFFF;
                }

                /* START STYLABLE DIRECTIVE RULES */
                #comp-kp0y94px .style-kp0y94so__root {
                    -st-extends: StylableButton;
                    transition: all 0.2s ease, visibility 0s;
                    border: 1px solid #384AD3;
                    background: rgba(255, 255, 255, 0)
                }

                #comp-kp0y94px .style-kp0y94so__root:hover {
                    background: #384AD3;
                }

                #comp-kp0y94px .style-kp0y94so__root:hover .StylableButton1872886392__label {
                    color: #FFFFFF;
                }

                #comp-kp0y94px .style-kp0y94so__root:disabled {
                    background: #E2E2E2
                }

                #comp-kp0y94px .style-kp0y94so__root:disabled .StylableButton1872886392__label {
                    color: #8F8F8F
                }

                #comp-kp0y94px .style-kp0y94so__root:disabled .StylableButton1872886392__icon {
                    fill: #8F8F8F
                }

                #comp-kp0y94px .style-kp0y94so__root .StylableButton1872886392__container {
                    transition: inherit
                }

                #comp-kp0y94px .style-kp0y94so__root .StylableButton1872886392__label {
                    transition: inherit;
                    font-size: 14px;
                    letter-spacing: 0.1em;
                    color: #384AD3;
                    font-family: poppins-extralight,poppins,sans-serif;
                    font-family: proxima-n-w01-reg,sans-serif;
                    font-size: 14px;
                    font-weight: normal;
                    font-style: normal;
                    margin: 0px 2px 0px 0px;
                    display: none
                }

                #comp-kp0y94px .style-kp0y94so__root .StylableButton1872886392__icon {
                    transition: inherit;
                    display: initial;
                    fill: #384AD3;
                    margin: 0px 0px 0px 2px;
                    width: 12px;
                    height: 12px;
                }
            </style>
        </pages-css>
        <div id="SITE_CONTAINER">
            <div id="main_MF">
                <div id="SCROLL_TO_TOP" class="GFY_- ignore-focus" tabindex="-1" role="region" aria-label="top of page"></div>
                <div id="WIX_ADS" class="_3jGoI _2ny4c">
                    <a data-testid="linkElement" href="//www.wix.com/lpviral/enviral?utm_campaign=vir_wixad_live&amp;adsVersion=white&amp;orig_msid=449452eb-9160-401f-a8e7-73181281adef" target="_blank" rel="nofollow" class="_3Dqvk _3hdQ6">
                        <span class="_1UBiC">
                            <span class="_17VLG">
                                Дизайн этого сайта создан в конструкторе 
                                <div data-testid="bannerLogo" style="direction:ltr;display:inline-flex">
                                    <div>
                                        <svg class="_3Qu-W" viewBox="0 0 28 10.89" aria-label="wix">
                                            <path d="M16.02.2c-.55.3-.76.78-.76 2.14a2.17 2.17 0 0 1 .7-.42 3 3 0 0 0 .7-.4A1.62 1.62 0 0 0 17.22 0a3 3 0 0 0-1.18.2z" class="_2TY8E"></path>
                                            <path d="M12.77.52a2.12 2.12 0 0 0-.58 1l-1.5 5.8-1.3-4.75a4.06 4.06 0 0 0-.7-1.55 2.08 2.08 0 0 0-2.9 0 4.06 4.06 0 0 0-.7 1.55L3.9 7.32l-1.5-5.8a2.12 2.12 0 0 0-.6-1A2.6 2.6 0 0 0 0 .02l2.9 10.83a3.53 3.53 0 0 0 1.42-.17c.62-.33.92-.57 1.3-2 .33-1.33 1.26-5.2 1.35-5.47a.5.5 0 0 1 .34-.4.5.5 0 0 1 .4.5c.1.3 1 4.2 1.4 5.5.4 1.5.7 1.7 1.3 2a3.53 3.53 0 0 0 1.4.2l2.8-11a2.6 2.6 0 0 0-1.82.53zm4.43 1.26a1.76 1.76 0 0 1-.58.5c-.26.16-.52.26-.8.4a.82.82 0 0 0-.57.82v7.36a2.47 2.47 0 0 0 1.2-.15c.6-.3.75-.6.75-2V1.8zm7.16 3.68L28 .06a3.22 3.22 0 0 0-2.3.42 8.67 8.67 0 0 0-1 1.24l-1.34 1.93a.3.3 0 0 1-.57 0l-1.4-1.93a8.67 8.67 0 0 0-1-1.24 3.22 3.22 0 0 0-2.3-.43l3.6 5.4-3.7 5.4a3.54 3.54 0 0 0 2.32-.48 7.22 7.22 0 0 0 1-1.16l1.33-1.9a.3.3 0 0 1 .57 0l1.37 2a8.2 8.2 0 0 0 1 1.2 3.47 3.47 0 0 0 2.33.5z"></path>
                                        </svg>
                                    </div>
                                    <div class="_3DZA8">.com</div>
                                </div>
                                . Создайте ваш сайт сегодня.
                            </span>
                            <span class="_3VwOd _3Dqvk">Создать сайт</span>
                        </span>
                    </a>
                </div>
                <div id="BACKGROUND_GROUP">
                    <div>
                        <div id="pageBackground_b5oae" data-media-height-override-type="" data-media-position-override="false" class="_2AO2a">
                            <div id="bgLayers_pageBackground_b5oae" class="X-jRX">
                                <div data-testid="colorUnderlay" class="mlsxv _22Lsw"></div>
                                <div id="bgMedia_pageBackground_b5oae" class="_1J6n9">
                                    <wix-image id="img_pageBackground_b5oae" class="rca7A _22Lsw _1-b-O ysaOK bgImage" data-image-info="{&quot;containerId&quot;:&quot;pageBackground_b5oae&quot;,&quot;alignType&quot;:&quot;center&quot;,&quot;displayMode&quot;:&quot;fit&quot;,&quot;imageData&quot;:{&quot;width&quot;:1280,&quot;height&quot;:716,&quot;uri&quot;:&quot;427fa1_abecc11e584d41b18cc5d67fcd304555~mv2.jpg&quot;,&quot;displayMode&quot;:&quot;fit&quot;}}" data-has-bg-scroll-effect="" data-bg-effect-name="" data-is-svg="false" data-is-svg-mask="false" data-image-zoomed="" data-has-ssr-src="true">
                                        <img src="https://static.wixstatic.com/media/427fa1_abecc11e584d41b18cc5d67fcd304555~mv2.jpg/v1/fill/w_480,h_269,al_c,q_80,usm_0.66_1.00_0.01,blur_2/427fa1_abecc11e584d41b18cc5d67fcd304555~mv2.jpg" alt="" style="width:100%;height:100%;object-fit:contain;object-position:center"/>
                                    </wix-image>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div id="site-root">
                    <div id="masterPage" class="mesh-layout">
                        <header tabindex="-1" id="SITE_HEADER_WRAPPER">
                            <div id="SITE_HEADER" class="UZpZM">
                                <div class="_2_Pya"></div>
                                <div class="_2qN73">
                                    <div class="_1M8CM"></div>
                                    <div class="_1jI8r">
                                        <div data-mesh-id="SITE_HEADERinlineContent" data-testid="inline-content" class="">
                                            <div data-mesh-id="SITE_HEADERinlineContent-gridContainer" data-testid="mesh-container-content">
                                                <div id="comp-kp0uk529" class="_1NSXQ N-2--">
                                                    <button class="_2PFxe">
                                                        <div class="_27KJ3">
                                                            <div id="defaultAvatar-comp-kp0uk529" class="">
                                                                <div data-testid="svgRoot-defaultAvatar-comp-kp0uk529" class="TG-Zk _1UnNA c0mZI">
                                                                    <svg data-bbox="0 0 50 50" data-type="shape" xmlns="http://www.w3.org/2000/svg" width="50" height="50" viewBox="0 0 50 50">
                                                                        <g>
                                                                            <path d="M25 48.077c-5.924 0-11.31-2.252-15.396-5.921 2.254-5.362 7.492-8.267 15.373-8.267 7.889 0 13.139 3.044 15.408 8.418-4.084 3.659-9.471 5.77-15.385 5.77m.278-35.3c4.927 0 8.611 3.812 8.611 8.878 0 5.21-3.875 9.456-8.611 9.456s-8.611-4.246-8.611-9.456c0-5.066 3.684-8.878 8.611-8.878M25 0C11.193 0 0 11.193 0 25c0 .915.056 1.816.152 2.705.032.295.091.581.133.873.085.589.173 1.176.298 1.751.073.338.169.665.256.997.135.515.273 1.027.439 1.529.114.342.243.675.37 1.01.18.476.369.945.577 1.406.149.331.308.657.472.98.225.446.463.883.714 1.313.182.312.365.619.56.922.272.423.56.832.856 1.237.207.284.41.568.629.841.325.408.671.796 1.02 1.182.22.244.432.494.662.728.405.415.833.801 1.265 1.186.173.154.329.325.507.475l.004-.011A24.886 24.886 0 0 0 25 50a24.881 24.881 0 0 0 16.069-5.861.126.126 0 0 1 .003.01c.172-.144.324-.309.49-.458.442-.392.88-.787 1.293-1.209.228-.232.437-.479.655-.72.352-.389.701-.78 1.028-1.191.218-.272.421-.556.627-.838.297-.405.587-.816.859-1.24a26.104 26.104 0 0 0 1.748-3.216c.208-.461.398-.93.579-1.406.127-.336.256-.669.369-1.012.167-.502.305-1.014.44-1.53.087-.332.183-.659.256-.996.126-.576.214-1.164.299-1.754.042-.292.101-.577.133-.872.095-.89.152-1.791.152-2.707C50 11.193 38.807 0 25 0"/>
                                                                        </g>
                                                                    </svg>
                                                                </div>
                                                            </div>
                                                        </div>
                                                        <span>Log In</span>
                                                    </button>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </header>
                        <main id="PAGES_CONTAINER" tabindex="-1">
                            <div id="SITE_PAGES">
                                <div class="_3tDhR">
                                    <div id="b5oae" class="_3akMP">
                                        <div class="_1vnzj"></div>
                                        <div class="_2egft">
                                            <div id="Containerb5oae" class="_1Cfot">
                                                <div data-mesh-id="Containerb5oaeinlineContent" data-testid="inline-content" class="">
                                                    <div data-mesh-id="Containerb5oaeinlineContent-gridContainer" data-testid="mesh-container-content">
                                                        <div id="comp-kp0y6g30">
                                                            <a data-testid="linkElement" href="https://albertkeshev.wixsite.com/my-site/5" target="_self" class="StylableButton1872886392__root style-kp0y6g40__root StylableButton1872886392__link" aria-label="Кнопка">
                                                                <div class="StylableButton1872886392__container">
                                                                    <span class="StylableButton1872886392__label" data-testid="stylablebutton-label">Кнопка</span>
                                                                    <span class="StylableButton1872886392__icon" aria-hidden="true">
                                                                        <div>
                                                                            <svg data-bbox="13.05 2.55 33.878 54.8" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60">
                                                                                <g>
                                                                                    <path d="M46.5 28.9L20.6 3c-.6-.6-1.6-.6-2.2 0l-4.8 4.8c-.6.6-.6 1.6 0 2.2l19.8 20-19.9 19.9c-.6.6-.6 1.6 0 2.2l4.8 4.8c.6.6 1.6.6 2.2 0l21-21 4.8-4.8c.8-.6.8-1.6.2-2.2z"/>
                                                                                </g>
                                                                            </svg>
                                                                        </div>
                                                                    </span>
                                                                </div>
                                                            </a>
                                                        </div>
                                                        <div id="comp-kp0y6opj">
                                                            <button type="button" class="StylableButton1872886392__root style-kp0y6oqu__root" data-testid="buttonContent" aria-label="Кнопка">
                                                                <div class="StylableButton1872886392__container">
                                                                    <span class="StylableButton1872886392__label" data-testid="stylablebutton-label">Кнопка</span>
                                                                    <span class="StylableButton1872886392__icon" aria-hidden="true">
                                                                        <div>
                                                                            <svg data-bbox="13.05 2.55 33.878 54.8" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60">
                                                                                <g>
                                                                                    <path d="M46.5 28.9L20.6 3c-.6-.6-1.6-.6-2.2 0l-4.8 4.8c-.6.6-.6 1.6 0 2.2l19.8 20-19.9 19.9c-.6.6-.6 1.6 0 2.2l4.8 4.8c.6.6 1.6.6 2.2 0l21-21 4.8-4.8c.8-.6.8-1.6.2-2.2z"/>
                                                                                </g>
                                                                            </svg>
                                                                        </div>
                                                                    </span>
                                                                </div>
                                                            </button>
                                                        </div>
                                                        <div id="comp-kp0y8x0p">
                                                            <a data-testid="linkElement" href="https://albertkeshev.wixsite.com/my-site/7" target="_self" class="StylableButton1872886392__root style-kp0y8x3k__root StylableButton1872886392__link" aria-label="Кнопка">
                                                                <div class="StylableButton1872886392__container">
                                                                    <span class="StylableButton1872886392__label" data-testid="stylablebutton-label">Кнопка</span>
                                                                    <span class="StylableButton1872886392__icon" aria-hidden="true">
                                                                        <div>
                                                                            <svg data-bbox="13.05 2.55 33.878 54.8" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60">
                                                                                <g>
                                                                                    <path d="M46.5 28.9L20.6 3c-.6-.6-1.6-.6-2.2 0l-4.8 4.8c-.6.6-.6 1.6 0 2.2l19.8 20-19.9 19.9c-.6.6-.6 1.6 0 2.2l4.8 4.8c.6.6 1.6.6 2.2 0l21-21 4.8-4.8c.8-.6.8-1.6.2-2.2z"/>
                                                                                </g>
                                                                            </svg>
                                                                        </div>
                                                                    </span>
                                                                </div>
                                                            </a>
                                                        </div>
                                                        <div id="comp-kp0y8x17">
                                                            <button type="button" class="StylableButton1872886392__root style-kp0y8x3v__root" data-testid="buttonContent" aria-label="Кнопка">
                                                                <div class="StylableButton1872886392__container">
                                                                    <span class="StylableButton1872886392__label" data-testid="stylablebutton-label">Кнопка</span>
                                                                    <span class="StylableButton1872886392__icon" aria-hidden="true">
                                                                        <div>
                                                                            <svg data-bbox="13.05 2.55 33.878 54.8" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60">
                                                                                <g>
                                                                                    <path d="M46.5 28.9L20.6 3c-.6-.6-1.6-.6-2.2 0l-4.8 4.8c-.6.6-.6 1.6 0 2.2l19.8 20-19.9 19.9c-.6.6-.6 1.6 0 2.2l4.8 4.8c.6.6 1.6.6 2.2 0l21-21 4.8-4.8c.8-.6.8-1.6.2-2.2z"/>
                                                                                </g>
                                                                            </svg>
                                                                        </div>
                                                                    </span>
                                                                </div>
                                                            </button>
                                                        </div>
                                                        <div id="comp-kp0y94pd">
                                                            <button type="button" class="StylableButton1872886392__root style-kp0y94sd__root" data-testid="buttonContent" aria-label="Кнопка">
                                                                <div class="StylableButton1872886392__container">
                                                                    <span class="StylableButton1872886392__label" data-testid="stylablebutton-label">Кнопка</span>
                                                                    <span class="StylableButton1872886392__icon" aria-hidden="true">
                                                                        <div>
                                                                            <svg data-bbox="13.05 2.55 33.878 54.8" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60">
                                                                                <g>
                                                                                    <path d="M46.5 28.9L20.6 3c-.6-.6-1.6-.6-2.2 0l-4.8 4.8c-.6.6-.6 1.6 0 2.2l19.8 20-19.9 19.9c-.6.6-.6 1.6 0 2.2l4.8 4.8c.6.6 1.6.6 2.2 0l21-21 4.8-4.8c.8-.6.8-1.6.2-2.2z"/>
                                                                                </g>
                                                                            </svg>
                                                                        </div>
                                                                    </span>
                                                                </div>
                                                            </button>
                                                        </div>
                                                        <div id="comp-kp0y94px">
                                                            <button type="button" class="StylableButton1872886392__root style-kp0y94so__root" data-testid="buttonContent" aria-label="Кнопка">
                                                                <div class="StylableButton1872886392__container">
                                                                    <span class="StylableButton1872886392__label" data-testid="stylablebutton-label">Кнопка</span>
                                                                    <span class="StylableButton1872886392__icon" aria-hidden="true">
                                                                        <div>
                                                                            <svg data-bbox="13.05 2.55 33.878 54.8" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 60">
                                                                                <g>
                                                                                    <path d="M46.5 28.9L20.6 3c-.6-.6-1.6-.6-2.2 0l-4.8 4.8c-.6.6-.6 1.6 0 2.2l19.8 20-19.9 19.9c-.6.6-.6 1.6 0 2.2l4.8 4.8c.6.6 1.6.6 2.2 0l21-21 4.8-4.8c.8-.6.8-1.6.2-2.2z"/>
                                                                                </g>
                                                                            </svg>
                                                                        </div>
                                                                    </span>
                                                                </div>
                                                            </button>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </main>
                        <div id="soapAfterPagesContainer" class="page-without-sosp">
                            <div data-mesh-id="soapAfterPagesContainerinlineContent" data-testid="inline-content" class="">
                                <div data-mesh-id="soapAfterPagesContainerinlineContent-gridContainer" data-testid="mesh-container-content">
                                    <div id="CONTROLLER_COMP_CUSTOM_ID" style="display:none"></div>
                                </div>
                            </div>
                        </div>
                        <footer tabindex="-1" id="SITE_FOOTER_WRAPPER">
                            <div id="SITE_FOOTER" class="UZpZM">
                                <div class="_2_Pya"></div>
                                <div class="_2qN73">
                                    <div class="_1M8CM"></div>
                                    <div class="_1jI8r">
                                        <div data-mesh-id="SITE_FOOTERinlineContent" data-testid="inline-content" class="">
                                            <div data-mesh-id="SITE_FOOTERinlineContent-gridContainer" data-testid="mesh-container-content"></div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </footer>
                    </div>
                </div>
                <div id="SCROLL_TO_BOTTOM" class="GFY_- ignore-focus" tabindex="-1" role="region" aria-label="bottom of page"></div>
            </div>
        </div>
        <script>
            window.firstPageId = 'b5oae'
            window.bi.sendBeat(12, 'Partially visible', {
                pageId: window.firstPageId
            })
            if (!window.__browser_deprecation__) {
                window.fedops.phaseStarted('partially_visible')
            }
            if (window.requestCloseWelcomeScreen) {
                window.requestCloseWelcomeScreen()
            }
        </script>
        <!--pageHtmlEmbeds.bodyEnd start-->
        <script type="wix/htmlEmbeds" id="pageHtmlEmbeds.bodyEnd start"></script>
        <script type="wix/htmlEmbeds" id="pageHtmlEmbeds.bodyEnd end"></script>
        <!--pageHtmlEmbeds.bodyEnd end-->
        <!-- warmup data start -->
        <script type="application/json" id="wix-warmup-data">
            {"platform":{"ssrPropsUpdates":[{"comp-kp0uk9ob":{"items":[{"isVisible":true,"isVisibleMobile":true,"items":[],"label":"Мой аккаунт","link":{"href":"https:\/\/albertkeshev.wixsite.com\/my-site\/account\/my-account","target":"_self","type":"DynamicPageLink"}}]}}],"ssrStyleUpdates":[]},"appsWarmupData":{},"ooi":{"failedInSsr":{}},"translations":{"default":{"Accessibility":{"Accessibility_Skip_Nav_Button_Text":"Перейти к основному контенту"},"Address_Input":{"address_input_states_no_results":"Ничего не найдено","address_input_states_error_feature_setup":"Адрес в данный момент недоступен. Попробуйте позже.","address_input_design_sample_address4":"Предлагаемый адрес 4","address_input_states_error_general":"Произошла ошибка","address_input_design_sample_address1":"Предлагаемый адрес 1","address_input_states_error_internet":"Нет подключения к интернету","address_input_states_error_quota":"Произошла ошибка","address_input_states_viewer_error_feature_setup":"Адрес в данный момент недоступен. Попробуйте позже.","address_input_design_sample_address2":"Предлагаемый адрес 2","address_input_states_error_preview":"Чтобы протестировать функцию автозаполнения, перейдите на опубликованный сайт.","address_input_design_sample_address3":"Предлагаемый адрес 3"},"GoogleMaps":{"GoogleMaps_Directions_Link":"Как добраться"},"MULTILINGUAL":{"ZHO_FULL_NAME":"Chinese","MULTILINGUAL_":"EN","ENG_SHORT_NAME":"EN","BEL_SHORT_NAME":"BE","ENG_FLAG_COUNTRY":"United_Kingdom","HEB_FLAG_COUNTRY":"Israel","BEL_FULL_NAME":"Belarusian","HEB_FULL_NAME":"Hebrew","SPA_FULL_NAME":"Spanish","MULTILIN ENG_SHORT_NAME GUAL_":"EN","ZHO_FLAG_COUNTRY":"China","DEU_SHORT_NAME":"DE","BEL_FLAG_COUNTRY":"Belarus","ZHO_SHORT_NAME":"ZH","SPA_SHORT_NAME":"ES","SPA_FLAG_COUNTRY":"Spain","ENG_FULL_NAME":"English","DEU_FLAG_COUNTRY":"Germany","DEU_FULL_NAME":"German","HEB_SHORT_NAME":"HE"},"Platform":{"PLATFORM_fallback_popup_copy_to_clipboard_mobile_description":"Выделите текст ниже и нажмите «Копировать».","PLATFORM_messages_byref_error_uou_title":"This Widget Didn’t Load\n","PLATFORM_fallback_popup_copy_to_clipboard_mac_description":"Выделите текст ниже и нажмите Command + C.","PLATFORM_fallback_popup_copy_to_clipboard_pc_title":"Копирование в буфер обмена","PLATFORM_fallback_popup_copy_to_clipboard_pc_description":"Выделите текст ниже и нажмите Ctrl + C.","PLATFORM_messages_byref_error_user_description":"Click save and refresh this page to try again. \n","custom_element_santa_error_state_text":"Custom Element is not supported by this version of the Editor.","PLATFORM_messages_JS_viewer_error_title":"<%= app_name %> Didn’t Load","PLATFORM_fallback_popup_copy_to_clipboard_mobile_title":"Копирование в буфер обмена","PLATFORM_fallback_popup_copy_to_clipboard_mac_title":"Копирование в буфер обмена","PLATFORM_fallback_popup_copy_to_clipboard_copy_button":"Копировать","PLATFORM_messages_byref_error_user_title":"This Widget Didn’t Load\n","PLATFORM_messages_byref_error_uou_description":"Refresh this page to try again.\n","PLATFORM_messages_JS_viewer_error_text":"The <%= app_name %> app on this site did not load. Try again later."},"SM":{"dialogMixinTranslations_RESET_PASSWORD_SAVE_PASSWORD_New":"Сохранить новый пароль","SMForm_Policies_PrivacyPolicy":"политику конфиденциальности","SMEmailVerification_EmailConfirmationSent":"Мы отправили вам письмо-подтверждение.","SMRegister_log_in_new":"Войти","SMRegister_sign_up_button":"Зарегистрироваться","SMForm_Policies_Join_Community_Link":"Подробнее","SMForm_Choose_Password_new":"Придумайте пароль","SMLogin_Remember_Me_new":"Запомнить меня","SMRegister_or_new":"или","SMEmailVerification_Thanks":"Спасибо за регистрацию! Мы отправим вам письмо-подтверждение.","dialogMixinTranslations_SEND_RESET_PASSWORD_BUTTON_new":"Отправить ссылку","SMRegister_switch_to_sign_up_new":"Зарегистрироваться","SMEmailVerification_ResendLink":"нажмите здесь, чтобы получить письмо-потверждение снова.","SMForm_Policies_Join_Community_Link_Less":"Свернуть","SMRegister_or_log_in_with":"или войдите через","SMWelcome_Check":"Убедитесь, что все правильно.","SMRegister_log_in":"Вход","SMResetPassMail_title_new":"Создайте пароль","SMForm_Policies_Agreement":"Регистрируясь, вы принимаете","SMForm_Error_Password_Retype_new":"Пароли не совпадают. Попробуйте еще раз.","SMEmailVerification_CheckYourInbox":"Проверьте входящие.","SMForm_Policies_Join_Community_Label":"Стать участником сообщества.","SMResetPassMail_Invalid_Email_new":"Перепроверьте эл. почту и попробуйте снова.","SMWelcome_Title":"Добро пожаловать в аккаунт!","SMWelcome_SomeInfo":"Некоторая информация осталась с вашего последнего посещения сайта.","dialogMixinTranslations_RESET_PASSWORD_NEWFIELD_RETYPE_New":"Повторите пароль","SMEmailVerification_DidntGetEmail":"Не получили письмо?","SMEmailVerification_CheckSpam":"Проверьте папку «Спам» или","dialogMixinTranslations_RESET_PASSWORD_CHECKEMAIL_TITLE_new":"Проверьте эл. почту","SMForm_Email_new":"Эл. почта","SMResetPassMail_confirmation_msg_Button_new":"Ясно","SMWelcome_Back":"Вернуться на сайт","SMForm_Error_Password_Length_new":"Passwords must be at least 8 characters long.","SMRegister_sign_up_button_new":"Зарегистрироваться","SMForm_Policies_CodeOfConduct":"Правила поведения","SMForm_Policies_Join_Community_Label_Link":"Подробнее","SMResetPassMail_No_Email_Found_new":"Для этой эл. почты аккаунт не найден. Перепроверьте и попробуйте снова.","SMResetPassMail_confirmation_msg_new":"Мы отправили вам ссылку для смены пароля.","SMForm_Error_19995_new":"This email already has a member account. Try logging in.","dialogMixinTranslations_RESET_PASSWORD_TEXT_new":"Придумайте новый пароль.","SMResetPassMail_Email_Field_new":"Эл. почта","SMResetPassMail_Enter_Email_new":"Чтобы получить ссылку для смены пароля, укажите свою эл. почту.","SMForm_Error_Email_Invalid_new":"Перепроверьте эл. почту и попробуйте снова.","SMForm_Error_Email_Not_Found_new":"Для этой эл. почты аккаунт не найден. Перепроверьте и попробуйте снова.","SMEmailVerification_Title":"Чтобы начать, подтвердите вашу эл. почту","dialogMixinTranslations_switch_to_signup_material_new":"Впервые на сайте?","SMForm_Policies_Join_Community_Read_More_Content":"Присоединяйтесь к сообществу нашего сайта. Оставляйте комментарии, подписывайтесь на участников и т. д. Ваш никнейм, фото профиля и активность будут видны на нашем сайте.","SMResetPassMail_Password_new":"Пароль","SMForm_Policies_Join_Community_Read_More_Content_Link":"Правила поведения","SMRegister_or_sign_up_with":"Или зарегистрируйтесь через","SMWelcome_Edit":"Редактировать данные аккаунта","SMNoPermissions":"У вас нет доступа к этой странице.","SMEmailVerification_ClickTheLink":"Пройдите по ссылке в письме, чтобы попасть в аккаунт.","SMSwitchAccount":"В другой аккаунт","SMForm_Policies_And":"и","dialogMixinTranslations_login_switch_email_new":"Войти через почту","SMForm_Policies_TermsOfUse":"условия использования"},"Site_Search":{"search_box_suggestions_show_all":"Показать все","search_box_clear_label":"Очистить поиск","search_box_search_all":"Поиск по всему сайту"},"Text_Input":{"text_input_phone_format_length_validation_error":"Пожалуйста, введите номер телефона цифрами {digits}.","text_input_phone_format_complex_phone_default_validation_error":"Введите от 4 до 17 цифр. Можно использовать дефисы (-), напр., 555-123-4567.","text_input_phone_format_default_validation_error":"Введите от 4 до 17 цифр. Можно использовать дефисы (-) или начать со знака (+), напр., 555-123-4567 или +(222)987654321."},"Wix_Ads":{"Wix_Ads_Mobile_Co_Branding_Top_Banner":"This website was created by {Logo}","Wix_Ads_Topbar_Upgrade_Banner_CTA":"На премиум","responsive_banner_alt_text_EditorX":"Editor X","wix_ads_bottom_banner_1":"Сайт создан на {Wix}.","Wix_Ads_Desktop_URL_NEW":"\/\/ru.wix.com\/lpviral\/ru900viral?utm_campaign=vir_wixad_live&adsVersion=white","Wix_Ads_Topbar_Mobile_Upgrade_Banner_Text":"чтобы удалить рекламу Wix.","Wix_Ads_2_top_banner":"Дизайн этого сайта создан в конструкторе {Wix}. Создайте ваш сайт сегодня.","Wix_Ads_2_top_banner_hover_1":"Чтобы удалить рекламу Wix, перейдите на премиум","wix_ads_top_banner_hover_3":"Чтобы удалить рекламу,","wix_ads_mobile_banner_2":" ","responsive_preview_banner_button":"На премиум","Wix_Ads_Topbar_Upgrade_Banner_Text":"Перейдите на премиум, чтобы удалить рекламу Wix.","Wix_Ads_2_top_banner_CTA":"Создать сайт","IEDeprecation_Banner_Text":"Internet Explorer скоро перестанет поддерживаться. Чтобы избежать перебоев в работе, используйте другой браузер.","wix_ads_top_banner_hover_4":"перейдите на премиум","responsive_preview_banner_url":"https:\/\/manage.editorx.com\/store\/plans?v=1","Wix_Ads_Topbar_Mobile_Upgrade_Banner_CTA":"Перейти на премиум","IEDeprecation_Banner_Button":"Выбрать другой браузер","wix_ads_top_banner_hover_1":"Вы сможете сделать это сами.","Wix_Ads_2_top_banner_hover_CTA":"Премиум","Wix_Ads_Desktop_URL":"\/\/www.wix.com\/lpviral\/enviral?utm_campaign=vir_wixad_live&adsVersion=blue","Wix_Ads_Mobile_URL":"\/\/www.wix.com?utm_campaign=vir_wixad_live&adsVersion=blue","Wix_Ads_Desktop_Bottom_Banner_Logo_URL":"http:\/\/www.wix.com?utm_campaign=vir_wixad_live&adsVersion=new","wix_ads_top_banner_upgrade_link":"upgrade.com","Wix_Ads_Preview_URL":"\/\/premium.wix.com\/wix\/api\/premiumStart?siteGuid=f5f48295-9716-44d5-84de-1d85c8602134&referralAdditionalInfo=edhtml_PREVIEW_FREE_SITE_BANNER_CLICK","wix_ads_bottom_banner_3":"Создать сайт","wix_ads_top_banner_2":" ","responsive_preview_banner_text":"Гордо носите {X} или","Wix_Ads_Mobile_URL_NEW":"\/\/ru.wix.com\/lpviral\/ru900viral?utm_campaign=vir_wixad_live&adsVersion=white","wix_ads_top_banner_hover_2":"Создать сайт","Wix_Ads_Co_Branding_Top_Banner":"Сайт создан","responsive_banner_url":"\/\/www.wix.com\/editorx","responsive_preview_banner_alt_text_X":"X","wix_ads_bottom_banner_2":" ","wix_ads_bottom_banner_1_2":"another key for JA, TR and DE","responsive_banner_text":"Created on Editor X","wix_ads_top_banner_1":"Создайте ваш сайт на {Wix}","wix_ads_mobile_banner_1":"Создайте ваш сайт на {Wix} сегодня","Mobile_Site_Banner_Widget":"Мы в приложении {Wix}"},"ariaLabels":{"InlinePopup_AriaLabel_Button_Close":"Закрыть окно","ImageZoom_AriaLabel_Button_Next":"Дальше","BoxSlideShow_AriaLabel_NavigationDots":"Slides","forms_ariaLabel_hiddenInput":"Пожалуйста, оставьте поле пустым.","Anchor_AriaLabel_Bottom_Page":"Вниз","AddressInput_AriaLabel_InputField":"Адрес","InlinePopup_AriaLabel_Button_Open":"Открыть окно навигации","SpotifyPlayer_AriaLabel_TopLevel":"Плеер Spotify","dropDownMenu_AriaLabel_TopLevel_SiteNavigation":"Сайт","AudioPlayer_AriaLabel_MediaButton_Pause":"Воспроизвести","Mobile_BackToTop_AriaLabel_Button":"Наверх","ImageZoom_AriaLabel_Button_Previous":"Назад","AudioPlayer_AriaLabel_TopLevel":"Аудиоплеер","StripSlideShow_AriaLabel_NavigationDots":"Go to slide","SingleAudioPlayer_AriaLabel_MediaButton_Mute":"Без звука","BoxSlideShow_AriaLabel_Button_Previous":"Previous","SkypeCallButton_AriaLabel_Button_Call":"Позвонить по Skype","LinkBar_AriaLabel_SocialBarContainer":"Панель соцсетей","StripSlideShow_AriaLabel_TopLevel":"Slideshow","StripSlideShow_AriaLabel_Button_Previous":"Previous","PaypalButton_AriaLabel_Button_Donate":"Внести вклад через PayPal","SlideShow_AriaLabel_Button_Next":"Вперед","LanguageSelector_AriaLabel_TopLevel":"Выбор языка {{language}} выбран","BoxSlideShow_AriaLabel_Button_Next":"Next","recaptcha_popup_ariaLabel_closeButton":"Закрыть","SingleAudioPlayer_AriaLabel_MediaButton_Pause":"Воспроизвести","AudioPlayer_AriaLabel_MediaButton_Play":"Воспроизвести","VKShareButton_AriaLabel_Button_Share":"ВК Поделиться","SingleAudioPlayer_AriaLabel_MediaButton_Play":"Воспроизвести","SlideShow_AriaLabel_TopLevel":"Слайд-шоу","SkypeCallButton_AriaLabel_Button_Chat":"Чат в Skype","BoxSlideShow_AriaLabel_TopLevel":"Slideshow","SlideShow_AriaLabel_Button_Previous":"Назад","StripSlideShow_AriaLabel_Button_Next":"Next","ContactForm_AriaLabel_Form":"Контактная форма","interactions_AriaLabel_contentOnHover_message":"содержание меняется при наведении","ImageZoom_AriaLabel_Button_Close":"Закрыть","SoundCloudWidget_AriaLabel_TopLevel":"Плеер SoundCloud","Mobile_QuickActionBar_AriaLabel_MenuButton":"Быстрые действия","SingleAudioPlayer_AriaLabel_MediaButton_Repeat":"Повторять","SingleAudioPlayer_AriaLabel_TopLevel":"Аудиоплеер","Anchor_AriaLabel_Top_Page":"Наверх","ItunesButton_AriaLabel_Button_GetOnItunes":"Скачать в Tunes","SlideShow_AriaLabel_NavigationDots":"Слайды","LoginSocialBar_AriaLabel_Button_LogIn":"Войти или зарегистрироваться","recaptcha_popup_ariaLabel_topLevel":"reCAPTCHA","PaypalButton_AriaLabel_Button_Buy":"Купить через PayPal","LoginSocialBar_AriaLabel_MembersBar_TopLevel":"Панель участников","PopupCloseIconButton_AriaLabel":"Вернуться на сайт","PinterestPinIt_AriaLabel_Button":"Сохранить в Pinterest"},"blogTranslations":{"blogTranslations_related_posts_empty_title":"You have no Related Posts","next_page":"Вперед","tags":"Теги:","read_more_button":"Подробнее","blogTranslations_please_reload":"Некоторые элементы страницы не загрузились. Обновите страницу и попробуйте снова.","blogTranslations_share_on_facebook":"Поделиться в Facebook","blogTranslations_share_on_twitter":"Поделиться в Twitter","blogTranslations_related_posts_empty_text":"Keep visitors reading on your blog! Click Manage Related Posts to add some now.","BLOGTRANSLATIONS_BLOG_EMPTY_COMPONENT":"Я вовсю работаю над блогом. Скоро вы увидите мои посты.","prev_page":"Назад"},"boxSlideShow":{"BOXSLIDESHOW_Regular_Slideshow_Slides_New_Slide_Label":"Слайд <%= curr_slide %>"},"component_label":{"COMPONENT_LABEL_googleMapsTitle":"Google Карты","component_label_ twitterFollowTitle":"Читать Twitter","component_label_ twitterTweetTitle":"Твит в Twitter","component_label_ facebookLikeTitle":"Лайк в Facebook"},"contactFormTranslations":{"wixMobileApp":"Wix Mobile App","emailFieldLabel":"Эл. почта","desktopViewEditYourSettings":"Настроить эл. почту","subject":"У вас на сайте новое сообщение от ","contactFormTranslations_test_shmool":"test shmool","errorMessage":"Пожалуйста, введите действительный email","viaContactForm":"заполнил контактную форму","downloadThe":"Скачайте","successMessage":"Отлично! Сообщение получено.","noOwner":"Почта владельца не указана","thanks":"Спасибо, что пользуетесь Wix!","phoneFieldLabel":"Телефон","formNameNoValuePlacholder":"Добавьте название","addressFieldLabel":"Адрес","to":"на сайте","aSiteVisitor":"Кто-то","ascendStore":"Ascend Store","mobileViewEditYourSettings":"Чтобы настроить эл. почту, откройте Wix Входящие на компьютере.","wixContactForm":"Wix Контактная форма","error":"Произошла ошибка","subjectFieldLabel":"Тема","nameFieldLabel":"Имя","via":"От: ","thanks_premium":"Спасибо!","sentOn":"Отправлено:","details":"Подробности: ","validationErrorMessage":"Пожалуйста, заполните все обязательные поля.","firstNameFieldLabel":"Имя","title":"У вас новое сообщение: ","lastNameFieldLabel":"Фамилия","neverMissALead":"Не упускайте потенциальных клиентов.","subject_premium":"У вас на сайте новое сообщение от ","formNameLabel":"Название формы","messageFieldLabel":"Сообщение"},"custom_element":{"Custom_element_gfpp_connect_domain_info_text":"Чтобы элемент появился на опубликованном сайте, подключите домен.","custom_element_gfpp_upgrade_premium_info_text":"Чтобы элемент появился на опубликованном сайте, перейдите на премиум-план.\n","custom_element_gfpp_upgrade_no_ads_info_text":"Чтобы элемент появился на опубликованном сайте, перейдите на премиум-план, который удаляет рекламу Wix. "},"datePicker":{"datePicker_month_february_min":"Фев.","datePicker_month_august_min":"Авг.","datePicker_day_monday":"ПН","datePicker_month_november_min":"Нояб.","datePicker_month_december_min":"Дек.","datePicker_day_saturday_reg":"Суббота","datePicker_day_friday":"ПТ","datePicker_day_saturday":"СБ","datePicker_month_june_min":"Июнь","datePicker_day_tuesday":"ВТ","datePicker_month_march":"Март","datePicker_month_january_min":"Янв.","datePicker_day_friday_reg":"Пятница","datePicker_month_october":"Октябрь","datePicker_month_december":"Декабрь","datePicker_day_wednesday":"СР","datePicker_month_january":"Январь","datePicker_month_august":"Август","datePicker_month_july_min":"Июль","datePicker_month_october_min":"Окт.","datePicker_month_march_min":"Март","datePicker_month_april":"Апрель","datePicker_day_sunday_reg":"Воскресенье","datePicker_day_thursday":"ЧТ","datePicker_day_monday_reg":"Понедельник","datePicker_month_june":"Июнь","datePicker_month_february":"Февраль","datePicker_previousMonthNav":"Предыдущий месяц","datePicker_month_july":"Июль","datePicker_month_april_min":"Апр.","datePicker_previousYearNav":"Предыдущий год","datePicker_day_sunday":"ВС","datePicker_month_may_min":"Май","datePicker_month_november":"Ноябрь","datePicker_month_september":"Сентябрь","datePicker_day_tuesday_reg":"Вторник","datePicker_nextYearNav":"Следующий год","datePicker_month_may":"Май","datePicker_day_thursday_reg":"Четверг","datePicker_month_september_min":"Cент.","datePicker_day_wednesday_reg":"Среда","datePicker_nextMonthNav":"Следующий месяц"},"dialogMixinTranslations":{"SMContainer_OK":"OK","dialogMixinTranslations_login_google":"Войти через Google","SMForm_Error_19958":"Ваша регистрация ждет подтверждения владельца сайта","SMLogin_Captcha_Error":"Верификация не работает. Повторите позже.","PasswordLogin_Empty_Password":"Пожалуйста, введите пароль.","dialogMixinTranslations_RESET_PASSWORD_NEWFIELD":"Новый пароль","SMForm_Policies_Join_Community_Link_Less_new":"Свернуть","SMContainer_Show_Confirm2":"Чтобы управлять контактами пользователей сайта: Wix Home > Контакты > Пользователи","SMLogin_Captcha_Timeout":"Срок проверки истек. Пожалуйста, повторите.","dialogMixinTranslations_switch_to_signup":"У вас нет аккаунта?","SMResetPass_Reset_Fail":"Не получилось изменить пароль. Попробуйте снова.","SMResetPassMail_Back_Login":"Назад","SMForm_Error_19995":"Аккаунт с такой эл. почтой уже существует.","SMForm_Error_Email_Invalid":"Перепроверьте эл. почту и попробуйте снова.","SMRegister_Already_Have_User":"Уже есть аккаунт?","dialogMixinTranslations_login_switch_email":"Войти через почту","dialogMixinTranslations_log_in_btn_new":"Войти","SMResetPass_Continue":"Продолжить","SMForm_Policies_Agreement_new":"Регистрируясь, вы принимаете","SMContainer_Show_Confirm":"Эта страница доступна только зарегистрированным пользователям. Посетители увидят ее, только указав email и пароль.","PasswordLogin_Header":"Для доступа к странице введите пароль","dialogMixinTranslations_confirmation_msg_Button":"Ясно","SMForm_Error_Password_Blank":"Убедитесь, что указали пароль.","dialogMixinTranslations_signup_switch_email":"Через эл. почту","SMProfile_Update_Details":"Обновите ваши данные","dialogMixinTranslations_or_social_signup_new":"Через эл. почту","dialogMixinTranslations_forgot_password":"Не помню пароль","SMForm_Policies_CodeOfConduct_new":"Правила поведения","SMContain_Cancel":"Отменить","PasswordLogin_Cancel":"Отменить","SMResetPass_Message":"Введите ваш новый пароль ниже. ","dialogMixinTranslations_No_Email_Found":"Для этой эл. почты аккаунт не найден. Попробуйте снова.","PasswordLogin_AdministratorLogin":"Логин администратора","dialogMixinTranslations_Error_Email_Not_Found":"Для этой эл. почты аккаунт не найден. Перепроверьте и попробуйте снова.","SMForm_Error_Non_Ascii_Chars":"Пароль может содержать только символы ASCII","dialogMixinTranslations_confirmation_msg":"Мы отправили вам ссылку для смены пароля.","SMForm_Error_Password_Retype":"Пароли не совпадают. Пожалуйста, исправьте.","dialogMixinTranslations_or":"или","dialogMixinTranslations_log_in_btn":"Войти","SMResetPass_New_Password":"Новый пароль","SMForm_Error_19971":"Подтвердите, что вы не робот.","SMForm_Error_19980":"Доступ запрещен владельцем сайта","SMForm_Error_19999":"Эта эл. почта не подходит ни к одному аккаунту. Попробуйте снова.","SMForm_Retype_Password":"Повторите пароль","dialogMixinTranslations_signup_google":"Войти через Google","SMForm_Error_17005":"Пожалуйста, введите правильный пароль","PasswordLogin_Submit":"OK","SMLogin_Forgot_Password":"Забыли пароль?","SMForm_Error_Password_Length_Login":"Passwords must be at least 4 characters long. Try again.","SMProfile_Update":"Обновить","dialogMixinTranslations_switch_to_sign_up":"Регистрация","SMForm_Error_Email_Blank":"Добавьте эл. почту","SMForm_Email":"Эл. почта","PasswordLogin_Password":"Пароль","SMForm_Policies_Join_Community_Link_new":"Подробнее","dialogMixinTranslations_GUEST_LOGIN_TITLE":"Зона для гостей","SMForm_Password":"Пароль","dialogMixinTranslations_link_copied":"Скопировано","SMLogin_Remember_Me":"Запомнить меня","SMForm_Error_19984":"Неверная сессия","SMResetPassMail_title":"Создайте пароль","dialogMixinTranslations_or_social_login":"Войти через почту","SMForm_Policies_PrivacyPolicy_new":"политику конфиденциальности","dialogMixinTranslations_or_social_signup":"Электронная почта","dialogMixinTranslations_login_facebook":"Войти через Facebook","SMForm_Policies_And_new":"и","SMRegister_sign_up":"Регистрация","SMForm_Error_19988":"Ошибка валидации","SMForm_Error_General_Err":"Что-то пошло не так... Попробуйте позже.","SMResetPassMail_confirmation_title":"Пожалуйста, проверьте свою эл. почту","SMForm_Error_19956":"Unable to log in with that email. Try a different account.","dialogMixinTranslation_log_in":"Войти","SMForm_Policies_Join_Community_Read_More_Content_new":"Присоединяйтесь к сообществу нашего сайта. Оставляйте комментарии, подписывайтесь на участников и т. д. Ваш никнейм, фото профиля и активность будут видны на нашем сайте.","dialogMixinTranslations_RESET_PASSWORD_NEWFIELD_RETYPE":"Повторите пароль","SMForm_Error_17002":"Страница удалена. Чтобы перейти на главную, нажмите «Обновить страницу» в браузере.","dialogMixinTranslations_Close_Dialog":"Закрыть","SMForm_Error_19972":"Ссылка устарела","dialogMixinTranslations_Log_In_Title":"Вход","SMRegister_GO":"Вперед","dialogMixinTranslations_RESET_PASSWORD_Password":"Пароль","dialogMixinTranslations_Log_In":"Войти","dialogMixinTranslations_RESET_PASSWORD_TITLE":"Смена пароля","dialogMixinTranslations_to_sign_up_with":"Чтобы зарегистрироваться через","dialogMixinTranslations_RESET_PASSWORD_BUTTON":"Создать пароль","SMRegister_sign_up_new":"Зарегистрироваться","dialogMixinTranslations_to_login_with":"Чтобы войти через","PasswordLogin_Wrong_Password":"Пожалуйста, введите правильный пароль","dialogMixinTranslations_Invalid_Email":"Перепроверьте эл. почту и попробуйте снова.","dialogMixinTranslations_visit_another_browser":"Скопируйте ссылку на страницу и откройте ее в другом браузере.","SMForm_Error_19976":"Неверный email или пароль","SMRegister_Already_Have_User_new":"Уже есть аккаунт?","PasswordLogin_Error_General":"Что-то пошло не так... Попробуйте позже.","SMForm_Policies_Join_Community_Label_new":"Присоединиться к сообществу сайта.","dialogMixinTranslations_signup_facebook":"Войти через Facebook","dialogMixinTranslations_or_sign_up_with":"Или зарегистрируйтесь через","SMApply_Success1":"Запрос регистрации отправлен администратору сайта","SMResetPass_Reset_Succ":"Вы успешно сменили пароль.","dialogMixinTranslations_or_email":"или","dialogMixinTranslations_or_email_new":"ИЛИ","SMLogin_OR":"или","SMContainer_Need_Log_In":"Для доступа к странице введите пароль.","dialogMixinTranslations_RESET_PASSWORD_SUCESS_TITLE":"Пароль успешно изменен.","dialogMixinTranslations_RESET_PASSWORD_TEXT":"Укажите новый пароль:","dialogMixinTranslations_social_login":"Вход через соцсети","dialogMixinTranslations_copy_link":"Скопировать ссылку","dialogMixinTranslations_forgot_password_mobile_new":"Не помню пароль","dialogMixinTranslations_Password_Reset_TooShort":"Пароль должен состоять из 4–15 знаков","SMResetPass_Retype_Password":"Повторите пароль","SMForm_Policies_TermsOfUse_new":"условия использования","SMLogin_Login":"Войти","dialogMixinTranslations_or_log_in_with":"Или войдите через","dialogMixinTranslations_switch_to_signup_material":"Впервые на сайте?","SMResetPassMail_confirmation_msg":"Мы отправили вам ссылку для смены пароля.","dialogMixinTranslations_RESET_PASSWORD_CHECKEMAIL_TITLE":"Проверьте эл. почту","SMForm_Error_19970":"Не удалось верифицировать. Пожалуйста, повторите.","SMForm_Error_19973":"Пароль сброшен. Чтобы войти, нажмите ссылку «Забыли пароль?» ниже и создайте новый.","SMForm_Error_Password_Length":"Длина пароля должна быть от {0} до {1} знаков.","dialogMixinTranslations_RESET_PASSWORD_CHECKEMAIL_TEXT":"Мы отправили вам ссылку для смены пароля.","SMForm_Error_18880":"Укажите эл. почту","SMForm_Error_17003":"Страница не защищена паролем. Чтобы увидеть ее, нажмите «Обновить страницу» в браузере.","dialogMixinTranslations_Error_Email_Not_Found _Error_Password_Length":"Пароль должен содержать хотя бы 8 символов.","dialogMixinTranslations_forgot_password_mobile":"Не помню пароль","SMResetPassMail_Enter_Email":"Пожалуйста, введите ваш email","dialogMixinTranslations_Choose_Password":"Придумайте пароль","dialogMixinTranslations_facebook":"Facebook","dialogMixinTranslations_GUEST_LOGIN_SUBTITLE":"Пожалуйста, укажите пароль:","SMRegister_Login":"Войти","SMApply_Success2":"После подтверждения вы получите письмо на ({0}).","dialogMixinTranslations_google":"Google-аккаунт"},"disqusComments":{"disqusComments_notDisqusIdMessage":"Для работы с Disqus зайдите в панель настроек."},"homePageLoginTranslations":{"SIGN_IN":"Вход \/ Регистрация","SIGN_OUT":"Выход","HELLO":"Привет,"},"loginButtonTranslations":{"Login_Button_Sign_In":"Вход \/ Регистрация","Login_Button_Sign_Out":"Выход","Login_Button_Hello":"Привет,","login_social_bar_choose_option_label":"Choose an Option"},"recaptcha":{"recaptcha_popup_title":"Подтверждение","recaptcha_popup_subtitle":"Пожалуйста, подтвердите, что вы не робот."},"siteMembersTranslations":{"SMContainer_OK":"OK","siteMembersTranslations_RESET_PASSWORD_CHECKEMAIL_TITLE":"Пожалуйста, проверьте свою эл. почту","siteMembersTranslations_TEMPLATE_NOTIFICATION_TITLE":"Деморежим","SMResetPass_Continue":"Продолжить","siteMembersTranslations_Reset_Password_OK":"Ясно","siteMembersTranslations_PASSWORD_HAS_EXPIRED_OK":"Отправить ссылку","siteMembersTranslatioins_PASSWORD_HAS_EXPIRED_TEXT":"Чтобы продолжить, отправьте себе на почту новую ссылку.","siteMembersTranslations_PASSWORD_HAS_EXPIRED_TEXT":"Чтобы продолжить, отправьте себе на почту новую ссылку.","SITEMEMBERMANGAGER_LOGOUT_MESSAGES_IN_PROGRESS":"Что-то не срослось. Пожалуйста, попробуйте еще раз.","siteMembersTranslations_Reset_Password_Sucess_Title":"Пароль успешно изменен.","siteMembersTranslations_RESET_PASSWORD_CHECKEMAIL_TEXT":"Отправили вам ссылку для смены пароля.","SITEMEMBERMANGAGER_OWNER_LOGOUT_ACTION_MESSAGE":"Чтобы протестировать эту функцию, пожалуйста, выйдите из аккаунта Wix.","siteMembersTranslations_TEMPLATE_NOTIFICATION_MESSAGE":"Начните редактировать и измените шаблон по-своему.","SITEMEMBERMANGAGER_LOGOUT_MESSAGES_TITLE":"Не получилось выйти","siteMembersTranslatioins_PASSWORD_HAS_EXPIRED_OK":"Отправить ссылку","SMResetPassMail_confirmation_title":"Пожалуйста, проверьте свою эл. почту","siteMembersTranslations_PASSWORD_HAS_EXPIRED_TITLE":"Ссылка для создания пароля устарела","SMApply_Success1":"Готово. Ваш запрос на регистрацию был отправлен на подтверждение.","SMResetPass_Reset_Succ":"Вы успешно сменили пароль.","SITEMEMBERMANGAGER_OWNER_LOGOUT_ACTION_TITLE":"Не удалось выйти","SMResetPassMail_confirmation_msg":"Мы отправили вам ссылку для смены пароля.","siteMembersTranslatioins_PASSWORD_HAS_EXPIRED_TITLE":"Ссылка для создания пароля устарела","SMApply_Success2":"Когда администратор подтвердит запрос, вы получите эл. письмо на {0}."},"subscribeFormTranslations":{"tnx":"Спасибо, что пользуетесь Wix!","submitButtonLabel":"Подписаться","emailFieldLabel":"Эл. почта","subject":"У вашего Wix-сайта новый подписчик!","errorMessage":"Пожалуйста, укажите верный email","successMessage":"Ура! Вы с нами :)","noOwner":"Почта владельца не указана","phoneFieldLabel":"Мобильный","error":"Произошла ошибка","via":"От: ","tnx_premium":"Спасибо!","sentOn":"Отправлено:","details":"Данные подписчика:","validationErrorMessage":"Заполните все обязательные поля.","subscribeFormTitle":"Подпишитесь на обновления","firstNameFieldLabel":"Имя","title":"У вас появился новый подписчик","lastNameFieldLabel":"Фамилия","subject_premium":"У вашего Wix-сайта новый подписчик!"},"tpaExtensionTranslations":{"tpa_unavail_problems_2":"за помощью.","tpa_oops":"Приложение не загрузилось","tpa_messages_app_installation_failed_message_title":"This App Wasn't Add to Your Site","tpa_unavail_problems":"Повторите позже, отключите блокировщики рекламы или перезагрузите страницу. Свяжитесь с автором","TPA_PRELOADER_LOADING":"Загружаем","tpa_messages_app_installation_failed_message_text":"Нажмите «Удалить» и добавьте приложение снова."},"upload_button":{"upload-button.validation_error.file_type_not_allowed":"File type is not supported. Try uploading a different file.","upload-button.wpm_error.zero_size_file":"File is empty and can't be uploaded. Try a different file.","upload-button.wpm_error.invalid_file_audio_duration_is_missing":"File is incomplete or damaged and can't be uploaded. Try a different file.","upload_button.mobile_popper.close":"Close","upload-button.wpm_error.unsupported_file_extension":"{extension} files are not supported. Try a different file.","Upload_Button_File_Number_Error":"Select up to <%=Max_Number_of_Files%> files.","upload-button.wpm_error.invalid_file_video_stream_is_missing":"File is incomplete or damaged and can't be uploaded. Try a different file.","Upload_Button_File_Upload_General_Error":"Не удалось загрузить","upload-button.wpm_error.site_quota_total_storage_exceeded":"This video can’t be uploaded. To send it, contact us.","upload-button.wpm_error.incorrect_file_info":"File is incomplete or damaged and can't be uploaded. Try a different file.","Upload_Button_File_Type_Error":"Файлы <%= extension %> не поддерживаются.","Upload_Button_File_Empty_Error":"This file is empty. Try a new file.","Upload_Button_File_Upload_Multiple_Errors":"<%=Number_of_Errors%> file errors","upload_button.validation_error.multiple_file_errors":"{errorAmount} errors found.","Upload_Button_Files_Menu_Close":"Close","Upload_Button_Video_Quota_Total_Reached":"Невозможно загрузить видео. Свяжитесь с нами.","upload-button.error.general":"File can't be uploaded due to a temporary technical issue. Try again in a few minutes.","Upload_Button_File_Size_Error":"Файл слишком большой. Выберите файл меньшего размера (<%= max_file_size %> max).","FileUploader.SingleSelectedFile":"1 file selected.","Upload_Button_Multiple_Files_Selected":"<%=Number_of_Files%> files selected","upload-button.validation_error.file_size_exceeds_limit":"File is too big. Upload a smaller file ({sizeLimit} max).","Upload_Button_One_File_Selected":"1 file selected","upload-button.wpm_error.invalid_file_audio_bitrate_is_missing":"File is incomplete or damaged and can't be uploaded. Try a different file.","upload-button.wpm_error.site_quota_free_video_duration_exceeded":"This video can’t be uploaded. To send it, contact us.","upload-button.wpm_error.authentication_failed":"File wasn't uploaded. Refresh the page and try again.","upload-button.wpm_error.site_quota_total_video_duration_exceeded":"This video can’t be uploaded. To send it, contact us.","upload-button.wpm_error.mime_type_mismatch":"File extension doesn't match the file type. Rename the extension to {extension} and try again.","Upload_Button_File_Upload_Required_Error":"Это обязательное поле.","FileUploader.NumberOfSelectedFiles":"{numberOfFiles} files selected.","Upload_Button_Filename_Preview_Text_Filename":"здесь имя файла","upload_button.validation_error.exceeded_files_limit":"Please select up to {numberOfFiles} files.","Upload_Button_File_Upload_1_Error":"1 file error","upload-button.wpm_error.file_size_exceeded_limit":"File is too big. Upload a smaller file ({sizeLimit} max). ","upload-button.wpm_error.invalid_file_video_duration_is_missing":"File is incomplete or damaged and can't be uploaded. Try a different file.","upload-button.wpm_error.invalid_file_video_bitrate_is_missing":"File is incomplete or damaged and can't be uploaded. Try a different file.","upload-button.wpm_error.invalid_file":"File is incomplete or damaged and can't be uploaded. Try a different file.","upload_button.validation_error.single_file_error":"1 error found.","upload-button.wpm_error.unsupported_format":"This file is not in a supported format and can't be uploaded. Try a different file or contact us for more info."},"wixOfTheDayTranslations":{"INTRO_PRE_TITLE":"НОВЫЕ ИДЕИ:","READ_ON_BUTTON_LABEL":"Читать дальше","CLOSE_DESCRIPTION_BUTTON_LABEL":"Закрыть","INTRO_TEXT":"Каждый день мы представляем новый классный сайт, созданный на Wix.\nХотите поделиться своим?\nОтправьте адрес сайта на wixofday@wix.com","INTRO_TITLE":"САЙТ ДНЯ"}},"Accessibility":{"Accessibility_Skip_Nav_Button_Text":"Перейти к основному контенту"},"Address_Input":{"address_input_states_no_results":"Ничего не найдено","address_input_states_error_feature_setup":"Адрес в данный момент недоступен. Попробуйте позже.","address_input_design_sample_address4":"Предлагаемый адрес 4","address_input_states_error_general":"Произошла ошибка","address_input_design_sample_address1":"Предлагаемый адрес 1","address_input_states_error_internet":"Нет подключения к интернету","address_input_states_error_quota":"Произошла ошибка","address_input_states_viewer_error_feature_setup":"Адрес в данный момент недоступен. Попробуйте позже.","address_input_design_sample_address2":"Предлагаемый адрес 2","address_input_states_error_preview":"Чтобы протестировать функцию автозаполнения, перейдите на опубликованный сайт.","address_input_design_sample_address3":"Предлагаемый адрес 3"},"GoogleMaps":{"GoogleMaps_Directions_Link":"Как добраться"},"MULTILINGUAL":{"ZHO_FULL_NAME":"Chinese","MULTILINGUAL_":"EN","ENG_SHORT_NAME":"EN","BEL_SHORT_NAME":"BE","ENG_FLAG_COUNTRY":"United_Kingdom","HEB_FLAG_COUNTRY":"Israel","BEL_FULL_NAME":"Belarusian","HEB_FULL_NAME":"Hebrew","SPA_FULL_NAME":"Spanish","MULTILIN ENG_SHORT_NAME GUAL_":"EN","ZHO_FLAG_COUNTRY":"China","DEU_SHORT_NAME":"DE","BEL_FLAG_COUNTRY":"Belarus","ZHO_SHORT_NAME":"ZH","SPA_SHORT_NAME":"ES","SPA_FLAG_COUNTRY":"Spain","ENG_FULL_NAME":"English","DEU_FLAG_COUNTRY":"Germany","DEU_FULL_NAME":"German","HEB_SHORT_NAME":"HE"},"Platform":{"PLATFORM_fallback_popup_copy_to_clipboard_mobile_description":"Выделите текст ниже и нажмите «Копировать».","PLATFORM_messages_byref_error_uou_title":"This Widget Didn’t Load\n","PLATFORM_fallback_popup_copy_to_clipboard_mac_description":"Выделите текст ниже и нажмите Command + C.","PLATFORM_fallback_popup_copy_to_clipboard_pc_title":"Копирование в буфер обмена","PLATFORM_fallback_popup_copy_to_clipboard_pc_description":"Выделите текст ниже и нажмите Ctrl + C.","PLATFORM_messages_byref_error_user_description":"Click save and refresh this page to try again. \n","custom_element_santa_error_state_text":"Custom Element is not supported by this version of the Editor.","PLATFORM_messages_JS_viewer_error_title":"<%= app_name %> Didn’t Load","PLATFORM_fallback_popup_copy_to_clipboard_mobile_title":"Копирование в буфер обмена","PLATFORM_fallback_popup_copy_to_clipboard_mac_title":"Копирование в буфер обмена","PLATFORM_fallback_popup_copy_to_clipboard_copy_button":"Копировать","PLATFORM_messages_byref_error_user_title":"This Widget Didn’t Load\n","PLATFORM_messages_byref_error_uou_description":"Refresh this page to try again.\n","PLATFORM_messages_JS_viewer_error_text":"The <%= app_name %> app on this site did not load. Try again later."},"SM":{"dialogMixinTranslations_RESET_PASSWORD_SAVE_PASSWORD_New":"Сохранить новый пароль","SMForm_Policies_PrivacyPolicy":"политику конфиденциальности","SMEmailVerification_EmailConfirmationSent":"Мы отправили вам письмо-подтверждение.","SMRegister_log_in_new":"Войти","SMRegister_sign_up_button":"Зарегистрироваться","SMForm_Policies_Join_Community_Link":"Подробнее","SMForm_Choose_Password_new":"Придумайте пароль","SMLogin_Remember_Me_new":"Запомнить меня","SMRegister_or_new":"или","SMEmailVerification_Thanks":"Спасибо за регистрацию! Мы отправим вам письмо-подтверждение.","dialogMixinTranslations_SEND_RESET_PASSWORD_BUTTON_new":"Отправить ссылку","SMRegister_switch_to_sign_up_new":"Зарегистрироваться","SMEmailVerification_ResendLink":"нажмите здесь, чтобы получить письмо-потверждение снова.","SMForm_Policies_Join_Community_Link_Less":"Свернуть","SMRegister_or_log_in_with":"или войдите через","SMWelcome_Check":"Убедитесь, что все правильно.","SMRegister_log_in":"Вход","SMResetPassMail_title_new":"Создайте пароль","SMForm_Policies_Agreement":"Регистрируясь, вы принимаете","SMForm_Error_Password_Retype_new":"Пароли не совпадают. Попробуйте еще раз.","SMEmailVerification_CheckYourInbox":"Проверьте входящие.","SMForm_Policies_Join_Community_Label":"Стать участником сообщества.","SMResetPassMail_Invalid_Email_new":"Перепроверьте эл. почту и попробуйте снова.","SMWelcome_Title":"Добро пожаловать в аккаунт!","SMWelcome_SomeInfo":"Некоторая информация осталась с вашего последнего посещения сайта.","dialogMixinTranslations_RESET_PASSWORD_NEWFIELD_RETYPE_New":"Повторите пароль","SMEmailVerification_DidntGetEmail":"Не получили письмо?","SMEmailVerification_CheckSpam":"Проверьте папку «Спам» или","dialogMixinTranslations_RESET_PASSWORD_CHECKEMAIL_TITLE_new":"Проверьте эл. почту","SMForm_Email_new":"Эл. почта","SMResetPassMail_confirmation_msg_Button_new":"Ясно","SMWelcome_Back":"Вернуться на сайт","SMForm_Error_Password_Length_new":"Passwords must be at least 8 characters long.","SMRegister_sign_up_button_new":"Зарегистрироваться","SMForm_Policies_CodeOfConduct":"Правила поведения","SMForm_Policies_Join_Community_Label_Link":"Подробнее","SMResetPassMail_No_Email_Found_new":"Для этой эл. почты аккаунт не найден. Перепроверьте и попробуйте снова.","SMResetPassMail_confirmation_msg_new":"Мы отправили вам ссылку для смены пароля.","SMForm_Error_19995_new":"This email already has a member account. Try logging in.","dialogMixinTranslations_RESET_PASSWORD_TEXT_new":"Придумайте новый пароль.","SMResetPassMail_Email_Field_new":"Эл. почта","SMResetPassMail_Enter_Email_new":"Чтобы получить ссылку для смены пароля, укажите свою эл. почту.","SMForm_Error_Email_Invalid_new":"Перепроверьте эл. почту и попробуйте снова.","SMForm_Error_Email_Not_Found_new":"Для этой эл. почты аккаунт не найден. Перепроверьте и попробуйте снова.","SMEmailVerification_Title":"Чтобы начать, подтвердите вашу эл. почту","dialogMixinTranslations_switch_to_signup_material_new":"Впервые на сайте?","SMForm_Policies_Join_Community_Read_More_Content":"Присоединяйтесь к сообществу нашего сайта. Оставляйте комментарии, подписывайтесь на участников и т. д. Ваш никнейм, фото профиля и активность будут видны на нашем сайте.","SMResetPassMail_Password_new":"Пароль","SMForm_Policies_Join_Community_Read_More_Content_Link":"Правила поведения","SMRegister_or_sign_up_with":"Или зарегистрируйтесь через","SMWelcome_Edit":"Редактировать данные аккаунта","SMNoPermissions":"У вас нет доступа к этой странице.","SMEmailVerification_ClickTheLink":"Пройдите по ссылке в письме, чтобы попасть в аккаунт.","SMSwitchAccount":"В другой аккаунт","SMForm_Policies_And":"и","dialogMixinTranslations_login_switch_email_new":"Войти через почту","SMForm_Policies_TermsOfUse":"условия использования"},"Site_Search":{"search_box_suggestions_show_all":"Показать все","search_box_clear_label":"Очистить поиск","search_box_search_all":"Поиск по всему сайту"},"Text_Input":{"text_input_phone_format_length_validation_error":"Пожалуйста, введите номер телефона цифрами {digits}.","text_input_phone_format_complex_phone_default_validation_error":"Введите от 4 до 17 цифр. Можно использовать дефисы (-), напр., 555-123-4567.","text_input_phone_format_default_validation_error":"Введите от 4 до 17 цифр. Можно использовать дефисы (-) или начать со знака (+), напр., 555-123-4567 или +(222)987654321."},"Wix_Ads":{"Wix_Ads_Mobile_Co_Branding_Top_Banner":"This website was created by {Logo}","Wix_Ads_Topbar_Upgrade_Banner_CTA":"На премиум","responsive_banner_alt_text_EditorX":"Editor X","wix_ads_bottom_banner_1":"Сайт создан на {Wix}.","Wix_Ads_Desktop_URL_NEW":"\/\/ru.wix.com\/lpviral\/ru900viral?utm_campaign=vir_wixad_live&adsVersion=white","Wix_Ads_Topbar_Mobile_Upgrade_Banner_Text":"чтобы удалить рекламу Wix.","Wix_Ads_2_top_banner":"Дизайн этого сайта создан в конструкторе {Wix}. Создайте ваш сайт сегодня.","Wix_Ads_2_top_banner_hover_1":"Чтобы удалить рекламу Wix, перейдите на премиум","wix_ads_top_banner_hover_3":"Чтобы удалить рекламу,","wix_ads_mobile_banner_2":" ","responsive_preview_banner_button":"На премиум","Wix_Ads_Topbar_Upgrade_Banner_Text":"Перейдите на премиум, чтобы удалить рекламу Wix.","Wix_Ads_2_top_banner_CTA":"Создать сайт","IEDeprecation_Banner_Text":"Internet Explorer скоро перестанет поддерживаться. Чтобы избежать перебоев в работе, используйте другой браузер.","wix_ads_top_banner_hover_4":"перейдите на премиум","responsive_preview_banner_url":"https:\/\/manage.editorx.com\/store\/plans?v=1","Wix_Ads_Topbar_Mobile_Upgrade_Banner_CTA":"Перейти на премиум","IEDeprecation_Banner_Button":"Выбрать другой браузер","wix_ads_top_banner_hover_1":"Вы сможете сделать это сами.","Wix_Ads_2_top_banner_hover_CTA":"Премиум","Wix_Ads_Desktop_URL":"\/\/www.wix.com\/lpviral\/enviral?utm_campaign=vir_wixad_live&adsVersion=blue","Wix_Ads_Mobile_URL":"\/\/www.wix.com?utm_campaign=vir_wixad_live&adsVersion=blue","Wix_Ads_Desktop_Bottom_Banner_Logo_URL":"http:\/\/www.wix.com?utm_campaign=vir_wixad_live&adsVersion=new","wix_ads_top_banner_upgrade_link":"upgrade.com","Wix_Ads_Preview_URL":"\/\/premium.wix.com\/wix\/api\/premiumStart?siteGuid=f5f48295-9716-44d5-84de-1d85c8602134&referralAdditionalInfo=edhtml_PREVIEW_FREE_SITE_BANNER_CLICK","wix_ads_bottom_banner_3":"Создать сайт","wix_ads_top_banner_2":" ","responsive_preview_banner_text":"Гордо носите {X} или","Wix_Ads_Mobile_URL_NEW":"\/\/ru.wix.com\/lpviral\/ru900viral?utm_campaign=vir_wixad_live&adsVersion=white","wix_ads_top_banner_hover_2":"Создать сайт","Wix_Ads_Co_Branding_Top_Banner":"Сайт создан","responsive_banner_url":"\/\/www.wix.com\/editorx","responsive_preview_banner_alt_text_X":"X","wix_ads_bottom_banner_2":" ","wix_ads_bottom_banner_1_2":"another key for JA, TR and DE","responsive_banner_text":"Created on Editor X","wix_ads_top_banner_1":"Создайте ваш сайт на {Wix}","wix_ads_mobile_banner_1":"Создайте ваш сайт на {Wix} сегодня","Mobile_Site_Banner_Widget":"Мы в приложении {Wix}"},"ariaLabels":{"InlinePopup_AriaLabel_Button_Close":"Закрыть окно","ImageZoom_AriaLabel_Button_Next":"Дальше","BoxSlideShow_AriaLabel_NavigationDots":"Slides","forms_ariaLabel_hiddenInput":"Пожалуйста, оставьте поле пустым.","Anchor_AriaLabel_Bottom_Page":"Вниз","AddressInput_AriaLabel_InputField":"Адрес","InlinePopup_AriaLabel_Button_Open":"Открыть окно навигации","SpotifyPlayer_AriaLabel_TopLevel":"Плеер Spotify","dropDownMenu_AriaLabel_TopLevel_SiteNavigation":"Сайт","AudioPlayer_AriaLabel_MediaButton_Pause":"Воспроизвести","Mobile_BackToTop_AriaLabel_Button":"Наверх","ImageZoom_AriaLabel_Button_Previous":"Назад","AudioPlayer_AriaLabel_TopLevel":"Аудиоплеер","StripSlideShow_AriaLabel_NavigationDots":"Go to slide","SingleAudioPlayer_AriaLabel_MediaButton_Mute":"Без звука","BoxSlideShow_AriaLabel_Button_Previous":"Previous","SkypeCallButton_AriaLabel_Button_Call":"Позвонить по Skype","LinkBar_AriaLabel_SocialBarContainer":"Панель соцсетей","StripSlideShow_AriaLabel_TopLevel":"Slideshow","StripSlideShow_AriaLabel_Button_Previous":"Previous","PaypalButton_AriaLabel_Button_Donate":"Внести вклад через PayPal","SlideShow_AriaLabel_Button_Next":"Вперед","LanguageSelector_AriaLabel_TopLevel":"Выбор языка {{language}} выбран","BoxSlideShow_AriaLabel_Button_Next":"Next","recaptcha_popup_ariaLabel_closeButton":"Закрыть","SingleAudioPlayer_AriaLabel_MediaButton_Pause":"Воспроизвести","AudioPlayer_AriaLabel_MediaButton_Play":"Воспроизвести","VKShareButton_AriaLabel_Button_Share":"ВК Поделиться","SingleAudioPlayer_AriaLabel_MediaButton_Play":"Воспроизвести","SlideShow_AriaLabel_TopLevel":"Слайд-шоу","SkypeCallButton_AriaLabel_Button_Chat":"Чат в Skype","BoxSlideShow_AriaLabel_TopLevel":"Slideshow","SlideShow_AriaLabel_Button_Previous":"Назад","StripSlideShow_AriaLabel_Button_Next":"Next","ContactForm_AriaLabel_Form":"Контактная форма","interactions_AriaLabel_contentOnHover_message":"содержание меняется при наведении","ImageZoom_AriaLabel_Button_Close":"Закрыть","SoundCloudWidget_AriaLabel_TopLevel":"Плеер SoundCloud","Mobile_QuickActionBar_AriaLabel_MenuButton":"Быстрые действия","SingleAudioPlayer_AriaLabel_MediaButton_Repeat":"Повторять","SingleAudioPlayer_AriaLabel_TopLevel":"Аудиоплеер","Anchor_AriaLabel_Top_Page":"Наверх","ItunesButton_AriaLabel_Button_GetOnItunes":"Скачать в Tunes","SlideShow_AriaLabel_NavigationDots":"Слайды","LoginSocialBar_AriaLabel_Button_LogIn":"Войти или зарегистрироваться","recaptcha_popup_ariaLabel_topLevel":"reCAPTCHA","PaypalButton_AriaLabel_Button_Buy":"Купить через PayPal","LoginSocialBar_AriaLabel_MembersBar_TopLevel":"Панель участников","PopupCloseIconButton_AriaLabel":"Вернуться на сайт","PinterestPinIt_AriaLabel_Button":"Сохранить в Pinterest"},"blogTranslations":{"blogTranslations_related_posts_empty_title":"You have no Related Posts","next_page":"Вперед","tags":"Теги:","read_more_button":"Подробнее","blogTranslations_please_reload":"Некоторые элементы страницы не загрузились. Обновите страницу и попробуйте снова.","blogTranslations_share_on_facebook":"Поделиться в Facebook","blogTranslations_share_on_twitter":"Поделиться в Twitter","blogTranslations_related_posts_empty_text":"Keep visitors reading on your blog! Click Manage Related Posts to add some now.","BLOGTRANSLATIONS_BLOG_EMPTY_COMPONENT":"Я вовсю работаю над блогом. Скоро вы увидите мои посты.","prev_page":"Назад"},"boxSlideShow":{"BOXSLIDESHOW_Regular_Slideshow_Slides_New_Slide_Label":"Слайд <%= curr_slide %>"},"component_label":{"COMPONENT_LABEL_googleMapsTitle":"Google Карты","component_label_ twitterFollowTitle":"Читать Twitter","component_label_ twitterTweetTitle":"Твит в Twitter","component_label_ facebookLikeTitle":"Лайк в Facebook"},"contactFormTranslations":{"wixMobileApp":"Wix Mobile App","emailFieldLabel":"Эл. почта","desktopViewEditYourSettings":"Настроить эл. почту","subject":"У вас на сайте новое сообщение от ","contactFormTranslations_test_shmool":"test shmool","errorMessage":"Пожалуйста, введите действительный email","viaContactForm":"заполнил контактную форму","downloadThe":"Скачайте","successMessage":"Отлично! Сообщение получено.","noOwner":"Почта владельца не указана","thanks":"Спасибо, что пользуетесь Wix!","phoneFieldLabel":"Телефон","formNameNoValuePlacholder":"Добавьте название","addressFieldLabel":"Адрес","to":"на сайте","aSiteVisitor":"Кто-то","ascendStore":"Ascend Store","mobileViewEditYourSettings":"Чтобы настроить эл. почту, откройте Wix Входящие на компьютере.","wixContactForm":"Wix Контактная форма","error":"Произошла ошибка","subjectFieldLabel":"Тема","nameFieldLabel":"Имя","via":"От: ","thanks_premium":"Спасибо!","sentOn":"Отправлено:","details":"Подробности: ","validationErrorMessage":"Пожалуйста, заполните все обязательные поля.","firstNameFieldLabel":"Имя","title":"У вас новое сообщение: ","lastNameFieldLabel":"Фамилия","neverMissALead":"Не упускайте потенциальных клиентов.","subject_premium":"У вас на сайте новое сообщение от ","formNameLabel":"Название формы","messageFieldLabel":"Сообщение"},"custom_element":{"Custom_element_gfpp_connect_domain_info_text":"Чтобы элемент появился на опубликованном сайте, подключите домен.","custom_element_gfpp_upgrade_premium_info_text":"Чтобы элемент появился на опубликованном сайте, перейдите на премиум-план.\n","custom_element_gfpp_upgrade_no_ads_info_text":"Чтобы элемент появился на опубликованном сайте, перейдите на премиум-план, который удаляет рекламу Wix. "},"datePicker":{"datePicker_month_february_min":"Фев.","datePicker_month_august_min":"Авг.","datePicker_day_monday":"ПН","datePicker_month_november_min":"Нояб.","datePicker_month_december_min":"Дек.","datePicker_day_saturday_reg":"Суббота","datePicker_day_friday":"ПТ","datePicker_day_saturday":"СБ","datePicker_month_june_min":"Июнь","datePicker_day_tuesday":"ВТ","datePicker_month_march":"Март","datePicker_month_january_min":"Янв.","datePicker_day_friday_reg":"Пятница","datePicker_month_october":"Октябрь","datePicker_month_december":"Декабрь","datePicker_day_wednesday":"СР","datePicker_month_january":"Январь","datePicker_month_august":"Август","datePicker_month_july_min":"Июль","datePicker_month_october_min":"Окт.","datePicker_month_march_min":"Март","datePicker_month_april":"Апрель","datePicker_day_sunday_reg":"Воскресенье","datePicker_day_thursday":"ЧТ","datePicker_day_monday_reg":"Понедельник","datePicker_month_june":"Июнь","datePicker_month_february":"Февраль","datePicker_previousMonthNav":"Предыдущий месяц","datePicker_month_july":"Июль","datePicker_month_april_min":"Апр.","datePicker_previousYearNav":"Предыдущий год","datePicker_day_sunday":"ВС","datePicker_month_may_min":"Май","datePicker_month_november":"Ноябрь","datePicker_month_september":"Сентябрь","datePicker_day_tuesday_reg":"Вторник","datePicker_nextYearNav":"Следующий год","datePicker_month_may":"Май","datePicker_day_thursday_reg":"Четверг","datePicker_month_september_min":"Cент.","datePicker_day_wednesday_reg":"Среда","datePicker_nextMonthNav":"Следующий месяц"},"dialogMixinTranslations":{"SMContainer_OK":"OK","dialogMixinTranslations_login_google":"Войти через Google","SMForm_Error_19958":"Ваша регистрация ждет подтверждения владельца сайта","SMLogin_Captcha_Error":"Верификация не работает. Повторите позже.","PasswordLogin_Empty_Password":"Пожалуйста, введите пароль.","dialogMixinTranslations_RESET_PASSWORD_NEWFIELD":"Новый пароль","SMForm_Policies_Join_Community_Link_Less_new":"Свернуть","SMContainer_Show_Confirm2":"Чтобы управлять контактами пользователей сайта: Wix Home > Контакты > Пользователи","SMLogin_Captcha_Timeout":"Срок проверки истек. Пожалуйста, повторите.","dialogMixinTranslations_switch_to_signup":"У вас нет аккаунта?","SMResetPass_Reset_Fail":"Не получилось изменить пароль. Попробуйте снова.","SMResetPassMail_Back_Login":"Назад","SMForm_Error_19995":"Аккаунт с такой эл. почтой уже существует.","SMForm_Error_Email_Invalid":"Перепроверьте эл. почту и попробуйте снова.","SMRegister_Already_Have_User":"Уже есть аккаунт?","dialogMixinTranslations_login_switch_email":"Войти через почту","dialogMixinTranslations_log_in_btn_new":"Войти","SMResetPass_Continue":"Продолжить","SMForm_Policies_Agreement_new":"Регистрируясь, вы принимаете","SMContainer_Show_Confirm":"Эта страница доступна только зарегистрированным пользователям. Посетители увидят ее, только указав email и пароль.","PasswordLogin_Header":"Для доступа к странице введите пароль","dialogMixinTranslations_confirmation_msg_Button":"Ясно","SMForm_Error_Password_Blank":"Убедитесь, что указали пароль.","dialogMixinTranslations_signup_switch_email":"Через эл. почту","SMProfile_Update_Details":"Обновите ваши данные","dialogMixinTranslations_or_social_signup_new":"Через эл. почту","dialogMixinTranslations_forgot_password":"Не помню пароль","SMForm_Policies_CodeOfConduct_new":"Правила поведения","SMContain_Cancel":"Отменить","PasswordLogin_Cancel":"Отменить","SMResetPass_Message":"Введите ваш новый пароль ниже. ","dialogMixinTranslations_No_Email_Found":"Для этой эл. почты аккаунт не найден. Попробуйте снова.","PasswordLogin_AdministratorLogin":"Логин администратора","dialogMixinTranslations_Error_Email_Not_Found":"Для этой эл. почты аккаунт не найден. Перепроверьте и попробуйте снова.","SMForm_Error_Non_Ascii_Chars":"Пароль может содержать только символы ASCII","dialogMixinTranslations_confirmation_msg":"Мы отправили вам ссылку для смены пароля.","SMForm_Error_Password_Retype":"Пароли не совпадают. Пожалуйста, исправьте.","dialogMixinTranslations_or":"или","dialogMixinTranslations_log_in_btn":"Войти","SMResetPass_New_Password":"Новый пароль","SMForm_Error_19971":"Подтвердите, что вы не робот.","SMForm_Error_19980":"Доступ запрещен владельцем сайта","SMForm_Error_19999":"Эта эл. почта не подходит ни к одному аккаунту. Попробуйте снова.","SMForm_Retype_Password":"Повторите пароль","dialogMixinTranslations_signup_google":"Войти через Google","SMForm_Error_17005":"Пожалуйста, введите правильный пароль","PasswordLogin_Submit":"OK","SMLogin_Forgot_Password":"Забыли пароль?","SMForm_Error_Password_Length_Login":"Passwords must be at least 4 characters long. Try again.","SMProfile_Update":"Обновить","dialogMixinTranslations_switch_to_sign_up":"Регистрация","SMForm_Error_Email_Blank":"Добавьте эл. почту","SMForm_Email":"Эл. почта","PasswordLogin_Password":"Пароль","SMForm_Policies_Join_Community_Link_new":"Подробнее","dialogMixinTranslations_GUEST_LOGIN_TITLE":"Зона для гостей","SMForm_Password":"Пароль","dialogMixinTranslations_link_copied":"Скопировано","SMLogin_Remember_Me":"Запомнить меня","SMForm_Error_19984":"Неверная сессия","SMResetPassMail_title":"Создайте пароль","dialogMixinTranslations_or_social_login":"Войти через почту","SMForm_Policies_PrivacyPolicy_new":"политику конфиденциальности","dialogMixinTranslations_or_social_signup":"Электронная почта","dialogMixinTranslations_login_facebook":"Войти через Facebook","SMForm_Policies_And_new":"и","SMRegister_sign_up":"Регистрация","SMForm_Error_19988":"Ошибка валидации","SMForm_Error_General_Err":"Что-то пошло не так... Попробуйте позже.","SMResetPassMail_confirmation_title":"Пожалуйста, проверьте свою эл. почту","SMForm_Error_19956":"Unable to log in with that email. Try a different account.","dialogMixinTranslation_log_in":"Войти","SMForm_Policies_Join_Community_Read_More_Content_new":"Присоединяйтесь к сообществу нашего сайта. Оставляйте комментарии, подписывайтесь на участников и т. д. Ваш никнейм, фото профиля и активность будут видны на нашем сайте.","dialogMixinTranslations_RESET_PASSWORD_NEWFIELD_RETYPE":"Повторите пароль","SMForm_Error_17002":"Страница удалена. Чтобы перейти на главную, нажмите «Обновить страницу» в браузере.","dialogMixinTranslations_Close_Dialog":"Закрыть","SMForm_Error_19972":"Ссылка устарела","dialogMixinTranslations_Log_In_Title":"Вход","SMRegister_GO":"Вперед","dialogMixinTranslations_RESET_PASSWORD_Password":"Пароль","dialogMixinTranslations_Log_In":"Войти","dialogMixinTranslations_RESET_PASSWORD_TITLE":"Смена пароля","dialogMixinTranslations_to_sign_up_with":"Чтобы зарегистрироваться через","dialogMixinTranslations_RESET_PASSWORD_BUTTON":"Создать пароль","SMRegister_sign_up_new":"Зарегистрироваться","dialogMixinTranslations_to_login_with":"Чтобы войти через","PasswordLogin_Wrong_Password":"Пожалуйста, введите правильный пароль","dialogMixinTranslations_Invalid_Email":"Перепроверьте эл. почту и попробуйте снова.","dialogMixinTranslations_visit_another_browser":"Скопируйте ссылку на страницу и откройте ее в другом браузере.","SMForm_Error_19976":"Неверный email или пароль","SMRegister_Already_Have_User_new":"Уже есть аккаунт?","PasswordLogin_Error_General":"Что-то пошло не так... Попробуйте позже.","SMForm_Policies_Join_Community_Label_new":"Присоединиться к сообществу сайта.","dialogMixinTranslations_signup_facebook":"Войти через Facebook","dialogMixinTranslations_or_sign_up_with":"Или зарегистрируйтесь через","SMApply_Success1":"Запрос регистрации отправлен администратору сайта","SMResetPass_Reset_Succ":"Вы успешно сменили пароль.","dialogMixinTranslations_or_email":"или","dialogMixinTranslations_or_email_new":"ИЛИ","SMLogin_OR":"или","SMContainer_Need_Log_In":"Для доступа к странице введите пароль.","dialogMixinTranslations_RESET_PASSWORD_SUCESS_TITLE":"Пароль успешно изменен.","dialogMixinTranslations_RESET_PASSWORD_TEXT":"Укажите новый пароль:","dialogMixinTranslations_social_login":"Вход через соцсети","dialogMixinTranslations_copy_link":"Скопировать ссылку","dialogMixinTranslations_forgot_password_mobile_new":"Не помню пароль","dialogMixinTranslations_Password_Reset_TooShort":"Пароль должен состоять из 4–15 знаков","SMResetPass_Retype_Password":"Повторите пароль","SMForm_Policies_TermsOfUse_new":"условия использования","SMLogin_Login":"Войти","dialogMixinTranslations_or_log_in_with":"Или войдите через","dialogMixinTranslations_switch_to_signup_material":"Впервые на сайте?","SMResetPassMail_confirmation_msg":"Мы отправили вам ссылку для смены пароля.","dialogMixinTranslations_RESET_PASSWORD_CHECKEMAIL_TITLE":"Проверьте эл. почту","SMForm_Error_19970":"Не удалось верифицировать. Пожалуйста, повторите.","SMForm_Error_19973":"Пароль сброшен. Чтобы войти, нажмите ссылку «Забыли пароль?» ниже и создайте новый.","SMForm_Error_Password_Length":"Длина пароля должна быть от {0} до {1} знаков.","dialogMixinTranslations_RESET_PASSWORD_CHECKEMAIL_TEXT":"Мы отправили вам ссылку для смены пароля.","SMForm_Error_18880":"Укажите эл. почту","SMForm_Error_17003":"Страница не защищена паролем. Чтобы увидеть ее, нажмите «Обновить страницу» в браузере.","dialogMixinTranslations_Error_Email_Not_Found _Error_Password_Length":"Пароль должен содержать хотя бы 8 символов.","dialogMixinTranslations_forgot_password_mobile":"Не помню пароль","SMResetPassMail_Enter_Email":"Пожалуйста, введите ваш email","dialogMixinTranslations_Choose_Password":"Придумайте пароль","dialogMixinTranslations_facebook":"Facebook","dialogMixinTranslations_GUEST_LOGIN_SUBTITLE":"Пожалуйста, укажите пароль:","SMRegister_Login":"Войти","SMApply_Success2":"После подтверждения вы получите письмо на ({0}).","dialogMixinTranslations_google":"Google-аккаунт"},"disqusComments":{"disqusComments_notDisqusIdMessage":"Для работы с Disqus зайдите в панель настроек."},"homePageLoginTranslations":{"SIGN_IN":"Вход \/ Регистрация","SIGN_OUT":"Выход","HELLO":"Привет,"},"loginButtonTranslations":{"Login_Button_Sign_In":"Вход \/ Регистрация","Login_Button_Sign_Out":"Выход","Login_Button_Hello":"Привет,","login_social_bar_choose_option_label":"Choose an Option"},"recaptcha":{"recaptcha_popup_title":"Подтверждение","recaptcha_popup_subtitle":"Пожалуйста, подтвердите, что вы не робот."},"siteMembersTranslations":{"SMContainer_OK":"OK","siteMembersTranslations_RESET_PASSWORD_CHECKEMAIL_TITLE":"Пожалуйста, проверьте свою эл. почту","siteMembersTranslations_TEMPLATE_NOTIFICATION_TITLE":"Деморежим","SMResetPass_Continue":"Продолжить","siteMembersTranslations_Reset_Password_OK":"Ясно","siteMembersTranslations_PASSWORD_HAS_EXPIRED_OK":"Отправить ссылку","siteMembersTranslatioins_PASSWORD_HAS_EXPIRED_TEXT":"Чтобы продолжить, отправьте себе на почту новую ссылку.","siteMembersTranslations_PASSWORD_HAS_EXPIRED_TEXT":"Чтобы продолжить, отправьте себе на почту новую ссылку.","SITEMEMBERMANGAGER_LOGOUT_MESSAGES_IN_PROGRESS":"Что-то не срослось. Пожалуйста, попробуйте еще раз.","siteMembersTranslations_Reset_Password_Sucess_Title":"Пароль успешно изменен.","siteMembersTranslations_RESET_PASSWORD_CHECKEMAIL_TEXT":"Отправили вам ссылку для смены пароля.","SITEMEMBERMANGAGER_OWNER_LOGOUT_ACTION_MESSAGE":"Чтобы протестировать эту функцию, пожалуйста, выйдите из аккаунта Wix.","siteMembersTranslations_TEMPLATE_NOTIFICATION_MESSAGE":"Начните редактировать и измените шаблон по-своему.","SITEMEMBERMANGAGER_LOGOUT_MESSAGES_TITLE":"Не получилось выйти","siteMembersTranslatioins_PASSWORD_HAS_EXPIRED_OK":"Отправить ссылку","SMResetPassMail_confirmation_title":"Пожалуйста, проверьте свою эл. почту","siteMembersTranslations_PASSWORD_HAS_EXPIRED_TITLE":"Ссылка для создания пароля устарела","SMApply_Success1":"Готово. Ваш запрос на регистрацию был отправлен на подтверждение.","SMResetPass_Reset_Succ":"Вы успешно сменили пароль.","SITEMEMBERMANGAGER_OWNER_LOGOUT_ACTION_TITLE":"Не удалось выйти","SMResetPassMail_confirmation_msg":"Мы отправили вам ссылку для смены пароля.","siteMembersTranslatioins_PASSWORD_HAS_EXPIRED_TITLE":"Ссылка для создания пароля устарела","SMApply_Success2":"Когда администратор подтвердит запрос, вы получите эл. письмо на {0}."},"subscribeFormTranslations":{"tnx":"Спасибо, что пользуетесь Wix!","submitButtonLabel":"Подписаться","emailFieldLabel":"Эл. почта","subject":"У вашего Wix-сайта новый подписчик!","errorMessage":"Пожалуйста, укажите верный email","successMessage":"Ура! Вы с нами :)","noOwner":"Почта владельца не указана","phoneFieldLabel":"Мобильный","error":"Произошла ошибка","via":"От: ","tnx_premium":"Спасибо!","sentOn":"Отправлено:","details":"Данные подписчика:","validationErrorMessage":"Заполните все обязательные поля.","subscribeFormTitle":"Подпишитесь на обновления","firstNameFieldLabel":"Имя","title":"У вас появился новый подписчик","lastNameFieldLabel":"Фамилия","subject_premium":"У вашего Wix-сайта новый подписчик!"},"tpaExtensionTranslations":{"tpa_unavail_problems_2":"за помощью.","tpa_oops":"Приложение не загрузилось","tpa_messages_app_installation_failed_message_title":"This App Wasn't Add to Your Site","tpa_unavail_problems":"Повторите позже, отключите блокировщики рекламы или перезагрузите страницу. Свяжитесь с автором","TPA_PRELOADER_LOADING":"Загружаем","tpa_messages_app_installation_failed_message_text":"Нажмите «Удалить» и добавьте приложение снова."},"upload_button":{"upload-button.validation_error.file_type_not_allowed":"File type is not supported. Try uploading a different file.","upload-button.wpm_error.zero_size_file":"File is empty and can't be uploaded. Try a different file.","upload-button.wpm_error.invalid_file_audio_duration_is_missing":"File is incomplete or damaged and can't be uploaded. Try a different file.","upload_button.mobile_popper.close":"Close","upload-button.wpm_error.unsupported_file_extension":"{extension} files are not supported. Try a different file.","Upload_Button_File_Number_Error":"Select up to <%=Max_Number_of_Files%> files.","upload-button.wpm_error.invalid_file_video_stream_is_missing":"File is incomplete or damaged and can't be uploaded. Try a different file.","Upload_Button_File_Upload_General_Error":"Не удалось загрузить","upload-button.wpm_error.site_quota_total_storage_exceeded":"This video can’t be uploaded. To send it, contact us.","upload-button.wpm_error.incorrect_file_info":"File is incomplete or damaged and can't be uploaded. Try a different file.","Upload_Button_File_Type_Error":"Файлы <%= extension %> не поддерживаются.","Upload_Button_File_Empty_Error":"This file is empty. Try a new file.","Upload_Button_File_Upload_Multiple_Errors":"<%=Number_of_Errors%> file errors","upload_button.validation_error.multiple_file_errors":"{errorAmount} errors found.","Upload_Button_Files_Menu_Close":"Close","Upload_Button_Video_Quota_Total_Reached":"Невозможно загрузить видео. Свяжитесь с нами.","upload-button.error.general":"File can't be uploaded due to a temporary technical issue. Try again in a few minutes.","Upload_Button_File_Size_Error":"Файл слишком большой. Выберите файл меньшего размера (<%= max_file_size %> max).","FileUploader.SingleSelectedFile":"1 file selected.","Upload_Button_Multiple_Files_Selected":"<%=Number_of_Files%> files selected","upload-button.validation_error.file_size_exceeds_limit":"File is too big. Upload a smaller file ({sizeLimit} max).","Upload_Button_One_File_Selected":"1 file selected","upload-button.wpm_error.invalid_file_audio_bitrate_is_missing":"File is incomplete or damaged and can't be uploaded. Try a different file.","upload-button.wpm_error.site_quota_free_video_duration_exceeded":"This video can’t be uploaded. To send it, contact us.","upload-button.wpm_error.authentication_failed":"File wasn't uploaded. Refresh the page and try again.","upload-button.wpm_error.site_quota_total_video_duration_exceeded":"This video can’t be uploaded. To send it, contact us.","upload-button.wpm_error.mime_type_mismatch":"File extension doesn't match the file type. Rename the extension to {extension} and try again.","Upload_Button_File_Upload_Required_Error":"Это обязательное поле.","FileUploader.NumberOfSelectedFiles":"{numberOfFiles} files selected.","Upload_Button_Filename_Preview_Text_Filename":"здесь имя файла","upload_button.validation_error.exceeded_files_limit":"Please select up to {numberOfFiles} files.","Upload_Button_File_Upload_1_Error":"1 file error","upload-button.wpm_error.file_size_exceeded_limit":"File is too big. Upload a smaller file ({sizeLimit} max). ","upload-button.wpm_error.invalid_file_video_duration_is_missing":"File is incomplete or damaged and can't be uploaded. Try a different file.","upload-button.wpm_error.invalid_file_video_bitrate_is_missing":"File is incomplete or damaged and can't be uploaded. Try a different file.","upload-button.wpm_error.invalid_file":"File is incomplete or damaged and can't be uploaded. Try a different file.","upload_button.validation_error.single_file_error":"1 error found.","upload-button.wpm_error.unsupported_format":"This file is not in a supported format and can't be uploaded. Try a different file or contact us for more info."},"wixOfTheDayTranslations":{"INTRO_PRE_TITLE":"НОВЫЕ ИДЕИ:","READ_ON_BUTTON_LABEL":"Читать дальше","CLOSE_DESCRIPTION_BUTTON_LABEL":"Закрыть","INTRO_TEXT":"Каждый день мы представляем новый классный сайт, созданный на Wix.\nХотите поделиться своим?\nОтправьте адрес сайта на wixofday@wix.com","INTRO_TITLE":"САЙТ ДНЯ"}}}
        </script>
        <!-- warmup data end -->
    </body>
</html>
 
