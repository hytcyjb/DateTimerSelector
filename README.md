这个日期选择器是仿IOS的，在工程创建中用了Yuri Kanivets的WheelView控件，另外还使用了一个开源的dialog建造器，在这两者的基础上进行了改进并整合在一块；由于最初这个项目是开发用于平板的，所以可能在手机段的显示上会有些问题；

修改Dialog的样式属性在DateTimeSelectorDialogBuilder类中的setDialogProperties()方法中，可根据自身的需求进行修改；