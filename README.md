 <!DOCTYPE html>
    <html>
           <head>
                   <style>
		#demo{color:yellow;background:blue;height:250px;width: 300px;font-size: 25px;}
		button{background:red;}
	</style>
           </head>
           <body>
            <h1>Đoạn mã JavaScript được đặt trong head</h1>
            <p id="demo"></p>
            <button type="button" onclick="hienthi()">Hiển thị</button>            
           <button type="button" onclick="tongn()">Tổng 1->n</button>  
           <button type="button" onclick="tongchan()">Tổng chẵn 1->n</button>  
          <script>
              function hienthi() {
                document.getElementById("demo").innerHTML = "Hello.";
              }
             function tongn() {
	//Hiển thị tổng 1 -> 10
                document.getElementById("demo").innerHTML = "Tổng 1->n.";
              }
            function tongchan() {
	//Hiển thị tổng chẵn 1->10
                document.getElementById("demo").innerHTML = "Tổng chẵn 1->n.";
              }
            </script>       
     </body>
    </html>
      
