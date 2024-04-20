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

| Name     | Repos                      |
| -------- | -------------------------- |
| BO       | https://github.com/bwhyman |
| Shaolong |                            |
| Jinxin   |                            |
| Qiuyue   |                            |
| Wenli    |                            |
| Kaidi    |                            |
| Mingyue  |                            |
| Yilin    |                            |
| Sidi     |                            |
| Tianxin  |                            |
| Dingxuan |                            |

### Update

#### 2024.04.20

掌握基本git/github本地远程版本控制

掌握基于gihub pull request的团队项目开发

```shell
 origin; master; branch; branch types; commit; commit message types; 
 push; pull; marge 
```

Github PR。操作基本可通过vs code实现

1. fork，源仓库至个人远程仓库

2. clone，个人仓库至本地

3. branch，创建docs branch。有点麻烦，但还是掌握了吧

4. commit，docs branch中修改提交

5. branch，切换回master branch

6. upstream，关联源仓库

7. pull，更新拉取源仓库至master branch

8. branch，切换回docs branch

9. merge，将master branch merge至docs branch。目的：如果有冲突，要在branch解决而不是master branch

10. branch，切换回master branch。此时master/docs branch汇聚为最新提交节点

11. push，可直接向源仓库push pull request。等待源仓库合并代码

12. push，可将修改推送至个人远程仓库，但源仓库还未merge，仅为个人修改内容

13. pull，收到源仓库merge通知后，更新本地master branch，并再次push至个人远程仓库

14. 此时，master branch; origin/master; upstream/master，同步

15. del branch，删除完成使命的docs branch

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
