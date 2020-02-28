# beifen2019
注意代理模式设置为全局，安卓客户端的代理模式在路由那里(默认全局，无需修改)，IOS小火箭的全局路由改成代理模式就可以了，理论支持电信联通所有互联网套餐卡！下面是各种卡对应的混淆参数。
所有混淆参数接入点都优先net！！！
如果要用免流代理必须选全局代理！
####(联通卡优先使用)
电信百度大圣卡（全国所有省份必免）：dx-baiducdnct.inter.iqiyi.com
全国联通沃商店：game.hxll.wostore.cn
全国联通沃商店：music.hxll.wostore.cn
沃阅读混淆参数：partner.iread.wo.com.cn
全国联通沃商店高级：game.hxll.wostore.cn
全国联通沃商店高级：music.hxll.wostore.cn
沃阅读高级：partner.iread.wo.com.cn
##通用免流混淆参数A
电信百度大圣卡（全国所有省份必免）：dx-baiducdnct.inter.iqiyi.com
QQ音乐混淆参数：dl.stream.qqmusic.com
梦想e卡混淆参数：imhdfs.icbc.com.cn
梦想e卡混淆参数(福建已免)：v.icbc.com.cn
爱奇艺混淆参数：data.video.qiyi.com
优酷混淆参数：vali-dns.cp31.ott.cibntv.net
高德地图混淆参数：mps.amap.com
央视影音混淆参数：asp.cntv.myalicdn.com
百度贴吧混淆参数：static.tieba.baidu.com
微信混淆参数(遵义广州已免)：short.weixin.qq.com
虾米音乐混淆参数：pic.xiami.net
天翼视讯混淆参数：vod3.nty.tv189.cn
钉钉混淆参数：tms.dingtalk.com
微博混淆参数：tobe.vip.weibo.com
微博混淆参数：new.vip.weibo.cn
微博混淆参数：simg.s.weibo.com
优酷混淆参数：push.m.youku.com
优酷混淆参数：api.mobile.youku.com
书旗混淆参数：spend1.shuqireader.com
书旗混淆参数：c1.shuqireader.com
优酷混淆参数：www.youku.com
###通用免流混淆参数B
电信百度大圣卡（全国所有省份必免）：dx-baiducdnct.inter.iqiyi.com
优酷：vali-dns.cp31.ott.cibntv.net#Range:bytes=25165824-32586598\nAccept: /
爱看4G：ltevod.tv189.cn#Connection: Keep-Alive\nAccept-Encoding: gzip
沃音乐：woif.10155.com#Accept-Encoding: gzip
微信(深圳已免)：szminorshort.weixin.qq.com#Upgrade: mmtls\nAccept: /\nConnection: close\nContent-Length: 533\nContent-Type: application/octet-stream
淘宝：adashbc.m.taobao.com#Accept-Encoding: gzip
央视影音：asp.cntv.myalicdn.com#Icy-MetaData: 1
抖音：dm.toutiao.com#Connection: Keep-Alive\nAccept-Encoding: gzip
百度：tbcdn.hiphotos.baidu.com#needginfo: 1/nConnection: Keep-Alive/nUser-Agent: bdtb for Android 9.0.8.0
爱奇艺：data.video.qiyi.com#Accept: /
美团：apimeishi.meituan.com#Connection: Keep-Alive
高德地图：mps.amap.com#Connection: Keep-Alive\nAccept-Encoding: gzip\nContent-Length: 680
###移动
www.10086.cn
mm.10086.cn
抖音卡头条卡定向 有定向包可用：dm.toutiao.com
抖音卡头条卡定向 有定向包可用：v9-dy.ixigua.com
###电信
电信百度大圣卡（全国所有省份必免）：dx-baiducdnct.inter.iqiyi.com
天翼视讯：h5.nty.tv189.com
天翼视讯：vod3.nty.tv189.cn
爱玩4G：open.4g.play.cn
爱看4G： ltetp.tv189.com
湖北电信：hb.10000shequ.com
湖北电信：hb.10000shequ.com:8081
电信天翼：dy3.nty.tv189.cn
电信天翼：ltewap.tv189.com
电信天翼：tp.nty.tv189.com
电信大王卡(可欠费使用)：lt.hn.189.cn:1082
阿里鱼卡：mps.amap.com#Connection: Keep-Alive\nAccept-Encoding: gzip\nContent-Length: 680
###联通
腾讯大王卡（优先测试，已免90%省份！）：wx.qlogo.cn#X-Online-Host: wx.qlogo.cn\nreferer: http://weixin.qq.com/?version=63 ... 13000&signal=77\nConnection: Keep-Alive
山东联通：m.t.17186.cn
联通114圣子全国：114.255.201.163(重庆、河南、福建、湖南等地)
哔哩哔哩：i1.hdslb.com
哔哩哔哩：i0.hdslb.com
浙江联通wo+：w.zj165.com
联通wotv全国：wotv.17wo.cn（浙江、安徽、江苏）
河北：hb.10000shequ.com
湖北(优先wap接入点不免net)：box.10155.com
沃音乐：box.10155.com
沃阅读：partner.iread.wo.com.cn
工商e卡：v.icbc.com.cn
m.icbc.com.cn
m.mall.icbc.com.cn
elife.icbc.com.cn
act.icbc.com.cn
hit.icbc.com.cn
pv.mall.icbc.com.cn
mybank.icbc.com.cn
腾讯大王卡（优先测试，已免90%省份！）：wx.qlogo.cn#X-Online-Host: wx.qlogo.cn\nreferer: http://weixin.qq.com/?version=63 ... 13000&signal=77\nConnection: Keep-Alive
腾讯大王卡：szminorshort.weixin.qq.com#Upgrade: mmtls\nAccept: /\nConnection: close\nContent-Length: 533\nContent-Type: application/octet-stream
腾讯大王卡：tx.flv.huya.com
腾讯大王卡：short.weixin.qq.com
腾讯大王卡：szextshort.weixin.qq.com
short.weixin.qq.com
电信百度大圣卡（全国所有省份必免）：dx-baiducdnct.inter.iqiyi.com
百度圣卡：data.video.qiyi.com
阿里宝卡：vali-dns.cp31.ott.cibntv.net
阿里宝卡：gw.alicdn.com
api.mobile.youku.com
米粉卡混淆参数：api.ad.xiaomi.com
〖微信〗mmbiz.qpic.cn
〖微信〗shmmsns.qpic.cn
〖QQ〗r.vip.qq.com
〖QQ〗m.qpic.cn
〖王者荣耀〗down-update.qq.com
〖王者荣耀〗140.207.122.139
〖王者茉耀〗58.247.215.101
〖支付宝〗mdap.alipay.com
〖芒果TV〗pcvideows.titan.mgtv.com
〖西瓜视频〗v6-ppx.ixigua.com
〖快手〗api.gifshow.com
〖快手〗ali2.a.yximgs.com
〖头条〗sf1-ttcdn-tos.pstatp.com
〖新浪微博〗mjs.sinaimg.cn
〖快手〗api.ksapisrv.com
〖QQ音乐〗dl.stream.qqmusic.qq.com
〖百度〗pic.rmb.bdstatic.com
〖UC〗serverfile. ac.uc.cn
〖网易〗s3.music.126.net
〖微云〗sz-download.weiyun.com
〖微云〗sh-download.weiyun.com
〖微信〗mmbiz.qpic.cn
〖百度〗vd3.bdstatic.com
〖微信〗shmmsns.qpic.cn
〖抖音〗v1-dy.ixigua.com
〖腾讯视频〗livep.l.qq.com
〖QQ空间登陆页面〗qzonestyle.gtimg.cn
〖抖音/头条〗log.snssdk.com
〖西瓜视频〗api.huoshan.com
〖西瓜视频〗v11-xg.ixigua.com
〖西瓜视频〗v9-dy-x.ixigua.co
〖爱奇艺〗t7z.cupid.iqiyi.com
〖百度知道〗zhidao.baidu.com
〖好看视频/百度系〗hpd.baidu.com
〖好看视频〗sv.baidu.com
〖腾讯视频〗pgdt.gtimg.cn

举个例子:联通卡不管什么套餐请优先用沃商店混淆！例如使用的是联通大王卡，大王卡对微信是免流的，所以使用微信混淆参数，通过联通掌上营业厅查询免费流量使用总量增加就是免流成功！而大王卡当月超过40G是不计算大王卡免费应用的！所以40G后使用全国混淆即可继续免流！或者不用微信直接用全国混淆也行！，要免流代理模式必须全局！接入点优先net！链接国内节点后软件提示无网络正常！软件测试的是能否访问谷歌！不影响免流正常使用！
