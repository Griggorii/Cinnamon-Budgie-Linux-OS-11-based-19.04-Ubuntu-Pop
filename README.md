# Cinnamon-Budgie-Linux-OS-15-based-19.04-Ubuntu-Pop требуется флешка на 4 гигабайта вес iso 3Гб 

Update Cinnamon-Budgie-Linux-OS-15-based-19.04-Ubuntu-Pop X64 Android + новое дополненное меню + my skel setting + Android

______________________________________________________________________________________________________________________

Скачать ISO дистрибутив Download Cinnamon Budgie OS 14 19.04 iso 3Гб  ----coming 15 min uploade---- + (Android https://yadi.sk/d/Cc-bpsnqtk1b9w) 

При загрузке в верхнем самом правом углу нажмите на значек и выбирите budgie окружение не budgie-panel это наработка так что не путать начнет проявляться сессия это будет долго так как флешка на рабочем столе жмём Установить RELEASE и пароль 123 если 
что какие проблемы то читать в Читать.txt в самом низу , но навряд ли они будут я проверил при установке пользователь все нормально создается как установите возможно вылетите в сессию unity так же выходим меняем на любое другое окружение , сами обновляем систему если надо. Кошелек для тех кто действительно видит что наработано нечто новое чем обычно в документах dconf 
конфигурации , для тех кому ну очень нужен режим блокировки экрана ставим dconf-editor там ищем lockdown который в сессии gnome и убираем галочку запретить блокировку экрана надеюсь вы поняли что вся конфигурация у меня нормальная , если проблемы 
какие черный экран ядро допустим новое поставили то от рута заходим в папку /root/.cache и чистим оттуда то что чистит остальное пропустить и не рутовый кеш тоже можнов хомяке почистить.


Android cm-x86-14.1-r2.i686.rpm распаковать прямо от рута в корень / и обновить груб после перезагрузки можно загрузиться , документация на рабочем столе читать расскажет как создать data.img
Пароль для установки 123 такой же пароль имеет рут. 
Понадобиться флешка с 4 гигабайтами для того что бы образ влез , 
можно взять флешку и не стирая её закинуть туда образ программой WinSetupFromUSB_1-0 
или программой (unetbootin не помню стирает она данные или нет перед прожигом) , 
точный пример без потери данных на флешке WinSetupFromUSB_1-0 выставив галки 
как на картинке https://imgur.com/a/7NugSRA , потому что не у всех есть флешка лишняя и так этот способ даст избежать лишних затрат на флешки , 
в play market тоже есть утилиты типа DriveDroid и другие с помощью которых можно 
даже с телефона установить по кабелю с ПК и установить образ со смартфона.
Для linux я использую https://unetbootin.github.io/linux_download.html просто делаете бинарник в свойствах
исполняемым и либо запускаете от админа или в терминал в той же папке руню рутирую и закидываю в его окно бинарь 
образ указываю предварительно смонтировав флешечку которая предварительно отформатирована не меньше чем fat32

Установка 

Flesh card / hdd / usb hdd / sdd / vhd / vhdx minimum size memory 16 gb

Как проверить любой дистрибутив , надо открыть настройки vlc плеера если вылетит значит не годится

Systemback также поможет восстановить систему и отремонтировать grub её и ваши фаилы не пропадут 
если они лежат именно в папке home , только пропадут программы которые установили после , это очень 
удобно на днях я попытался скомпилировать и разработать свой xorg-server в итоге ни клавиатура не 
мышь не работали и с помощью systemback я восстановил систему без всяких переустановок просто подмонтировал 
свой sd раздел в /mnt и включил восстановление системных файлов.

Про интернет соединение без роутера https://www.youtube.com/watch?v=mAUXs3WLuug у вас должно быть там всё на родном языке.
step 3: save правильнее , после step 3 yes ничего не делаем и выходим из терминала.
Потом у меня ниже на панели есть network-manager апплет зайдите щёлкнув на него либо лкм или пкм (потому что я не знаю как ваша мышь работает программно или настроена) изменить соединения и удаляете созданные проводное и Автоматический Ethernet и dsl соединение.

Затем жмёте + и создать из списка выбираете DSL/PPPoE

Соединение DSL 1 , 
предковый интерфейс enp2 , 
