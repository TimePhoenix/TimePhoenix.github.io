
README
---
**目录**
[更新日志](#更新日志)

---
# 更新日志

## 2021/6/3 

- 为网站添加ICON图标

![莲花](https://gitee.com/the-stars-dont-wait/cludimage/raw/master/img/%E8%8E%B2%20(1).png)

 采用RGB#FB7299

- 博客本地预览正常，提交Github后出现网站无法被建立

经查阅资料和邮件咨询Github，该问题出现大致有三种可能：

第一种可能，GitHub正在进行相关更新，可以访问  [GitHub Status](https://www.githubstatus.com/) 查看GitHub的状态，如果出现

![image-20210603184717117](https://gitee.com/the-stars-dont-wait/cludimage/raw/master/img/image-20210603184717117.png)

就说明Github服务器没有出问题，而是其他方面的问题。

第二种可能，Git提交时出现了问题，这时可以尝试删除本地博客根目录下“.deploy_git”文件夹，并执行

```
hexo cl
hexo g -d
```

之后可以看看博客在Github的状态有没有恢复正常

第三种可能，Github误认为你的博客采用Jekyll，这时，需要在GitHub博客目录下建立一个为 .nojekyll的空文件

![image-20210603191142890](https://gitee.com/the-stars-dont-wait/cludimage/raw/master/img/image-20210603191142890.png)



![image-20210603185505947](https://gitee.com/the-stars-dont-wait/cludimage/raw/master/img/image-20210603185505947.png)

这时博客就可以恢复正常了

![image-20210603185744570](https://gitee.com/the-stars-dont-wait/cludimage/raw/master/img/image-20210603185744570.png)

## 2021/6/4

为博客绑定域名 decodezoom.cn



## 2021/6/5

解决本地上传后 ".nojekyll"文件被自动清除的问题

![image-20210605142718189](https://gitee.com/the-stars-dont-wait/cludimage/raw/master/img/image-20210605142718189.png)
