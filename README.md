# About Momo


<h3>Install</h3>
<p>Download &amp; Extract the zip file</p>
<p>Under the Project folder open the .env file and setup your database configurations</p>
<pre>
	APP_ENV=local
	APP_DEBUG=true
	APP_KEY=SomeRandomString
	APP_URL=http://localhost

	DB_HOST=127.0.0.1
	DB_PORT=3306
	DB_DATABASE=<-- Here goes database name -->
	DB_USERNAME=<-- Here goes database username -->
	DB_PASSWORD=<-- Here goes database password -->

	CACHE_DRIVER=file
	SESSION_DRIVER=file
	QUEUE_DRIVER=sync

	REDIS_HOST=127.0.0.1
	REDIS_PASSWORD=null
	REDIS_PORT=6379

	MAIL_DRIVER=smtp
	MAIL_HOST=mailtrap.io
	MAIL_PORT=2525
	MAIL_USERNAME=null
	MAIL_PASSWORD=null
	MAIL_ENCRYPTION=null
</pre>
<p>Run the migration command to create tables under Momo directory via CLI</p>
<pre>
	php artisan migrate
</pre>
<h6>Or</h6>
<p>You can directly import the sql dump from DB folder in case of servers</p>
<p>Now you can open the Momo link in your browser</p>
<h3><a id="user-content-credits" href="https://github.com/ladybirdweb/faveo-helpdesk#credits" aria-hidden="true"></a>Credits</h3>
<ul>
  <li><a href="https://github.com/laravel/laravel">Laravel Framework</a></li>
  <li><a href="https://github.com/almasaeed2010/AdminLTE">Admin LTE Theme</a></li>
  <li><a href="https://github.com/barbushin/php-imap">PHP IMAP</a></li>
  <li><a href="https://github.com/PHPMailer/PHPMailer">PHP MAILER</a></li>
</ul>

<h3>YouTube Channel</h3>
<p><a href="https://www.youtube.com/channel/UC-eqh-h241b1janp6sU7Iiw" target="_blank">Click here</a></p>


