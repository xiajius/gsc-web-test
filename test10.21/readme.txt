1.将两个字符利用字符串对象的方法变成一个字符,显示在页面id为h1的元素中
答:
    <script language="JavaScript">       
        var str = "ni";
        var str1 = "hao";
        var s1=document.write( str.concat(str1,));
        document.getElementById('h1').innerHTML = "s1";
    </script>

2.一个富豪想存87万,给理财顾问写了87w,请自动生成存储870000的方法,显示在页面id为h2的元素中
答:
    <script language="javascript" type="text/javascript">
        document.getElementById('box1').innerHTML = "内容"; 
        var s1='123456'
        var s2=s1.padEnd(6,'0')      
    </script>
3.一个数字79387.348的工程款,保留两位小数存入,显示在页面id为h3的元素中
答:
    <script>
        var num1 = 79387.348; 
        console.log(num1.toFixed(2));       
    </script>

4.一张图片是一个相对路径img/head/icon/1.jpg,我只需要拿到它的文件夹目录后显示在页面id为h4的元素中
答:
    <script>
        var str='img/head/icon/1.jpg';
        var nstr1=str.substring(0,13)
        console.log(nstr1);
    </script>
5.用户输入验证码,无论大小写输入都会正确的方法,显示在页面id为h5的元素中,显示在页面id为h4的元素中
答:<script>
        var s1='ABCDE'    
        var s2='abcde'
        //将字符串转为小写
        console.log(s1.toLowerCase());
        //将字符串转为大写
        console.log(s2.toUpperCase());
    </script>