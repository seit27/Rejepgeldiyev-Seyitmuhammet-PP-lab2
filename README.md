# Лабораторная работа №2  
## Технологии программирования  

---

# 📌 ЗАДАНИЕ 1. Консольные приложения в Repl.it  

## 🎯 Цель работы  
Изучить процесс создания, редактирования и запуска консольных приложений на языке C с использованием онлайн-среды разработки Repl.it.

<img width="1364" height="598" alt="2 (соеденил репозиторию к replit)" src="https://github.com/user-attachments/assets/40a3cdce-ae7e-4977-aeab-caad54f0fa8b" />


---

## 🧩 Ход выполнения работы  

### 🔹 1. Создание проекта  
Был создан новый проект в среде Repl.it с языком программирования C.

<img width="1365" height="600" alt="1 (создано репазитория в git)" src="https://github.com/user-attachments/assets/d88b68bf-82f5-4f26-8100-eca2f2941476" />

<img width="1365" height="600" alt="1 (создано репазитория в git)" src="https://github.com/user-attachments/assets/45efed7c-d375-4413-8fc3-df7b3a7dedc5" />


---

### 🔹 2. Создание исходного файла  
В проекте был создан файл `hello.c`, в котором реализована простая программа.

Программа выводит сообщение на экран с помощью функции `printf`.

<img width="862" height="134" alt="4 (переименовал hello на main)" src="https://github.com/user-attachments/assets/40d35358-f732-4bd2-a14b-2b98c2df5675" />

<img width="937" height="214" alt="5 (направил на правильный адрес  replit)" src="https://github.com/user-attachments/assets/1eda331d-f04a-4b6e-abed-e842ca731d79" />


---

### 🔹 3. Изучение структуры программы  
В ходе работы была изучена базовая структура программы на языке C:

- подключение библиотек (`#include <stdio.h>`)
- функция `main()`
- использование команд вывода (`printf`)

<img width="526" height="573" alt="6 (написал код на main c)" src="https://github.com/user-attachments/assets/91bafa3f-00b4-4f02-ab6b-5dd0d96396d4" />

 <img width="422" height="503" alt="7 (написал код на main c)" src="https://github.com/user-attachments/assets/f9cba885-66a4-4e6f-9b0f-206e7a50ff27" />


---

### 🔹 4. Компиляция и запуск программы  
Программа была успешно скомпилирована и запущена с помощью кнопки **Run** в Repl.it.

<img width="404" height="218" alt="8 (запускаем приложение)" src="https://github.com/user-attachments/assets/3ed80a6e-8ad9-4052-b960-c5aa3f8e0f19" />


---

### 🔹 5. Результат выполнения  
На экран было выведено сообщение, заданное в программе.

<img width="1076" height="428" alt="9 (сделаем commit)" src="https://github.com/user-attachments/assets/d1d1c1a5-f54b-4a5f-92d0-aa2fb3ce5260" />


---

## ✅ Результат  

В результате выполнения задания была освоена работа с онлайн-средой разработки Repl.it, создано и запущено первое консольное приложение на языке C.

---

# 📌 ЗАДАНИЕ 2. Изучение GitHub Actions (Hello World)  

## 🎯 Цель работы  
Изучить систему автоматизации GitHub Actions и научиться создавать workflow для автоматического выполнения команд.

---

## 🧩 Ход выполнения работы  

### 🔹 1. Создание структуры workflow  
В репозитории был создан каталог:

.github/workflows  

В этом каталоге размещаются файлы автоматизации.

<img width="1353" height="463" alt="1 (создаём)" src="https://github.com/user-attachments/assets/8506717a-7798-470d-acf3-5142ddf8d0b4" />


---

### 🔹 2. Создание файла workflow  
Был создан файл:

learn-github-actions.yml  

<img width="1332" height="593" alt="2 (пишем правильный путь)" src="https://github.com/user-attachments/assets/b63b0286-b87c-44b3-b51d-0f6af75f3883" />


---

### 🔹 3. Описание workflow  

В файл был добавлен следующий код:

<img width="1353" height="516" alt="3 (добавил код и commit)" src="https://github.com/user-attachments/assets/37d89af6-4c38-4812-a674-d8487f5d5c4e" />


---

### 🔍 Объяснение работы  

- `name` — имя рабочего процесса  
- `on: push` — запуск при отправке кода  
- `jobs` — список заданий  
- `runs-on` — операционная система  
- `steps` — шаги выполнения  
- `checkout` — скачивает репозиторий  
- `run` — выполняет команды  


---

### 🔹 4. Отправка workflow  

Файл был добавлен в репозиторий:

git add .  
git commit -m "Add workflow"  
git push  


---

### 🔹 5. Проверка работы  

После отправки изменений workflow автоматически запустился во вкладке **Actions**.

<img width="1345" height="504" alt="4 (всё работает)" src="https://github.com/user-attachments/assets/c7052fbe-e556-4690-8ed3-bcc19136ebc1" />
  

---

## ✅ Результат  

В результате выполнения задания был создан workflow, который автоматически выполняет команды при каждом изменении в репозитории.

---

# 📌 ЗАДАНИЕ 3. Использование структур в C  

## 🎯 Цель работы  
Изучить структуры в языке C и научиться создавать многомодульные программы.

---

## 🧩 Ход выполнения работы  

### 🔹 1. Создание каталогов  

Была создана структура проекта:

mkdir labtp2026  
cd labtp2026  
mkdir labrabota2  
cd labrabota2  
mkdir labtask3  
cd labtask3  

<img width="616" height="439" alt="2 (Создал папку)" src="https://github.com/user-attachments/assets/d30f5606-3043-496e-9efc-e5eaaaa02001" />


---

### 🔹 2. Инициализация Git  

git init  
echo "# labrabota2-task3" >> README.md  
git add README.md  
git commit -m "first commit"  

<img width="662" height="506" alt="3 (Создал Git репозитория)" src="https://github.com/user-attachments/assets/d9967585-b7dc-416c-b367-26fd54055736" />


---

### 🔹 3. Подключение GitHub  

git remote add origin (ссылка)  
git push -u origin main  

<img width="661" height="468" alt="8" src="https://github.com/user-attachments/assets/f479be17-b73f-44cd-afeb-a660b12e78a0" />


---

### 🔹 4. Создание ветки  

git checkout -b dev  
 

---

### 🔹 5. Создание структуры проекта  

Создан каталог `src`, в котором размещены исходные файлы:

- `student.h` — описание структур  
- `student.c` — реализация  
- `main.c` — основной файл  

<img width="676" height="169" alt="10 (main c)" src="https://github.com/user-attachments/assets/66561084-03f0-441b-8097-899dccc8ce0d" />

<img width="677" height="525" alt="10 (student c)" src="https://github.com/user-attachments/assets/4ec4c065-00ba-440c-8093-8c2cd78e5873" />



---

### 🔹 6. Реализация структуры  

В программе были реализованы:

- структура адреса  
- структура студента  
- вложенные структуры   

---

### 🔹 7. Добавление файлов в Git  

git add .  
git commit -m "Add source files"  
git push  

<img width="654" height="655" alt="4 3" src="https://github.com/user-attachments/assets/65593f15-b3ab-464a-8caf-fa196f612721" />

<img width="496" height="584" alt="5" src="https://github.com/user-attachments/assets/9a0d49a5-e664-4c5f-a8ce-d4bf873d05e2" />

<img width="595" height="257" alt="6" src="https://github.com/user-attachments/assets/3db07e8d-d08c-4f2e-bc4e-7fd54315c58b" />


---

### 🔹 8. Компиляция программы  

Программа была скомпилирована с помощью компилятора gcc:

gcc main.c student.c -o program  

<img width="677" height="525" alt="10 (student c)" src="https://github.com/user-attachments/assets/a45fd14f-fe97-4848-a28e-2f4e5fac87c5" />
 

---

### 🔹 9. Результат выполнения  

Программа успешно выводит данные о студенте:

- имя  
- возраст  
- id  
- адрес
- 
./program.exe  

<img width="486" height="130" alt="9" src="https://github.com/user-attachments/assets/a9d20aae-d16a-47fb-8953-8224bb948415" />


---

## ✅ Результат  

В результате выполнения задания была разработана программа с использованием структур, разбитая на несколько файлов, успешно скомпилированная и запущенная.

---

# 📌 ОБЩИЙ ВЫВОД  

В ходе выполнения лабораторной работы были получены следующие навыки:

- создание консольных приложений на языке C  
- работа с Git и GitHub  
- создание автоматических процессов с помощью GitHub Actions  
- использование структур в языке C  
- работа с многомодульными программами  

Полученные знания позволяют создавать полноценные проекты, управлять кодом и автоматизировать процессы разработки.
