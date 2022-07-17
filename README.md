Hiya.

This my site, currently http://chesden.com
Started November 2019 - Cameron Carroll

Build environment: None -- This website will be plain HTML/CSS with no external dependencies.

How were we serving this locally?
ruby -rwebrick -e'WEBrick::HTTPServer.new(:Port => 8000, :DocumentRoot => Dir.pwd).start'
