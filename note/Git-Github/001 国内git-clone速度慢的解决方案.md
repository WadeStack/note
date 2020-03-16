# 0. 国内为什么速度会慢

- github的服务器在国外
- gfw

# 解决方案

> 这里就不在推荐修改dns的做法，我也尝试过，不仅麻烦，速度还是不稳定。

## 1. 拥有科学上网的能力

> 如果是计算机相关专业的学生或者软件开发人员，只会用百度，我觉得是一件很可悲的事。



## 2. 配置git

### 2.1 配置socks5代理
```git
git config --global http.proxy 'socks5://127.0.0.1:对应的端口号'
git config --global http.proxy 'socks5://127.0.0.1:对应的端口号'
```
### 2.2 取消代理
```git
git config --global --unset http.proxy
git config --global --unset https.proxy
```

配置完之后，enjoy你的带宽跑满的愉悦。