### switch
```
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title>流程控制範例</title>
    <script language="javascript">
  var X = prompt("請輸入1-5的數字", "");
  switch(X)
  {
    case "1":    	//當使用者輸入1時
      alert("ONE");
      break;
    case "2":    	//當使用者輸入2時
      alert("TWO");
      break;
    case "3":    	//當使用者輸入3時
      alert("THREE");
      break;
    case "4":    	//當使用者輸入4時
      alert("FOUR");
      break;
    case "5":    	//當使用者輸入5時
      alert("FIVE");
      break;
    default:    	//當使用者輸入1-5以外的數字時
      alert("您輸入的數字超過範圍！");
      break;
  }
    </script>
  </head>
  <body>
  </body>
</html
```
