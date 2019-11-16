// =====Reject=====

// -----Anti Hijack-----

// >> Anti_ISP_JavaScript_Injection
^https?://101.251.211.235 - reject
^https?://103.249.254.113 - reject
^https?://106.75.65.92 - reject
^https?://120.132.57.41 - reject
^https?://120.132.63.203 - reject
^https?://120.26.151.246 - reject
^https?://120.55.199.139 - reject
^https?://120.76.189.132 - reject
^https?://122.226.223.163 - reject
^https?://139.196.239.52 - reject
^https?://180.76.155.58 - reject
^https?://183.131.79.30 - reject
^https?://211.155.94.198 - reject
^https?://223.6.255.99 - reject
^https?://c.minisplat.cn/ - reject
^https?://c1.minisplat.cn/ - reject
^https?://cache.changjingyi.cn/ - reject
^https?://cache.gclick.cn/ - reject

// >> Anti_ISP_Safari_Baidu_CPM_Hijack
^https?://m.coolaiy.com/b.php - reject
^https?://www.babyye.com/b.php - reject
^https?://www.gwv7.com/b.php - reject
^https?://www.likeji.net/b.php - reject

// -----AD Blocker-----
// >> 0013
^https?://.+0013.+/upload/activity/app_flash_screen_ - reject

// >> 1qianbao
^https?://d.1qianbao.com/youqian/ads/ - reject

// >> 91 Porn
^https?://192.133.+.mp4$ - reject

// >> AiRav
^https?://bbs.airav.cc/data/.+.jpg - reject
^https?://image.airav.cc/AirADPic/.+.gif - reject
^https?://m.airav.cc/images/Mobile_popout_cn.gif - reject

// >> Apple
^https?://a.applovin.com/.+/ad - reject

// >> AppSo
^https?://sso.ifanr.com/jiong/IOS/appso/splash/ - reject

// >> Auto home
^https?://adproxy.autohome.com.cn/AdvertiseService/ - reject
^https?://app2.autoimg.cn/appdfs/ - reject

// >> Baidu
(ps|sv|offnavi|newvector|ulog\.imap|newloc)(\.map)?\.(baidu|n\.shifen)\.com - reject
^https?://afd.baidu.com/afd/entry - reject
^https?://als.baidu.com/clog/clog - reject
^https?://baichuan.baidu.com/rs/adpmobile/launch - reject
^https?://bj.bcebos.com/fc-feed/0/pic/ - reject
^https?://c.tieba.baidu.com/c/p/img\?src= - reject
^https?://c.tieba.baidu.com/c/s/logtogether\?cmd= - reject
^https?://gss0.bdstatic.com/.+/static/wiseindex/img/bd_red_packet.png - reject
^https?://imgsrc.baidu.com\/forum\/pic\/item/ - reject
^https?://sm.domobcdn.com/ugc/\w/ - reject
^https?://tb1.bdstatic.com/tb/cms/ngmis/adsense/*.jpg - reject
^https?://tb2.bdstatic.com/tb/mobile/spb/widget/jump - reject

// >> Baidu Wenku
^https?://wapwenku.baidu.com/view/fengchao/ - reject
^https?://wapwenku.baidu.com/view/fengchaoTwojump/ - reject
^https?://wenku.baidu.com/shifen/ - reject

// >> Baiduyun
^https?://issuecdn.baidupcs.com/issue/netdisk/guanggao/ - reject

// >> Chelaile
^https?://pic1.chelaile.net.cn/adv/ - reject

// >> ChinaMobile
^.+/gmccapp/file/image/preloading/preloading\d{17}.jpg - reject
^https?://app.10086.cn/group - reject
^https?://app.m.zj.chinamobile.com/zjweb/SpAdvert - reject
^https?://mbusihall.sh.chinamobile.com:\d{4}/upload/v4/img/homePage/ - reject
^https?://\w{2}.10086.cn/gmccapp/file/image/homepage/adver - reject
^https?://\w{2}.10086.cn/upfile/khd/loadingpage/ - reject

// >> ChinaRailcom
^https?://211.98.70.226:8080/ - reject
^https?://211.98.71.195:8080/ - reject
^https?://211.98.71.196:8080/ - reject

// >> ChinaTelecom
^https?://image1.chinatelecom-ec.com/images/.+/\d{13}.jpg - reject

// >> ChinaUnicom
^https://\w{11,12}.wo.com.cn - reject
^https?://m.client.10010.com/mobileService/activity/get_client_adv - reject
^https?://m.client.10010.com/mobileService/activity/get_startadv - reject
^https?://m1.ad.10010.com/noticeMag/images/imageUpload/2\d{3} - reject
^https?://res.mall.10010.cn/mall/common/js/fa.js?referer= - reject

// >> Cmblife
^https?://mlife.cmbchina.com/ClientFace/preCacheAdvertise.json - reject

// >> DangDang
^https?://img\d{2}.ddimg.cn/upload_img/.+/670x900 - reject
^https?://img\d{2}.ddimg.cn/upload_img/.+/750x1064 - reject
^https?://mapi.dangdang.com/index.php\?action=init&user_client=iphone - reject

// >> Discuz
^https?://discuz.gtimg.cn/cloud/scripts/discuz_tips.js - reject

// >> Douban
^https?://(\d{1,3}\.){1,3}\d{1,3}/view/dale-online/dale_ad/ - reject
^https?://api.douban.com/v2/app_ads/common_ads - reject
^https?://frodo.douban.com/api/v2/movie/banner - reject
^https?://img\d.doubanio.com/rda - reject
^https?://img\d.doubanio.com/view/dale-online/dale_ad/ - reject

// >> Douyin
^https?://aweme.snssdk.com/aweme/v1/screen/ad/ - reject

// >> Douyu
^https?://capi.douyucdn.cn/api/v1/getStartSend - reject
^https?://capi.douyucdn.cn/lapi/sign/appapi/getinfo - reject
^https?://douyucdn.cn/.+/appapi/getinfo - reject
^https?://staticlive.douyucdn.cn/.+/getStartSend - reject
^https?://staticlive.douyucdn.cn/upload/signs/ - reject

// >> ele
^https?://elemecdn.com/.+/sitemap - reject
^https?://m.elecfans.com/static/js/ad.js - reject
^https?://www1.elecfans.com/www/delivery/ - reject

// >> ElongClient
^http?://123.59.30.10/adv/advInfos - reject
^https?:\/\/.+/(adgateway|adv)/ - reject

// >> Facebook
^https?://connect.facebook.net/en_US/fbadnw.js - reject

// >> Flow cbb
^https?://bank.wo.cn/v9/getstartpage - reject

// >> Guopan
^https?://sapi.guopan.cn/get_buildin_ad - reject

// >> Guotai
^https?://dl.app.gtja.com/operation/config/startupConfig.json - reject

// >> Haiyan
^https?://img.ihytv.com/material/adv/img/ - reject

// >> Huasheng
^https?://cmsfile.wifi8.com/uploads/png/ - reject

// >> HuomaoTV
^https?://api.huomao.com/channels/loginAd - reject

// >> Hupu
^https?://i1.hoopchina.com.cn/blogfile/.+_750x1334 - reject

// >> Ifeng
^https?://api.newad.ifeng.com/ClientAdversApi1508\?adids= - reject
^https?://exp.3g.ifeng.com/coverAdversApi\?gv=. - reject
^https?://ifengad.3g.ifeng.com/ad/pv.php\?stat= - reject
^https?://iis1.deliver.ifeng.com/getmcode\?adid= - reject

// >> IfengNews
^https?://c1.ifengimg.com/.+_w1080_h1410.jpg - reject

// >> ios.win007
^https?://ios.win007.com/Phone/images - reject

// >> IQIYI
^https?://.+/cdn/qiyiapp/\d{8}/.+&dis_dz= - reject
^https?://.+/cdn/qiyiapp/\d{8}/.+&z=\w - reject

// >> JD
^https?://111.13.29.201/client.action\?functionId=start - reject
^https?://api.m.jd.com/client.action\?functionId=start - reject
^https?://m.360buyimg.com/mobilecms/s640x1136_jfs/ - reject

// >> JDjr
^https?://ms.jr.jd.com/gw/generic/base/na/m/adInfo - reject

// >> Jiakaobaodian
^https?://789.kakamobi.cn/.+adver - reject
^https?://smart.789.image.mucang.cn/advert - reject

// >> Jiankang 160
^https?://images.91160.com/primary/ - reject

// >> Jiemian News
^https?://img.jiemian.com/ads/ - reject

// >> KFC
^https?://res.kfc.com.cn/advertisement/ - reject

// >> Kuaidi100
^https?://cdn.kuaidi100.com/images/open/appads - reject
^https?://p.kuaidi100.com/mobile/mainapi.do - reject
^https?://qzonestyle.gtimg.cn/qzone/biz/gdt/mob/sdk/ios/v2/ - reject

// >> Kuaikanmanhua
^https?://api.kkmh.com/v3/ad/show - reject

// >> Laifeng Live
^https?://api.laifeng.com/v1/start/ads - reject

// >> Lanrentingshu
^https?://118.178.214.118/yyting/advertclient/ClientAdvertList.action - reject
^https?://dapis.mting.info/yyting/advertclient/ClientAdvertList.action - reject

// >> Meituan Waimai
^https?://p\d{1}.meituan.net/wmbanner/ - reject

// >> MiFit
^https?://api-mifit-cn.huami.com/.+/app/startpages.json - reject
^https?://api-mifit-cn.huami.com/.+/soc/well/list/community - reject
^https?://api-mifit-cn.huami.com/discovery/mi/discovery/homepage_ad - reject
^https?://api-mifit-cn.huami.com/discovery/mi/discovery/sport_ad - reject
^https?://api-mifit.huami.com/.+/app/startpages.json - reject
^https?://api-mifit.huami.com/.+/soc/well/list/community - reject
^https?://api-mifit.huami.com/discovery/mi/discovery/homepage_ad - reject
^https?://api-mifit.huami.com/discovery/mi/discovery/sport_ad - reject
^https?://hm.xiaomi.com/.+/app/startpages.json - reject
^https?://hm.xiaomi.com/.+/soc/well/list/community - reject
^https?://hm.xiaomi.com/discovery/mi/discovery/homepage_ad - reject
^https?://hm.xiaomi.com/discovery/mi/discovery/sport_ad - reject

// >> Moji
^https?://ad.api.moji.com/ad/log/stat - reject
^https?://ast.api.moji.com/assist/ad/moji/stat - reject
^https?://cdn.moji.com/adlink/avatarcard - reject
^https?://cdn.moji.com/adlink/common - reject
^https?://cdn.moji.com/adlink/splash/ - reject
^https?://cdn.moji.com/advert/ - reject
^https?://cdn2.moji002.com/webpush/ad2/ - reject
^https?://fds.api.moji.com/card/recommend - reject
^https?://show.api.moji.com/json/showcase/getAll - reject
^https?://stat.moji.com - reject
^https?://storage.360buyimg.com/kepler-app - reject
^https?://ugc.moji001.com/sns/json/profile/get_unread - reject

// >> Netease
^https?://mimg.127.net/external/smartpop-manger.min.js - reject

// >> Netease Music
^https?://.+?163.com/madr?app=\b.+platform=\b.+uid - reject
^https?://dongfeng.alicdn.com/.+\d{4}y\d{3} - reject
^https?://haitaoad.nosdn.127.net/ad - reject
^https?://iadmat.nosdn.127.net/ad - reject
^https?://iadmatvideo.nosdn.127.net/ad - reject
^https?://music.163.com/eapi/ad/ - reject

// >> Netease News
^https?://g1.163.com/madfeedback - reject
^https?://img1.126.net/.+dpi=6401136 - reject
^https?://img1.126.net/channel14/ - reject
^https?://nex.163.com/q - reject

// >> Panda TV
^https?://static.api.m.panda.tv/index.php\?method=clientconf\.firstscreen - reject

// >> Peanut
^https?://cmsapi.wifi8.com/v1/emptyAd/info - reject
^https?://cmsapi.wifi8.com/v2/adNew/config - reject

// >> Qidiandushu
^https?://mage.if.qidian.com/Atom.axd/Api/Client/GetConfIOS - reject

// >> QQ Misic
^https?://.+/music/common/upload/t_splash_info - reject
^https?://.+/tips/fcgi-bin/fcg_get_advert - reject
^https?://y.gtimg.cn/music/common/upload/targeted_ads - reject

// >> QQ Pim
^https?://mmgr.gtimg.com/gjsmall/qqpim/public/ios/splash/.+/\d{4}_\d{4} - reject

// >> Shenzhou auto
^https?://img01.10101111cdn.com/adpos/share/ - reject

// >> Shouyue auto
^https?://img.yun.01zhuanche.com/statics/app/advertisement/.+-750-1334 - reject

// >> Snail Sleep
^https?:\/\/snailsleep\.net\/snail\/v1\/screen\/qn\/get\? - reject
^https?:\/\/snailsleep\.net\/snail\/v1\/adTask\/ - reject

// >> Sohu
^https?://agn.aty.sohu.com/m? - reject
^https?://api.tv.sohu.com/mobile/control/switch.json? - reject
^https?://api.tv.sohu.com/mobile_user/device/clientconf.json? - reject
^https?://api.tv.sohu.com/mobile_user/push/uploadtoken.json? - reject
^https?://api.tv.sohu.com/v4/mobile/albumdetail.json? - reject
^https?://api.tv.sohu.com/v4/mobile/albumdetail.json\?poid= - reject
^https?://api.tv.sohu.com/v4/mobile/control/switch.json? - reject
^https?://hui.sohu.com/predownload2/? - reject
^https?://m.aty.sohu.com/openload? - reject
^https?://mbl.56.com/config/v1/common/config.union.ios.do? - reject
^https?://mmg.aty.sohu.com/mqs? - reject
^https?://mmg.aty.sohu.com/pvlog? - reject
^https?://photocdn.sohu.com/tvmobilemvms - reject
^https?://s.go.sohu.com/adgtr/\?gbcode= - reject
^https?://s1.api.tv.itc.cn/v4/mobile/feeling/list.json - reject
^https?://s1.api.tv.itc.cn/v4/mobile/searchFunctionConfig/list.json - reject

// >> StarFans
^https?://g.cdn.pengpengla.com/starfantuan/boot-screen-info/ - reject

// >> Taobao
^https?://gw.alicdn.com/imgextra/i\d/.+960x960.+ - reject
^https?://gw.alicdn.com/tfs/.+-1125-1602 - reject

// >> Tencent
^https?://imgcache.qq.com/qqlive/ - reject
^https?://mi.gdt.qq.com\/gdt_mview.fcg\?posid= - reject
^https?://mp.weixin.qq.com/mp/report - reject
^https?://news.l.qq.com\/app\? - reject
^https?://r.inews.qq.com/adsBlacklist - reject
^https?://r.inews.qq.com/getBannerAds - reject
^https?://r.inews.qq.com/getFullScreenPic - reject
^https?://r.inews.qq.com/getNewsRemoteConfig - reject
^https?://r.inews.qq.com/getSplash\?apptype=ios\&startarticleid=\&__qnr= - reject
^https?://r.inews.qq.com/searchHotCatList - reject
^https?://r.inews.qq.com/upLoadLoc - reject

// >> Tencent guanjia
^https?://mmgr.gtimg.com/gjsmall/qiantu/upload/ - reject

// >> Tencent live
^https?://bla.gtimg.com/qqlive/\d{6}.+.png - reject
^https?://lives.l.qq.com/livemsg\?sdtfrom= - reject
^https?://splashqqlive.gtimg.com/website/\d{6} - reject

// >> The Paper
^https?:\/\/adpai\.thepaper\.cn\/.+&ad= - reject

// >> Tianshan live
^http?://www.tsytv.com.cn/api/app/ios/ads - reject

// >> Toutiao
^https?://pb\d{1}.pstatp.com/origin - reject
^https?://p\d{1}.pstatp.com/origin - reject

// >> ttlrs
^https?://img.53site.com/Werewolf/AD/ - reject
^https?://werewolf.53site.com/Werewolf/.+/getAdvertise.php - reject

// >> Weibo
^https?://sdkapp.uve.weibo.com/interface/sdk/sdkad.php - reject
^https?://simg.s.weibo.com/.+_ios\d{2}.gif - reject
^https?://u1.img.mobile.sina.cn/public/files/image/\d{3}x\d{2,4} - reject

// >> Weico
^https?://.+/portal.php\?a=get_ads - reject
^https?://.+/portal.php\?a=get_coopen_ads - reject
^https?://.+/portal.php\?c=duiba - reject
^https?://.+/weico4ad/ad/ - reject
^https?://weicoapi.weico.cc/img/ad/ - reject

// >> Weihou
^https?://api.app.vhall.com/v5/000/webinar/launch - reject

// >> Weiyi
^https?://kano.guahao.cn/.+\?resize=\w{3}-\w{4} - reject

// >> Wiki

// >> Xiachufang
^https?://api.xiachufang.com/v2/ad/ - reject

// >> Xianyu
^https?://gw.alicdn.com/mt/ - reject
^https?://gw.alicdn.com/tfs/.+\d{3,4}-\d{4} - reject
^https?://gw.alicdn.com/tps/.+\d{3,4}-\d{4} - reject

// >> Ximalaya
^https?://adse.+\.com\/[a-z]{4}\/loading\?appid= - reject
^https?://adse.ximalaya.com\/ting\/feed\?appid= - reject
^https?://adse.ximalaya.com\/ting\/loading\?appid= - reject
^https?://adse.ximalaya.com\/ting\?appid= - reject
^https?://fdfs.xmcdn.com/group21/M03/E7/3F/ - reject
^https?://fdfs.xmcdn.com/group21/M0A/95/3B/ - reject
^https?://fdfs.xmcdn.com/group22/M00/92/FF/ - reject
^https?://fdfs.xmcdn.com/group22/M05/66/67/ - reject
^https?://fdfs.xmcdn.com/group22/M07/76/54/ - reject
^https?://fdfs.xmcdn.com/group23/M01/63/F1/ - reject
^https?://fdfs.xmcdn.com/group23/M04/E5/F6/ - reject
^https?://fdfs.xmcdn.com/group23/M07/81/F6/ - reject
^https?://fdfs.xmcdn.com/group23/M0A/75/AA/ - reject
^https?://fdfs.xmcdn.com/group24/M03/E6/09/ - reject
^https?://fdfs.xmcdn.com/group24/M07/C4/3D/ - reject
^https?://fdfs.xmcdn.com/group25/M05/92/D1/ - reject

// >> Ydstatic
^https?://oimage\w\d.ydstatic.com/image\?.+=adpublish - reject

// >> Yiche
^https?://api.ycapp.yiche.com/appnews/getadlist - reject
^https?://api.ycapp.yiche.com/yicheapp/getadlist - reject
^https?://api.ycapp.yiche.com/yicheapp/getappads/ - reject
^https?://cheyouapi.ycapp.yiche.com/appforum/getusermessagecount - reject

// >> Youdao
^https?://dict.youdao.com/infoline/style\?client= - reject
^https?://gorgon.youdao.com/gorgon/request.s\?v= - reject
^https?://impservice.dictapp.youdao.com/imp/request.s\?req= - reject

// >> Youdao Translation
^https?://dict.youdao.com/infoline/style\?client=translator&apiversion=3.0&lastId=0&style=fanyiguantuijian - reject
^https?://oimagec2.ydstatic.com/image\?id=.+&product=adpublish - reject

// >> Youku
^https?://.+&duration=\d{2}& - reject
^https?://ad.api.3g.youku.com - reject
^https?://api.appsdk.soku.com/bg/r - reject
^https?://api.appsdk.soku.com/tag/r - reject
^https?://api.k.sohu.com/api/channel/ad/ - reject
^https?://api.mobile.youku.com/adv/ - reject
^https?://api.mobile.youku.com/layout/search/hot/word - reject
^https?://hd.api.mobile.youku.com/common/v3/hudong/new - reject
^https?://hd.mobile.youku.com/common/v3/hudong/new - reject
^https?://k.youku.com/player/getFlvPath/ - reject
^https?://m.youku.com/video/libs/iwt.js - reject
^https?://pic.k.sohu.com/img8/wb/tj/ - reject
^https?://r.l.youku.com/rec_at_click - reject
^https?://r1.ykimg.com/material/.+/\d{3,4}-\d{4} - reject
^https?://r1.ykimg.com/material/.+/\d{6}/\d{4}/ - reject
^https?://r1.ykimg.com/\w{30,35}.jpg - reject

// >> Youtube
^https?://m.youtube.com/_get_ads - reject
^https?://pagead2.googlesyndication.com/pagead/ - reject
^https?://s0.2mdn.net/ads/ - reject
^https?://stats.tubemogul.com/stats/ - reject

// >> Zhangyue
^https?://book.img.ireader.com/group6/M00 - reject

// >> Zhaoshang cbb
^https?://pic1cdn.cmbchina.com/appinitads/ - reject

// >> Zhihu
^https?://api.zhihu.com/launch - reject
^https?://api.zhihu.com/real_time_launch - reject

// >> ZhuiShu
^https?://api.zhuishushenqi.com/advert - reject
^https?://api.zhuishushenqi.com/notification/shelfMessage - reject
^https?://api.zhuishushenqi.com/recommend - reject
^https?://api.zhuishushenqi.com/splashes/ios - reject
^https?://mi.gdt.qq.com/gdt_mview.fcg - reject
// Update
^https?://api.zhuishushenqi.com/user/bookshelf-updated - reject
^https?://itunes.apple.com/lookup\?id=575826903 - reject

// >> Other
^.+/ad(s|v)?.js - reject
^.+allOne.php\?ad_name=main_splash_ios - reject
^.+nga.cn.+\bhome.+\b=ad - reject
^.+resource=article\/recommend\&accessToken= - reject
^https?://113.200.76.*:16420/sxtd.bike2.01/getkey.do - reject
^https?://creatives.ftimg.net/ads/ - reject
^https?://dd.iask.cn/ddd/adAudit - reject
^https?://g.tbcdn.cn/mtb/ - reject
^https?://gorgon.youdao.com\/gorgon\/request\.s\?v= - reject
^https?://huichuan.sm.cn/jsad? - reject
^https?://impservice.youdao.com\/imp\/request\.s\?req= - reject
^https?://iphone265g.com/templates/iphone/bottomAd.js - reject
^https?://m.+.china.com.cn/statics/sdmobile/js/ad - reject
^https?://m.+.china.com.cn/statics/sdmobile/js/mobile.advert.js - reject
^https?://m.+.china.com.cn/statics/sdmobile/js/mobileshare.js - reject
^https?://m.elecfans.com/static/js/ad.js - reject
^https?://mi.gdt.qq.com\/gdt_mview.fcg\?posid= - reject 
^https?://nga\.cn.+\bhome.+\b=ad - reject
^https?://player.hoge.cn/advertisement.swf - reject
^https?://ress.dxpmedia.com/appicast/ - reject
^https?://s1.api.tv.itc.cn/v4/mobile/feeling/list.json\?api_key= - reject
^https?://s3.pstatp.com/inapp/TTAdblock.css - reject
^https?://statc.mytuner.mobi/media/banners/ - reject
^https?://static.cnbetacdn.com/assets/adv - reject
^https?://static.iask.cn/m-v20161228/js/common/adAudit.min.js - reject
^https?://v.17173.com/api/Allyes/ - reject
^https?://wmedia-track.uc.cn - reject
^https?://www.ft.com/__origami/service/image/v2/images/raw/https%3A%2F%2Fcreatives.ftimg.net%2Fads* - reject
^https?://www.inoreader.com/adv/ - reject
^https?://www.lianbijr.com/adPage/ - reject
