# Spring Dev Team Java Styling

## Installation
<span style="color:blue">**Set Up the Code style XML file**</span>

1. Install the checkstyle plugin
'checkstyle idea'
<br />
(**Intellij**: File →  Settings →  Plugins → Install and restart)

2. Configure it to use our custom checkstyle.xml
<br />
(**Intellij**: File →  Settings →  Tools → CheckStyle → '+' sign → Use a local Checkstyle file → tick the active checkbox) 
<br /> **and**
( File → Settings → Editor → Code Style → :gear: icon → select the new code style)

2. Go back to your editor main page elect, Select the 'Checkstyle' tab at the bottom, set rules to the checkstyle created.

<span style="color:blue">**Setting the Formatter**</span>

1. Install the Google Formatter plugin
'google-java-format'
<br />
(File →  Settings →  Plugins → Install and restart)
1. Set it from the settings
<br />
(File →  Settings →  google-java-format settings → Enable checkbox → set Code Style: Android Open Source Project (AOSP) style)


For Other IDEs install the JAR file and set the --aosp   --skip-sorting-imports params from https://github.com/google/google-java-format