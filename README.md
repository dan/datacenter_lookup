# Datacenter Lookup

Datacenter Detective is an IP address parser in Ruby using the datacenters list from [IPCat](https://github.com/client9/ipcat).

Installation:

```
gem 'datacenter-lookup', '~> 0.1.0'
```

Then, look up your IP address like so:

```
dd = DatacenterLookup::Parser.new()
ip = "5.79.26.0"
puts dd.parse(ip) # http://www.rackspace.com/
```
