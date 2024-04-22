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

| Name     | Repos                          |
| -------- | ------------------------------ |
| BO       | https://github.com/bwhyman     |
| Shaolong |                                |
| Jinxin   | https://github.com/LLL-zqvr    |
| Qiuyue   | https://github.com/yue24413    |
| Wenli    |                                |
| Kaidi    | https://github.com/11hkd       |
| Mingyue  |                                |
| Yilin    |                                |
| Sidi     |                                |
| Tianxin  |                                |
| Dingxian | https://github.com/MikeColeone |

### Update

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

3. branch，创建 docs branch。有点麻烦，但还是掌握了吧

4. commit，docs branch 中修改提交

5. branch，切换回 master branch

6. upstream，关联源仓库

7. pull，更新拉取源仓库至 master branch

8. branch，切换回 docs branch

9. merge，将 master branch merge 至 docs branch。目的：如果有冲突，要在 branch 解决而不是 master branch

10. branch，切换回 master branch。此时 master/docs branch 汇聚为最新提交节点

11. push，可直接向源仓库 push pull request。等待源仓库合并代码

12. push，可将修改推送至个人远程仓库，但源仓库还未 merge，仅为个人修改内容

13. pull，收到源仓库 merge 通知后，更新本地 master branch，并再次 push 至个人远程仓库

14. 此时，master branch; origin/master; upstream/master，同步

15. del branch，删除完成使命的 docs branch

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
