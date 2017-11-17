# basetools
 LogUtils使用log4j类似的风格

用法：
LogUtils.i("hello");
正式版本可以关闭日志，例如：
LogUtils.setLogIsOpen(false);

提供另外一个工具，一个全局的Toast,使应用的提示不再杂乱无序，用法如下：
ToastUtils.createToast(getApplication(),"hello");
在activity不可见时清除，例如在activity的onStop方法中调用ToastUtils.cancelToast();
