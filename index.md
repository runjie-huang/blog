# Change Language Setting to English in R & RStudio permanently

This is my first blog.
## Mission:Change Language Setting to English in R & RStudio permanently

* step1: find the path of file： *Rprofile.site*. For me, it is *D:\software\R\R-4.0.5\etc\Rprofile.site*
* step2: open it and add *Sys.setlocale(category = "LC_ALL",locale = "English_United States.1252")*. Then save the file.
* step3: Restart R
 Finally, you will see
 ![image](https://user-images.githubusercontent.com/88473583/147118513-6af1c80e-d088-42aa-a2fe-b2abb83e5629.png)

