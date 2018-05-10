# Первые шаги по освоению HTML
## Инструкция по запуску проекта
1. Скачиваем и устанавливаем Vagrant и Virtual box
1. Клонируем репозиторий в удобную нам папку с помощью команды:

       git clone git@github.com:sofiamaslova/MY-NEW-Rep.git
1. Переходим в папку **cd html-first-steps**  `cd html-first-steps`
1. Запускаем виртуальную машину: `vagrant up`
1. Заходим в командную строку по SSH - протоколу: `vagrant ssh`
       
 ## Инструкция по базовой работе с Git
       
1. `git add` добавляет файлы в индекс
1. `git commit` -создает коммит из весх файлов в индексе
1. `git commit -m ""Comment"` - позволяет добавиить комментарий к коммиту в командной строке
1. `git push`
1. `git pull`
1. `git clone `

## Работа с HTML
### Подключение скриптов и стилей

*скрипты можно подключить с помощью тега `<script>`:

    <script type="text/javascript">
        // Обьявляем переменную только в Java скрипт
         var j = 10;
     console.log(j);
     </script>
   
* стили создаются с помощью тега `<style>`:
        
            <style>
                h1 {
                    text-align: center;
                }
                h1 {
                    background: aqua;
                }
                </style >
### Подключение файлов
 Чтобы подключить файл со скриптом, необходимо прописать тег `<script>` с атрибутом `src`:
 
         <script src="index.js" type="text/javascript"> </script>
         
* Для получения файла со стилями прописываем тег `<link>` с атрибутом `rel="stylesheet"`:
          
          <link rel="stylesheet" href="index.css">
          
                                