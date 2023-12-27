
Редактор должен позволять делать следующие действия:
1. Добавлять новые NPC по разным координатам (типы объектов предопределены заданием)
a. NPC размещаются в квадрате 0<=x<=500 метров, 0<=y<=500 метров
b. У каждого типа объекта помимо координат должно быть уникальное имя.
2. Сохранять объекты в файл и загружать из файла
3. Печатать перечень объектов на экран (с типом объектов, координатами и именем)
4. Запускать боевой режим с указанием дальности, на которой могут сражаться NPC. В боевом режиме NPC начинают сражаться каждый с каждым (если дальность позволяет), проигравший NPC – удаляется. При этом погибнуть могут и оба NPC.

При создании программы обязательно использовать паттерны:
- Какой-нибудь из вариантов Factory для создания NPC и загрузки NPC из файла
- Visitor – для проведения цикла сражения
- Observer – для печати событий о совершенных убийствах. Сделать два класса Observer – для записи в файл “log.txt” и для печати на экран.


