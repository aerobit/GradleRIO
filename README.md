# GradleRIO
GradleRIO is a powerful Gradle Plugin that allows teams competing in the FIRST
robotics competition to produce and build their code without being limited to
the Eclipse IDE.

GradleRIO extracts the WPILib sources from the eclipse plugin and allows you to
use it with eclipse or IntelliJ IDEA. GradleRIO also allows you to build and
deploy your code to the RoboRIO without using eclipse.  


* WPILib is downloaded and extracted using 'gradlew wpi'
* A workspace is setup using 'gradlew idea' or 'gradlew eclipse'
* Code is deployed using 'gradlew deploy' or 'gradlew deployIP' (deployIP for custom IP addresses)
* Robot Code or the RoboRIO can be restarted using 'gradlew robot' or 'gradlew reboot'
* Robot Code can be removed from the RoboRIO using 'gradlew cleanRIO'

*If you're using the ToastAPI, we'll also generate the Run Configurations for you!*

## Download
To get GradleRIO, simply head to the [releases page](http://github.com/Open-RIO/GradleRIO/releases) and download the .zip file containing the archive. Extract it to your working directory and get coding!
