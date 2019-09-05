
### 1. Get Started 

#### 1.1 HTML canvas fundamentals 

Features: 
+ provide a drawing surface 
+ pixel-based rendering 
+ draw shapes, lines, gradients, and images 
+ built in support for transformation 
+ no built in support for animations 

```html
<canvas width="400" height="400" id="loopCanvas"></canvas>
```

steps to use canvas:

+ Define a canvas element 
+ locate the canvas id 
+ access the 2d context 
+ draw shapes


```js
        window.onload = function () {
            // 1. find the cavnas element
            var canvas = document.getElementById('loopCanvas');
            // 2 .get the 2d context (pencil）
            var ctx = canvas.getContext('2d');
            // 3. render graphics( x, y , width, height)
            ctx.fillStyle = 'orange';
            ctx.fillRect(100, 200, 200, 150);
            // (x, y , radius, startAngle, endAngle, atiCLockwise)
            ctx.fillStyle = 'navy';
            ctx.arc(100, 100, 50, 0, 2*Math.PI, false);
            ctx.fill()

```

#### 1.2 Canvas API 

+ canvas api functions 
+ canvas api properties 
+ line and shape functions 
+ text functions 
+ transforms functions 

#### 1.3 documentations 

www.whatwg.org/specs/web-apps/current-work/multipage/

https://www.w3schools.com/html/default.asp

