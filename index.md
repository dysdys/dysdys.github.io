## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/dysdys/dysdys.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
<!DOCTYPE html>
<html>

<head>
	<meta charset="utf-8" />
	<style>
		/*最外层容器样式*/
		.wrap {
			width: 200px;
			height: 200px;
			margin: 200px;
			position: relative;
		}

		/*包裹所有容器样式*/
		.cube {
			width: 200px;
			height: 200px;
			margin: 0 auto;
			transform-style: preserve-3d;
			transform: rotateX(-30deg) rotateY(-80deg);
			animation: rotate linear 20s infinite;
		}

		@-webkit-keyframes rotate {
			from {
				transform: rotateX(0deg) rotateY(0deg);
			}
			to {
				transform: rotateX(360deg) rotateY(360deg);
			}
		}

		.cube div {
			position: absolute;
			width: 200px;
			height: 200px;
			opacity: 0.8;
			transition: all .4s;
		}

		/*定义所有图片样式*/
		.pic {
			width: 200px;
			height: 200px;
		}

		.cube .out_front {
			transform: rotateY(0deg) translateZ(100px);
		}

		.cube .out_back {
			transform: translateZ(-100px) rotateY(180deg);
		}

		.cube .out_left {
			transform: rotateY(-90deg) translateZ(100px);
		}

		.cube .out_right {
			transform: rotateY(90deg) translateZ(100px);
		}

		.cube .out_top {
			transform: rotateX(90deg) translateZ(100px);
		}

		.cube .out_bottom {
			transform: rotateX(-90deg) translateZ(100px);
		}

		/*定义小正方体样式*/
		.cube span {
			display: block;
			width: 100px;
			height: 100px;
			position: absolute;
			top: 50px;
			left: 50px;
		}

		.cube .in_pic {
			width: 100px;
			height: 100px;
		}

		.cube .in_front {
			transform: rotateY(0deg) translateZ(50px);
		}

		.cube .in_back {
			transform: translateZ(-50px) rotateY(180deg);
		}

		.cube .in_left {
			transform: rotateY(-90deg) translateZ(50px);
		}

		.cube .in_right {
			transform: rotateY(90deg) translateZ(50px);
		}

		.cube .in_top {
			transform: rotateX(90deg) translateZ(50px);
		}

		.cube .in_bottom {
			transform: rotateX(-90deg) translateZ(50px);
		}

		/*鼠标移入后样式*/
		.cube:hover .out_front {
			transform: rotateY(0deg) translateZ(200px);
		}

		.cube:hover .out_back {
			transform: translateZ(-200px) rotateY(180deg);
		}

		.cube:hover .out_left {
			transform: rotateY(-90deg) translateZ(200px);
		}

		.cube:hover .out_right {
			transform: rotateY(90deg) translateZ(200px);
		}

		.cube:hover .out_top {
			transform: rotateX(90deg) translateZ(200px);
		}

		.cube:hover .out_bottom {
			transform: rotateX(-90deg) translateZ(200px);
		}
	</style>
</head>

<body>
	<!-- 外层最大容器 -->
	<div class="wrap">
		<!--包裹所有元素的容器-->
		<div class="cube">
			<!--前面图片 -->
			<div class="out_front">
				<img src="https://img-blog.csdn.net/20170716094246620" class="pic" />
			</div>
			<!--后面图片 -->
			<div class="out_back">
				<img src="https://img-blog.csdn.net/20170716094334594" class="pic" />
			</div>
			<!--左面图片 -->
			<div class="out_left">
				<img src="https://img-blog.csdn.net/20170716094400013" class="pic" />
			</div>
			<!--右面图片 -->
			<div class="out_right">
				<img src="https://img-blog.csdn.net/20170716094422331" class="pic" />
			</div>
			<!--上面图片 -->
			<div class="out_top">
				<img src="https://img-blog.csdn.net/20170716094444434" class="pic" />
			</div>
			<!--下面图片 -->
			<div class="out_bottom">
				<img src="https://img-blog.csdn.net/20170716094504432" class="pic" />
			</div>

			<!--小正方体 -->
			<span class="in_front">
				<img src="https://img-blog.csdn.net/20170716120759718" class="in_pic" />
			</span>
			<span class="in_back">
			     <img src="https://img-blog.csdn.net/20170716120759718" class="in_pic" />
			</span>
			<span class="in_left">
				<img src="https://img-blog.csdn.net/20170716120759718" class="in_pic" />
			</span>
			<span class="in_right">
				<img src="https://img-blog.csdn.net/20170716120759718" class="in_pic" />
			</span>
			<span class="in_top">
				<img src="https://img-blog.csdn.net/20170716120759718" class="in_pic" />
			</span>
			<span class="in_bottom">
				<img src="https://img-blog.csdn.net/20170716120759718" class="in_pic" />
			</span>
		</div>

	</div>
</body>

</html>

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/dysdys/dysdys.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
