My Awesome Book

This file file serves as your book's preface, a great place to describe your book's content and ideas.

![](/assets/2017-04-24_23-13-59.png)

```javascript
<script type="text/javascript">
	$(document).ready(function(){
		$("#rezon-forms").rezOnForm({
			projectUrl: "https://rezon-az.galileo.com.ua/",
			defaultLang: "ru", // ua|ru|en
                        formType: "avia",
			formTarget: "_blank" // '_blank' - загружает поисковую выдачу в новое окно браузера., '_self' - в текущее окно.
		});
	});
</script>
```

<iframe src="https://rezon-az.galileo.com.ua/ru/IFrame?t=all" width="100%" height="350px"></iframe>


<!-- Установите блок в удобном месте -->
<div id="galileoForm"></div>

<script type="text/javascript">
    var galileoProject = "https://rezon-az.galileo.com.ua/ru/IFrame?t=all"; //Ссылка на iframe
    (function(d) {
        d.head.appendChild((function() {
            var s = d.createElement('script');
            s.src = 'https://bo.galileo.com.ua/Scripts/iframe.js';
            s.defer = true;
            return s;
        })());
    })(document);
</script>