---
layout: page
title: SICP解答
---
{% include JB/setup %}

## [查看所有解答]({{ BASE_PATH }}/answers.html)       

        + 本站想要做的事情，参考[关于]({{ BASE_PATH }}/about.html)   

        + 如果您想要把您的SICP解答加入本站，请：  
        > 1. 发送github中你的SICP解答仓库地址到youtuans@yahoo.com  
        > 2. 或者提出ISSUE到本站    

            本人会使用GIT的SUBMODULE的方式，更新所有人的仓库，然后拷贝到本项目地址，推送到GITHUB上   

### 你的解答请遵守如下格式：  
        文件名    

            文件名2012-10-27-1-1.md，日期+题号.md，不接受其它格式文件   

        头部使用        

            layout: post
            title : "1.1"
            category : tom
            tags : [1.1]
            其中会根据相同的category显示所有的解答  
            tags使用SICP中的题号  
            标题也尽量使用题号    

        文件日期    

            根据相同的category分类时，使用的是正序排序，而不是jekyll中的默认逆序  
            请自行设定解题文件的日期
