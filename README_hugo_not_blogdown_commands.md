.\hugo.exe new site quickstart 
  45 cd quickstart                                                                                                                                                                                                                  
  46 git init  
  54 git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke  
     git submodule add https://github.com/curtiscde/hugo-theme-dopetrope.git themes/dopetrope
  55 echo theme = \"ananke\" >> config.toml
          theme = "dopetrope"
  65 ..\hugo.exe new posts/hello-world.md   
  78 ..\hugo.exe help                                                                                                                                                                                                               
  79 ..\hugo.exe env                                                                                                                                                                                                                
  80 ..\hugo.exe list                                                                                                                                                                                                               
  81 ..\hugo.exe list all                                                                                                                                                                                                           
  82 ..\hugo.exe server                                                                                                                                                                                                             
  83 ..\hugo.exe help                                                                                                                                                                                                               
  84 ..\hugo.exe -D                                                                                                                                                                                                                 
  85 ..\hugo.exe server    

hugo server -D

mv C:\Hugo\Sites\dopetrope\themes\dopetrope\layouts C:\Hugo\Sites\dopetrope\layouts

mv all the example site stuff over into the the main
ie. mv C:\Hugo\Sites\dopetrope\themes\dopetrope & C:\Hugo\Sites\dopetrope\themes\dopetrope\ExampleSite  TO  C:\Hugo\Sites\dopetrope
mv over some of the customizations from https://github.com/data-and-visualization/blogdown2-rfun