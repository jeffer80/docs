## x509: certificate signed by unknown authority - when using self signed certification
copy the root CA.crt into the following directory, and restart docker
```
"/etc/ssl/certs/ca-certificates.crt",     // Debian/Ubuntu/Gentoo etc.
"/etc/pki/tls/certs/ca-bundle.crt",       // Fedora/RHEL
"/etc/ssl/ca-bundle.pem",                 // OpenSUSE
"/etc/ssl/cert.pem",                      // OpenBSD
"/usr/local/share/certs/ca-root-nss.crt", // FreeBSD/DragonFly
"/etc/pki/tls/cacert.pem",                // OpenELEC
"/etc/certs/ca-certificates.crt",         // Solaris 11.2+
```
