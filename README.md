# Technical Documentation

## Combine Mp4 files using ffmpeg 
Make sure you have file1.mp4 and file2.mp4 and create list.txt file

- file1.mp4
- file2.mp4
- Create a list.txt file with below contents save it in the same folder
```
        file 'file1.mp4'
        file 'file2.mp4'
```
 - Run below command in the terminal
```
    $ ffmpeg.exe -f concat -i list.txt -c copy output.mp4
```    
   
 
