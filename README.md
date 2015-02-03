# SSL Cipher Test

I needed to test what ssl ciphers a server had, and found this script on a [stackoverflow question](http://superuser.com/questions/109213/is-there-a-tool-that-can-test-what-ssl-tls-cipher-suites-a-particular-website-of). Packaged up as a docker container, this is how to use it:

    docker run --rm programmerq/ciphercheck <server>:<port>

The `:<port>` part is required.
