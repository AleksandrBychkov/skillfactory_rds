Основные цели и задачи проекта: научиться и использовать на практике основные методы разведывательного анализа данных (EDA), а именно – первичная оценка данных, проверка их на пустые значений, их замена или удаление при необходимости, проверка на выбросы, отбор данных для дальнейшей модели с использованием различных статистических методов.

Исходные данные представляют собой массив качественных (17) и количественных (13) переменных.  Пропущенных данных по всем показателям не более 10%, что говорит о репрезентативности данных. Данные позволяют построить модель для анализа влияния различных факторов и предсказания итогового балла по госэкзамену по математике у учеников (score), после соответствующей обработки.

Основные этапы работы над проектом:
- первичный анализ данных.
- определение пустых значений.
- замена пустых значений на моду для качественных переменных, на медиану для количественных (пустые значения в score удаляются).
- анализ количественных переменных с помощью графиков и метода корреляции. Анализ выбросов.
- по итогам, удаление 100% коррелирующего столбца. Работа с выбросами индивидуально по каждому столбцу.
- анализ количественных переменных c помощью коробчатых диаграмм и теста Стьюдента с поправкой Банферони.
- отбор итоговых переменных, влияющих на результат госэкзамена, для дальнейшего использования в модели.

Вопросы саморефлексии:
-	Моя роль в команде была самая что ни на есть ведущая.
-	Работой доволен в целом, получилось красиво и четко.
-	Не получилось разобраться как точно работает тест Стьюдента, пришлось его использовать как шаблон из примера.
-	Из модуля узнал в принципе, что такое EDA. Методы, используемые в нем я знал ранее, но было приятно их вспомнить на хорошем уровне.
-	Главный результат прохождения модуля, хорошее понимание и умение пользоваться на практике методами анализа массивов данных. Их обработки и подготовки для дальнейшего использования.
-	Эти же навыки я уже могу применять на практике.
-	Да, надеюсь, что по ходу обучения еще будет информация на эту тему.

Комментарий для ментора: 
Основное сомнение по ходу работы было – удалять или нет значения 0 в переменной score. Их там достаточно много, 0 вероятно означает, что ученик не смог принять участие в экзамене, что также важно для итога. Поэтому в основной работе, представленной для проверки я принял решение не удалять нули. Тем не менее дополнительно провел ту же работу, где 0 удалены, это повлияло на существенное снижение параметров, влияющих на score, что дополнительно убедило меня остаться при первоначальном мнении.
Спасибо.
