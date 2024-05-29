## unraid主题，一分钟diy自己喜欢的主题！！！（含去黑条）
### 1 、下载资源,点击终端，运行下面代码即可。
![image](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/0a5224a5-f3fe-4ba5-977b-acb1ef767628)
```
cd /mnt/user/ && git clone https://github.com/XiaoNieGPT/unraid-theme.git
```
### 2、在 shares里面可以看到刚刚下载的文件。文件路径是/mnt/user/unraid-theme/，后面需要用到。
![image](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/a7a15b1a-8bca-4d52-9916-aecdb78c4917)
![image](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/5c3a5821-9957-416d-bd7e-782300d43f03)
### 3、在【应用】app里面安装Theme Engine插件。
![image](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/9cbd266c-14bb-423e-9cf6-6cc6a1d031f1)
### 4、在【设置】settings里面找到Theme Engine并打开。
### 5、在Base Theme 里面选择Black主题，并点击应用。
![image](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/41142b78-1c0a-415a-bcb6-6143c42ffb3c)
### 6、在Theme Setting 里面打开Advanced VIEW，第一个Enable Theme Engine修改为NO。
![image](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/37ea54ba-b8d6-4438-bda8-c7284b1f0a9d)
### 7、拉到最底下，把Enable custom styling (below)改为yes。
![image](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/e8f31b42-20aa-4027-8aca-140a53495091)
### 8、继续拉到最后面，在Custom styling (advanced)填入下面的代码。
```
</style>
<link type="text/css" rel="Stylesheet" href="/mnt/user/unraid-theme/theme.css" />
```
![image](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/9f928eae-adfd-4a3d-b263-3f805d3188c6)
### 9、修改显示设置
![image](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/c63de185-a881-4ed2-8e28-11ce8b662269)
### 10、显示设置里面
![image](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/a9f348f2-8746-4f84-8c1c-51acc5500514)
### 11、去掉黑条
![image](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/605f792c-87d9-4b81-8aa0-d21d6ca070b0)
#### 11.1 下载page替换文件,第一步下载了就不用再次下载了
```
cd /mnt/user/ && git clone https://github.com/XiaoNieGPT/unraid-theme.git
```
#### 11.2 备份及替换文件
```
#备份文件
cp /usr/local/emhttp/plugins/dynamix/DisplaySettings.page DisplaySettings.pagebak
#替换文件
cp /mnt/user/unraid-theme/DisplaySettings.page /usr/local/emhttp/plugins/dynamix
```
#### 11.3 设置 
![image](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/ef662306-a3af-4667-9b55-9cf5a17c8fb3)
#### 11.4 原理
修改文件，文件路径/usr/local/emhttp/plugins/dynamix/DisplaySettings.page
解除长度限制，加上透明，自己修改就行。6.12.10在第300行，别的版本大差不差！记得备份！
![image](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/caeee42b-93d7-4f65-b469-cc9883cd087f)
### 12、效果 
![image](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/d9b7642c-9169-4a6a-b7da-d40f508b0d8e)


