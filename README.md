#AJAX+PHP+JS Web chat,no database needet!
Simple Web chat using AJAX+PHP,no database needet

Written in HTML,CSS,JS,PHP
#Live preview
http://itmu.vpn-host.ru/chat.php

#Description
Simple web chat,chat only working,if you have upload the unzipped archive into you hosting
no database needet,because all chat log saving into chat.txt (nickname+message)

#Files overview
1.chat.php-main screen (like index.HTML)
2.chat.js-javascript actions
3.chat.txt-its small database of sendet chat message
4.style.css-style of chat/body
5.process.php-its a main PHP code of send action using AJAX

#How it works
1.If you have load a page,you recive dialog,then should give you Nickname.
2.You See main interface its a Form(input) and send button(not working for now)
3.If you have press "Enter" button of you keyboard,starts a process(PHP) gets nickname and message and  adds this into chat.txt in Form: nickname(<span>) and message(<a>)
4.Chat reloading to See changes in chat.txt

also you have a short Form nickname+message


