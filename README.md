# javascript

　　1、数组方法总览：
　　concat() 　　连接两个或更多的数组，并返回结果。
　　join() 　　把数组的所有元素放入一个字符串。元素通过指定的分隔符进行分隔。
　　pop() 　　删除并返回数组的最后一个元素 。
　　push() 　　向数组的末尾添加一个或更多元素，并返回新的长度。
　　reverse() 　　颠倒数组中元素的顺序。
　　shift() 　　删除并返回数组的第一个元素 。
　　slice() 　　从某个已有的数组返回选定的元素 。
　　sort() 　　对数组的元素进行排序 。
　　splice() 　　删除元素，并向数组添加新元素。
　　toSource() 　　返回该对象的源代码。
　　toString() 　　把数组转换为字符串，并返回结果。
　　toLocaleString() 　　把数组转换为本地数组，并返回结果。
　　unshift() 　　向数组的开头添加一个或更多元素，并返回新的长度。
　　valueOf() 　　返回数组对象的原始值。

　　

　　2、数组方法分类：
　　可改变原数组：

　　　　pop() 、 push() 、 reverse() 、 shift() 、 sort() 、 splice() 、 unshift()

　　不可改变原数组：

　　　　concat() 、 join() 、 slice() 、toSource() 、 toString() 、 toLocaleString() 、 valueOf()
    
    
    3、接下来我们示例一下一些常用的方法
　　　　concat()：用来连接数组并返回出来，但并不会改变原有的数组。

　　　　　　

        var arr = [1,2,3,4,5,6,7]
        var arr2 = [8,9,0,]
        console.log(arr.concat(arr2));
　　　　返回结果为：



　　　　可以看到原数组arr和arr2都是没有改变的。

 

　　　　join()：

        var arr = [1,2,3,4]
        console.log(arr.join("-"));
　　　　结果为：



　　　　可以看到我们用join可以将数组中元素用我们想要的方法连接起来。但并不会改变原有数组。

　　　　

　　　　pop()：

        var arr = [1,2,3,4]
        console.log(arr.pop());
　　　　结果为：



　　　　用pop会删除数组的最后一位并返回出来，而且会改变原有数组。

 

　　　　push()：

        var arr = [1,2,3,4]
        console.log(arr.push("0"));
　　　　结果为：



　　　　用push会在数组的最后添加元素并返回新数组的长度，而且会改变原有数组。

 

　　　　reverse()：

        var arr = [1,2,3,4]
        console.log(arr.reverse());
　　　　结果为：



　　　　用reverse会将原有数组顺序颠倒过来，会改变原有数组。

 

　　　　shift()：

        var arr = [1,2,3,4]
        console.log(arr.shift());
　　　　结果为：



　　　　用shift会删除数组的第一个元素并返回，会改变原有数组。

 

　　　　slice()：

        var arr = [1,2,3,4]
        console.log(arr.slice(3));
　　　　结果为：



　　　　用slice会查找你所传入的索引值并返回找到的对应的元素，并不会改变原有的数组。

 

　　　　sort()：

        var arr = [2,1,4,3,11,22]
        console.log(arr.sort());
　　　　结果为：



　　　　用sort会对数组进行重新排序，并不是从小到大的排序，而是通过首字符的顺序。会改变原有数组。

 

　　　　splice()：

        var arr = [1,2,3,4]
        console.log(arr.splice(1,2));
　　　　结果为：



　　　　用splice会删除数组元素，第一个参数为要删除元素的索引值，第二个参数为删除的长度，并返回所删除的元素。会改变原有数组。

 

　　　　toString()：

        var arr = [1,2,3,4]
        console.log(arr.toString());
　　　　结果为：



　　　　用toString会将数组转换成字符串的形式，但并不会改变原有数组。

 

　　　　unshift()：

        var arr = [1,2,3,4]
        console.log(arr.unshift("0"));
　　　　结果为：


　　　　用unshift会在数组最前面添加元素并返回新数组的长度，会改变原有数组。
    
字符串方法总览：
　　anchor() 　　创建 HTML 锚。
　　big() 　　用大号字体显示字符串。
　　blink() 　　显示闪动字符串。
　　bold() 　　使用粗体显示字符串。
　　charAt() 　　返回在指定位置的字符。
　　charCodeAt() 　　返回在指定的位置的字符的 Unicode 编码。
　　concat() 　　连接字符串。
　　fixed() 　　以打字机文本显示字符串。
　　fontcolor() 　　使用指定的颜色来显示字符串。
　　fontsize() 　　使用指定的尺寸来显示字符串。
　　fromCharCode() 　　从字符编码创建一个字符串。
　　indexOf() 　　检索字符串。
　　italics() 　　使用斜体显示字符串。
　　lastIndexOf() 　　从后向前搜索字符串。
　　link() 　　将字符串显示为链接。
　　localeCompare() 　　用本地特定的顺序来比较两个字符串。
　　match() 　　找到一个或多个正则表达式的匹配。
　　replace() 　　替换与正则表达式匹配的子串。
　　search() 　　检索与正则表达式相匹配的值。
　　slice() 　　提取字符串的片断，并在新的字符串中返回被提取的部分。
　　small() 　　使用小字号来显示字符串。
　　split() 　　把字符串分割为字符串数组。
　　strike() 　　使用删除线来显示字符串。
　　sub() 　　把字符串显示为下标。
　　substr() 　　从起始索引号提取字符串中指定数目的字符。
　　substring()　　 提取字符串中两个指定的索引号之间的字符。
　　sup() 　　把字符串显示为上标。
　　toLocaleLowerCase() 　　把字符串转换为小写。
　　toLocaleUpperCase() 　　把字符串转换为大写。
　　toLowerCase() 　　把字符串转换为小写。
　　toUpperCase() 　　把字符串转换为大写。
　　toSource() 　　代表对象的源代码。
　　toString() 　　返回字符串。
　　valueOf() 　　返回某个字符串对象的原始值。

111111
