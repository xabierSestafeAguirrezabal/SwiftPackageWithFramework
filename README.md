# SwiftPackageWithFramework

A description of this package.
To be able to use This SwiftPackage you will need to add to the target of your app in Singing and Capabilities add access Wifi Information.
Then in the Target of the app in info tab you have to add the key values of location permission.
Privacy - Location Always and When In Use Usage Description, and insert the description as string
Privacy - Location When In Use Usage Description, and insert the description as string
Privacy - Location Always Usage Description, and insert the description as string
Request Permission in your app 
 import CoreLocation
 let locationManager = CLLocationManager()
           locationManager.requestWhenInUseAuthorization()