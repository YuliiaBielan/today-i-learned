# _today-i-learned_
## git bash
- ls - виводить файли,які зберігаються в поточній директорії;
- ls -a - показує приховані файли і папки;
- cd - переходить до вказаної директорії:
    - cd ~/../.. - переходимо до вказаних директорій (з пробілом);
    - cd <назва директорії> - переходимо до вказаної директорії;
    - cd  .. - перехід на одну директорії вище (з пробілом);
    - cd  ../.. - перехід на дві директорії вище (з пробілом);
    - сd c:/ - перехід на диск С;
    - cd, cd ~ - перехід в кореневий каталог (з пробілом);
 - pwd - поточна директорія;
 - mkdir - створити директорію;
 - rmdir - видалити директорію;
 - touch - створити файл;
 - rm <iм'я файлу> - видалити файл;
 - cp - копіювати;
 - mv - перемістити;
 - cat - команда, що показує,що містить файл;
 - rm -rf <ім'я директорії>-видалити репозиторій чи директорію;

## git
- git version - версія git
- git init - ініціалізація репозиторію для поточного проекту;
- git status - перевірка статусу репозиторію (створених,змінених, видалених файлів);
- git add <назва файлу> - додаємо файл для відслідковування гітом ( в індекс)
- git add . - додаємо всі файли в індекс;
- git commit -m - фіксуємо зміни комітом (повідомленням) у кінцеву версію файлу,яку опрацювали;
- git log - перегляд комітів;
- git restore --staged <ім'я файлу> - видалити файл з області підготованих файлів;

## branches
- git branch <назва> - створити гілку;
- git checkout <назва> - переключитися в іншу гілку;
- git checkout -b <назва> - cтворити і переключитися в нову гілку;
- git merge - злиття гілок ( коміт має двох "батьків". Коміт з двома "батьками" означає,що михочемо об'єднати зміни із одного коміту з іншим комітом та всіма "батьківськими");
- git rebase - злиття гілок ( копіювання комітів та перенесення в інше місце, чисті лінійні послідовності коммітів);
