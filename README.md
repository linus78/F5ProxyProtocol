This iRule appends the content of the TCP payload to include a Proxy Protocol v1 complaint 'header' including "PROXY TCP4 <source ip> <destination ip> <source port> <destination port>"  This is useful when using SNAT on an F5 and still needing to retain the original source and destination ip/port for use with HA proxy, smtp, etc.
