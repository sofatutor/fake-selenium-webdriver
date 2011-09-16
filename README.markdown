Why?
====

If you're using Capybara with Akephalos and don't need selenium-webdriver, you may want to
prevent it from loading crazy dependencies (childprocess, ffi, json_pure, and rubyzip).

To install, put this in your Gemfile:

    gem "selenium-webdriver", "= 0.0.3", :git => "git://github.com/sofatutor/fake-selenium-webdriver"
