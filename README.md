package tesNg;

import java.util.ArrayList;
import java.util.Arrays;
import java.util.List;

import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;


public class aboutMe {

	public static void main(String[] args) {
		
		System.setProperty("webdriver.chrome.driver", "C:/Users/asket/Desktop/Softwares/chromedriver/chromedriver.exe");
		
		WebDriver driver = new ChromeDriver();
		
		String newLine = System.getProperty("line.separator");
		
		System.out.println("MY Name is Asik Ali Peermuhammed Syed Ziadueen");
		
		System.out.println(newLine);
		 
		System.out.println("I have 10+ expereince in Software Quality Assurance - ETL & Automation");
		
		System.out.println(newLine);
		
		System.out.println("My Blog can be found at -  asiketltestanalyst.wordpress.com");
		
		driver.get("https://asiketltestanalyst.wordpress.com/");
		
		System.out.println(newLine);
		
		System.out.println("My LinkedIn Profile : https://www.linkedin.com/in/asik-ali-1b353923/");
		
		driver.get("https://www.linkedin.com/in/asik-ali-1b353923/");
		
		System.out.println(newLine);
		
		System.out.println("My GitHUb: https://github.com/AsikDataPshyco");
		
		driver.get("https://github.com/AsikDataPshyco");
		
		System.out.println(newLine);
		
		
        System.out.println("Work Experience - HCL Technologies - Software QA Analyst - 2009 to 2014");
        
        System.out.println(newLine);
        
        System.out.println("Work Experience - Wipro Technologies - Software QA Analyst - 2014 to 2019");
        
        System.out.println(newLine);
        
        System.out.println("Work Experience -Exacz Matrix IFS - Software QA Analyst - 2019 to till Date");
		
		System.out.println(newLine);
		
		List<String> myTechStack = new ArrayList<String>() ;
		
		myTechStack.add("Core Java");
		myTechStack.add("Spring Boot / Batch / JPA");
		myTechStack.add("Spring Boot MVC - CRUD");
		myTechStack.add("Oracle SQL");
		myTechStack.add("CICD Pipeline Jenkins GitHub DockerHub Vulcan Splunk Logs");
		myTechStack.add("API Testing - RESTAssured / PostMan Runner Get Post Delete");
		myTechStack.add("Actimize RCM AIS IDM");
		myTechStack.add("Selenium WebDriver / Grid / Docker / BDD / TestNg / Cucumber /Page Object Model / QAF QMetry");
		
		
		System.out.println(Arrays.deepToString(myTechStack.toArray()));
	
		
		

	}

}
