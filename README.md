# online-video
一个在线直播  这个直播是有弹幕的。

简单的讲一下  录制直播是zhibo，观看页面在dome

zhibo：

rec.html ： 录制视频;

start.php： swoole服务端;

index.html: 能观看录制的页面;

client 文件夹是用来存放录制视频的base64的图片，然后转发;


dome：
demo：观看直播 发送弹幕 ;

index.html :里面有两个websocket 的端口;

ws_server.php ： 弹幕的服务端;

log.txt：记录的日志


尽量在本地虚拟机上观看，那样会比较流畅。
不能传递声音，这个还在研究中。
代码修修改改，都是借鉴别人的。
如有侵犯知识产权的一定要通知我，我会及时改正。


