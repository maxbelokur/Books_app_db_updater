# ПОРТФОЛИО: PET-Проекты
______________________________________________________
## Python.

### 1. Book store app:
#### Цель проекта: Создание базы данных для продуктового анализа и визуализации. 
Задачи:
- Создать скрипт для рандомного ежедневного пополнения базы данных онлайн магазина книг действиями существующих и новых клиентов.
- Настроить автоматическое выполнение скрипта через Git Action.
- Настройка загрузки отформатированного датафрейма .CSV в Google Sheets для создания Dashboard в Tableu. 
- Настроить отправку автоматических уведомлений в Телеграм Бот.

Выполнение:
1. Скрипт генерирующий данные новый действий клиентов - **Python__Books_store_app/script_gen_books_app_data.py**
2. Скрипт форматирующий полученный данные перед выгрузкой в Google Sheets - **Python__Books_store_app/script_format_books_df.py**
3. Скрипт выгружает CSV файл в Google Sheets - **Python__Books_store_app/script_books_df_upload_to_gsh.py**
4. Dashboard Tableu - https://public.tableau.com/app/profile/maksim.belokur/viz/Book_app_dashboarv_v_1/Dashboard1



## PostgreSQL

### 1. Online_retail: Анализ удержания клиентов | Retention Analyst
Задачи:
- Построить когортный анализ.
- Определить долю пользователей, который веронулись после 30, 60 и 90 дней.

_Датафрей: Online Retail (https://archive.ics.uci.edu/dataset/352/online+retail)_

Выполнение: Скрипт PostgreSQL__Online_retail/Online_retail_retention_cohort.sql

Результат:
![image](https://github.com/user-attachments/assets/6fd9bde1-c94e-422d-abd1-96776792008b)

