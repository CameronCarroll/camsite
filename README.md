Hiya.

This my site, currently http://chesden.com
Started November 2019 - by Cam

Build environment: None -- This website will be plain HTML/CSS with no external dependencies.

How were we serving this locally for testing? (Note to self...)
ruby -rwebrick -e'WEBrick::HTTPServer.new(:Port => 8000, :DocumentRoot => Dir.pwd).start'
