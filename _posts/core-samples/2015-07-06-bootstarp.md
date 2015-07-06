---
layout: post
category : "bootstarp"
tagline: ""
tags : [js]
---

<script id="ad-template" type="text/x-handlebars-template">
    {{#each ads}}
    <div class="col-xs-12 col-md-6">
        <article class="post tag-ad">
            <h2 class="post-title">
                <a href="{{url}}" onclick="_hmt.push(['_trackEvent', 'titlelink', 'click', '{{{title}}}'])"
                   target="_blank">{{{title}}}</a>
            </h2>

            <div class="post-featured-image">
                <a class="thumbnail" href="{{url}}"
                   onclick="_hmt.push(['_trackEvent', 'imagelink', 'click', '{{{title}}}'])" target="_blank">
                    <img src="{{img}}" width="800" height="600" alt="{{{title}}}" data-original="{{img}}">
                </a>
            </div>
        </article>
    </div>
    {{/each}}
</script>

<script>
    var ads = [
        {
            title: 'Ghost中文网',
            url: 'http://www.ghostchina.com/',
            img: 'http://static.bootcss.com/expo/img/7/b5/f9c2f01fad1f23574156e0577a06c.jpg',
        },
        {
            title: '猎聘网',
            url: 'http://www.liepin.com/event/landingpage/it_rd.shtml?mscid=b_o_0003',
            img: 'http://static.bootcss.com/expo/img/e/93/06ce7866570d459fc6132b823d9f2.png',
        },
        {
            title: 'Laravel中文网',
            url: 'http://www.golaravel.com/',
            img: 'http://static.bootcss.com/expo/img/8/01/3069bcd2889acfe435c32005be151.jpg'
        },

        {
            title: 'Bootstrap求职招聘',
            url: 'http://www.liepin.com/event/bootstrap/index.shtml?mscid=b_o_0001',
            img: 'http://static.bootcss.com/expo/img/1/fe/f36d7232d5e063f2de4f144c6749a.png',
        }

    ];
</script>

<!-- Favicons -->
<link rel="apple-touch-icon-precomposed" sizes="144x144"
      href="/assets/ico/apple-touch-icon-144-precomposed.png?v=ae3dba82d6">
<link rel="shortcut icon" href="/assets/ico/favicon.png?v=ae3dba82d6">
<script>
    var _hmt = _hmt || [];
</script>


<div class="wrap">


    <div class="header"
         style="background-image: url(http://static.bootcss.com/expo/img/d/dd/2de797545de56274f03a5920eb3a1.jpg)">
        <div class="logoimg">
            <a href="http://expo.bootcss.com"><img
                    src="http://static.bootcss.com/expo/img/d/f5/ab31f6c55403cfa55ccb32bc7f29b.png" alt="Bootstrap 优站精选"
                    width="78"></a>
        </div>
        <div class="container">
            <div class="row">
                <div class="col-xs-12">
                    <div class="logotxt"><h1><a href="http://expo.bootcss.com">Bootstrap</a></h1></div>
                    <h2 class="site-name text-center">优站精选<span>www.YouZhan.org</span></h2>

                </div>
            </div>

        </div>
    </div>
    <main class="main" role="main">
        <div class="container">
            <div class="row" id="post-list">

                <div class="col-xs-12 col-sm-6">
                    <article class="post tag-guo-wai-wang-zhan tag-bootstrap-v3">
                        <h2 class="post-title">
                            <a href="/respond/" onclick="_hmt.push(['_trackEvent', 'titlelink', 'click', 'Respond'])"
                               target="_blank">Respond</a>
                        </h2>

                        <div class="post-featured-image">
                            <a class="thumbnail" href="/respond/"
                               onclick="_hmt.push(['_trackEvent', 'imagelink', 'click', 'Respond'])" target="_blank">
                                <img src="/assets/img/loader.gif?v=ae3dba82d6" width="800" height="600" alt="Respond"
                                     data-original="http://static.bootcss.com/expo/img/c/9b/046abe2a70fb03664b2af8d8e3e49.png">
                            </a>
                        </div>
                        <div class="post-content">
                            <p><a href="http://respondcms.com/">Respond</a></p>
                        </div>
                    </article>
                </div>


                <div class="col-xs-12 col-sm-6">
                    <article class="post tag-guo-wai-wang-zhan tag-bootstrap-v3">
                        <h2 class="post-title">
                            <a href="/laravel-recipes/"
                               onclick="_hmt.push(['_trackEvent', 'titlelink', 'click', 'Laravel Recipes'])"
                               target="_blank">Laravel Recipes</a>
                        </h2>

                        <div class="post-featured-image">
                            <a class="thumbnail" href="/laravel-recipes/"
                               onclick="_hmt.push(['_trackEvent', 'imagelink', 'click', 'Laravel Recipes'])"
                               target="_blank">
                                <img src="/assets/img/loader.gif?v=ae3dba82d6" width="800" height="600"
                                     alt="Laravel Recipes"
                                     data-original="http://static.bootcss.com/expo/img/a/58/c82449313dee04b243629a27dceec.png">
                            </a>
                        </div>
                        <div class="post-content">
                            <p><a href="http://laravel-recipes.com/">Laravel Recipes</a></p>
                        </div>
                    </article>
                </div>


                <div class="col-xs-12 col-sm-6">
                    <article class="post tag-guo-wai-wang-zhan tag-bootstrap-v3">
                        <h2 class="post-title">
                            <a href="/unsplash/" onclick="_hmt.push(['_trackEvent', 'titlelink', 'click', 'Unsplash'])"
                               target="_blank">Unsplash</a>
                        </h2>

                        <div class="post-featured-image">
                            <a class="thumbnail" href="/unsplash/"
                               onclick="_hmt.push(['_trackEvent', 'imagelink', 'click', 'Unsplash'])" target="_blank">
                                <img src="/assets/img/loader.gif?v=ae3dba82d6" width="800" height="600" alt="Unsplash"
                                     data-original="http://static.bootcss.com/expo/img/a/0c/7e3ff1fa4104046f0225eca22e430.png">
                            </a>
                        </div>
                        <div class="post-content">
                            <p><a href="https://unsplash.com/">Unsplash</a></p>
                        </div>
                    </article>
                </div>


                <div class="col-xs-12 col-sm-6">
                    <article class="post tag-guo-wai-wang-zhan tag-bootstrap-v3">
                        <h2 class="post-title">
                            <a href="/microsoft-power-bi/"
                               onclick="_hmt.push(['_trackEvent', 'titlelink', 'click', 'Microsoft Power BI'])"
                               target="_blank">Microsoft Power BI</a>
                        </h2>

                        <div class="post-featured-image">
                            <a class="thumbnail" href="/microsoft-power-bi/"
                               onclick="_hmt.push(['_trackEvent', 'imagelink', 'click', 'Microsoft Power BI'])"
                               target="_blank">
                                <img src="/assets/img/loader.gif?v=ae3dba82d6" width="800" height="600"
                                     alt="Microsoft Power BI"
                                     data-original="http://static.bootcss.com/expo/img/2/4d/a6c42fe4d566c6ccb07e4301ac27b.jpg">
                            </a>
                        </div>
                        <div class="post-content">
                            <p><a href="http://powerbi.microsoft.com/">Microsoft Power BI</a></p>
                        </div>
                    </article>
                </div>


                <div class="col-xs-12 col-sm-6">
                    <article class="post tag-guo-wai-wang-zhan tag-bootstrap-v3">
                        <h2 class="post-title">
                            <a href="/twenty-over-ten/"
                               onclick="_hmt.push(['_trackEvent', 'titlelink', 'click', 'Twenty Over Ten'])"
                               target="_blank">Twenty Over Ten</a>
                        </h2>

                        <div class="post-featured-image">
                            <a class="thumbnail" href="/twenty-over-ten/"
                               onclick="_hmt.push(['_trackEvent', 'imagelink', 'click', 'Twenty Over Ten'])"
                               target="_blank">
                                <img src="/assets/img/loader.gif?v=ae3dba82d6" width="800" height="600"
                                     alt="Twenty Over Ten"
                                     data-original="http://static.bootcss.com/expo/img/4/e7/cff58fd9f7a980aaf1546bb8bdd81.jpg">
                            </a>
                        </div>
                        <div class="post-content">
                            <p><a href="https://twentyoverten.com/">Twenty Over Ten</a></p>
                        </div>
                    </article>
                </div>


                <div class="col-xs-12 col-sm-6">
                    <article class="post tag-guo-wai-wang-zhan tag-bootstrap-v3">
                        <h2 class="post-title">
                            <a href="/ing-world/"
                               onclick="_hmt.push(['_trackEvent', 'titlelink', 'click', 'ing.world'])" target="_blank">ing.world</a>
                        </h2>

                        <div class="post-featured-image">
                            <a class="thumbnail" href="/ing-world/"
                               onclick="_hmt.push(['_trackEvent', 'imagelink', 'click', 'ing.world'])" target="_blank">
                                <img src="/assets/img/loader.gif?v=ae3dba82d6" width="800" height="600" alt="ing.world"
                                     data-original="http://static.bootcss.com/expo/img/f/6c/0052253666fed35781219ccafae23.jpg">
                            </a>
                        </div>
                        <div class="post-content">
                            <p><a href="https://ingworld.ing.com/en/2015-1Q">ing.world</a></p>
                        </div>
                    </article>
                </div>


                <div class="col-xs-12 col-sm-6">
                    <article class="post tag-guo-wai-wang-zhan tag-bootstrap-v3">
                        <h2 class="post-title">
                            <a href="/plan/" onclick="_hmt.push(['_trackEvent', 'titlelink', 'click', 'Plan'])"
                               target="_blank">Plan</a>
                        </h2>

                        <div class="post-featured-image">
                            <a class="thumbnail" href="/plan/"
                               onclick="_hmt.push(['_trackEvent', 'imagelink', 'click', 'Plan'])" target="_blank">
                                <img src="/assets/img/loader.gif?v=ae3dba82d6" width="800" height="600" alt="Plan"
                                     data-original="http://static.bootcss.com/expo/img/9/35/9f2e944702f8d52922d47b16f9742.jpg">
                            </a>
                        </div>
                        <div class="post-content">
                            <p><a href="http://www.getplan.co/">Plan</a></p>
                        </div>
                    </article>
                </div>


                <div class="col-xs-12 col-sm-6">
                    <article class="post tag-guo-wai-wang-zhan tag-bootstrap-v3">
                        <h2 class="post-title">
                            <a href="/gogoro/" onclick="_hmt.push(['_trackEvent', 'titlelink', 'click', 'Gogoro'])"
                               target="_blank">Gogoro</a>
                        </h2>

                        <div class="post-featured-image">
                            <a class="thumbnail" href="/gogoro/"
                               onclick="_hmt.push(['_trackEvent', 'imagelink', 'click', 'Gogoro'])" target="_blank">
                                <img src="/assets/img/loader.gif?v=ae3dba82d6" width="800" height="600" alt="Gogoro"
                                     data-original="http://static.bootcss.com/expo/img/3/01/df0f142fb517188e25c3e10ca9377.png">
                            </a>
                        </div>
                        <div class="post-content">
                            <p><a href="http://www.gogoro.com/">Gogoro</a></p>
                        </div>
                    </article>
                </div>


                <div class="col-xs-12 col-sm-6">
                    <article class="post tag-guo-wai-wang-zhan tag-bootstrap-v3">
                        <h2 class="post-title">
                            <a href="/gitbook/" onclick="_hmt.push(['_trackEvent', 'titlelink', 'click', 'GitBook'])"
                               target="_blank">GitBook</a>
                        </h2>

                        <div class="post-featured-image">
                            <a class="thumbnail" href="/gitbook/"
                               onclick="_hmt.push(['_trackEvent', 'imagelink', 'click', 'GitBook'])" target="_blank">
                                <img src="/assets/img/loader.gif?v=ae3dba82d6" width="800" height="600" alt="GitBook"
                                     data-original="http://static.bootcss.com/expo/img/f/51/80c97ca879bff50c1e85d5fd8f32b.png">
                            </a>
                        </div>
                        <div class="post-content">
                            <p><a href="https://www.gitbook.com/">GitBook</a></p>
                        </div>
                    </article>
                </div>


                <div class="col-xs-12 col-sm-6">
                    <article class="post tag-guo-wai-wang-zhan tag-bootstrap-v3">
                        <h2 class="post-title">
                            <a href="/truth-labs/"
                               onclick="_hmt.push(['_trackEvent', 'titlelink', 'click', 'Truth Labs'])" target="_blank">Truth
                                Labs</a>
                        </h2>

                        <div class="post-featured-image">
                            <a class="thumbnail" href="/truth-labs/"
                               onclick="_hmt.push(['_trackEvent', 'imagelink', 'click', 'Truth Labs'])" target="_blank">
                                <img src="/assets/img/loader.gif?v=ae3dba82d6" width="800" height="600" alt="Truth Labs"
                                     data-original="http://static.bootcss.com/expo/img/3/8e/dc0534401c56e6a653478da853b3c.png">
                            </a>
                        </div>
                        <div class="post-content">
                            <p><a href="http://truthlabs.com/">Truth Labs</a></p>
                        </div>
                    </article>
                </div>


            </div>
            <nav class="pagination">
                <a class="newer-posts" href="/">&larr; 上一页</a>
                <span class="page-number">第 2 页/共 25 页</span>
                <a class="older-posts" href="/page/3/">下一页 &rarr;</a>
            </nav>
        </div>


    </main>

</div>

<footer>
    <div class="container">
        <div class="row">
            <div class="col-xs-12">
                <div class="submit">
                    <p class="text-center">如果你的网站基于<a href="http://www.bootcss.com/" target="_blank">Bootstrap</a>构建、并且用心的设计，那就提交到
                        <a href="mailto:youzhan@bootcss.com">youzhan@bootcss.com</a> 在这里展示吧！</p>

                    <p class="text-center">请注明“Bootstrap网站作品提交 -- 你的网址”</p>
                </div>
            </div>
        </div>
    </div>
</footer>

<script src="http://cdn.bootcss.com/jquery/1.11.3/jquery.min.js"></script>
<script src="http://cdn.bootcss.com/bootstrap/3.3.4/js/bootstrap.min.js"></script>
<script src="http://cdn.bootcss.com/jquery.lazyload/1.9.0/jquery.lazyload.min.js"></script>
<script src="http://cdn.bootcss.com/handlebars.js/3.0.3/handlebars.min.js"></script>

<script type="text/javascript" src="/assets/js/index.js?v=ae3dba82d6"></script>


<script type="text/javascript">
    var _bdhmProtocol = (("https:" == document.location.protocol) ? " https://" : " http://");
    document.write(unescape("%3Cscript src='" + _bdhmProtocol + "hm.baidu.com/h.js%3F15c141dd41d16b47f32d4c5476e1f6f4' type='text/javascript'%3E%3C/script%3E"));
</script>

<!-- 全局统计代码 -->
<script type="text/javascript">
    var _bdhmProtocol = (("https:" == document.location.protocol) ? " https://" : " http://");
    document.write(unescape("%3Cscript src='" + _bdhmProtocol + "hm.baidu.com/h.js%3F079fac161efc4b2a6f31e80064f14e82' type='text/javascript'%3E%3C/script%3E"));
</script>
