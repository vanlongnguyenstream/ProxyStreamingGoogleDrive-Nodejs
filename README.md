# ProxyStreamingGoogleDrive-Nodejs

This is a system that allows you to run your own Google Drive video on your own server. Code run in Linux và Windows OS

# Link Dowload Code!
   - https://drive.google.com/open?id=0B-Bw4HuaOS4kT0tlY0NRR0ZhSWc
   - Download to your server then extract it we have a folder contain 
        - Readme file
        - Config file 
        - Folder code Linux
        - Folder code Windows

# Features!
  - This is a very good streaming system (10K user online).
  - Download file streaming
  - Very fast streaming
  - Easy scale by edit config file
# Components!
  - Root Worker: Responsible for providing address information for other components.
  - Master Worker: Responsible for balancing when the system has many users
  - Slave Worker : Responsible for streaming video
  - Download Worker: Responsible for download video
# Configs!
  - Replace ip diffrent 127.0.0.1 with your server ip in file areainfo.xml
  - On ubuntu: move file areainfo.xml to /root/areainfor.xml
  - On windows: move file areainfo.xml to C:/areainfo.xml
  - It is ok
  - More configs for big site : Contact https://www.facebook.com/profile.php?id=100010999245493
# Requiments!
  - Install redis on your server with port 6379
# Start on linux!
  - suppose we are in folder you downloaded from google drive
  - ```sh
    $ cd Linux
    $ chmod 777 root-linux
    $ chmod 777 master-linux
    $ chmod 777 slave-linux
    $ chmod 777 download-linux
    $ screen -S root-screen    [Create screen for root worker]
    $ ./root-linux             [Run root worker]
    $ Ctrl+A , Ctrl+D          [Deattach root-screen]
    $ screen -S master-screen    [Create screen for master worker]
    $ ./master-linux             [Run master worker]
    $ Ctrl+A , Ctrl+D          [Deattach master-screen]
    $ screen -S slave-screen    [Create screen for slave worker]
    $ ./slave-linux             [Run slave worker]
    $ Ctrl+A , Ctrl+D          [Deattach slave-screen]
    $ screen -S download-screen    [Create screen for download worker]
    $ ./download-linux             [Run download worker]
    $ Ctrl+A , Ctrl+D          [Deattach download-screen]
    That all, done!
    ```

# Test!
  - If running the code locally, type: http://127.0.0.1:5566/linkmaster?driveId=0B7znQz9FgfqWbHc3QXhUTTR2ZlU (If true then the result is the link streaming with quanlity 306p, 720p, 480p)
  - If running on the server, type http://server-ip:5566/linkmaster?driveId=0B7znQz9FgfqWbHc3QXhUTTR2ZlU
# Start on Windows!
  - Double click exe files in foler Windows
  - That all, it run and make your test
# Import notes
Contact me: https://www.facebook.com/profile.php?id=100010999245493
  - If you want change port or domain to streming please inbox me
  - Free with 20 user online, if you want more, please inbox me
  - If has any question, inbox me
# Goodbye
