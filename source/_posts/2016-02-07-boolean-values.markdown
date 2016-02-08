---
layout: post
title: "Boolean Values"
date: 2016-02-07 00:44:33 -0500
comments: true
 
---


original: 

```ruby
	def boolean_to_string(b)
  		if b == true 
    "true"
  		else b == false
    "false"
  end
end
```

better answer: 

def boolean_to_string(b)
  b ? "true" : "false"
end

need to have a question mark to denote the boolean theory!!

need to submit something to get my streak going :( tomorrow is th real thing)