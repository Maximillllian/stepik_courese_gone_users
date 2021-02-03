Предсказываем, уйдет ли пользователь  курса на основе данных за первые три дня

Нужно скачать папку (там файлы с данными):
https://drive.google.com/drive/folders/1AHXG0Rc8A03xBxV28JfZrOPB3VC_g7QU?usp=sharing

# Описание файлов
 **analysis_and_model.ipynb** - анализ данных, фичаинжиниринг, создание моделей и базовая оценка моделей
 **stepik_ml_test_data.ipynb** - некоторые функции
 Скачанные файлы:
 **/data_files/stepik_ml/event_data_train.csv** - данные о ивентах со степами
 step_id - номер степа (шага, где есть теория/задание)
 timestamp - время
 action - действие (viewed - открыл, discovered - открыл в первый раз, sterted_attempt - начало решения, passed - пройдено)
 user_id - id пользователя 
 **/data_files/stepik_ml/submissions_data_train.csv** - данные о решениях практических степов
 step_id - номер степа (шага, где есть теория/задание)
 timestamp - время
 submission_status - статус решения (correct - правильно, wrong - неправильно)
 user_id - id пользователя 
 
 **/data_files/stepik_ml/events_data_test.csv** - тоже, что и event_data_train.csv, только за первые три дня. В анализе и построении модели роли не играет
 **/data_files/stepik_ml/submission_data_test.csv** - тоже, что и submissions_data_train.csv, только за первые три дня. В анализе и построении модели роли не играет
 **/data_files/stepik_ml/user_score_test.csv** - таблица, созданная на основе events_data_test.csv и submission_data_test.csv. В анализе и построении модели роли не играет
