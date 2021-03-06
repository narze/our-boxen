# This file manages Puppet module dependencies.
#
# It works a lot like Bundler. We provide some core modules by
# default. This ensures at least the ability to construct a basic
# environment.

def github(name, version, options = nil)
  options ||= {}
  options[:repo] ||= "boxen/puppet-#{name}"
  mod name, version, :github_tarball => options[:repo]
end

# Includes many of our custom types and providers, as well as global
# config. Required.

github "boxen",      "3.0.2"

# Core modules for a basic development environment. You can replace
# some/most of these if you want, but it's not recommended.

github "autoconf",   "1.0.0"
github "dnsmasq",    "1.0.0"
github "gcc",        "2.0.1"
github "git",        "1.2.5"
github "homebrew",   "1.4.1"
github "hub",        "1.0.3"
github "inifile",    "1.0.0", :repo => "puppetlabs/puppetlabs-inifile"
github "nginx",      "1.4.2"
github "nodejs",     "3.2.9"
github "openssl",    "1.0.0"
github "repository", "2.2.0"
github "ruby",       "6.3.4"
github "stdlib",     "4.1.0", :repo => "puppetlabs/puppetlabs-stdlib"
github "sudo",       "1.0.0"
github "xquartz",    "1.1.0"

# Optional/custom modules. There are tons available at
# https://github.com/boxen.

github "alfred",         "1.1.4"
github "bartender",     "0.0.1", :repo => "jpsirois/puppet-bartender"
github "better_touch_tools", "1.0.0"
github "caffeine",       "1.0.0"
github "chrome",         "1.1.1"
github "cyberduck",      "1.0.1"
github "dropbox",        "1.1.1"
github "evernote",       "2.0.4"
github "flux",           "1.0.0"
github "gitx",           "1.2.0"
github "hipchat",        "1.0.8"
github "iterm2",         "1.0.3"
github "keyremap4macbook", "1.0.4"
github "macvim",         "1.0.0"
github "mongodb",        "1.0.4"
github "mplayerx",       "1.0.0"
github "noip_duc",       "1.0.1"
github "ohmyzsh",        "1.0.0", :repo => "samjsharpe/puppet-ohmyzsh"
github "onepassword",    "1.0.2"
github "pckeyboardhack", "1.0.5", :repo => "smh/puppet-pckeyboardhack"
github "pgadmin3",       "1.0.0"
github "postgresapp",    "1.0.0"
github "python",         "1.2.1"
github "quicksilver",    "0.0.1", :repo => "jplana/puppet-quicksilver"
github "skype",          "1.0.4"
github "slate",		 "1.0.0"
github "sublime_text",   "1.2.1", :repo => "slantview/puppet-sublime_text"
github "tmux",           "1.0.2"
github "unarchiver",     "1.2.0", :repo => "fredoliveira/puppet-unarchiver"
github "vagrant",        "2.0.10"
github "xtrafinder",     "1.0.1"

# to-do
# github "hazel", "0.0.3", :repo => "narze/puppet-hazel"
# github "scrollreverser", "1.0.0", :repo => "narze/puppet-scrollreverser"
# github "symboliclinker", "1.0.0", :repo => "narze/puppet-symboliclinker"
# github "utorrent",       "1.0.0", :repo => "joeyvandijk/puppet-utorrent"


