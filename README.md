# js-bookmarklet 2022-04-07 時点

## [ロリポップログイン](https://user.lolipop.jp/)
```
javascript:$("input[name='account']").val("アカウント");$('#domain-id').val(ドメイン番号);$("input[name='passwd']").val("パスワード");jf_Login();void(0);
```

![image](https://user-images.githubusercontent.com/1501327/162091644-d7cd4a44-481b-45a6-83c9-537364657bef.png)


## Google パスワード入力部分
```
javascript:document.getElementsByTagName("input")[3].value="パスワード";document.getElementsByTagName("button")[1].click();void(0);
```

## 選択した英語を Google 翻訳する
```
javascript:(function(){var b=((window.getSelection&&window.getSelection())||(document.getSelection&&document.getSelection())||(document.selection&&document.selection.createRange&&document.selection.createRange().text));if(b!=''){window.open('https://translate.google.co.jp/?hl=ja&tab=wT#en/ja/'+encodeURIComponent(b));}else{window.open('https://translate.google.co.jp/translate?sl=en&tl=ja&js=n&prev=_t&hl=ja&ie=UTF-8&u='+encodeURIComponent(location.href)+'&act=url');}})();
```

## 選択した日本語文字列を Google 翻訳する
```
javascript:(function(){var b=((window.getSelection&&window.getSelection())||(document.getSelection&&document.getSelection())||(document.selection&&document.selection.createRange&&document.selection.createRange().text));if(b!=''){window.open('https://translate.google.co.jp/?hl=ja&tab=wT#ja/en/'+encodeURIComponent(b));}else{window.open('https://translate.google.co.jp/translate?sl=ja&tl=en&js=n&prev=_t&hl=ja&ie=UTF-8&u='+encodeURIComponent(location.href)+'&act=url');}})();
```

## ドメイン内検索
```
javascript:var wnd=document.createElement('iframe');wnd.setAttribute('id','if');wnd.frameBorder=0;document.body.appendChild(wnd);wnd.contentWindow.document.write('<script src=\'https://winofsql.jp/gds2.js\' charset=\'shift_jis\'></script>')
```

## Twitter
```
javascript:var d=document,w=window,enc=encodeURIComponent,e=w.getSelection,k=d.getSelection,x=d.selection,s=(e?e():(k)?k():(x?x.createRange().text:0)),s2=((s.toString()==%27%27)?s:(enc(s)+enc("\u000d\u000a"))),f=%27https://twitter.com/intent/tweet%27,l=d.location,p=%27?text=%27+s2+enc(l)+enc("\u000d\u000a\u0023\u30a4\u30e9\u30b9\u30c8\u0041\u0043\u0020\u3088\u308a\u30d5\u30ea\u30fc\u30c0\u30a6\u30f3\u30ed\u30fc\u30c9\u000d\u000a\u000d\u000a\u000d\u000a\u000d\u000a\u0023\u0043\u0047\u0020\u0023\u0033\u0044\u0020\u0023\u0033\u0044\u0043\u0047\u0020\u0023\u0033\u0044\u0041\u0052\u0054\u0020\u0023\u0044\u0041\u005a\u0033\u0044\u0020\u0023\u0044\u0041\u005a\u0053\u0074\u0075\u0064\u0069\u006f"),u=f+p;try{if(!/^(.*.)?tumblrzzz[^.]*$/.test(l.host))throw(0);tstbklt();}catch(z){a =function(){if(!w.open(u))l.href=u;};if(/Firefox/.test(navigator.userAgent))setTimeout(a,0);else a();}void(0)
```

## GINPRO 印刷
```
javascript:document.getElementById("top_1").remove();document.getElementById("banner").remove();document.getElementById("ginpro_links").remove();document.getElementsByClassName("navi")[0].remove();document.getElementsByClassName("date")[0].remove();document.getElementsByClassName("iphide")[1].remove();document.getElementsByClassName("iphide")[0].remove();try{document.getElementsByClassName("listCategoryArticle")[2].remove()}catch(e){};try{document.getElementsByClassName("listCategoryArticle")[1].remove()}catch(e){};try{document.getElementsByClassName("listCategoryArticle")[0].remove()}catch(e){};document.getElementById("DispArea2").remove();document.getElementsByClassName("powered")[0].remove();document.getElementsByClassName("posted")[0].remove();document.getElementsByClassName("gad")[1].remove();document.getElementsByClassName("gad")[0].remove();document.getElementsByClassName("sbtn")[0].remove();document.getElementsByTagName("h3")[0].remove();try{javascript:document.getElementById("top_1").remove();document.getElementById("banner").remove();document.getElementById("ginpro_links").remove();document.getElementsByClassName("navi")[0].remove();document.getElementsByClassName("date")[0].remove();document.getElementsByClassName("iphide")[1].remove();document.getElementsByClassName("iphide")[0].remove();try{document.getElementsByClassName("listCategoryArticle")[2].remove()}catch(e){};try{document.getElementsByClassName("listCategoryArticle")[1].remove()}catch(e){};try{document.getElementsByClassName("listCategoryArticle")[0].remove()}catch(e){};document.getElementById("DispArea2").remove();document.getElementsByClassName("powered")[0].remove();document.getElementsByClassName("posted")[0].remove();document.getElementsByClassName("gad")[1].remove();document.getElementsByClassName("gad")[0].remove();document.getElementsByClassName("sbtn")[0].remove();document.getElementsByTagName("h3")[0].remove();document.getElementsByClassName("google-auto-placed")[0].remove();window._cnt=document.getElementsByTagName("img").length;for(i=0;i<window._cnt;i++){document.getElementsByTagName("img")[i].style.boxShadow="none"};document.getElementById("content").style.cssText="width:1070px!important";void(0);}catch(e){};window._cnt=document.getElementsByTagName("img").length;for(i=0;i<window._cnt;i++){document.getElementsByTagName("img")[i].style.boxShadow="none"};document.getElementById("content").style.cssText="width:1070px!important";void(0);
```
