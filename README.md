Цель проекта
Персонализировать предложения постоянным клиентам, чтобы увеличить их покупательскую активность

Описание проекта

Интернет-магазин «В один клик» продаёт разные товары: для детей, для дома, мелкую бытовую технику, косметику и даже продукты. Отчёт магазина за прошлый период показал, что активность покупателей начала снижаться. Привлекать новых клиентов уже не так эффективно: о магазине и так знает большая часть целевой аудитории. Возможный выход — удерживать активность постоянных клиентов. Сделать это можно с помощью персонализированных предложений. «В один клик» — современная компания, поэтому её руководство не хочет принимать решения просто так — только на основе анализа данных и бизнес-моделирования. У компании есть небольшой отдел цифровых технологий, и вам предстоит побыть в роли стажёра в этом отделе.

План работ

Загрузить данные
Провести предобработку
Провести Исследовательский анализ данных
Корреляционный анализ
Создание Пайплайна (выбор подходящих моделей)
Анализ влияющих признаков
Сегментация покупателей
Результат

Создали один общий пайплайн и обучили четыре модели KNeighborsClassifier(), DecisionTreeClassifier(), LogisticRegression() и SVC(). В качестве метрики выбрали универсальный вариант ROC-AUC.

Лучшая модель LogisticRegression(C=10, penalty='l1', random_state=42, solver='liblinear'))]), метрика roc_auc по кросс валидации = 0.896
