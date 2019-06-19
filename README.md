# Steam-Signature
PHP script to display image with steam profile information

requirements:
	webserver with php-gd support
	a steam api key; you can get yours here: https://steamcommunity.com/dev/apikey

installation:
	you'll need to enter your api key within the steam.php file here: $str_api_key='';
	upload steam.php & the resources folder to your webserver.

usage:
	use your steamID64 as a variable on parameter called profiles; examples below

	the link below can used with an forum image bbcode;
		www.example.com/steam.php?profiles=76561197979918844
	or inserted into html like so;
		<img src="www.example.com/steam.php?profiles=76561197979918844">
