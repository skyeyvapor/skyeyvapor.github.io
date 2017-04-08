## Skeleton
skyeyvapor.github.io/
├── _includes/
│   ├── comments.html
│   ├── head.html
│   └── sidebar.html
├── _layouts/
│   ├── default.html
│   ├── page.html  # layout: default
│   ├── post.html  # layout: default
│   └── tag_index.html
├── _plugins/
│   └── tag_gen.rb
├── _posts/  
│   └── # 放一堆post.md，就在這寫blog
├── _site/
│   └── # jekyll serve會自動產生本地端的檔案在這裡，gitignored
├── public/
│   ├── css/
│   └── favicon.ico
├── _config.yml
├── 404.html
├── about.md  # layout:page, title:about。 about裡的東西
├── archives.md
├── atom.xml
├── CNAME  # 放自己網域
├── index.html  # layout: default  
                # 掌控首頁右半部的顯示：posts, pagination
├── LICENSE.md
├── README.md
├── .gitignore  # gp_pages/  # _site/
└── tagcloud.md