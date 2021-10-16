https://github.com/rymar3/rymar3.github.io.git

git remote set-url origin https://rymar3:TOKEN@github.com/rymar3/rymar3.github.io.git

## 01. Прописуємо данні про себе щоб автори проекта знали хто вносив зміни 
	електронна пошта повинна бути зареєстрована в github !!!
	git config --global user.email "rymar@ukr.net"
	
## 02. Клонуємо сайт на свій комп
	cd c:\intel
	git clone https://github.com/rymar3/rymar3.github.io.git
	cd rymar3.github.io.git

## 03. 	Створюємо нову вітку:
		git branch site
## 04.	Переходимо в вітку site :
		git checkout site
## 05.   Робимо зміни на сайті
		=== --- === --- === --- === --- === --- === --- 
## 06.  Проводимо індексацію змінених файлів
	 git add index.html

## 07.  Вносимо зміни в репозитарій:
	git commit -m "Римар В.О. - 03-Добавив заголовок"

## 08.	Перемкаємся на основну вітку :
	git branch
	git checkout main
	
## 09.  Отримуємо останню версію файла проекту :
	git pull 

## 10.  Добавляємо наші зміни до основного пректу : 		
	 git merge site

## 11. Заносим зміни на основний репозиторій :
	git push
