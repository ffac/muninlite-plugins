# muninlite-plugins

Add ```plugindir_``` to PLUGINS variable in ```/usr/sbin/munin-node```, for example:

```PLUGINS="plugindir_ cpu if_ if_err_ load memory processes netstat uptime interrupts irqstats"```

Make the plugins in the custom plugins runable:
chmod u+x /usr/sbin/munin-node-plugin.d/ff_clients 
