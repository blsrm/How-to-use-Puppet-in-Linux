# How-to-use-Puppet-in-Linux #

##Overview

The doc provides CLI interface for installing, configuring, and running packages / services using puppet tool in linux operating system.

```Puppet Master 
	
	


```

```Puppet Agent

	sudo puppet agent -t --environment <custom user> --noop
	sudo puppet agent -t --environment <custom user>
	

```

How can I modify a config file based on certain logic?
```

<% if broadcast != "NONE" %>       
 broadcast <%= broadcast %> 
<% end %>

To do an if/else statement, simply add <% else %>

<% if @someclass::someparameter != true %>
  bar = 42
<% else %> 
   bar = 0
<% end %>
	

```
