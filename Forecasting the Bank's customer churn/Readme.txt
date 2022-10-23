# Bank customer churn


Clients started leaving the bank. Every month. Few, but noticed. Bank marketers considered that the main customers are cheaper than attracting new ones.
It is necessary to predict whether the client of the bank will leave in the near future or not. Provided historical data on customer behavior and termination of agreements with the bank.

В проекте реализованы 2 модели:  модель логистической регрессиии и модель случайного леса. Лучшей себя показала модель случайного леса как при подборе параметров, 
так и на тестовой выборке. Основные метрики качества модели случайного леса на тестовой выборке:

Accuracy лучшей модели: 0.863 - доля верных ответов предсказанных моделью
F1 лучшей модели: 0.636 - среднее гармоническое (качество прогноза положительного класса)
Auc_roc составил 0.868 - доля верных ответов модели (или площадь под кривой)

На графике ROC-кривой хорошо видно на сколько кривая реализованной модели поднимается над "кривой" случайной модели. 
Разность их площадей 0.86-0.5= 0.36, т е на 36% реализованная модель эффективнее случайной и в 86% случаев дает верный результат.