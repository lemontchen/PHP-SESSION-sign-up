# PHP-SESSION-sign-up

PHP处理session跨域--同一根域名下子域名之间的跨域


ini_set('session.name', 'sid'); //设置session_id的键名

ini_set('session.use_trans_sid', 0); //不使用 GET/POST 变量方式

ini_set('session.use_cookies', 1); //使用cookie保存session_id的方式

ini_set('session.cookie_path', '/');

ini_set('session.cookie_domain', '.havegood.com');//跨域访问Session

session_start();//开启session
