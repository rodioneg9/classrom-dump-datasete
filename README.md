# classrom-dump-datasete
dump classroom course
Етот програма позволяет превратить весь курс в датасет для обучения ИИ

Как ее использововать :
1 Сначала получите oauch 2 google в Google Cloud ето несложно  и скачайте файл client_secret_********vd.apps.googleusercontent.com.json и закинте файл в директорию проетка перейменовавши ево в credentials.json
Какие нада API 
Classroom Api и Drive API
Затем запустие oauch-create.py и автоизуйтесь в нужний акаут на которм есть курс которий нада сдампить 
Затем получаем Course ID ето не в ссилке https://classroom.google.com/u/0/c/ODMxMzE0MTMxNTI3 или подобние а числовой он вигляит так 389530578212
Где ево взять запускаем id-class-dunp.py и получаем id и меняем получений id в  переменую COURSE_ID в main.py 
И всее
