# Examples for jQuery DatePicker

## 调用

    $('#startDate').datepicker({
        maxDate: new Date()
    });

## 配置项

### 日期最小值
支持YYYY-MM-DD格式的字符串、时间戳、Date对象实例等类型。

minDate: '1900-01-01'

### 日期最大值

maxDate: '2099-12-31'

### 起始星期值
其中，0为星期日，大于6按7取余。

firstDay: 0

### 日期选择事件回调

onSelect: null

### 触发日期控件事件类型

showOn: 'focus'

### 错误模式
取值包括：alert, confirm, clear, custom, none。

errMode: 'confirm'

### 自定义错误处理函数
``注意``：仅在errMode为custom时有效。

errHandler: null

### 错误提示消息

errMessage: '不合法的日期格式或者日期超出限定范围'

### 错误确认消息
``注意``：errMode为confirm时有效

errConfirmMsg: '不合法的日期格式或者日期超出限定范围,需要撤销吗?'

### 星期显示文本，与firstDay对应

weekNames: ['日', '一', '二', '三', '四', '五', '六']

### 月份显示文本

months: ['一月', '二月', '三月', '四月', '五月', '六月', '七月', '八月', '九月', '十月', '十一', '十二']//

Visit [抚云生活](http://www.ifuyun.com/ "抚云生活") for more information.