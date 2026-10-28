#new-project
Один раз: git config --global user.name "..." и git config --global user.email "...".
творити каталог: mkdir new-project
Перейти в каталог: cd new-project
Створити локальний репозиторый: git init -b main 
Створити README.md з текстом: echo "# new-project" > README.md 
Підготувати до комміту: git add README.md 
Комміт: git commit -m "init".
Створити нові гілку: git checkout -b development 
Проверка: git branch → звёздочка у development.
Додати інструкцію в README 
Підготувати до комміту: git add README.md.
Використати Smart Commit:  git commit -m "DEV-4 #time 30m #comment Add instructions to README" 
Переключитись: git checkout main 
Зробити merge: git merge development
Перевірити: git status повинно бути nothing to commit, working tree clean;
Створити репозиторий new-project на Github
Зв'язати репозиторії: git remote add origin https://github.com/<user>/new-project.git
Залити main git push -u origin main 
Залити dev git push -u origin development. 
