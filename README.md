# web-examples

### Introductions

基础网页开发技术，为前端开发技术提供支撑。  
熟悉 Markdown 文档语法。  
熟悉 git/github。

### Development Environments

- VS Code
- Prettier
- Git

### Seeds

| Name     | Repos                                  |
| -------- | -------------------------------------- |
| BO       | https://github.com/bwhyman             |
| Shaolong | https://github.com/zsliszhangxiaochong |
| Jinxin   | https://github.com/LLL-zqvr/           |
| Qiuyue   | https://github.com/yue24413            |
| Wenli    | https://github.com/DTBtrigger          |
| Kaidi    | https://github.com/11hkd               |
| Mingyue  | https://github.com/hemingyueyyqx       |
| Yilin    | https://github.com/songsongyl          |
| Sidi     | https://github.com/dieatmore           |
| Tianxin  | https://github.com/ChengTX666          |
| Dingxian | https://github.com/MikeColeone         |
| KeFan    | https://github.com/vow717              |

### Update

#### 2024.05.14

**CSS**

flex 布局；12 栅格布局；  
CSS 选择器从右向左解析的原因；

**JS**

JS 基本语法；箭头函数；对象；模板字符串；JSON；callback；

```shell
arrays；for-of/for-in/forEach()/find()/map()/filter()/sort()/splice()/includes();
onclick/onchange/onkeyup/onkeydown events；
document/getElementById()
```

**需求**

当改变课程名称下拉框值时，从对象数组中找到对应的授课教师姓名，渲染到页面。

当 2s 后输入框没有输入时，将输入字母转为大写。(up/down 事件；定时器；定时器取消；封装)

#### 2024.04.26

**CSS**

```shell
element/id/class Selectors; Cascading; Units; Box Model;
Background/Image/Text/Opacity; Combinators Selectors; display;
Vertical-Align; table; float; position; Box-Sizing; Navigation Bar
```

#### 2024.04.20

掌握基本 git/github 本地远程版本控制

掌握基于 gihub pull request 的团队项目开发

```shell
 origin; master; branch; branch types; commit; commit message types;
 push; pull; marge
```

Github PR。操作基本可通过 vs code 实现

1. fork，源仓库至个人远程仓库

2. clone，个人仓库至本地

3. upstream，关联源仓库

4. branch，创建 docs branch。有点麻烦，但还是掌握了吧

5. commit，docs branch 中修改提交

6. pull，更新拉取源仓库至当前 docs branch

7. merge，将源仓库 upstream merge 至 docs branch。目的：如果有冲突，要在 branch 解决而不是 master

8. branch，切换回 master branch，再从 master merge docs branch。由于 upstream/docs branch 冲突已经在 docs branch 解决，因此可直接整合 upstream 至 master branch。此时，upstream/master/bocs 汇聚为最新提交节点

9. push，可直接向源仓库 push upstream。等待源仓库合并代码

10. pull，收到源仓库 merge 通知后，更新本地 master branch，并再次 push 至个人远程仓库

11. 此时，master branch; origin/master; upstream/master，同步

12. del branch，删除完成使命的 docs branch

#### 2024.04.16

**HTML**

```shell
div; span; p; h1; br; hr; table; ul; img;
```

**Emmet**

```shell
>; +; ^; (); *; $; lorem;
```

**markdown**

维护学习文档

#### 2024.04.10

项目`.vscode/`目录？目录下的文件？文件中的配置？`.prettierrc.json`？  
熟悉 vscode 功能。  
创建基本网页，在 vscode 中调用浏览器打开。  
熟悉基本 HTML 标签。  
熟悉基本 Emmet 语法。
