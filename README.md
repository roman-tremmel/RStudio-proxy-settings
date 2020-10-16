# RStudio-proxy-settings
Two lines of code for the Rprofile.site


Add these two line to the Rprofile.site which is located in `R/etc/` folder: 


    Sys.setenv(http_proxy="myproxy.me.intra:2020")
    Sys.setenv(https_proxy="myproxy.me.intra:2020")


Then, RStudio has the correct proxy setting. 
