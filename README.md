# interview
Interview questions
### CSS
1. Box model
2. CSS hack or alternative
3. CSS selector priority
4. Float
5. Some practice questions like align, table-cell
6. Code standard
7. Response Design
8. 用css实现垂直居中效果，尽可能跨平台， 尽可能适配各种尺寸的浏览器
```
<html>
<body>
  <div>
     <p>hello</p>
     <p>hello</p>
  </div>
</body>
</html>
```

### HTML Standard
1. HTML standard
2. HTML status code
3. Code standard
4. Rendering technic 
5. element.addEventListener(event, function, useCapture), useCapture是什么意思
6. 什么是capture phase 和 bubble phase
7. Jquery的on 是在capture phase还是bubble phase
8. event.target 和 currentTarget
9. 用addEventListener会有什么兼容性问题么？
10. 

### JS
1. Closure
2. Frameworks
3. OOP
4. Jquery ： promise， defer
5. Asynchronize
6. 继承， Dog, Cat类，继承自Animal，测试用例
```
var dog = new Dog();
var cat = new Cat();
dog.bark();//output "Wow"
cat.bark();//output error, cat don't bark
```

7. +function(){return {}}() 和 function(){return {}}() 各自输出什么
8.  event.stopPropagation() 和 event.stopImmediatePropagation()的区别是什么

### Jquery
1. .load()和 .ready()有什么区别
2. .focus()和.focusin()有什么区别
3. $(document).on( "ready", handler ); 这句话有什么问题？
4. 如果你需要在一开始执行些逻辑，需要知道下载图片的高度和宽度的， 你的逻辑写在.load()里面还是在.ready()里面 
5. .remove()和.detach()有什么区别（去不去掉event handler）
6. $('body').on('click.myPlugin.simple', 'button', fn1); 请问 click, .myPlugin.simple, button, fn1 分别代表什么
7. $( "a" ).on( "click", false ) 实现什么功能(等同event.stopPropagation() && event.preventDefault()) 
8. $( "p" ).click(function( event ) {
  alert( event.currentTarget === this ); // 请问输出什么
});
9. 很多jquery的插件里面都以这样开头 ;(function(){$, window, document, undefined })(jQuery, window, document) 能解释下为什么嘛？

### Other engineer practice
1. How to manage code(versioning)
2. Code Standard

### Advanced topic
1. Backend Javascript
2. V8 engine
3. Webkit
4. Spidermonkey
5. W3C
6. Tools

### 服务器端
1. 在服务器端用过js么
2. 在服务器端用过js template么
3. 用过photomjs么

### Passion
1. Stackoverflow
2. CanIuse
