> *The following text is extracted and transformed from the adwaremedic.com privacy policy that was archived on 2015-06-13. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20150613051519id_/http%3A//www.adwaremedic.com/privacy.php) for the most accurate reproduction.*

# AdwareMedic Privacy Policy

The following outlines the measures taken to protect your privacy by this website and by the AdwareMedic application. It is important to understand that our top priority is not just respecting your privacy, but helping you regain it by removing adware that is violating it. 

## This site

This site (and its parent site, The Safe Mac) collects no information about you beyond the data that all web servers collect in the course of normal operations (IP address, pages being loaded, etc). No personally identifying information is collected. There are also no cookies used by this site. 

When purchasing AdwareMedic, you will be directed to PayPal. PayPal is responsible for the personal information it collects. This site will never receive information such as your credit card information after a purchase, but will receive information such as the name, e-mail address and postal address provided to PayPal. This information will not be shared with anyone else, and The Safe Mac will never spam you or use your postal address in any way at all. 

## The AdwareMedic application

AdwareMedic does not collect information about you or transmit information anywhere automatically. When it is launched, it will contact www.adwaremedic.com twice: once to check for and download updates to the adware signatures, and once to check for updates to the app itself. When AdwareMedic scans for adware, the information on the adware detected is logged to your hard drive, but is not sent anywhere. 

AdwareMedic has a "System Snapshot" feature that gathers information about your system and creates a report from that information. This snapshot is only created when you request it by choosing Take System Snapshot from the Scanner menu. The snapshot is always displayed to you when it is complete, and is not sent anywhere unless you click the "Submit to The Safe Mac" button in the System Snapshot window. If you choose to click that button, an e-mail message with the snapshot data will be created in Mail; you will then need to click the Send button in Mail before the data is sent. 

AdwareMedic may ask you for an administrative username and password at two different times. One is when you tell it to remove adware that was detected. In this case, only an AppleScript tasked with the process of moving files to the trash is given admin privileges. This AppleScript can be reviewed by control-clicking the AdwareMedic application and choosing Show Package Contents. Inside the folder that is opened, go to the Contents folder, then the Resources folder. Inside that folder is a RemoveFiles.scpt file. That file can be opened with Apple's Script Editor to review exactly what that script is doing with those admin privileges. 

The other time AdwareMedic will request this username and password is when creating a system snapshot. Admin privileges are needed to get information about root cron tasks (tasks that are set to perform on a timed basis for all users of the computer). This task is done by another AppleScript, named GetRootCronTasks.scpt, whose code can also be reviewed just as for the file removal script. 

At no time does AdwareMedic actually see your password. The authentication request comes directly from Mac OS X, and never shares that password with the requesting app. AdwareMedic also does not ever gain admin privileges... only the two aforementioned AppleScripts gain those privileges. 
