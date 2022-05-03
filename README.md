

## 01. Клонуємо сайт на свій комп
  	cd /c/intel  (для GitBash)
	cd c:\intel  (для GitCMD)
	git clone https://github.com/rymar3/rymar3.github.io.git
	cd rymar3.github.io
	
## 02. Прописуємо данні про себе щоб автори проекта знали хто вносив зміни 
	Eлектронна пошта повинна бути зареєстрована в github !!!
	git config --global user.name "ВАШ ЛОГІН GITHUB"
	git config --global user.email "ВАША ПОЧТА GITHUB"	
	git remote set-url origin https://rymar3:TOKEN@github.com/rymar3/rymar3.github.io.git
## 03. 	Створюємо нову вітку - site:
		git branch site
## 04.	Переходимо в вітку site :
		git checkout site
## 05.   Робимо зміни на сайті
		=======================================================
## 06.  Проводимо індексацію змінених файлів
	 git add .

## 07.  Вносимо зміни в репозитарій:
	git commit -m "Римар В.О. - 03-Добавив заголовок"

## 08.	Перемкаємся на основну вітку :
	git branch
	git checkout main (master)
	
## 09.  Отримуємо останню версію файла проекту :
	git pull 

## 10.  Добавляємо наші зміни до основного пректу : 		
	 git merge site

## 11. Заносим зміни на основний репозиторій :
	git push
