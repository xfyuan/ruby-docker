# Ruby Docker (Xlym)

## Features

### From official docker

- From docker official ruby latest version
- apt updated packages
- clean apt package cache to reduce image size

### For special rails features

- install bundler gem
- install packages for js runtime: nodejs
- install packages for nokogiri
- install packages for capybara-webkit
- set BUNDLE_PATH to path /rubygems, then we can mount a volume to store gems cache