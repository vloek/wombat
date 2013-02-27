Improved wombat. Allows to changes user agent.
Example:
```ruby
require 'wombat'

Wombat.crawl do
  base_url "http://www.google.ru"
  path '/'
	user_agent_alias 'Mac Safari'
	
	headers css: 'head'	
end
```
