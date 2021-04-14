## <a href="https://github.com/Hidekithiago/Automacao/blob/master/README.md">Image</a> <br>
<details>
<details><summary><b>Comparar imagem</b></summary>
  
####  NuGet
  > System.Drawing.Common
  
####  import
  > using System.Drawing;
  ><br>using System.Drawing.Imaging;
  
####  Code  
  > private static void comparatorImage(String urlImg1, String urlImg2)
  ><br>      {
  ><br>            string img1_ref, img2_ref;
  ><br>            Bitmap img1 = new Bitmap(urlImg1);
  ><br>            Bitmap img2 = new Bitmap(urlImg2);
  ><br>            var flag=true;
  ><br>
  ><br>
  ><br>            if (img1.Width == img2.Width && img1.Height == img2.Height)
  ><br>            {
  ><br>                for (int i = 0; i < img1.Width; i++)
  ><br>                {
  ><br>                    for (int j = 0; j < img1.Height; j++)
  ><br>                    {
  ><br>                        img1_ref = img1.GetPixel(i, j).ToString();
  ><br>                        img2_ref = img2.GetPixel(i, j).ToString();
  ><br>                        if (img1_ref != img2_ref)
  ><br>                        {                            
  ><br>                            flag = false;
  ><br>                            break;
  ><br>                        }
  ><br>                    }
  ><br>                }
  ><br>                Console.WriteLine(flag);
  ><br>            }
  ><br>            else
  ><br>            {                
  ><br>            }
  ><br>        }
  
</details>
</details>
