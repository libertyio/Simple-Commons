# Liberty Infrasystems Fork of Simple Commons by Simple Mobile Tools

This repository is an open source fork of [Simple Commons](https://github.com/SimpleMobileTools/Simple-Commons), which was available with a [GPLv3 license](https://www.gnu.org/licenses/gpl-3.0.html) at the time of the
fork.

This fork features the following changes in the `liberty_main` branch:

* created a new "liberty" flavor for release
* added Maven publishing task for local development
* disabled "fake version" popup
* disabled "donate or upgrade" popup
* disabled "rate this app" popup
* changed default color scheme to purple
* fixed circular reference in style.xml
* disabled use of windowLightStatusBar from API level 23 (because this library targets API level 21 and above)
* added linkTextColor, link_text_color, and LINK_TEXT_COLOR functions and constants
* fixed references to accent color which were using primary color instead
* customized some strings for the "liberty" flavor

For more information, please visit [Liberty Messenger for Android](https://github.com/libertyio/liberty-messenger-android)
