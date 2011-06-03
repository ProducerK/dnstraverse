require 'rake/gempackagetask'
spec = Gem::Specification.new do |s|
  s.name = 'dnstraverse'
  s.summary = 'Complete DNS traversal checker'
  s.description = File.read(File.join(File.dirname(__FILE__), 'README'))
  s.requirements = []
  s.version = '0.0.3'
  s.author = 'James Ponder'
  s.email = 'james@squish.net'
  s.homepage = 'http://www.squish.net/dnstraverse/'
  s.platform = Gem::Platform::RUBY
  s.required_ruby_version = '>=1.8'
  s.files = Dir['**/**']
  s.executables = [ 'dnstraverse' ]
  s.test_files = Dir["test/test*.rb"]
  s.has_rdoc = true
  s.add_dependency('dnsruby', '>= 1.30')
end
Rake::GemPackageTask.new(spec).define