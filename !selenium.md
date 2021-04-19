## <a href="https://github.com/Hidekithiago/Automacao/blob/master/README.md">Selenium</a> <br>
<details>
<details><summary><b>Escrever algo</b></summary>
  
####  NuGet
  >Selenium.Support
  ><br>Selenium.WebDriver
  ><br>Selenium.WebDriver.ChromeDriver
####  import
  >using OpenQA.Selenium;
  ><br>using OpenQA.Selenium.Chrome;
  ><br>using OpenQA.Selenium.Support.UI;
     
####  Code
  > driver.FindElement(By.XPath("/html/body/div[2]/div/form/fieldset/p/input")).Clear();
  ><br> driver.FindElement(By.XPath("/html/body/div[2]/div/form/fieldset/p/input")).SendKeys(crmMedico);
  
</details>
<details><summary><b>Clicar no botao</b></summary>
  
####  NuGet
  >Selenium.Support
  ><br>Selenium.WebDriver
  ><br>Selenium.WebDriver.ChromeDriver
####  import
  >using OpenQA.Selenium;
  ><br>using OpenQA.Selenium.Chrome;
  ><br>using OpenQA.Selenium.Support.UI;
     
####  Code
  > driver.FindElement(By.XPath("/html/body/age_nao_gravar/div[2]/div/form/age_substituir_cabec_log/table/tbody/tr[5]/td/table[2]/tbody/tr[1]/td[2]/a[1]/img")).Click();
  
</details>
<details><summary><b>Capturar o texto</b></summary>
  
####  NuGet
  >Selenium.Support
  ><br>Selenium.WebDriver
  ><br>Selenium.WebDriver.ChromeDriver
####  import
  >using OpenQA.Selenium;
  ><br>using OpenQA.Selenium.Chrome;
  ><br>using OpenQA.Selenium.Support.UI;
     
####  Code
  > string variavel = driver.FindElement(By.XPath("")).Text;  
</details>
<details><summary><b>Seleciona uma opcao Droplist</b></summary>
  
####  NuGet
  >Selenium.Support
  ><br>Selenium.WebDriver
  ><br>Selenium.WebDriver.ChromeDriver
####  import
  >using OpenQA.Selenium;
  ><br>using OpenQA.Selenium.Chrome;
  ><br>using OpenQA.Selenium.Support.UI;
     
####  Code
  > var selectElement = new SelectElement(driver.FindElement(By.XPath("/html/body/div[2]/div/form[1]/table[1]/tbody/tr[1]/td/table/tbody/tr[4]/td[2]/span[1]/select")));
  ><br> selectElement.SelectByText("Atestado Médico");
</details>
</details>
