# jQuery-lastfm

This plugin will get the Recent Tracks for a lastfm user and it produces structured HTML with in-built CSS classes for styling.
check it out: [http://plugins.jquery.com/lastfm/]

# Usage

```html
    <div class="yui-u first">

       <div id="result"></div>

    </div>
    <div class="yui-u">

       <div id="result2"></div>
	
    </div>

```

```js
$(document).ready(function(){ 

     $('#result').lastfm({username: 'thinkphp'});
     $('#result2').lastfm({username: 'yelf'});

}); 

```


# License

  MIT
  
[http://plugins.jquery.com/lastfm/]: http://plugins.jquery.com/lastfm/
