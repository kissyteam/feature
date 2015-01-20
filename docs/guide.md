## 使用说明

硬件环境关键特性检测，这类功能通常在判断硬件环境时使用。例如需要判断某个css3特性在当前浏览器环境是否支持时则可使用此模块

## 引用模块


	require(['feature'], function(Feature){
		//use Feature
	});

## 基本使用例子

	require(['feature'], function(Feature){
		if(Feature.isTouchEventSupported()){
			alert('该环境支持touch事件...');
		}
	});