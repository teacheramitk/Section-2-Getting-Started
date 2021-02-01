# Section-2-Getting-Started

Setting up your AWS Free Tier Account - Lab
------------
**Step 1. Open up your browser and type- setting up your AWS free Tier account**

**Step 2. Click on the first result**

**Step 3. Then Click on Create a Free Account**

**Step 4. Provide the following details-**
- Email address
- Password
- Confirm password
- AWS account name

Click on Continue

**Step 5. Give details for Contact Information**
- Account type - select Personal
- Full name
- Company name
- Phone number
- Country/Region
- Address
- City
- State
- Postal code

Click on Create account and continue

**Step 6. Payment Information details-**
- Credit/Debit card number
- Expiration date
- Cardholder's name
- Billing address

**Step 7. Authenticate Transaction with OTP**

**Step 8. Confirm your identity with the following-**
- Text message/Voice call
- Country/Region code
- Cell Phone Number
- Security check

Click on Send SMS

**Step 9. Enter verification code**
Click on Verify Code 

**Step 10. Your identity has been verified successfully**
Click on Continue

**Step 11. Select a Support Plan**
- Select Free

**Step 12. Fill the details before it will ask you to sign in to AWS Console**
- My Role is:Academic/Researcher
- I am interested in:Devops

Click on Submit
See Thank You message

**Step 13. Click on Sign in to the Console**
- Link - https://signin.aws.amazon.com

**Step 14. Sign in page-**
- Provide Root user email address.

Click on Next

**Step 15. Type the password**
Click on Sign In

Our Free Tier AWS Acoount is Ready.


### End of Lab


# IAM User Set-up - Lab

**Step 1. Login to AWS Console>Click on Your AWS Account>My Billing Dashboard>Billing preferences**

**Step 2. Under Billing Preferences-**
- Select Receive Free Usage Alerts
- Mention Email address
- Select Receive Billing Alerts

Click on Save preferences.

**Step 3. Goto AWS Console>All Services>CloudWatch>Billing**
- Please Switch Region to # US East(N.Virginia) as CloudWatch displays all billing data
and alarms in # US East(N.Virginia)

**Step 4. Billing>Create Alarm>Conditions**
- Threshold type - Static
- Whenever EstimatedCharges is.. - Greater
- than... - 5 USD

Click on Next

**Step 5. Configure actions>Notification**
- Alarm state trigger - In alarm
- Select an SNS topic>Create new topic
    - topic name - Default_CloudWatch_Alarms_Topic
	- Provide Email address to receive the notification.
- Click on Create Topic
	
Now Click on Next
	
**Step 6. Add name and description**
- Alarm name - MyBillingAlarm
- Description

Click on Next

**Step 7. Preview all the details and Click on Create Alarm**
- Successfully created MyBillingAlarm

**Step 8. Goto your Email inbox and look for the email from AWS**
- Open Email and click on Confirm Subscription
- See the message Subscription confirmed

**Step 9. AWS Console>All services>IAM>IAM Dashboard>Users>Add user**
- Set User details-Provide User name
- Select AWS access type 
  - Access Type
     - Programmatic access
     - AWS Management Console access
	 
 - Console password
  
 Click on Next:Permissions
 
 **Step 10. Click on Attach existing policies directly**
 - Select AdministratorAccess
 
 Click on Next:Tags
 
 **Step 11. Click on Next:Review**
 
 **Step 12. Review your choices and Click on Create user**
 
 **Step 13. Click on Download.csv**
 

### End of Lab

# AWS CLI set-up - Lab
 
 **Step 1. Signin into AWS Console with Account ID and IAM user name.**

**Step 2. Type the following to change the password at first login-**
- Old password
- New password
- Confirm new password

Click on Confirm password change

**Step 3. Open Amazon Document with following link.**
- https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2-mac.html

**Step 4. Open your Terminal in MACOS and type the following commands with help of above link.**
```sh
$ curl "https://awscli.amazonaws.com/AWSCLIV2.pkg" -o "AWSCLIV2.pkg"
$ sudo installer -pkg AWSCLIV2.pkg -target /
$ aws --version
```
**Step 5. Follow the link and type the command**
- https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html
```sh
$ aws configure
```
- Provide AWS Access key ID
- Provide Secret Access key
- Default region name
- Default output format

**Step 6.Test the following command to list all the Buckets**
```
$aws s3 ls
```
**Step 7. Type the following commands to see secret access key id and access key**
```sh
$ cd ~/.aws
$ ls
$ cat credentials
$ cat configure
```

### End of lab

# Download & install Git - Lab (MACOS)
------------------------------------------------------------

**Open Terminal in MACOS**
- Run the following commands to install Git

``` sh
$ git --version
$ brew update && brew upgarde
$ brew install git
$ brew link --force git
$ git --version
```
### End of Lab


# Download & install Git - Lab (Windows)

**Step 1. Open internet Browser and Search for Download git for windows. 
Click on "Downloads git" link**

**Step 2. Click on Download 2.28.0 for windows**

**Step 3  Click on the downloaded file GIT-2.28.0-64-bit.exe**

**Step 4. Click on Run**

**Step 5. Click Next**

**Step 6. Select Destination Location and Click on Next**

**Step 7. Select Components and  Click on Next**

**Step 8. To continue,click Next.If you would like to select a different folder,click Browse.**

**Step 9. Select Use Git from the Windows Command Prompt**
- Click on Next

**Step 10. Select Use the OpenSSL library and Click on Next**

**Step 11. Select Checkout Windows-style,commit unix style and Click on Next**

**Step 12. Select Use MinTTY and Click Next**

**Step 13. Select Enable file system caching and Enable Git credentials Manager and Click Next**

**Step 14. Click Install**

**Step 15. Installation has been started**

**Step 16. Select Launch Git bash**
- Click on Finish

**Step 17. Open Local PC and Goto Start>Git Bash**

```
Type #“git init” to initialize the git
Type  #“mkdir” to make a new directory(folder)
Type # “cd test” to move into test directory

```

### End of lab

# Download & install Node JS - Lab (MACOS)

**Step 1. Open google in Internet Browser and type "install node js on mac"**
 
 **Step 2. Click on Very first link "Download | Node.js"**
 - nodejs.org/en/download
 
 **Step 3. Downloads>LTS version>macos installer**
 - Download has been started
 
 **Step 4. Open downloaded file to Install Node.js**
 
 **Step 5. Click on Continue>continue>Agree>Install**

 **Step 6. Give User name and Password**

**Step 7. Click on Install Software**

**Step 8. Click on Install**

**Step 9. Click on Close**
 
**Step 10. Open Terminal in MACOS**

Run the following command
```sh
$ node -v
```

### End of lab

# Download & Install Node.js - Lab (Windows)

**Step 1. Open google in Internet Browser and type "install Node.js on windows"**
 
 **Step 2. Click on Very first link "Download | Node.js"**
 - nodejs.org/en/download
 
 **Step 3. Downloads>LTS version>windows installer**
 - Download has been started 
 
 **Step 4. Open and run this downloaded file to Install Node.js**
 
 **Step 5. Welcome to Node.js Setup Wizard**
 - Click on Next

 **Step 6. Accept terms in the license agreement**
 - Click on Next

**Step 7.Choose custom location of Destination Folder**
- By default it is C:\program Files\nodejs\
- Click on Next

**Step 8. Click on Next**

**Step 9.Tools for Native Modules**
- Select the checkbox Automatically install the necessary tools
- Click on Next
 
**Step 10.Ready to install Node.js**
- Click on Install

**Step 11.Ready to install Node.js**
- Completed the Node.js Setup Wizard
- Click on Finish

**Step 12.Install Additional Tools for Node.js Command prompt widow will open automatically**
- Press any key

**Step 13. Windows power shell is installing chocolatey package manager for windows**

**Step 14. Everything is installed press Enter to exit**

**Step 15. Open command prompt**

Run the following command to see the version

```sh
$ node -v
```

### End of lab





# Download & install Visual Studio Code - Lab (MACOS)

**Step 1. Open Internet Browser and type "install visual studio code" in google search**

**Step 2. Click on the very first link**

**Step 3. Select your Operating system link**
- As soon as you click on link it will start downloading vscode zip file

**Step 4. Goto Downloads>VSCode-drawin-stable.zip>RightClick>open with>Archive Utility**

**Step 5. File is Unzipped**

**Step 6. Now Move content to Application folder**

**Step 7. Goto Applications and click on VisualStudioCode icon to access it**

### End of lab

# Download & install Visual Studio Code - Lab (Windows)

**Step 1. Open Internet Browser and type "install visual studio code" in google search**

**Step 2. Click on the very first link**
- www.code.visualstudio.com

**Step 3. Click on Download for Windows stable Build**
- As soon as you click on link it will start downloading vscodeusersetup.exe file

**Step 4. Click on downloaded file**

**Step 5.Accept the License Agreement**
- Click on Next

**Step 6. Select start menu Folder**
- Click on Next

**Step 7. Do nothing in select additional tasks**
- Click on Install


**Step 8.Visual studio Code Setup Wizard has been completed**
- keep selected Launch Visual studio Code
- Click on Finish

**Step 9.See the interface of Visual studio Code**
- Installation has been completed

### End of lab











