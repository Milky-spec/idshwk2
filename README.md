如果snort在TCP流中看到两个包:
(1)第一个包在载荷中有“login”或“Initial”，目的端口是3399;
(2)第二个包在负载中有一个“IPv4Address:Port”字符串(例如:123.45.6.7:8080)。目的端口是3399;
(3)输出一个警告，msg " bot founded "和sid 1000001
