source 'git@github.com:layerhq/cocoapods-specs.git'
source 'https://github.com/CocoaPods/Specs.git'

dropbox_path = ENV['LAYER_DROPBOX_PATH'] || '~/Dropbox (Layer)'

target 'Atlas Messenger' do
  pod 'SVProgressHUD', :head
  pod 'LayerKit', git: 'git@github.com:layerhq/LayerKit.git'
  #pod 'LayerKit', path: "#{dropbox_path}/Layer/Builds/iOS/LayerKit-0.10.0-rc1"
  pod 'LayerIdentity', git: 'git@github.com:layerhq/layer-identity-ios'
  pod 'Atlas', path: 'Libraries/Atlas'
end

target 'Atlas MessengerTests' do
  pod 'KIF', '~> 3.0.8'
  pod 'OCMock', '~> 3.1'
  pod 'KIFViewControllerActions', git: 'https://github.com/blakewatters/KIFViewControllerActions.git'
  pod 'Expecta', '~> 0.3.0'
  pod 'LYRCountDownLatch', git: 'https://github.com/layerhq/LYRCountDownLatch.git'
end
