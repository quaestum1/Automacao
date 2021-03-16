## <a href="https://github.com/Hidekithiago/Automacao/blob/master/README.md">Windows</a> <br>
<details>
<details><summary><b>Execute Program</b></summary>
  
####  NuGet
  > 
  
####  import
  > 
  
####  Code  
  > System.Diagnostics.Process.Start("PathToExe.exe");
  
</details>
<details><summary><b>Execute Program and Wait answer</b></summary>
  
####  NuGet
  > 
  
####  import
  > 
  
####  Code  
  > Process p = new Process(); 
 ><br>p.StartInfo.UseShellExecute = false;
 ><br>p.StartInfo.RedirectStandardOutput = true;
 ><br>p.StartInfo.FileName = "YOURBATCHFILE.bat";
 ><br>p.Start(); 
 ><br>string output = p.StandardOutput.ReadToEnd();
 ><br>p.WaitForExit();
  
</details>

<details><summary><b>Taskkill</b></summary>
  
####  NuGet
  > 
  
####  import
  > using System.Diagnostics;
  
####  Code  
  > Process.Start("taskkill", "/F /IM [taskname].exe");
  
</details>

</details>
