PROJECT OVERVIEW

The function of this library is to detect the user's device operating system. A common use case for this library to reveal device-specific content or to link to the OS-specific App store .

PROJECT REQUIREMENTS:

The lib will rely on the user agent (UA) string
The lib should not depend on jquery
The lib should append the OS value to the class attribute of the HTML node to serve as a 'hook' for application-specific functionality
The lib should use the 'Revealing Module Pattern' for structuring the code
The script should be testable outside of a web browser (TDD)

Current OS Considerations

AndroidPhone
AndroidTablet
BlackBerry
iPhone
iPad
Kindle
Opera
WindowsPhone
WindowsTablet

For example, if the user is on an android phone, the expected outcome would be:

<html class="AndroidPhone">