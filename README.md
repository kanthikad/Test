# WalletHub-Assignment
Submission of Wallethub initial Screening Test 

<b>Manual part: Check Documents Folder</b> 

<b>Automation part:</b>

Completed with selenium + testng, Tested on Chrome only as maven project

How to run it (<b>Tested on Windows only</b>)

Install: java jdk 1.8, chrome latest version 
git clone 
Build module WalletHub-app with Maven 
Resolve TODO (insert credentials for login/pass in tests class) 

public class Facebooklogin {
 
	public static WebDriver driver;
	static String baseurl="http://www.facebook.com";
	//change username and password here for login
	String username="";
	String password="";
  
  public class WalletHubReview {
	
	public static WebDriver driver;
	static String baseurl="https://wallethub.com/join/light";
	static String review_sub_url="http://wallethub.com/profile/test_insurance_company/";
	static String review_verification_url="https://wallethub.com/profile/rohitnegi548/reviews/";
	
	//change username and password here for login
	String username="";
	String password="";
  
Run Facebook/Wallethub tests with TestNG OR use testng.xml

<b>Automation test results:</b> Check Video Folder: <b>WalletHub-Assignment/Video/Test Results.mp4</b>
