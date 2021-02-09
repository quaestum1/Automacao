## <a href="https://github.com/Hidekithiago/Automacao/blob/master/README.md">FILES</a> <br>
<details>
<details><summary><b>DELETE FILE</b></summary>
  
####  NuGet
  > 
  
####  import
  >using System; <br>
   using System.IO; <br>
  
####  Code
  >try <br>
        { <br>
            File.Delete(diretorio);<br>
        } <br>
        catch (Exception e) <br>
        { <br>
            Console.WriteLine("The process failed: {0}", e.ToString()); <br>
        } <br>
  
</details>
</details>
