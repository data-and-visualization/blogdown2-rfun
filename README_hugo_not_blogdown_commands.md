.\hugo.exe new site quickstart 

cd quickstart                                                                                                                                                                                                                  
git init  
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke  
git submodule add https://github.com/curtiscde/hugo-theme-dopetrope.git themes/dopetrope
echo theme = \"ananke\" >> config.toml
    theme = "dopetrope"
..\hugo.exe new posts/hello-world.md   
..\hugo.exe help                                                                                                                                                                                                          
..\hugo.exe env                                                                                                                                                                                                           
..\hugo.exe list                                                                                                                                                                                                          
..\hugo.exe list all                                                                                                                                                                                                      
..\hugo.exe server                                                                                                                                                                                                        
..\hugo.exe help                                                                                                                                                                                                          
..\hugo.exe -D                                                                                                                                                                                                            
..\hugo.exe server    

hugo server -D

mv C:\Hugo\Sites\dopetrope\themes\dopetrope\layouts C:\Hugo\Sites\dopetrope\layouts

mv all the example site stuff over into the the main
ie. mv C:\Hugo\Sites\dopetrope\themes\dopetrope & C:\Hugo\Sites\dopetrope\themes\dopetrope\ExampleSite  TO  C:\Hugo\Sites\dopetrope
mv over some of the customization from https://github.com/data-and-visualization/blogdown2-rfun