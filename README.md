# -2
无敌是寂寞的
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>{$DT["sitename"]}</title>
    <meta name="keywords" content="{$keywords}" />
    <meta name="description" content="{$description}" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="format-detection" content="telephone=no">
    <meta name="renderer" content="webkit">
    <meta http-equiv="Cache-Control" content="no-siteapp"/>
    <!--网站样式-->
    <link rel="stylesheet" href="{DT_SKIN}/css/amazeui.min.css"/>
    <link rel="stylesheet" href="{DT_SKIN}/css/reset.css"/>
    <link rel="stylesheet" href="{DT_SKIN}/css/font-awesome.css"/>
    <link rel="stylesheet" href="{DT_SKIN}/css/common.css"/>
    <link rel="stylesheet" href="{DT_SKIN}/css/index.css"/>
    <link rel="stylesheet" href="{DT_SKIN}/css/media.css"/>
    <link rel="stylesheet" href="{DT_SKIN}/css/animate.css"/>

    <!--ie 样式-->
    <!--[if lt IE 9]>
    <link rel="stylesheet" type="text/css" href="{DT_SKIN}/css/browser.css"/>
    <![endif]-->

    <!--网站js-->
    <script type="text/javascript" src="{DT_SKIN}/js/jquery-1.9.1.min.js" charset="utf-8"></script>
    <script type="text/javascript" src="{DT_SKIN}/js/amazeui.min.js" charset="utf-8"></script>
    <script type="text/javascript" src="{DT_SKIN}/js/common.js" charset="utf-8"></script>
    <script type="text/javascript" src="{DT_SKIN}/js/index.js" charset="utf-8"></script>
    <!--ie6兼容-->
    <!--[if IE 6]>
        <script type="text/javascript" src="{DT_SKIN}/js/DD_belatedPNG_0.0.8a-min.js"></script>
        <script type="text/javascript">
        DD_belatedPNG.fix('*');
        </script>
    <![endif]-->
    <!--[if IE]>
    <script src="{DT_SKIN}/js/html5shiv.min.js"></script>
    <![endif]-->
    <!--[if lte IE 8]>
        <script src="{DT_SKIN}/js/ie_browser.js"></script>
    <![endif]-->
</head>
<body>
{template "header"}
<!--header_bottom end-->
<!--头部 end-->

<!--banner begin-->
<div class="banner sliderBox">
        <ul>
<!--{php $tags=tag("table=ad&condition=pid=26&template=null");}-->
            {loop $tags $t}
                <li>
                    <a title="{$t[title]}" target="_blank">
                        <img src="{$t[image_src]}" alt="img1"/>
                    </a>
                </li>
            {/loop}
        </ul>
        <ol>

        </ol>
    </div>
</div>
<!--banner end-->

<!--puzzled begin-->
<div class="puzzled floor">
    <div class="am-container">
        <div class="title">
            <img src="{DT_SKIN}/images/puzzled_title.png" alt="困惑"/>
        </div>
        <div class="puzzled_box">
            <img src="{DT_SKIN}/images/puzzled_img.png" alt="puzzled_box" class="puzzled_box_pic"/>
            <ul id="ulone">
                <li>
                    <h4>不懂网络营销</h4>
                    <p>公司没有专业的网络营销人员
                        想营销，没方向；有营销，无策划；有问题，无法
                        解决</p>
                </li>
                <li>
                    <h4>望“网”兴叹</h4>
                    <p>看到别人家的网推做的风生水起，自己网站却门可罗雀。明明是一片蓝海，又有资金投入，就是抓不到客户</p>
                </li>
                <li>
                    <h4>网站、微信无新意</h4>
                    <p>网站内容平淡无奇，微信活动毫无创意，明明有点击量，却没有客户咨询，转化率太低，伤透脑筋</p>
                </li>
                <li>
                    <h4>费用高昂</h4>
                    <p>公司自己进行线上线下广告，投入少，没效果；有效果，但费用无法控制，不知如何是好？</p>
                </li>
                <li>
                    <h4>无人打理</h4>
                    <p>网络营销无人管，网站长时间没有更新，做了网站不等于盈利；推广无人打理，钱没了，却不知道花在哪里？</p>
                </li>
                <li>
                    <h4>网络推广平台单一</h4>
                    <p>公司网络推广只能通过百度或者360单一推广，无法覆盖广大消费者群体。</p>
                </li>
            </ul>
        </div>
    </div>
</div>
<!--puzzled end-->

<!--sever begin-->
<div class="floor sever">
    <div class="am-container">
        <div class="title">
            <img src="{DT_SKIN}/images/sever_title.png" alt="服务"/>
        </div>
        <div class="sever-grids">
            <ul>
                <li><a href="">
<!--                    {php $data=tag("table=webpage&condition=itemid=6&template=null")}-->
                    <dl>
                        <dt></dt>
                        <dd>
                            <p>{$data[0][title]}</p>
                            <a class="next" href="javascript:(void);">
                                <span class="icon-wrap"></span>
                            </a>
                        </dd>
                    </dl>

                    <!--hover-->
                    <div class="hover">
                        <div class="txt">
                            <p>{$data[0][content]}</p>
                            <a href="{$data[0][linkurl]}" class="more">Read more</a>
                        </div>
                    </div>

                </a></li>
                <li><a href="">
<!--                    {php $data=tag("table=webpage&condition=itemid=7&template=null")}-->
                    <dl>
                        <dt></dt>
                        <dd>
                            <p>{$data[0][title]}</p>
                            <a class="next" href="javascript:(void);">
                                <span class="icon-wrap"></span>
                            </a>
                        </dd>
                    </dl>

                    <!--hover-->
                    <div class="hover">
                        <div class="txt">
                            <p>{$data[0][content]}</p>
                            <a href="{$data[0][linkurl]}" class="more">Read more</a>
                        </div>
                    </div>
                </a></li>
                <li><a href="">
<!--            {php $data=tag("table=webpage&condition=itemid=8&template=null")}-->
                    <dl>
                        <dt></dt>
                        <dd>
                            <p>{$data[0][title]}</p>
                            <a class="next" href="javascript:(void);">
                                <span class="icon-wrap"></span>
                            </a>
                        </dd>
                    </dl>

                    <!--hover-->
                    <div class="hover">
                        <div class="txt">
                            <p>{$data[0][content]}</p>
                            <a href="{$data[0][linkurl]}" class="more">Read more</a>
                        </div>
                    </div>
                </a></li>
                <li><a href="">
<!--            {php $data=tag("table=webpage&condition=itemid=9&template=null")}-->
                    <dl>
                        <dt></dt>
                        <dd>
                            <p>{$data[0][title]}</p>
                            <a class="next" href="javascript:(void);">
                                <span class="icon-wrap"></span>
                            </a>
                        </dd>
                    </dl>

                    <!--hover-->
                    <div class="hover">
                        <div class="txt">
                            <p>{$data[0][content]}</p>
                            <a href="{$data[0][linkurl]}" class="more">Read more</a>
                        </div>
                    </div>
                </a></li>
                <li><a href="">
                    <dl>
                        <dt></dt>
                        <dd>
                            <p>更多产品服务</p>
                            <a class="next" href="/service/more.html">
                                <span class="icon-wrap"></span>
                            </a>
                        </dd>
                    </dl>

                    <!--hover-->
                    <div class="hover">
                        <div class="txt">
                            <p>搜索引擎优化是一种利用搜索引擎的搜索规则来提高目前网站在有关搜索引擎内的自然排名的方式。</p>
                            <a href="/service/more.html" class="more">Read more</a>
                        </div>
                    </div>
                </a></li>
            </ul>
        </div>
    </div>
</div>
<!--sever end-->

<!--case begin-->
<div class="case floor">
    <div class="am-container">
        <div class="title">
            <img src="{DT_SKIN}/images/case_title.png" alt="服务"/>
        </div>
        <div class="case_box">
            <div class="case_box_menu fl">
                <h4>行业分类</h4>
                <ul>
<!--                    {php $tags=tag("table=category&condition=moduleid=24 and parentid=17&template=null")}-->
                        {loop $tags $k $v}
                    <li>
                        <a href="{$MODULE[24]['linkurl']}{$v[linkurl]}">
                            <span style="text-align:left;">{chr(65+$k)}</span>{$v[catname]}
                        </a>
                    </li>
                        {/loop}
                </ul>
                <a href="{$MODULE[24][linkurl]}" class="more">更多案例<i>+</i></a>
            </div>
        </div>
        <div class="case_box_con fr">
            <div class="case_box_con-grids">
                <div class="case_list">
                    <div class="case_list_item">
                        <ul>
                            <li><img src="{DT_SKIN}/images/case_banner.png" alt=""></li>
                            <li><img src="{DT_SKIN}/images/case_banner.png" alt=""></li>
                            <li><img src="{DT_SKIN}/images/case_banner.png" alt=""></li>
                            <li><img src="{DT_SKIN}/images/case_banner.png" alt=""></li>
                            <li><img src="{DT_SKIN}/images/case_banner.png" alt=""></li>
                        </ul>
                    </div>
                </div>

                <div class="case_list_active">
                    <ol>
                        <li class="on"><a href="javascript:(void);">
<!--                    {php $data=tag("table=webpage&condition=itemid=6&template=null")}-->
                            <dl>
                                <a href="{$data[0][linkurl]}">
                                    <dt></dt>
                                    <dd>
                                        <h5>{$data[0][title]}</h5>
                                    </dd>
                                </a>
                            </dl>
                        </a></li>
                        <li><a href="javascript:(void);">
<!--                    {php $data=tag("table=webpage&condition=itemid=7&template=null")}-->
                            <dl>
                                <a href="{$data[0][linkurl]}">
                                    <dt></dt>
                                    <dd>
                                        <h5>{$data[0][title]}</h5>
                                    </dd>
                                </a>
                            </dl>
                        </a></li>
                        <li><a href="javascript:(void);">
<!--                    {php $data=tag("table=webpage&condition=itemid=8&template=null")}-->
                            <dl>
                                <a href="{$data[0][linkurl]}">
                                    <dt></dt>
                                    <dd>
                                        <h5>{$data[0][title]}</h5>
                                    </dd>
                                </a>
                            </dl>
                        </a></li>
                        <li><a href="javascript:(void);">
<!--                    {php $data=tag("table=webpage&condition=itemid=9&template=null")}-->
                            <dl>
                                <a href="{$data[0][linkurl]}">
                                    <dt></dt>
                                    <dd>
                                        <h5>{$data[0][title]}</h5>
                                    </dd>
                                </a>
                            </dl>
                        </a></li>
                        <li><a href="javascript:(void);">
                            <dl>
                                <a href="/service/more.html">
                                    <dt></dt>
                                    <dd>
                                        <h5>更多产品服务</h5>
                                    </dd>
                                </a>
                            </dl>
                        </a></li>
                    </ol>
                </div>
            </div>
        </div>
    </div>
</div>
<!--case end-->

<!--advantage begin-->
<div class="advantage floor">
    <div class="am-container">
        <div class="title">
            <img src="{DT_SKIN}/images/advantage_title.png" alt="优势"/>
        </div>
        <div class="advantage_list" id="advantage_list">
            <ul>
                <li>
                    <dl>
                        <dt></dt>
                        <dd>
                            <h4>专业专注</h4>
                            <p>鑫灵锐公司鑫灵锐公司核心团队来自超过6年从业经验的行业精英组建，自公司创建以来专注于搜索引擎营销的研究和服务；
                            </p>
                        </dd>
                    </dl>
                </li>
                <li>
                    <dl>
                        <dt></dt>
                        <dd>
                            <h4>领导地位</h4>
                            <p> 截止2016年鑫灵锐业务范围已经覆盖湖北各县市，无论是从技术力量还是业务范围，都已经是湖北地区搜索引擎服务领导品牌；
                            </p>
                        </dd>
                    </dl>
                </li>
                <li>
                    <dl>
                        <dt></dt>
                        <dd>
                            <h4>优质服务</h4>
                            <p>公司所有部门坚决落实“四四三一”流程，客服部严格执行2小时回复制，对客户提供全方位保障，目前客户好评率在95%以上基本达到“0”风险合作。
                            </p>
                        </dd>
                    </dl>
                </li>
                <li>
                    <dl>
                        <dt></dt>
                        <dd>
                            <h4>价值体现</h4>
                            <p>截至目前鑫灵锐已经为5000多家企业做过网络营销服务，累计为企业客户创造近百亿元产值。互联网营销浪潮不可阻挡。
                            </p>
                        </dd>
                    </dl>
                </li>
                <li>
                    <dl>
                        <dt></dt>
                        <dd>
                            <h4>合作伙伴</h4>
                            <p>鑫灵锐Alibaba和UC旗下神马搜索战略合作伙伴。神马搜索是阿里巴巴集团和UC视讯基于UC浏览器开发的一款专注于移动用户的搜索引擎。目前用户已到6亿，日均活跃用户量接近2亿，客户群体庞大。
                            </p>
                        </dd>
                    </dl>
                </li>
            </ul>
        </div>
    </div>
</div>
<!--advantage end-->

<!--合作伙伴banner-->
<div class="partners floor">
    <div class="am-container">
        <div class="txt">
            <p> 或许我们做不到您心中的100分，但我们拥有追求100分的心<br/>
                在互联网+ 企业的路上，有我们，一路相伴！<br/>
                不管您现在是才开始做网站，尝试做网络营销<br/>
                还是已经在网络营销的路上<br/>
                也还是经历过挫折，走过弯路<br/>
                甚至于怀疑、不信任<br/>
                也或者走在互联网转型的十字路口、迷茫、困惑<br/>
                只要您一直走在做企业的路上<br/>
                我们一定会携手成长，一路相伴！
            </p>
            <span>致鑫灵锐客户</span>
        </div>
    </div>
</div>


<!--新闻 begin-->
<div class="news floor">
    <div class="am-container">
        <div class="title">
            <img src="{DT_SKIN}/images/news_title.png" alt="新闻"/>
        </div>
        <div class="news_con">
<!--            {php $news=tag("moduleid=21&condition=catid=15 and level=5&template=null")}-->
            <div class="news_con-grids">
                <div class="pic fl" style="width:295px;">
                    <img width="20" src="{$news[0][thumb]}" alt=""/>
                </div>
                <div class="txt fr">
                    <a href="{$news[0][linkurl]}">
                    <h3>{$news[0][title]}<span>{date('n.d',$news[0][addtime])}<i>{date("Y",$news[0][addtime])}</i></span></h3>
                    <p>{dsubstr($news[0][introduce],420,'...')}</p>
                    </a>
                </div>
            </div>
            <div class="clearfix"></div>
            <div class="news_con_list">
                <ul>
<!--               {php $news=tag("moduleid=21&condition=catid=15 and level=1&&pagesize=3&template=null")}-->
                    {loop $news $k $v}
                    <li>
                        <a href="{$v[linkurl]}">
                            <div class="text">
                                <h3>{dsubstr($v[title],20,'...')}</h3>
                                <p style="text-indent:2em;">{dsubstr($v[introduce],120,'...')}</p>
                            </div>
                            <div class="data">
                                <h2>{date('n.d',$v[addtime])}</h2>
                                <p>{date('Y',$v[addtime])}</p>
                            </div>
                        </a>
                    </li>
                    {/loop}
<!--
                    <li>
                        <a href="">
                            <div class="text">
                                <h3>锤子发布会...</h3>
                                <p>在于赤裸裸地“；来得及发给多少
                                    了；了对方感受到；联发科对方感
                                    受到多个但是发射点发生士大夫士
                                </p>
                            </div>
                            <div class="data">
                                <h2>10.18</h2>
                                <p>2016</p>
                            </div>
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <div class="text">
                                <h3>锤子发布会...</h3>
                                <p>在于赤裸裸地“；来得及发给多少
                                    了；了对方感受到；联发科对方感
                                    受到多个但是发射点发生士大夫士
                                </p>
                            </div>
                            <div class="data">
                                <h2>10.18</h2>
                                <p>2016</p>
                            </div>
                        </a>
                    </li>
-->
                </ul>
            </div>
        </div>
    </div>
</div>
<!--新闻 end-->

<!--commitment begin-->
<div class="commitment floor">
    <div class="am-container">
        <div class="fl_con fl">
            <div class="commitment_title">
                <div class="fl">
                    <i class="fa fa-heart" aria-hidden="true"></i>
                </div>
                <div class="fr">
                    <h3>我们承诺</h3>
                    <p>四大考核指标：</p>
                    <cite>our promission</cite>
                </div>
            </div>

            <div class="fl_con_list">
                <ul>
                    <li>
                        <dl>
                            <dt>1</dt>
                            <dd>
                                销售人员不得胡乱承诺，所有承诺必须写在合同上第三方核实合
                                同内容，确保合同内容的真实规范
                            </dd>
                        </dl>
                    </li>
                    <li>
                        <dl>
                            <dt>2</dt>
                            <dd>优化达标订单高于95%</dd>
                        </dl>
                    </li>
                    <li>
                        <dl>
                            <dt>3</dt>
                            <dd>
                                客户回访满意度超过85%
                            </dd>
                        </dl>
                    </li>
                    <li>
                        <dl>
                            <dt>4</dt>
                            <dd>
                                客户问题回复不超过2小时
                            </dd>
                        </dl>
                    </li>
                </ul>
            </div>

        </div>
        <div class="fr_con fr">
            <div class="fr_con_logo">
                <img src="{DT_SKIN}/images/xlr.png" alt=""/>
            </div>
            <div class="fr_con_grids">
                <!--交互1-->
                <div class="fr_con_grids_item">
                    <div class="Welcome">
                        <h3>1欢迎参与</h3>
                        <fieldset>
                            <p>我们专长于互联网营销推广，而您比我们更懂您产
                                品的知识，所以不论网站设计还是网络营销推广，
                                我们希望您能够负责任地参与到企业营销策划中来。
                                将您对公司产品理解，对公司理念形象的
                                阐释告诉我们，我们会给你一个满意的结果。</p>
                        </fieldset>
                    </div>
                    <div class="Welcome">
                        <h3>2欢迎参与</h3>
                        <fieldset>
                            <p>我们专长于互联网营销推广，而您比我们更懂您产
                                品的知识，所以不论网站设计还是网络营销推广，
                                我们希望您能够负责任地参与到企业营销策划中来。
                                将您对公司产品理解，对公司理念形象的
                                阐释告诉我们，我们会给你一个满意的结果。</p>
                        </fieldset>
                    </div>
                    <div class="Welcome">
                        <h3>3欢迎参与</h3>
                        <fieldset>
                            <p>我们专长于互联网营销推广，而您比我们更懂您产
                                品的知识，所以不论网站设计还是网络营销推广，
                                我们希望您能够负责任地参与到企业营销策划中来。
                                将您对公司产品理解，对公司理念形象的
                                阐释告诉我们，我们会给你一个满意的结果。</p>
                        </fieldset>
                    </div>
                    <div class="Welcome">
                        <h3>4欢迎参与</h3>
                        <fieldset>
                            <p>我们专长于互联网营销推广，而您比我们更懂您产
                                品的知识，所以不论网站设计还是网络营销推广，
                                我们希望您能够负责任地参与到企业营销策划中来。
                                将您对公司产品理解，对公司理念形象的
                                阐释告诉我们，我们会给你一个满意的结果。</p>
                        </fieldset>
                    </div>
                    <i class="fa fa-times-circle fr" aria-hidden="true" id="next" title="返回"></i>
                </div>
                <!--交互2-->
                <div class="fr_con_grids_active">
                    <article>
                        <ul>
                            <li>欢迎参与</li>
                            <li>合作原则</li>
                            <li>付款后工作</li>
                            <li>我们必须有所坚持</li>
                        </ul>
                    </article>
                </div>
            </div>
            <figure>
                <p>武汉鑫灵锐是专注于互联网营销策划的外包公司，我们专长于营
                    销型网站建设、搜索引擎优化、神马推广（阿里巴巴联合UC推广）
                    竞价托管、微信搭建等业务。我们希望和您一道，在互联网+的道
                    路上一同成长。</p>
            </figure>
        </div>
    </div>
</div>
<!--commitment end-->

<!--项目内容 begin-->
{template "footer"}
</body>
</html>
