<div align="center">

## Dynamic Favorites Function


</div>

### Description

To dynamically add a web page to a user's favorites folder.
 
### More Info
 
Make sure you set TITLE tags as I have them in the sample code.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Matt Khoury](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/matt-khoury.md)
**Level**          |Intermediate
**User Rating**    |4.5 (27 globes from 6 users)
**Compatibility**  |
**Category**       |[\.JS files](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/js-files__2-77.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/matt-khoury-dynamic-favorites-function__2-2198/archive/master.zip)





### Source Code

```

  <HTML>
  <HEAD>
  <TITLE>ADD To Favs</TITLE>
  <SCRIPT language="JavaScript1.2">
  	var bookmarkurl = window.location.href;
  	var bookmarktitle = document.title;
  	function addfav(){
  	if (document.all) window.external.AddFavorite(bookmarkurl,bookmarktitle);
  	}
  </SCRIPT>
  </HEAD>
  	<BODY>
  		<A href="javascript:addfav()">Add page To favorites</A>
  	</BODY>
  </HTML>
```

