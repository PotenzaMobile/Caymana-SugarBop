# Uncomment the next line to define a global platform for your project
platform :ios, '10.3'

pod 'OneSignal', '>= 2.6.2', '< 3.0'
pod 'Google-Mobile-Ads-SDK'
pod 'Promises'


post_install do |installer|
   installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings["EXCLUDED_ARCHS[sdk=iphonesimulator*]"] = "arm64 i386"
   end
   end
 end

target 'Convertify' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!
  
  # Pods for Convertify
  #  pod 'OneSignal', '>= 2.6.2', '< 3.0'
  #  pod 'Google-Mobile-Ads-SDK'
  
end

target 'PushNotification' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!
  
  # Pods for PushNotification
  #  pod 'OneSignal', '>= 2.6.2', '< 3.0'
  
end
