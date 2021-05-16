 [![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Hydrahail-Johnson&show_icons=true)](https://github.com/anuraghazra/github-readme-stats)

## 介绍
本库是用来同步大佬们的自定义js脚本，本人并不做任何脚本修改，保证原作者脚本的原汁原味  

##  感谢

感谢以下大佬们的无偿分享，让我们才能使用这么多的免费脚本，在此表示感谢。

请关注原作者的github，并打赏原作者支持作者不断更新。

[Tartarus2014](https://github.com/Tartarus2014/)，[monk-coder](https://github.com/monk-coder/)，[i-chenzhe](https://github.com/monk-coder/dust/tree/dust/i-chenzhe/)，[whyour](https://github.com/whyour/)，[moposmall](https://github.com/moposmall/)

[qq34347476](https://github.com/qq34347476/)，[ZCY01](https://github.com/ZCY01/)，[cui521](https://github.com/cui521/)，[sparkssssssss](https://github.com/sparkssssssss/)

## 使用说明

**注意**：diy.sh和git_diy.sh仅适用V3版docker，不适用于V4版docker镜像  

V3镜像：
nevinee/jd:gitee，noobx/jd:py，noobx/jd:gitee，whyour/qinglong:latest  

V4镜像：
nevinee/jd:v4，nevinee/jd:v4-bot

**注意**：遇到问题别PR，请自行探索

## 安装教程
### V3 DOCKER
#### 方法1. 修改diy.sh 【更新不太及时，推荐小白使用，建议自行维护】
从网页上复制diy.sh文件的内容，在web面板中替换自己原有的自定义任务后，保存修改。

diy.sh下载地址：https://raw.githubusercontent.com/Hydrahail-Johnson/diy_scripts/main/diy.sh

#### 方法2. 修改crontab.list 配合 git_diy.sh 【无需更新，推荐】
a. 从网页上下载git_diy.sh，并存放在/jd/scripts文件夹；

下载地址1【原作者】：https://raw.githubusercontent.com/sparkssssssss/scripts/main/git_diy.sh

下载地址2【本人镜像】：https://raw.githubusercontent.com/Hydrahail-Johnson/diy_scripts/main/git_diy/git_diy.sh 

b. 在crontab.list添加计划任务，根据自己实际情况添加，格式如下：

*/30 * * * *  bash /jd/scripts/git_diy.sh monk-coder dust i-chenzhe

### V4 DOCKER
修改config.sh，按照说明添加即可

### 教程合集
[我的博客](https://blog.zjxnas.top)中有大量完整的教程，想要折腾可以自行查阅，请勿骚扰

## 参与贡献

[qiaoqi](https://github.com/qiao112)，
[ktandykok](https://github.com/ktandykok)，
[XINZHOUZHANG](https://github.com/XINZHOUZHANG)，
[Nanase](https://github.com/jsyzdej)
