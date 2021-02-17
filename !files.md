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
  >private static void getFilesinFolder(String urlPasta, String tipo)
  ><br>      {
  ><br>            try
  ><br>            {                
  ><br>                string[] dirs = Directory.GetFiles(urlPasta, tipo);
  ><br>                Console.WriteLine("The number of files starting with c is {0}.", dirs.Length);
  ><br>                foreach (string dir in dirs)
  ><br>                {
  ><br>                    Console.WriteLine(dir);
  ><br>                }
  ><br>            }
  ><br>            catch (Exception e)
  ><br>            {
  ><br>                Console.WriteLine("The process failed: {0}", e.ToString());
  ><br>            }
  ><br>        }
</details>
<details><summary><b>Change folder a file</b></summary>
  
####  NuGet
  > 
  
####  import
  >using System;
  ><br>using System.IO;
  
####  Code
  >private static void ChangeFolder()
  ><br>      {
  ><br>            string sourceFile = @"C:\Users\Public\public\test.txt";
  ><br>            string destinationFile = @"C:\Users\Public\private\test.txt";
  ><br>
  ><br>            // To move a file or folder to a new location:
  ><br>            System.IO.File.Move(sourceFile, destinationFile);
  ><br>
  ><br>            // To move an entire directory. To programmatically modify or combine
  ><br>            // path strings, use the System.IO.Path class.
  ><br>            System.IO.Directory.Move(@"C:\Users\Public\public\test\", @"C:\Users\Public\private");
  ><br>        }
</details>
</details>
