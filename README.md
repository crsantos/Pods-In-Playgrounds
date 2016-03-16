# Pods In Playgrounds
Demo integration of CocoaPods into a Playground

## Environment
* OS X El Capitan 10.11.4
* Xcode 7.2.1 (7C1002)
* CocoaPods 1.0.0.beta.6

## Steps to reproduce
* Create a new Xcode project
* Close Xcode
* Navigate to project directory
* pod init
* Update Podfile with Alamofire (see example)
* pod install
* Open .xcworkspace
* Add a new playground to the workspace
* Manage schemes -> Check 'Alamofire'
* Build the Alamofire scheme
* Xcode triggers a warning about updating the bundle settings for Alamofire; accept changes
* You should now be able to 'import Alamofire' in the playground

