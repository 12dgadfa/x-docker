主要特点：

1、节点在日志可看，粘贴到软件即可食用，高手可以随意更改

2、进程名称与MD5值随机变化，每次部署都不一样

3、Super与Chatdog双进程守护

4、采用Apline最小化

变量建议设置：

PW  :启动密码，必须，否则无法启动

UUID： 默认 f0177922-2dcc-4c0f-819c-7b74b7bbbfac ，可选,建议更改

VMPATH：默认vm123456 ，可选,建议更改

VLPATH：默认vl123456 ，可选,建议更改

PORT：端口，默认7860 ，huggingface默认端口，不可更改，其他容器可以改，不建议更改.

TOK： Argo TOKEN ，必须。

DOMAIN： 隧道域名或套了CF的域名,可选 （DOMAIN填写只是为了小白粘贴节点方便，高手随意）。

NEZHA_SERVER： 哪吒 ，可选，有平台封杀，不需要最好不设置

NEZHA_KEY： 哪吒 ， 可选，有平台封杀，不需要最好不设置

NEZHA_PORT： 哪吒 ，默认443， 可选，不建议更改

NEZHA_TLS： 哪吒TLS ，默认1,设置0关闭，不建议更改

URL  :伪装的主页，默认www.aifure.com，建议更改

说明：这里面的所有变量都可以不改，也都可以改，只是为了小白提供了设置建议，高手随意改

二、PATR部署：

![image](https://github.com/dsadsadsss/x-docker/blob/main/png/patr1.PNG)

![image](https://github.com/dsadsadsss/x-docker/blob/main/png/patr2.PNG)

三、节点不通的可能原因：默认节点套CF的，所以可以换CF优选IP试试，或者你的PATH设置有问题，或者更换客户端试试


