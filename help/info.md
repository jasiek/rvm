
∴ rvm info [ruby_string[,ruby_string[,...] [section,[section[,...]

where sections are one of:

  system rvm ruby homes binaries environment debug

Both ruby strings and sections are optional arguments.

By default, with no parameters, rvm info will output all sections except debug.

To display system rvm debug information:

  ∴ rvm debug

which will display all sections including debug for the current or specified interpreters.

Example:

  ∴ rvm info 1.9.2-head,1.8.7 homes,binaries,environment

  ruby-1.9.2-head:

    homes:
      gem:          "/Users/wayne/.rvm/gems/ruby-1.9.2-head"
      ruby:         "/Users/wayne/.rvm/rubies/ruby-1.9.2-head"

    binaries:
      ruby:         "/Users/wayne/.rvm/rubies/ruby-1.9.2-head/bin/ruby"
      irb:          "/Users/wayne/.rvm/rubies/ruby-1.9.2-head/bin/irb"
      gem:          "/Users/wayne/.rvm/rubies/ruby-1.9.2-head/bin/gem"
      rake:         "/Users/wayne/.rvm/gems/ruby-1.9.2-head/bin/rake"

    environment:
      GEM_HOME:     "/Users/wayne/.rvm/gems/ruby-1.9.2-head"
      GEM_PATH:     "/Users/wayne/.rvm/gems/ruby-1.9.2-head:/Users/wayne/.rvm/gems/ruby-1.9.2-head@global"
      MY_RUBY_HOME: "/Users/wayne/.rvm/rubies/ruby-1.9.2-head"
      IRBRC:        "/Users/wayne/.rvm/rubies/ruby-1.9.2-head/.irbrc"
      RUBYOPT:      ""
      gemset:       ""

  ruby-1.8.7-p249:

    homes:
      gem:          "/Users/wayne/.rvm/gems/ruby-1.8.7-p249"
      ruby:         "/Users/wayne/.rvm/rubies/ruby-1.8.7-p249"

    binaries:
      ruby:         "/Users/wayne/.rvm/rubies/ruby-1.8.7-p249/bin/ruby"
      irb:          "/Users/wayne/.rvm/rubies/ruby-1.8.7-p249/bin/irb"
      gem:          "/Users/wayne/.rvm/rubies/ruby-1.8.7-p249/bin/gem"
      rake:         "/Users/wayne/.rvm/gems/ruby-1.8.7-p249/bin/rake"

    environment:
      GEM_HOME:     "/Users/wayne/.rvm/gems/ruby-1.8.7-p249"
      GEM_PATH:     "/Users/wayne/.rvm/gems/ruby-1.8.7-p249:/Users/wayne/.rvm/gems/ruby-1.8.7-p249@global"
      MY_RUBY_HOME: "/Users/wayne/.rvm/rubies/ruby-1.8.7-p249"
      IRBRC:        "/Users/wayne/.rvm/rubies/ruby-1.8.7-p249/.irbrc"
      RUBYOPT:      ""
      gemset:       ""


