# Rakefile
include Rake::DSL
require 'bundler'
Bundler.require

Wox::Tasks.create :info_plist => 'HiWorld/HiWorld-Info.plist', :sdk => 'iphonesimulator5.0' do
  build :debug, :configuration => 'Debug'
end
