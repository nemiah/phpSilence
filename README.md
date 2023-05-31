# phpSilence
Get your Silence scooter data from their servers in JSON format

I send a big thank you to [https://github.com/lorenzo-deluca/homeassistant-silence](https://github.com/lorenzo-deluca/homeassistant-silence) for reverse engineering the API!

##Usage:

	composer.phar require nemiah/php-silence:dev-main

Make an instance and get the data:

	$api = new nemiah\phpSilence\api($email, $password);
	$data = $api->getData();
	
##Contributions:
Sure, just send me a PR!