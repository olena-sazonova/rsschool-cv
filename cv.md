# Curriculum Vitae

## Olena Sazonova
### Junior Front-End Developer

**My Contacts**

| Source | Links |
| ------ | ------ |
| e-mail |olena.s.sazonova@gmail.com |
| Telegram | https://t.me/Sazonova_Elen|


**Summary**
>I am an assistant professor in the university and I am really keen on programming. Now I want to improve myself in development.
>Self-motivated, responsible, determined and decisive.

**Skills**
- HTML5/CSS3
- Javascript, Python, C++
- MySQL, PostgreSQL

**Code example**
	setInterval(function(){
		context.clearRect(0,0,1000,600)
		for(let i=0;i<balls.length;i++){
			context.beginPath()
			context.fillStyle=balls[i].color
			if ((balls[i].x < balls[i].minX && balls[i].speedX<0)||(balls[i].x > balls[i].maxX && balls[i].speedX>0))
				balls[i].speedX = -balls[i].speedX
			if ((balls[i].y < balls[i].minY && balls[i].speedY<0)||(balls[i].y > balls[i].maxY && balls[i].speedY>0))
				balls[i].speedY = -balls[i].speedY
			context.arc(balls[i].x+=balls[i].speedX,balls[i].y+=balls[i].speedY,balls[i].radius,0,Math.PI*2,true)
			context.closePath()
			context.fill()
		}
		}, 100);
    
**Experience**

>Writing web-pages for online courses in the university. Some pet projects for friends.

**Education**
>V.N. Karazin Kharkiv National University, Kharkiv, Ukraine

**Languages**
- English - B1
- Ukrainian - fluent
- Russian - native
