		MouseWheel = 0;
	}, 30);
};
//给页面绑定滑轮滚动事件
if (cvs.parentNode.addEventListener) { //火狐使用DOMMouseScroll绑定
	cvs.parentNode.addEventListener('DOMMouseScroll', scrollFunc, false);
}
//其他浏览器直接绑定滚动事件
cvs.parentNode.onmousewheel = scrollFunc;
