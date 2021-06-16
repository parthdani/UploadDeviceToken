# UploadDeviceToken
This project is to upload the Device token to CleverTap.

**Step 1**: Create the CSV file. For Format, refer to the sample Profile.CSV file

Explanation:
1) Name, E-Mail and User Id - User Information
2) Device Id - If you do not have the device Id, Use the same value of the User Id
3) Device OS - Android/iOS
4) Token - FCM token for Android and APNs token for iOS

**Step 2**: Download this project

**Step 3**: Run the Script

```
python3 ct-token-uploads.py
```

**Step 4:** Enter your file location, Account Region, CleverTap Account Id and CleverTap Passcode.

**Account Region**: 
If your account is hosted on our **US server** (if the CleverTap dashboard URL is us1.dashboard.clevertap.com) then add **us1**. 
Similarly, 
**EU** server = **eu1**, 
**SG** server = **sg1**,
**In** server = **in1**

CleverTap **Account Id** and **Passcode** can be fetched from CleverTap Dashboard > Settings

Example: ![input](https://github.com/parthdani/UploadDeviceToken/blob/main/Screenshot%202021-06-17%20at%203.37.13%20AM.png)
