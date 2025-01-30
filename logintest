
Create a LoginPageTest class and write the test cases for the below test scenarios,

package Nxtwave;

import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.chrome.ChromeDriver;

public class LoginPageTest {
    public static void main(String[] args) throws InterruptedException {
        WebDriver driver = new ChromeDriver();
        driver.get("https://qamoviesapp.ccbp.tech");
        driver.manage().window().maximize();
        WebElement loginButton = driver.findElement(By.className("login-button"));
        loginButton.click();
        WebElement one=driver.findElement(By.id("usernameInput"));
        one.sendKeys("rahul");
        WebElement two=driver.findElement(By.id("passwordInput"));
        two.sendKeys("wrongpassword");
        driver.findElement(By.className("login-button")).click();
        Thread.sleep(2000);
        one.clear();
        two.clear();

        Thread.sleep(2000);
        driver.findElement(By.id("usernameInput")).sendKeys("rahul");
        driver.findElement(By.id("passwordInput")).sendKeys("rahul@2021");
        driver.findElement(By.className("login-button")).click();
        Thread.sleep(2000);
        driver.quit();
    }
}
