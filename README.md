<!DOCTYPE html>
    <html>
           <head>
                      <style>
		#noidung{background: blue; height:250px; width:100%;color:yellow; font-size:25px;}
		button{background:red;}
	</style>
           </head>
           <body>
            <h1>Bài tập JavaScript</h1>
          <form id="myForm" action="">
             <p>Vui lòng nhập tên: <input id="textbox1" name="ten" type="text" /></p>
             <p>n =  <input id="textbox2" name="n" type="text" /></p>
           </form>
            <p id="noidung">hi</p>
            <button type="button" onclick="hienthi()">Tên </button>            
           <button type="button" onclick="tinhtong()">Tổng</button>            
          <button type="button" onclick="tinhtongchan()">Tổng chẵn</button>  
            <script>
              function hienthi() {
	// Giới thiệu tên
	document.getElementById("noidung").innerHTML = "Tên tôi là " + document.forms["myForm"].ten.value;
              }
             function tinhtong() {
                  //Tính tổng từ 1 -> n
	document.getElementById("noidung").innerHTML ="Tổng từ 1 đến " +  document.forms["myForm"].n.value + " là: ";
	
              }
            function tinhtongchan() {
                  //Tính tổng các số chẳn từ 1 -> n
	document.getElementById("noidung").innerHTML ="Tổng các số chẵn từ 1 đến " +  document.forms["myForm"].n.value + " là: ";
              }
            </script>    
         </body>
    </html>
      
