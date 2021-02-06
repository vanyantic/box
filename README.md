# box
/*마우스 제한 스크립트*/

<script language='javascript' type='text/javascript'>  
  

    document.oncontextmenu = new Function('return false');  
    document.ondragstart = new Function('return false');  
    document.onselectstart = new Function('return false');  
    document.onkeydown = new Function('return false');  
  
</script>  

/*마우스 제한 스크립트*/




/*입력창에 Ctrl + V, Ctrl + C 막기*/
<script language='javascript' type='text/javascript'>  
  
    function checkCtl(e) {  
        var code = (document.all) ? event.keyCode:e.which;  
        var ctrl = (document.all) ? event.ctrlKey:e.modifiers & Event.CONTROL_MASK;  
        var msg = "Ctrl + C / Ctrl + V키 금지 ";  
      
      
        if (document.all) {  
            if (ctrl && code==86) {//CTRL+V  
                alert("Ctrl + V는 사용할수 없습니다.");  
                window.event.returnValue = false;  
            } else if (ctrl && code==67) { //CTRL+C (Copy)  
                alert("Ctrl + C는 사용할수 없습니다.");  
                window.event.returnValue = false;  
            }  
        }  
      
    }   
        
</script>  
/*입력창에 Ctrl + V, Ctrl + C 막기*/

