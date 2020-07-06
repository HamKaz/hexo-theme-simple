# hands on
1. make a NEW Directory, `mkdir [dir-name]`
2. go down to the New Directory, `cd [dir-name]`
3. Initialize the Directory, `hexo init`
   It placed 'default theme landscape' in [dir-name]/themes
   (It can check [dir-name]/themes/landscape by using `ls`)
4. go down to the Directory, `cd themes`
5. Clone this hexo theme, `git clone https://github.com/HamKaz/blog-theme-simpler`.
   It placed 'blog-theme-simpler' under the Directory [dir-name]/themes
   (It can check [dir-name]/themes/hexo-theme-simpler by using `ls`)
6. go up to the Directory, `cd ..`, to [dir-name]
7. change and set theme name in site-config, from landscape to blog-theme-simpler
   (If neccesary, it can be renamed)
  (`#theme
    - landscape (delete or comment-out)
    + blog-theme-simpler`)
8. generate hexo initial page, `hexo generate`
   It generated `public` Directory ([dir-name/public])
9. run hexo server, `hexo server`
   It can check this theme.
