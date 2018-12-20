# Uncomment this line to define a global platform for your project
# platform :ios, '9.0'

source 'https://github.com/CTMediatorDemo/PrivatePods.git'
source 'https://github.com/CocoaPods/Specs.git'

target 'MainProject' do
  # Uncomment this line if you're using Swift or would like to use dynamic frameworks
  # use_frameworks!

  # Private Pods
  pod 'HandyFrame'

  #pod "A_Category", :path => "../A_Category"
  #pod 'A', :path => "../A"

  # Cocoapods/specs 中也有 A/A_Category，因此直接指定了:git
  pod 'A_Category', :git => 'git@github.com:CTMediatorDemo/A_Category.git'
  pod 'A',          :git => 'git@github.com:CTMediatorDemo/A.git'

end
