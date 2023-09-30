## S3 Versioning

## What is versioning?
- Allows you to have multiple versions of an object within S3

## Advantages of Versioning
- **All Versions** - All versions of an object are stored in S3.  This includes all writes and even if the object is deleted.
- **Backup** - Can be used to backup objects
- **Cannot be disabled** - Once enabled, versioning cannot be disabled... only suspended.
- **Lifecycle Rules** - Versioning can be integrated into lifecycle rules
- **MFA Support** - Versioning supports MFA

## To Enable Versioning
- Browse to the bucket you want to enable versioning on
- Click **Properties** tab
- Click **Enable** and the **Save changes** button
![](2021-12-12-14-13-41.png)

## To View Versions
- Browse to your bucket
- Click the file you want to view the versions list
- Click **Version** tab
