#  Description
Аудиоплеер с клиентской и серверной частью. На клиенте реализуется пользовательский интерфейс в виде списка аудиозаписей, загруженных из базы данных, и панель управления воспроизведением с кнопками «старт/пауза», «стоп», «следующий трек», «предыдущий трек».
На серверной части будет размещена база данных со списком аудиозаписей. Задача сервера – отправить требуемый аудиофайл клиенту по запросу.

## Screenshots 
![main_view](screenshots/main_view.png) <br/>
![file_menu](screenshots/file_menu.png) 
![playback_menu](screenshots/playback_menu.png) 
![audio_menu](screenshots/audio_menu.png) 
![options_menu](screenshots/options_menu.png) 

## Target
Основной целью является реализация минимального объёма работ, включающего в себя следующие объекты: <br/>
1.	Пользовательский интерфейс (клиент) <br/>
	1.1.	Список аудиозаписей – создаётся запрос к базе данный, в ответ принимается список файлов <br/>
	1.2.	Панель управления – осуществляет управление воспроизведением текущей аудиозаписей. Кнопки «старт/пауза», «стоп», «следующий трек», «предыдущий трек». <br/>
2.	Сервер <br/>
	2.1.	База данных – SQLite, содержит список треков, по запросу от клиента производит поиск файла по наименованию, отправляет файл на клиент. <br/>
	2.2.	Сетевой интерфейс – осуществляет передачу запроса от клиента к серверу и передачу файлов от сервера к клиенту. <br/>

## Plan 
Loading...

## Supported format
- Audio : mp3 , wav , aif <br/>
- Viedo : mp4 , flv <br/>

## Credits
•	Инструмент разработки – IntelliJ IDEA <br/>
•	Язык программирования – Java. <br/>
•	Среда разработки интерфейса – SceneBuilder. <br/>

## Authors
Чикулаев Владислав Алексеевич - _M3RL1N_ (frontend dev) <br/>
Кушнир Никита Анатольевич - barsiqe (teamlead) <br/> 
Тимофеев Кирилл Александрович - its_clicking (backend dev) <br/>