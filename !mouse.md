## <a href="https://github.com/Hidekithiago/Automacao/blob/master/README.md">Mouse</a> <br>
<details>
<details><summary><b>Move mouse and Click</b></summary>
  
####  NuGet
  > 
  
####  import
  > 
  
####  Code  
  > public static void LeftMouseClick(int xpos, int ypos)
  ><br>      {
  ><br>            SetCursorPos(xpos, ypos);
  ><br>            mouse_event(MOUSEEVENTF_LEFTDOWN, xpos, ypos, 0, 0);
  ><br>            mouse_event(MOUSEEVENTF_LEFTUP, xpos, ypos, 0, 0);
  ><br>        }
  
</details>
</details>
