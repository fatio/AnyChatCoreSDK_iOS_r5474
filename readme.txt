
   		    AnyChat for iOS SDK （V6.0）


    欢迎您选择佰锐科技的产品，我们将以“锐意创新 引领未来”的佰锐精神为您提供
优质的产品和服务。

一、SDK包概述

    AnyChat是一套跨平台的音、视频即时通讯解决方案，支持Windows、Linux、Web浏览
器、Android、iOS等操作系统平台，提供客户端SDK、服务器端SDK，可与第三方平台紧密
集成。

    AnyChat for iOS SDK基于iOS 5.1研发，支持iPhone 4、iPhone 4S、iPhone5、iPhone5S
iPhone5C、iPhone 6以及iPhone 6 Plus等设备，同时也支持iPad3、iPad4、iPad mini设备，
提供Objective-C接口，支持iOS全系列架构（i386、x86_64、armv7、armv7s、arm64）。

    AnyChat for iOS SDK可与其它平台的AnyChat互联互通，连接同一个服务器程序，有关
服务器的SDK可参考AnyChat for Windows SDK开发包。

    AnyChat for iOS SDK包里面提供了Demo程序源代码（基于xCode工程）供参考。


目录清单

|----bin				AnyChat示例程序
|
|----doc				客户端开发指南
|
|----src				Demo程序源代码（XCode工程）
|
|----sdk				客户端SDK引用文件



技术支持

                                http://bbs.anychat.cn
                                http://www.anychat.cn
                                TEL：+86-020-85276986 38103410
                                Email：service@bairuitech.com
                                广州佰锐网络科技有限公司
                        广州市天河区天河软件园建工路9号309、310室

                                       2016年04月

附：版本变更记录

2016-02-02	V6.0
更新AnyChat Platform Core SDK V6.0内核，采用与Core SDK一致的版本命名；
支持RSA非对称加密签名用户接入验证体系；
支持字符串用户ID，可与默认的整形用户ID混用；
支持HTML5音视频接入，与WebRTC音视频互通；
支持上层业务自定义录像文件名；
支持公有云、私有云的接入；
优化透明通道功能，突破传输缓冲区为1KByte的限制；

2015-07-15	V2.3
优化移动设备上服务器合成流录制，功能更稳定；
增加业务对象API，支持智能排队等新功能
支持视频数据回调接口，可用于活体检测、人脸识别等业务场景；
支持动态调节视频参数，包括码率、视频质量、预设参数等；
增加中心服务器拍照功能；
优化网络数据传输，提高移动网络抖动时的音视频质量；
修正部分客户反馈与其它第三方库冲突的问题；

2015-01-15	V2.2
优化音视频内核，编解码效率更高；
增加服务器合成录制、合成流录制功能；
视频录制过程中支持动态改变视频分辩率；
优化网络抖动，减少网络连接断开，提高连接速度；
支持通过API接口开启AnyChat内核调试模式；
支持iOS全系列架构（i386、x86_64、armv7、armv7s、arm64），兼容iOS 8；
修正iOS设备外接耳机之后声音继续从喇叭播放的问题；
修正iOS写入中文文件名为乱码的问题；
iOS平台增加本地视频录制，拍照功能；

2014-09-01	V2.1
基于AnyChat Platform Core SDK V5.1版本编译；
优化并更新内核Codec库，整体性能有较大幅度提升
针对网络状况较差时网络连接的稳定性进行优化
AnyChat支持录像文件格式设置（MP4、WMV、FLV、MP3）
中心录像服务器返回录像文件路径可配置
中心服务器录像支持触发客户端回调事件
实现服务器集中收集客户端日志信息功能
修正iOS设备平放（FACEUP）时视频采集方向不准确的问题
修正低性能设备上视频通话时延迟累计增大的问题
修正合成录像时本地视频有时会卡顿的问题

2014-06-01	V2.0
基于AnyChat Platform Core SDK V5.0版本编译；
增加数据加密、解密API接口，可实现上层应用对语音、视频等数据的加解密；
AnyChat Server SDK支持64bit Java环境
增加视频方向手工修正API接口，包括本地视频采集方向和远程视频显示方向
修正文件传输时在某些网络环境下文件内容接收不完整的问题；
修正iOS设备在某些分辩率下视频采集显示花屏的问题
修正iOS平台部分设备前置摄像头方向不准确的问题；
修正iOS音频在关闭后，需要退出房间才能重新打开的问题；
iOS平台支持显示远程视频时视频方向不随设备的旋转而改变；

2014-01-01	V1.9
基于AnyChat Platform Core SDK V4.9版本编译；
Android、iOS、Web等平台支持中心服务器录像；
iOS平台支持视频分辩率参数设置；
修正iOS设备水平放置时视频会自动旋转的问题；
增加VP8编码器
提供完整的视频呼叫解决方案；
提供完整的大厅好友解决方案；
修正iOS平台下文件传输事件回调中路径为空的Bug
优化回声消除算法，提高通话过程中的用户体验；
支持最新的iOS 7平台；

2013-07-28	V1.8
基于AnyChat Platform Core SDK V4.8版本编译
支持中心服务器录像，音视频录像文件服务器集中保存；
优化P2P算法，提升复杂网络环境下音视频体验；

2013-03-20	V1.7
基于AnyChat Platform Core SDK V4.7版本编译
兼容iOS 6.x，支持iPhone 5
优化回声消除算法，极大提高语音通话体验

2012-11-21	V1.6
基于AnyChat Platform Core SDK V4.6版本编译

2012-09-10	V1.5
基于AnyChat Platform Core SDK V4.5版本编译

2012-05-11	V1.4
基于AnyChat Platform Core SDK V4.4版本编译

2012-02-20	V1.3
基于AnyChat Platform Core SDK V4.3版本编译

2011-09-23	V1.0
初始版本，基于AnyChat Platform Core SDK V4.1版本编译