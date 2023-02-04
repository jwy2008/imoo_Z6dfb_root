# imoo_Z6dfb_root
## 该仓库用与讲述如何root小天才z6dfb及以上版本。

- **⚠仅限有一定基础的人，不建议0基础者使用**

1. 将仓库目录[apks](https://github.com/jwy2008/imoo_Z6dfb_root/tree/main/apks)内的安装包全部安装在手表上。
   - **把充电特效改成流光**
   - 命令行输入: 
       ```sh
       adb shell am density 200
       ```
2. 在**QFIl**把**Boot**提取出来把文件导到手表的内部存储根目录`/sdcard/`。
3. 打开**magisk**点击安装，选择直接选择并修补一个文件。
   - **不要选择保留avb**
4. 打开找到刚刚导入的`boot.bin`。
   - **magsik**会开始修补显示**All done**就是成功。
5. 接下来到手表下载目录`/sdcard/Download/`，将`boot.img`上传到电脑上
6. 使用**QFIl**进入**9008**，将`boot.img`刷进**recovery**里面，`misc.bin`刷进**misc**里，确定刷完依次退出刷完之后就**root**成功了。
   - **`misc.bin`在仓库目录[misc](https://github.com/jwy2008/imoo_Z6dfb_root/tree/main/misc)里**

- **发现者:[早茶光不是找茬光](https://space.bilibili.com/1268760897)**
