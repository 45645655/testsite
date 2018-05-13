<!DOCTYPE html>
<html>
<head></head>
<body>
  <script>
    'use strict';
var UserName = prompt('Кто пришёл?', ''); 
if (userName == 'Админ') {
	
var pass = prompt('Введите пароль', '');

if  (pass == 'Чёрный Властелин') {
alert( 'Добро пожаловать!' );
} else if ( pass == null ) {
alert( 'Вход отменён' );
} else {
alert( 'Пароль неверен' );
}

} else if (UserName == null) {
alert( 'Вход отменён' );
} else {
alert( 'Я вас не знаю' );
}
  </script>
</body>
</html>
