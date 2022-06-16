package ui;

import org.openqa.selenium.chrome.ChromeDriver;
import org.openqa.selenium.firefox.FirefoxDriver;
import org.testng.Assert;
import org.testng.annotations.Test;

import io.github.bonigarcia.wdm.WebDriverManager;

public class verifytitaltest {

	@Test
	public void TitleTest() {
		
		String Title = "Electronics, Cars, Fashion, Collectibles & More | eBay";
		WebDriverManager.chromedriver().setup();
		ChromeDriver driver = new ChromeDriver();
		driver.get("http://www.ebay.com");
		//WebDriverManager.firefoxdriver().setup();
		//FirefoxDriver driver = new FirefoxDriver()
		String acctualtitle = driver.getTitle();
		Assert.assertEquals(acctualtitle, Title);
	}

}
