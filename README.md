# netoaster
A .net toaster library for very simple and slightly customizable toaster notifications

# how to use

1. Install using [nuget](https://www.nuget.org/packages/netoaster/1.0.0 "nuget") or by including the 
above netoaster project into your WPF app

2. create an instance of a toaster, and call .Show()

```
ErrorToaster.Toast("My Error Message!");
``` 

![alt tag](https://raw.github.com/zachatrocity/netoaster/toasterdemoapp/error.png)

```
SuccessToaster.Toast("Success message");
```

![alt tag](https://raw.github.com/zachatrocity/netoaster/toasterdemoapp/success.png)

```
WarningToaster.Toast("Warning message", "bottomright");
```

![alt tag](https://raw.github.com/zachatrocity/netoaster/toasterdemoapp/warning.png)

3. Optional parameters (more to come)

	* message - the text to display in the toaster
	* position - the position to show the toaster, like "bottomright" (default is topright)

#To do:
	* add more positions
	* add optional colors
	* add more animations
	* for feature requests open a new issue

	
#Concept 
skeleton of code came from [this](http://stackoverflow.com/questions/3034741/create-popup-toaster-notifications-in-windows-with-net/3035755#3035755, "this") stackoverflow post
by [Ray Burns](http://stackoverflow.com/users/199245/ray-burns, "Ray Burns"). I customized it to my own needs.
			
			
#Contribute
feel free to submit pull-requests
