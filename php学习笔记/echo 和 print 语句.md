# echo 和 print 语句

echo 和 print 是php中两个基本的输出方式，使用时都可以加括号，也可以不加括号。

## echo 和 print 区别

- echo - 可以输出一个或多个字符串，没有返回值
- print - 只允许输出一个字符串，返回值总为 1
- echo 输出的速度比 print 快

## echo 语句

输出字符串和变量：

    <?php
        $txt1="学习 PHP";
        $txt2="RUNOOB.COM";
        $cars=array("Volvo","BMW","Toyota");
        
        echo $txt1;
        echo "<br>";
        echo "在 $txt2 学习 PHP ";
        echo "<br>";
        echo "我车的品牌是 {$cars[0]}";
        echo "这是一个", "字符串，", "使用了", "多个", "参数。";
    ?>

- 可以输出多个字符串
- 字符串变量可以直接写在字符串中
- 数组则需要用大括号括起来

## print 语句

除了智能输入单个字符串，其他用法和 echo 一样。

