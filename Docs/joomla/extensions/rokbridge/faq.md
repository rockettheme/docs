---
title: RokBridge - FAQ
description: Your Guide to Using RokBridge for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/!RokBridge:RokBridge

---

### Is the bridge free?
Yes, the bridge is 100% GPL and Free. That means that you are free to use it and contribute back if you find any bugs and/or add features.

### Can the bridge sync my updated password from phpBB to Joomla?
When you create a user via phpBB, the user's password is stored in phpBB. If you create the user in Joomla!, the password is stored in Joomla!. If you created a user in phpBB and try to change it in Joomla!, it will update the password on phpBB for you, however phpBB does not have a 'change password event', so if you create the user in Joomla! and change the password in phpBB, it does not know to update your Joomla! password. Things can get a bit screwy. We suggest you only allow users to change passwords in Joomla!. To ensure this, you should disable the ability in phpBB via the user profile by going to the ACP -> System -> Module Management -> User Control Panel -> Profile, and then disabling Account Settings

### Can I integrate with Joomla! visually?
Currently no this is not possible. You will need to create a matching theme for phpBB and Joomla!. We are however exploring a technique to add this feature to future versions of the bridge.

### My PM and Topic notifications point to "distribution" folder and not the "forum" folder. How can I fix this?
Login to phpBB as an administrator go to ACP -> General -> Server Settings -> Server URL Settings. Change the Script Path to your forum location and then change Force Server URL Settings to yes.