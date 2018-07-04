expose
Expose ports without publishing them to the host machine - they’ll only be accessible to linked services. Only the internal port can be specified.

expose:
 - "3000"
 - "8000"

ports
Expose ports.

Note: Port mapping is incompatible with network_mode: host