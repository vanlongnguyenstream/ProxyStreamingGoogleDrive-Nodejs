# ProxyStreamingGoogleDrive-Nodejs
Link dowload source code https://drive.google.com/file/d/0B-hxz6ee5n8_bW16ZThMZVI1ZEE/view
Download to your server, extract it we have code incluce readme file, and config file and code for linux + ubuntu
This is a system that allows you to run your own Google Drive video on your own server.
Code run in Linux và Windows OS
Attention:
This is a very good system load (10K user online).
Therefore, you will have understand with the following components:
Inclued in systems:
- Worker Root: Responsible for providing address information for other components
- Worker Master: Responsible for balancing when the system has many users
- Worker Slave: Responsible for streaming video about the browser
- Worker Download: Responsible for download video
This system run if you will need to start all components on above
Follow these steps:
Step 1: Open the areainfo.xml file (this file is in the same directory as this Readme)
- Fix ip is not to 127.0.0.1 to ip or your server
- After fixing,
+ For the linux files you put in the / root directory (we will file the path is /root/areainfo.xml)
+ For the windows you put that file into the C: drive (/ will get the file path is C: /areainfo.xml)
Step 2:
- Run each component
+ Employee
+ Workers Master
+ Slave workers
+ Download workers
(For linux, use Screen to create terminals and execute permissions for files such as chmod 777 root-linux) (to make 777 for sure)
(With windows, click on exe file is finished)
Step 3:
- Experience:
+ If running the code locally, type: http://127.0.0.1:5566/linkmaster?driveId=0B8kcnU4E3p-yNXBCZllWY2dXVVE (If true then the result is the link thread)
If running on the server, type http: // server-ip: 5566 / linkmaster? DriveId = 0B8kcnU4E3p-yNXBCZllWY2dXVVE

Done

Note: - Want to change the port and domain for the IP, there are ways, the mailbox will support itself
- Inbox you register IP to run any file offline
- You are free 20 users online, higher, have to buy his key
- Hope to help people
If you have a problem, just mail it!

Contact https://www.facebook.com/groups/112613769385658/?ref=bookmarks
