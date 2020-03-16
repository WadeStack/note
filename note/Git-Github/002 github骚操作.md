
**整理自尚硅谷周阳老师**

## 1.常用词

### watch：

对于别人的项目，默认自己都处于 Not watching 的状态，当你选择 Watching，表示你以后会关注这个项目的所有动态，这个项目以后只要发生变动，如被别人提交了 pull request、被别人发起了issue等等情况，你都会在自己的个人通知中心，收到一条通知消息，如果你设置了个人邮箱，那么你的邮箱也可能收到相应的邮件。

### stars：

星星，相当于点赞，不过这个赞需要得到程序员小伙伴的认可才会被star

### fork：

把当前项目拷贝一份到自己账号下



## 2.in限制搜索

**以springboot项目为例：**

### 2.1.直接检索

### 2.2.用in限制搜索

#### 2.2.1 `关键词 in:name`

#### 2.2.2 `关键词 in:description`

#### 2.2.3 `关键词 in:readme`

#### 2.2.4 `关键词 in:xx,yy,zz组合`


## 3.基于star和fork范围搜索
### 3.1 基于stars
#### 3.1.1 stars多于xx：
`关键词 stars:数量`

#### 3.1.2 stars数在某个区间
`关键词 stars:xx..yy`

### 3.2 基于fork数 
#### 3.2.1 fork多余xx
`关键词 forks:>=xx`

#### 3.2.2 fork数在某个区间
`
### 3.3 多级组合
可将多种检索规则组合
例：Springboot forks:>=5000 stars:>=5000 in:name

## 4.awesome搜索
`awesome 关键字`
可搜索到堪比（甚至优于）官网文档的学习资源

## 5.#L数字
>功能：高亮代码行
### 5.1 #L数字
例：[https://github.com/527515025/springBoot/blob/master/springboot-mybatis2/src/main/java/cn/abel/Application.java#L11](https://github.com/527515025/springBoot/blob/master/springboot-mybatis2/src/main/java/cn/abel/Application.java#L11)


### 5.2 #L数字1..#L数字2
例：[https://github.com/527515025/springBoot/blob/master/springboot-mybatis2/src/main/java/cn/abel/Application.java#L11..L16](https://github.com/527515025/springBoot/blob/master/springboot-mybatis2/src/main/java/cn/abel/Application.java#L11..L16)


## 6.T搜索
>功能：在项目内搜索
进入项目主页：[https://github.com/527515025/springBoot](https://github.com/527515025/springBoot)

按`T`后可查看代码文件

###### tips:谷歌浏览器可通过安装插件octoree更好的阅读代码和查看层级目录
## 7.搜索区域活跃用户（大佬）
`location:地区 language:编程语言`

