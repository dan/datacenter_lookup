# Datacenter Lookup

Datacenter Lookup is an IP address parser in Ruby using the datacenters list from [IPCat](https://github.com/client9/ipcat).

Installation:

```
gem 'datacenter_lookup', '~> 0.1.3'
```

Then, look up your IP address like so:

```
irb
require 'datacenter_lookup'
dc = DatacenterLookup::Parser.new()
ip = "5.79.26.0"
puts dc.find(ip) # => "http://www.rackspace.com/"
ip = "1.1.1.1"
puts dc.find(ip) # => nil
```
