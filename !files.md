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
<details><summary><b>GetFiles in folder</b></summary>
  
####  NuGet
  > 
  
####  import
  >using System;
  ><br>using System.IO;
  
####  Code
  >try
  ><br>      {
  ><br>            // Only get files that begin with the letter "c".
  ><br>            string[] dirs = Directory.GetFiles(@"c:\", "c*");
  ><br>            Console.WriteLine("The number of files starting with c is {0}.", dirs.Length);
  ><br>            foreach (string dir in dirs)
  ><br>            {
  ><br>                Console.WriteLine(dir);
  ><br>            }
  ><br>        }
  ><br>        catch (Exception e)
  ><br>        {
  ><br>            Console.WriteLine("The process failed: {0}", e.ToString());
  ><br>        }
</details>
</details>
