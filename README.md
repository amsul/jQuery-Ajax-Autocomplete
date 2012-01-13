# Ajax Autocomplete for jQuery 1.1.4

***

Fork of http://www.devbridge.com/projects/autocomplete/jquery

Added a callback function option to the plugin

***

Can be called as any other option:


```
var options = {
  			callback = function() {
				console.log('List has been filtered! :D');
			}
		}

$('#search').autocomplete(options);
```