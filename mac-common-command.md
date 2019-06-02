把当前文件夹下的mp4文件都单独打包成zip文件，此时文件名为xxx.mp4.zip  
ls *.mp4 | while read file;do zip ${file}.zip ${file};done

批量文件改名，这里把xxx.mp4.zip改为xxx.zip  
for i in *.zip;do mv "$i" "${i%.mp4.zip}.zip";done

把当前文件夹下的mp4文件都单独打包成zip文件，此时文件名为xxx.zip 去掉了.mp4后缀  
for i in *.zip;do zip "${i%.mp4}.zip" "$i";done
