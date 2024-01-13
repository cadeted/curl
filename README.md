# cadeted/curl
Docker curl check Alpine base

Useful to check IP of running container -- e.g. determine VPN IP

Examples:

Check IP of running container:

<code>docker run --rm --net=container:[<i>container</i>] cadeted/curl curl -s ifcongi.co</code>

Check IP of docker host:

<code>docker run --rm cadeted/curl curl -s ifcongi.co</code>
