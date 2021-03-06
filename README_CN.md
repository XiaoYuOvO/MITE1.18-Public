[English Version](https://github.com/XiaoYuOvO/MITE1.18Pub/blob/master/README.md)
# MITE1.18
**_一个人不可能只是搞了几个胡萝卜然后制成夜视药水，去到地底世界挖钻石就一夜暴富_**
## 特性
* 让你更难采集资源
* 怪物更具有攻击性
* 续航性更差
* 添加多种怪物、食物、工具、护甲

## 客户端安装
* 客户端安装请查看[此视频](https://www.bilibili.com/video/BV1MS4y117mk/)

## 制作服务端
### 请先制作好客户端后再进行这步,本教程将以HMCL启动器为例,其他启动器根据情况修改步骤
1. 安装好1.18客户端后打开HMCL启动器
2. 打开版本列表![img.png](images/zh_cn/ver_list.png)
3. 找到1.18-MITE并点击右边三个点,选择导出启动脚本,保存![img.png](images/zh_cn/generate_bat.png)
4. 将生成出来的启动脚本以任意文本编辑软件(如记事本)打开![img.png](images/zh_cn/edit.png)
5. 向下翻找,找到`net.minecraft.client.main.Main`,删除这个和此行后面的所有内容,如图\
    ![img.png](images/zh_cn/delete_content.png)\
    删除后如图\
    ![img.png](images/zh_cn/after_delete.png)
6. 在`1.18-MITE.jar`后加上`net.minecraft.server.Main --nogui`(注意空格),如图
    ![img.png](images/zh_cn/add_content.png)
7. 保存内容,双击更改后的脚本启动服务器
### 注意事项&常见问题
* 服务器的目录就是在客户端的根目录,若要更改,请修改启动脚本中`cd /D`后的路径
* 如果服务器一开启就退出,并显示如下内容:\
    `You need to agree to the EULA in order to run the server. Go to eula.txt for more info.`\
  请到服务器根目录(默认即为客户端根目录)下寻找`eula.txt`,并将其中的`eula=false`改为`eula=true`\
  保存然后重启服务器
* 若服务器崩溃,请将logs的latest.log发送过来并说明发生问题时玩家的动作
* 若要修改服务器最大内存,请修改启动脚本中`-Xmx`后的数值
    
## 赞助
* 你可以给我赞助,并获得测试版的体验资格,链接:
   #### [爱发电](https://afdian.net/@XiaoYu233)  