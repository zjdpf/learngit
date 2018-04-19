try_n: 0, //别改.后面要用,已经尝试了的次数.
try_max: 10, //404,500,或者ajax未响应的失败重试次数
interval: 2000, //请求间隔
state_url: '/state', //接口url
state_img: 'http://p4.qhimg.com/t01460f91162ab4c0b3.png', //检测网络是否畅通的图片地址
online_url: 'http://wifi.360.cn/huodong/portal?%param%',
isLoading: false, //是否正在检测,暂时没使用.加入超时策略的话就需要了

20180419 13:27 haha 