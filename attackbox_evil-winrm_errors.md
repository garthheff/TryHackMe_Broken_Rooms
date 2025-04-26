
## Attackbox Error  evil-winrm errors

```
root@ip-10-10-166-239:/opt/impacket/examples# evil-winrm -i 10.200.79.201 -u ServerAdmin -H 3279a0c6dfe15dc3fb6e9c26dd9b066c
/usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1398:in `rescue in block in activate_dependencies': Could not find 'ffi' (>= 1.0.1) among 132 total gem(s) (Gem::MissingSpecError)
Checked in 'GEM_PATH=/usr/local/rvm/gems/ruby-3.0.0:/usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/gems/3.0.0' at: /usr/local/rvm/gems/ruby-3.0.0/specifications/gssapi-1.3.1.gemspec, execute `gem env` for more information
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1395:in `block in activate_dependencies'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1384:in `each'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1384:in `activate_dependencies'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1366:in `activate'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1402:in `block in activate_dependencies'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1384:in `each'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1384:in `activate_dependencies'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1366:in `activate'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1402:in `block in activate_dependencies'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1384:in `each'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1384:in `activate_dependencies'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1366:in `activate'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems.rb:302:in `block in activate_bin_path'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems.rb:301:in `synchronize'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems.rb:301:in `activate_bin_path'
	from /usr/local/rvm/gems/ruby-3.0.0/bin/evil-winrm:23:in `<main>'
	from /usr/local/rvm/gems/ruby-3.0.0/bin/ruby_executable_hooks2.7:22:in `eval'
	from /usr/local/rvm/gems/ruby-3.0.0/bin/ruby_executable_hooks2.7:22:in `<main>'
/usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/dependency.rb:307:in `to_specs': Could not find 'ffi' (>= 1.0.1) among 132 total gem(s) (Gem::MissingSpecError)
Checked in 'GEM_PATH=/usr/local/rvm/gems/ruby-3.0.0:/usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/gems/3.0.0' , execute `gem env` for more information
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1396:in `block in activate_dependencies'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1384:in `each'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1384:in `activate_dependencies'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1366:in `activate'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1402:in `block in activate_dependencies'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1384:in `each'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1384:in `activate_dependencies'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1366:in `activate'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1402:in `block in activate_dependencies'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1384:in `each'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1384:in `activate_dependencies'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems/specification.rb:1366:in `activate'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems.rb:302:in `block in activate_bin_path'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems.rb:301:in `synchronize'
	from /usr/local/rvm/rubies/ruby-3.0.0/lib/ruby/3.0.0/rubygems.rb:301:in `activate_bin_path'
	from /usr/local/rvm/gems/ruby-3.0.0/bin/evil-winrm:23:in `<main>'
	from /usr/local/rvm/gems/ruby-3.0.0/bin/ruby_executable_hooks2.7:22:in `eval'
	from /usr/local/rvm/gems/ruby-3.0.0/bin/ruby_executable_hooks2.7:22:in `<main>'

```
## fix

```
root@ip-10-10-166-239:/opt/impacket/examples# gem install ffi
```
