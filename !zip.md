## <a href="https://github.com/Hidekithiago/Automacao/blob/master/README.md">ZIP</a> <br>
<details>
<details><summary><b>Unzip</b></summary>
  
####  NuGet
  > 
  
####  import
  > using System.IO.Compression;
  
####  Code  
  ><br>string startPath = @".\start";
  ><br>      string zipPath = @".\result.zip";
  ><br>        string extractPath = @".\extract";
  ><br>      ZipFile.CreateFromDirectory(startPath, zipPath);
  ><br> ZipFile.ExtractToDirectory(zipPath, extractPath);
  
</details>
</details>
