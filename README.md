## web-isSupportH5
- 判断浏览器是否支持html5
```
window.onload = function() {
	if(window.applicationCache){
		console.log('support html5'); // 支持
	}else{
		console.log('nonsupport html5'); // 不支持
	}
}
```
