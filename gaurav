# Automation-Project3
this is automation testing
public static void main(String[] args) {
		
		System.setProperty("webdriver.chrome.driver", PathConfig.driverPath);
		//1. Launch browser
		WebDriver driver = new ChromeDriver();
		//2. Enter URL
		driver.get(PathConfig.appUrl);
		
		//3. Enter User ID
		driver.findElement(By.xpath("//input[@name='email']")).sendKeys("balaji@gmail.com");
		
		//4. ENter password
		driver.findElement(By.xpath("//input[@name='pass']")).sendKeys("balaji@123");
		
		//5. click on LOgin button
		driver.findElement(By.xpath("//button[@name='login']")).click();
		
		String txt = driver.findElement(By.xpath("//div[contains(text(),'password')]")).getText();
		
