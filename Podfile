# Uncomment this line to define a global platform for your project
# platform :ios, '10.0'
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '10.0'
use_frameworks!

target “IOSTaskPuneet” do
    pod 'Alamofire'
    pod 'AlamofireImage'
   
end

post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['SWIFT_VERSION'] = '3.0'
        end
    end
end
