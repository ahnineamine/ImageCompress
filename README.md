# Compress images
JAR that reads images and compresses them in order to reduce the overall size to the detriment of quality.  

## how to use  
1. pull repo.  
2. access directory from CMD.  
3. run the following command:  java -jar ImageCompress-jar-percentile.jar  
4. et voila!

## Config file  
configuration file contains:  
1. the directory of images to be compressed  
2. the directory where to put the compressed images (the directory will be automatically created when the jar is successfully ran, so just specify whatever name you see fit)  
3. the percentile of compression (ex:0.3f). Compression quality is a value between 0 and 1. //f is just java syntax for float
