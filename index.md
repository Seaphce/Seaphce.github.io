## Welcome to My GitHub Pages

You can use the [editor on GitHub](https://github.com/Seaphce/Seaphce.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

###git 上传本地文件

1.进入本地的项目目录，右键“Git Bash here”,调出git命令行界面，然后输入
  
	git init 

2.就是将目录下的所有文件上传，也可以将“.”换成具体的文件名
  
	git add . 

3.将项目提交到gitHub
  
	git commit -m "注释语句"  

4.将本地的代码关联到github上

	  git remote add origin 项目的github地址

5.上传代码到github之前需要先pull（仓库名需要一致，否则报refusing to merge unrelated histories；可在命令行后加--allow-unrelated-histories）
  
	git pull origin master  

6.上传代码到远程仓库
  
	git push -u origin master
	
###github删除文件

	1.git rm --cached filename
	
	2.git commit -m "hehe"
	
	3.git push origin
	
	
### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Seaphce/Seaphce.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
