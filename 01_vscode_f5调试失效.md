# 1.vscode调试python代码时F5键失效的原因
![image](https://github.com/LONGWA312/work_issue/assets/73162051/a5ebde7f-6a23-4136-8af6-4f097d99d924)
vscode python扩展更新，运行python代码时突然无法F5运行与调试，是因为更新后的python扩展版本无法调式version<=3.6的python版本，版本python版本高于3.6的依然可以正常调式

# 2.解决办法
    1.升级python版本  
    2.降低vscode的python扩展（插件）  
        （1）打开vscode扩展插件的官网  
            https://marketplace.visualstudio.com/items?itemName=ms-python.python  
![image](https://github.com/LONGWA312/work_issue/assets/73162051/59995a27-165b-44a2-b126-7c6584c35b75)

        （2）查找历史版本  
![image](https://github.com/LONGWA312/work_issue/assets/73162051/ba642d0a-b886-4c5b-acf0-9fb648fdae07)

        （3）点击download下载历史版本  
            下载的插件文件为：ms-python.python-2023.9.11571010.vsix  
        （4）本地离线安装插件：  
            如下图点击，选择从VSIX安装，选择下载好的ms-python.python-2023.9.11571010.vsix文件  
![image](https://github.com/LONGWA312/work_issue/assets/73162051/cb47b173-a83c-4fa2-a55d-a840fc844693)

# 3.如果你需要的python扩展插件版本在历史版本里面没有，可以按如下操作：
![image](https://github.com/LONGWA312/work_issue/assets/73162051/7ae20b46-ce60-40d7-af27-a95dfd5efad8)

    假如需要的python扩展插件版本为：2021.10.1365161279， 
    但是在官网history version中没有，  
    可以在下图中右键【download】按钮，点击复制链接，可以得到当前版本的下载链接：  
        https://marketplace.visualstudio.com/_apis/public/gallery/publishers/ms-python/vsextensions/python/2023.9.11571010/vspackage  
    然后将你需要的版本号替换链接中的版本号：  
        https://marketplace.visualstudio.com/_apis/public/gallery/publishers/ms-python/vsextensions/python/2021.10.1365161279/vspackage  
    然后直接通过链接下载插件，下载完成后通过离线【vsix】方式安装插件即可  




    


