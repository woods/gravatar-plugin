require 'spec/rake/spectask'

desc 'Default: run all specs'
task :default => :spec

desc 'Run all application-specific specs'
Spec::Rake::SpecTask.new(:spec) do |t|
  t.spec_files = FileList['spec/**/*_spec.rb']
end
