#turndown
---

API

	new Countdown({
			endTime: '2014-5-17 15:12:00',  //必选 结束时间
			bgColor: 'pink',                //可选 背景圆环色
			c1: '#999',                     //可选 天 圆环色
			c2: 'yellow',                   //可选 小时 间圆环色
			c3: 'red',                      //可选 分 圆环色
			c4: 'black',                    //可选 秒 圆环色
			color: 'deeppink',              //可选 4个计时圆环色，设置才c1,c1...会被覆盖
			parent: 'body',                 //可选 倒计时插入目标节点, 没有设置，请手动插入实例$frame至目标节点 如: document.body.appendChild(instance.$frame)
			diameter: 100,                  //可选 直径 默认200
			radius: 10,                     //可选 直径 默认20
			lang:'chs'                       //可选 语言 默认chs
		},function (){                      //可选 回调 倒计时结束时调用

	});