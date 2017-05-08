# Pods In Playgrounds ⚙️
Demo integration of CocoaPods into a Playground

## Environment 📦
* macOS Sierra 10.12.4
* Xcode 8.3.2 (8E2002)
* CocoaPods 1.2.1

## Steps to reproduce 👣
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

