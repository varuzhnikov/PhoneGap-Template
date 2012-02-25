# Rakefile
include Rake::DSL
require 'bundler'
Bundler.require

Wox::Tasks.create :info_plist => 'HiWorld/HiWorld-Info.plist' do
  build :debug, :configuration => 'Debug'
end
