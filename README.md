# Compress images
JAR that reads images and compresses them in order to reduce the overall size to the detriment of quality.  

## how to use  
pull repo.  
access directory from CMD.  
run the following command:  java -jar ImageCompress-jar-percentile.jar
et voila!

## Config file  
configuration file contains:  
1.the directory of images to be compress
2.the directory where to put the compressed images (the directory will be automatically created when the jar is successfully ran, so just specify whatever name you see fit)  
3.the percentile of compression (ex:0.3f) //f is just java syntax for float
