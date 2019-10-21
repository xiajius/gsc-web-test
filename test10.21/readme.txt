1.将两个字符利用字符串对象的方法变成一个字符,显示在页面id为h1的元素中
答:   var h1 = document.getElementById('h1')
      var str = "字符1";
      h1.innerHTML=str.concat('字符2')

2.一个富豪想存87万,给理财顾问写了87w,请自动生成存储870000的方法,显示在页面id为h2的元素中
答:   var h2 = document.getElementById('h2')
      var num = '870000';
      h2.innerHTML= num;

3.一个数字79387.348的工程款,保留两位小数存入,显示在页面id为h3的元素中
答:   var h3 = document.getElementById('h3')
      var num = 79387.348;
      h3.innerHTML= num.toFixed(2);

4.一张图片是一个相对路径img/head/icon/1.jpg,我只需要拿到它的文件夹目录后显示在页面id为h4的元素中
答:    var h4 = document.getElementById('h4');
       var img = document.getElementById('img');
       h4.innerHTML=img.src;

5.用户输入验证码,无论大小写输入都会正确的方法,显示在页面id为h1的元素中,显示在页面id为h5的元素中
答:
        var s1='ABCDE'    
        var s2='abcde'
        //将字符串转为小写
        console.log(s1.toLowerCase());
        //将字符串转为大写
        console.log(s2.toUpperCase());
