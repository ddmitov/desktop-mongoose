
Desktop Mongoose
==================================
  
Desktop Mongoose is a slightly modified version of the famous Mongoose v.5.1 web server by Sergey Lyubka prepared for testing and demonstrations of CGI scripts or collaboration in private networks through an HTTP server and CGI scripting. Only two modifications are made:  

* *URI handler that can stop the server* - necessary for stopping the server from another program, a custom browser for example.  

* *Option to start web browser simultaneously with the server* - any browser on PATH can be selected and saved in the configuration file.  

All changes within the source code are marked with a comment reading 'Desktop Mongoose modification'.  
Only 'mongoose/mongoose.c' and 'mongoose/build/main.c' are modified.  
  
