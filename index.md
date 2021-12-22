## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/runjie-huang/blog/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown
This is my first blog.
Mission:Change Language Setting to English in R & RStudio permanently

* step1: find the path of file： *Rprofile.site*. For me, it is *D:\software\R\R-4.0.5\etc\Rprofile.site*
* step2: open it and add *Sys.setlocale(category = "LC_ALL",locale = "English_United States.1252")*. Then save the file.
* step3: Restart R
 you will see
 ![image](https://user-images.githubusercontent.com/88473583/147118513-6af1c80e-d088-42aa-a2fe-b2abb83e5629.png)

