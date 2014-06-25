
Desktop Mongoose
==================================
  
Desktop Mongoose is a slightly modified version of the famous Mongoose v.5.1 web server by Sergey Lyubka prepared for testing and demonstrations of CGI scripts or collaboration in private networks through an HTTP server and CGI scripting. Only two modifications are made:  

* *Option to start web browser simultaneously with the server and quit server when browser exits* - any browser on PATH can be selected and saved in the configuration file.  

* *URI handler that can stop the server* - necessary for stopping the server from another program, including when browser is started simultaneously with the server.  

All changes within the source code are marked with a comment reading 'Desktop Mongoose modification'.  
Only 'mongoose/mongoose.c' and 'mongoose/build/main.c' are modified.  
  
