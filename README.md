# LightSERVER
程序的函数图：

Lightserver
	|---------------main
	|
	|-----lightserver
	|	|------start  
	|	|
	|	|------accept 
	|	|
	|	|------cgi 
	|	|
	|	|------cat
	|	|
	|	|------return_file
	|		
	|-----status
	|	|------headers  200
	|	|
	|	|------unimplemented 501
	|	|
	|	|------unfound 404
	|       |
	|	|------internalerr 500
	|	|
	|	|------requesterr 400
	|
	|-----helper
		|------get_line
		|
