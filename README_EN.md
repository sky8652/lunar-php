# lunar [![License](https://img.shields.io/badge/license-MIT-4EB1BA.svg?style=flat-square)](https://github.com/6tail/lunar-php/blob/master/LICENSE)

lunar is a calendar library for Solar and Chinese Lunar.

[简体中文](https://github.com/6tail/lunar-php/blob/master/README.md)

## Example

    <?php
    include 'lunar.php';
     
    use com\nlf\calendar\Lunar;
     
    $lunar = Lunar::fromYmd(1986,4,21);
    echo $lunar->toFullString()."\n";
    echo $lunar->getSolar()->toFullString()."\n";

Output:

    1986-05-29 00:00:00 星期四 双子座
    壹玖捌陆年肆月廿一 丙寅(虎)年 癸巳(蛇)月 癸酉(鸡)日 子(鼠)时 纳音[炉中火 长流水 剑锋金 海中金] 星期四 北方玄武 星宿[斗木獬](吉) 彭祖百忌[癸不词讼理弱敌强 酉不会客醉坐颠狂] 喜神方位[巽](东南) 阳贵神方位[巽](东南) 阴贵神方位[震](正东) 福神方位[兑](正西) 财神方位[离](正南) 冲[(丁卯)兔] 煞[东]

## Documentation

Please visit [http://6tail.cn/calendar/api.html](http://6tail.cn/calendar/api.html "http://6tail.cn/calendar/api.html")

## Contact

<a target="_blank" href="https://jq.qq.com/?_wv=1027&k=5F9Pbf0"><img border="0" src="http://pub.idqqimg.com/wpa/images/group.png" alt="lunar" title="lunar"></a>

