# formater
简单的日期格式转化，通过正则的特殊判断，兼容大小写。 

# how to use
## step 1
- npm install -g cnpm --registry=https://registry.npm.taobao.org
- cnpm install formater --save

- 或者使用 yarn add formater

## step 2
最好在全局下引用
<br/>
import 'formater';

- use

<pre>
new Date().formater('yyyy-mm-dd hh:mm:ss');
2018-11-12 14:26:52

new Date().formater('yyyy年mm月dd日 hh时mm分ss秒');
2018年11月12日 14时26分52秒

目前仅支持年、月、日、时、分、秒，
季度与毫秒暂不支持

有什么好的想法，欢迎一起成长交流
WeChat：mrliaojun
</pre>

### github
[Jared](https://github.com/aisriver/formater.git)