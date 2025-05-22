# Setup

#### Step 1: Download the Project

#### Step 2: Open in Unity

#### Step 3: Customize the UI to your requirements, though these can be edited remotely too!

#### Step 4: The Remote Config and Authentication packages should already be installed but if they aren't go ahead and install them

#### Step 5: Go to the [Unity Cloud Dashboard](https://cloud.unity.com/) and click on the Dashboard tab. Sign in/up if necessary
![image](./Assets/b3da9d70-ed3e-4b74-95df-0608700ee0d6.png)


### Step 6: Create a new Project if you don't have one
![image](./Assets/3dee8321-d8fe-4cc9-ba01-bfeed48460b1.png)


### Step 7: Enter the Project View
![image](./Assets/a7d5f70d-4dd7-4ba9-a076-558eb28cbd72.png)


### Step 8: Launch Remote Config under Services
![image](./Assets/3fb6db82-fc6c-442d-94e3-412ff97d2dd2.png)


### Step 9: You fill find some pop-ups and on-boarding steps. Click on Check Environements
![image](./Assets/8918e0d3-d898-4e14-b9de-3def95f34c45.png)


### Step 10: Create new environments or just choose Confirm to continue with the Production environment
![image](./Assets/6c79fc0f-8a14-4eb3-8e5f-0aa206b9e705.png)


### Step 11: Click on the Drop Down with the chosen environment
![image](./Assets/853579ce-ed34-4557-a01c-f731f3bcf6bb.png)


### Step 12: Click on Manage Environments and Scroll down till you find the Environment ID
![image](./Assets/f4b0c6e9-e5e3-42ec-b0e5-47df4c76323d.png)


### Step 13: Copy this ID

### Step 14: Go back to the Config tab on the Remote Config Service
![image](./Assets/8d79264c-97cf-4711-96c0-4fe7cc0a697b.png)


### Step 15: Now visit the Unity editor and Click on the Launcher GameObject to edit it in the inspector and Check Out the Remote Config Variables
![image](./Assets/bd5eab3d-6516-4273-8149-f30686392d5e.png)


### Step 16: Enter the previously copied ID in the Environement ID slot and configure the variable names for remote config as you wish

### Step 17: Create all the variables in the actual Remote Config dashboard as "Keys" with their correct values (What [values](./Files.md)?)
![image](./Assets/53974721-e3d4-4aee-83b7-a283868e195e.png)

![image](./Assets/e3b60433-3518-4eae-beef-1ff9d362e3bf.png)

![image](./Assets/4f9d5a75-5036-4e7a-9221-6c68d64d7f40.png)


### Step 18: Publish
![image](./Assets/86323296-c21b-4b23-9afb-ac8f932e4aad.png)


### Step 19: Go to the main project view which we visit at Step 7 
### Step 20: Go back to the Unity Editor and Click on the Services option in the title ribbon
![image](./Assets/135ac169-8654-4d95-9466-ff77aa94e8eb.png)


### Step 21: Go to General Settings and choose your Organisation and Project and click on "Link Unity project to cloud project"
![image](./Assets/5ddcd522-5942-4a6b-a0ae-0fe613e233a7.png)

![image](./Assets/c8ebf879-b5d3-4c36-ba6f-4d546aa5f876.png)

# Hosting
You can host the files on and http hosting service like dropbox, google drive or even onedrive. You would need to convert the links to direct download links using some kind of online converters. 
For example this is a direct download link for a dropbox file `https://www.dropbox.com/s/SOME_ID/Application_Zip?dl=1`

Google Drive shows a pop-up if the file is more than 50mb which breaks the download http request. You can either use [Google APIs](https://bytesbin.com/skip-google-drive-virus-scan-warning-large-files/) to get rid of the whole problem altogether... Or you could even do a [workaround via code](https://stackoverflow.com/a/44402826)

So the Remote Config variables would point to these variables... Here is an example (acknowledgement is basically subtitle.. I renamed it for my project)

### Also the \_name variables should be equal the name for the Zip files
![image](./Assets/59fab93f-c0f6-4470-bb5b-0a8e11462694.png)

### Step 22: ANDDDD you are done! Export the project to all required platforms and it 'should' work perfectly fine
