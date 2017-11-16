Init Ubuntu
===

## 截图

菜单

![menu](images/menu.png)

运行截图

![run](images/run.png)

## 配置文件

- tmux

集成了个人最常用的几个功能   

https://gist.github.com/XuCcc/2f3d5d05a39f10b871aa10095318ca22

- 各种源的替换,按需求取消对应注释即可

```sh
# pip
printf "[global]\nindex-url = https://pypi.tuna.tsinghua.edu.cn/simple\n" >> .pip/pip.conf

# npm
gem sources --add https://gems.ruby-china.org/ --remove https://rubygems.org

# docker
echo -e "{\n\t\"registry-mirrors\": [\"https://docker.mirrors.ustc.edu.cn\"]\n}\n" >> /etc/docker/daemon.json
```

## 最终效果

### 终端

![term](images/term.png)

### Desktop图形化

TODO

