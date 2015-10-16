# OpenShift Ruby Cartridge
This cartridge is documented in the [Cartridge Guide](http://openshift.github.io/documentation/oo_cartridge_guide.html#ruby).

# Changes from original
File: openshift-origin-cartridge-ruby/versions/2.0/etc/conf.d/openshift.conf.erb
PassengerRuby <%= ENV['OPENSHIFT_DATA_DIR'] %>.rbenv/versions/2.1.6/bin/ruby
PassengerDefaultRuby <%= ENV['OPENSHIFT_DATA_DIR'] %>.rbenv/versions/2.1.6/bin/ruby

# Usage
rhc create-app myapp http://cartreflect-claytondev.rhcloud.com/github/xenonl/openshift-origin-cartridge-ruby
