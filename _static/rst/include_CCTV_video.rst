
.. raw:: html

    <head>
    <SCRIPT LANGUAGE="JavaScript">
        var url_domainname = location.href;
        var str1_dm = url_domainname.substring(7, url_domainname.length);
        var num_ = str1_dm.indexOf("/");
        var domainame_ = str1_dm.substring(0, num_);
        var type_str = domainame_.indexOf(".");
        var type_ = domainame_.substring(0, type_str);
        var commentTitle = "《走近科学》 20171213 潜入深海（上）"; /*评论标题*/
        /* 评论对象ID 20位以内的字符串 每个被评论对象不同 */
        var itemid1 = "VIDEedA5wLi8E6g69L7B3w73171213";/*正文页id，赋值给留言评论模块的参数之一*/
        var commentUrl = "http://tv.cctv.com/2017/12/13/VIDEedA5wLi8E6g69L7B3w73171213.shtml";
        var column_id = "TOPC1451558190239536";/*专题id*/
        var sub_column_id = "PAGEtzC1QjHdEia6x3BnUTv1160120";/*页面id*/
        var video_ad_tvcctvlanmu = "";
        var domainname = domainame_;
        var chnl_domain = domainame_;
        var video_ad_primary_column_id = sub_column_id;
        var video_ad_channel_id = "CHAL1450953121759377";
        var sobey_video_flag = '1';
        var type = type_;
        var pindao_1 = "CHAL1450953121759377";
        var dateNum = (new Date()).toLocaleDateString() + " " + (new Date()).toLocaleTimeString();
        var times_str = dateNum.replace(/年/g, '-').replace(/月/g, '-').replace(/日/g, '-').replace(/:/g, '-');
        var new_str = times_str.replace(/ /g, '-');
        var arr = new_str.split("-");
        var datum = new Date(Date.UTC(arr[0], arr[1] - 1, arr[2] - 2, arr[3] - 8, arr[4], arr[5]));
        var timeint = datum.getTime() / 1000;
        var html;
        var sorts_dianji = sub_column_id + ',' + column_id + ',' + itemid1.substring(0, 4);
        function loadData() {
            var urls = "http://bbs.cntv.cn/cctvapi/Comment/icms_comment.php?id=" + id + "&type=" + type;
            html = $.ajax({
                url: urls,
                async: false
            }).responseText;
            html = html.replace('article_comment_count=', '').replace(';', '');
            html = "评论(" + html + ")";
            $("#content").html(html);
        }
    </SCRIPT>
    <!--专题模版通用脚本统一调用-->
    <link href="http://p1.img.cctvpic.com/photoAlbum/templet/common/DEPA1452928146750159/videoStyle2017.css"
        rel="stylesheet" type="text/css" />
    <script type="text/javascript" src="http://r.img.cctvpic.com/library/content/tw/script/a2.js"></script>
    <script type="text/javascript" src="http://r.img.cctvpic.com/library/content/tw/script/newDJpfdc.js"></script>
    <script type="text/javascript" src="http://r.img.cctvpic.com/library/content/tw/script/share.js"></script>
    <script type="text/javascript" src="http://r.img.cctvpic.com/library/content/tw/script/top.js"></script>
    <script type="text/javascript" src="http://r.img.cctvpic.com/library/script/jquery-1.7.2.min.js"></script>
    <script src="http://p1.img.cctvpic.com/photoAlbum/templet/common/DEPA1452765360136771/cnt_nav.js"
        type="text/javascript" charset="gbk"></script>

    </head>

    <body>

    <div class="video">
        <a class="right_but"><img
                src="http://p1.img.cctvpic.com/photoAlbum/templet/common/DEPA1452928146750159/right_butpng_03.png"
                width="15" height="500" title="" /></a>
        <div class="nr_1">
            <div class="video_left">
                <div id="myFlash" style="position: relative;"></div> <a class="left_but"><img
                        src="http://p1.img.cctvpic.com/photoAlbum/templet/common/DEPA1452928146750159/left_butpng_03.png"
                        width="15" height="500" title="" /></a>
            </div>

            <!--下面是播放器 start player-->
            <script type="text/javascript">
                var videokeyWord = "走近科学，蛟龙号，龙旂作业区，热液喷口，树脂玻璃";//暂未实现
                var video_CHANNEL = "PAGEtzC1QjHdEia6x3BnUTv1160120";//主分类id
            </script>
            <script type="text/javascript" src="http://www.cctv.com/js/cntv_Advertise.js"></script>
            <script type="text/javascript" src="http://www.cctv.com/playcfg/video_content.js"></script>
            <script type="text/javascript">
                var channelId = domainame_;//频道id
                var adcalldomain = domainame_;
                var width = "670";
                var height = "500";
                var sysSource = channelId; //视频来源
                var isLogin = isLogin_115;//用户中心相关
                var userId = userId_115;//用户中心相关
                var sorts = "1";
                var guid = "3182e9ba66af4bcbb05295218bd01265";
            </script>
            <script type="text/javascript" src="http://www.cctv.com/js/video_type.js"></script>
            <script type="text/javascript" src="http://js.player.cntv.cn/creator/common_standard.js"></script>
            <script type="text/javascript">
                function loading_video() {
                    var fo = createCommonPlayer("vplayer", width, height, type_video);
                    fo.addVariable("videoId", "dA5wLi8E6g69L7B3w73171213");//视频id
                    fo.addVariable("scheduleId", "走近科学，蛟龙号，龙旂作业区，热液喷口，树脂玻璃");//关键字
                    fo.addVariable("filePath", "/flvxml/2009/10/14/");//txt路径
                    fo.addVariable("sysSource", sysSource);//视频来源
                    fo.addVariable("url", "http://tv.cctv.com/2017/12/13/VIDEedA5wLi8E6g69L7B3w73171213.shtml");//视频url
                    fo.addVariable("videoCenterId", "3182e9ba66af4bcbb05295218bd01265");//视频生产中心guid (必要值)
                    fo.addVariable("adCall", ad_Call);//前贴片广告
                    fo.addVariable("adPause", ad_Pause);//暂停广告
                    fo.addVariable("adAfter", ad_After);//后贴片广告
                    fo.addVariable("adCorner", ad_Corner);//角标广告
                    fo.addVariable("adCurtain", ad_Curtain);//跑马灯广告
                    fo.addParam("wmode", "Transparent");//Transparent在IE下标签(顶通)可以显示在播放窗口之上
                    writePlayer(fo, "myFlash");
                }
                setTimeout(loading_video, 1000);//延时1秒
            </script>
            <!--播放器 end-->
        </div>


    </div>

    </body>
