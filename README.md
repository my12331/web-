<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript 核心语法学习（一）</title>
    <script>
        let a =100
        //alert(a)
        console.log(a)
        const api_key='ssssx-=-dddd'
        console.log(api_key)
        console.log(typeof a,typeof api_key,typeof true)
        let b = '1'
        console.log(a+b)
        console.log(a+Number(b))
        let c ='100'
        console.log(a==c)
        console.log(a===c)
        //分支语句
        let current_time='12:20'
        if(current_time='12:20'){
            console.log('时间到了')
        }else{
            console.log('该吃饭了')
        }
        //for循环
        for(let i=0;i<10;i++){
            console.log(i)
        }
        //while循环
        let hug=60
        while(hug>0){
            console.log('继续干饭')
            hug=hug-10
        }
        //函数
        function intro(){
            console.log('你好，我是一个脚本')
        }
        intro()
        function intro2(content){
            console.log('以下是我介绍的内容：'+Spring(content))
        }
        intro2('我这是传入的参数')
        function intro3(content1,content2){
            console.log('以下是我介绍的内容：'+Spring(content1)+Spring(content2))
        }
        intro3('我这是传入的参数1','我这是传入的参数2',444)
        function intro4(content){
            console.log(content)
            return content+'我是返回值'
        }
        intro4('带返回值的函数')
        let intro5=intro4('带返回值的函数')
        console.log(result)
      </script>
    </head>
    <body>
    </body>
</html>
