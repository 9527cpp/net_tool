安装
注册 ngrok获得账号 目前我的是以我的github账号登陆的
然后执行  ngrok authtoken K6yiCfx1m4ba2UcWsy9N_3aenzwVCG8gNyKdcYPs1i(后面的值具体要在ngrok官网上第三步)
然后双击ngrok
在弹出的ngrok框中 输入 ngrok start -config ngrok.yml  tunnel1 tunnel2 
（ngrok.yml默认在C:\Users\Administrator\.ngrok\ngrok.yml）路径下
可以执行多个-config xxx.yml 
tunnel1 和 tunnel2 根据具体的yml中的定义确定