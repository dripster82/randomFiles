To enable the additional emulator options first locate your emulators.html usually located at
```
/var/www/html/emulators.html
```

then add the contents of the extra_options.js below the jquery script
eg
```
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
	<script>
		$(function() {
		  	launchPageConfig["apps"][0]["iOS"]["devices"] = [
			  	{
.
.
.
```
this will add the following Apple emulators
![image](https://github.com/dripster82/randomFiles/assets/408524/82ccda24-09f7-414f-bc7b-a24906647206)
