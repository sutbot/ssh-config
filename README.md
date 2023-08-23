# `/etc/ssh/sshd_config`


### Key Exchange Algorithms

<table><colgroup><col> <col> <col></colgroup><tbody><tr><td><code>ext-info-s</code></td><td></td><td><span>Unknown</span></td></tr><tr><td><code>diffie-hellman-group14-sha256</code></td><td><p>Diffie-Hellman with 2048-bit Oakley Group 14 with SHA-256 hash<a href="https://tools.ietf.org/html/draft-ietf-curdle-ssh-modp-dh-sha2-01"><span></span></a></p><span>Oakley Group 14 should be secure for now.</span></td><td><span>Secure</span></td></tr><tr><td><code>diffie-hellman-group15-sha512</code></td><td><p>Diffie-Hellman with 3071-bit MODP Group 15 with SHA-512 hash<a href="https://tools.ietf.org/html/draft-ietf-curdle-ssh-modp-dh-sha2-01"><span></span></a></p></td><td><span>Secure</span></td></tr><tr><td><code>diffie-hellman-group16-sha512</code></td><td><p>Diffie-Hellman with 4096-bit MODP Group 16 with SHA-512 hash<a href="https://tools.ietf.org/html/draft-ietf-curdle-ssh-modp-dh-sha2-01"><span></span></a></p></td><td><span>Secure</span></td></tr><tr><td><code>diffie-hellman-group-exchange-sha256</code></td><td><p>Diffie-Hellman with MODP Group Exchange with SHA-256 hash<a href="https://tools.ietf.org/html/rfc4419"><span></span></a></p></td><td><span>Secure</span></td></tr><tr><td><code>curve25519-sha256</code></td><td><p>Elliptic Curve Diffie-Hellman on Curve25519 with SHA-256 hash<a href="https://tools.ietf.org/html/draft-ietf-curdle-ssh-curves-00"><span></span></a></p></td><td><span>Secure</span></td></tr><tr><td><code>curve25519-sha256@libssh.org</code></td><td><p>Elliptic Curve Diffie-Hellman on Curve25519 with SHA-256 hash<a href="https://tools.ietf.org/html/draft-ietf-curdle-ssh-curves-00"><span></span></a></p></td><td><span>Secure</span></td></tr><tr><td><code>ecdh-sha2-nistp256</code></td><td><p>Elliptic Curve Diffie-Hellman on NIST P-256 curve with SHA-256 hash<a href="https://tools.ietf.org/html/rfc5656"><span></span></a></p><span><a href="https://safecurves.cr.yp.to/">Possible NSA backdoor</a>.</span></td><td><span>Secure</span></td></tr><tr><td><code>ecdh-sha2-nistp384</code></td><td><p>Elliptic Curve Diffie-Hellman on NIST P-384 curve with SHA-384 hash<a href="https://tools.ietf.org/html/rfc5656"><span></span></a></p><span><a href="https://safecurves.cr.yp.to/">Possible NSA backdoor</a>.</span></td><td><span>Secure</span></td></tr><tr><td><code>ecdh-sha2-nistp521</code></td><td><p>Elliptic Curve Diffie-Hellman on NIST P-521 curve with SHA-512 hash<a href="https://tools.ietf.org/html/rfc5656"><span></span></a></p><span><a href="https://safecurves.cr.yp.to/">Possible NSA backdoor</a>.</span></td><td><span>Secure</span></td></tr><tr><td><code>diffie-hellman-group14-sha1</code></td><td><p>Diffie-Hellman with 2048-bit Oakley Group 14 with SHA-1 hash<a href="https://tools.ietf.org/html/rfc4253"><span></span></a></p><span>SHA-1 is becoming obsolete, consider using SHA-256 version.</span></td><td><span>Weak</span></td></tr></tbody></table>

### Server Host Key Algorithms

<table><colgroup><col> <col> <col></colgroup><tbody><tr><td><code>ssh-ed25519</code></td><td><p>Ed25519, an Edwards-curve Digital Signature Algorithm (EdDSA)<a href="https://tools.ietf.org/html/draft-bjh21-ssh-ed25519-02"><span></span></a></p></td><td><span>Secure</span></td></tr><tr><td><code>ecdsa-sha2-nistp256</code></td><td><p>Elliptic Curve Digital Signature Algorithm (ECDSA) on NIST P-256 curve with SHA-256 hash<a href="https://tools.ietf.org/html/rfc5656"><span></span></a></p><span><a href="https://safecurves.cr.yp.to/">Possible NSA backdoor</a>.</span></td><td><span>Secure</span></td></tr><tr><td><code>ecdsa-sha2-nistp384</code></td><td><p>Elliptic Curve Digital Signature Algorithm (ECDSA) on NIST P-384 curve with SHA-384 hash<a href="https://tools.ietf.org/html/rfc5656"><span></span></a></p><span><a href="https://safecurves.cr.yp.to/">Possible NSA backdoor</a>.</span></td><td><span>Secure</span></td></tr><tr><td><code>ecdsa-sha2-nistp521</code></td><td><p>Elliptic Curve Digital Signature Algorithm (ECDSA) on NIST P-521 curve with SHA-512 hash<a href="https://tools.ietf.org/html/rfc5656"><span></span></a></p><span><a href="https://safecurves.cr.yp.to/">Possible NSA backdoor</a>.</span></td><td><span>Secure</span></td></tr><tr><td><code>rsa-sha2-256</code></td><td><p>RSA with SHA-256 hash<a href="https://tools.ietf.org/html/draft-ietf-curdle-rsa-sha2-02"><span></span></a></p></td><td><span>Secure</span></td></tr><tr><td><code>ssh-rsa-sha256@ssh.com</code></td><td><p>RSA with SHA-256 hash by SSH Communications Security</p></td><td><span>Secure</span></td></tr><tr><td><code>rsa-sha2-512</code></td><td><p>RSA with SHA-512 hash<a href="https://tools.ietf.org/html/draft-ietf-curdle-rsa-sha2-02"><span></span></a></p></td><td><span>Secure</span></td></tr><tr><td><code>ssh-rsa</code></td><td><p>RSA with SHA-1 hash<a href="https://tools.ietf.org/html/rfc4253"><span></span></a></p><span>SHA-1 is becoming obsolete.</span></td><td><span>Weak</span></td></tr></tbody></table>

### Encryption Algorithms

<table><colgroup><col> <col> <col></colgroup><tbody><tr><td><code>chacha20-poly1305@openssh.com</code></td><td><span></span><p>256-bit ChaCha20 with Poly1305 authenticator by OpenSSH<a href="https://tools.ietf.org/html/draft-josefsson-ssh-chacha20-poly1305-openssh-00"><span></span></a></p></td><td><span>Secure</span></td></tr><tr><td><code>aes256-gcm@openssh.com</code></td><td><span></span><p>AES with 256-bit key in GCM mode by OpenSSH<a href="https://www.openssh.com/txt/release-6.2"><span></span></a></p></td><td><span>Secure</span></td></tr><tr><td><code>aes128-gcm@openssh.com</code></td><td><span></span><p>AES with 128-bit key in GCM mode by OpenSSH<a href="https://www.openssh.com/txt/release-6.2"><span></span></a></p></td><td><span>Secure</span></td></tr><tr><td><code>aes256-ctr</code></td><td><span></span><p>AES with 256-bit key in CTR mode<a href="https://tools.ietf.org/html/rfc4344"><span></span></a></p></td><td><span>Secure</span></td></tr><tr><td><code>aes192-ctr</code></td><td><span></span><p>AES with 192-bit key in CTR mode<a href="https://tools.ietf.org/html/rfc4344"><span></span></a></p></td><td><span>Secure</span></td></tr><tr><td><code>aes128-ctr</code></td><td><span></span><p>AES with 128-bit key in CTR mode<a href="https://tools.ietf.org/html/rfc4344"><span></span></a></p></td><td><span>Secure</span></td></tr><tr><td><code>twofish256-ctr</code></td><td><span></span><p>Twofish with 256-bit key in CTR mode<a href="https://tools.ietf.org/html/rfc4344"><span></span></a></p></td><td><span>Secure</span></td></tr><tr><td><code>twofish192-ctr</code></td><td><span></span><p>Twofish with 192-bit key in CTR mode<a href="https://tools.ietf.org/html/rfc4344"><span></span></a></p></td><td><span>Secure</span></td></tr><tr><td><code>twofish128-ctr</code></td><td><span></span><p>Twofish with 128-bit key in CTR mode<a href="https://tools.ietf.org/html/rfc4344"><span></span></a></p></td><td><span>Secure</span></td></tr></tbody></table>

### MAC Algorithms

<table><colgroup><col> <col> <col></colgroup><tbody><tr><td><code>hmac-sha2-512-etm@openssh.com</code></td><td><span></span><p>Hash-based MAC using SHA-512 (Encrypt-then-MAC) by OpenSSH</p></td><td><span>Secure</span></td></tr><tr><td><code>hmac-sha2-256-etm@openssh.com</code></td><td><span></span><p>Hash-based MAC using SHA-256 (Encrypt-then-MAC) by OpenSSH</p></td><td><span>Secure</span></td></tr><tr><td><code>hmac-sha2-512</code></td><td><span></span><p>Hash-based MAC using SHA-512<a href="https://tools.ietf.org/html/rfc6668"><span></span></a></p></td><td><span>Secure</span></td></tr><tr><td><code>hmac-sha2-256</code></td><td><span></span><p>Hash-based MAC using SHA-256<a href="https://tools.ietf.org/html/rfc6668"><span></span></a></p></td><td><span>Secure</span></td></tr><tr><td><code>hmac-sha1</code></td><td><span></span><p>Hash-based MAC using SHA-1<a href="https://tools.ietf.org/html/rfc4253"><span></span></a></p><span>SHA-1 is becoming deprecated - consider replacing with SHA-256 or SHA-512.</span></td><td><span>Weak</span></td></tr><tr><td><code>hmac-sha1-96</code></td><td><span></span><p>Hash-based MAC using SHA-1 truncated to 96 bits<a href="https://tools.ietf.org/html/rfc4253"><span></span></a></p><span>SHA-1 is becoming deprecated - consider replacing with SHA-256 or SHA-512.</span></td><td><span>Weak</span></td></tr></tbody></table>

### Compression Algorithms

<table><colgroup><col> <col> <col></colgroup><tbody><tr><td><code>none</code></td><td><span></span><p>No compression<a href="https://tools.ietf.org/html/rfc4253"><span></span></a></p></td><td><span>Unknown</span></td></tr></tbody></table>

### Server Public Keys

#### ssh-ed25519

<table><colgroup><col> <col></colgroup><tbody><tr><td>Key size:</td><td>256bit</td></tr><tr><td>MD5 Fingerprint:</td><td><code>e7:e4:45:c6:b8:e4:bb:d8:68:89:27:86:fd:01:58:f0</code></td></tr><tr><td>SHA-256 Fingerprint:</td><td><code>d7Te2DHmvBNSWJNBWik2KbDTjmWtYHe2bvXTMM9lVg4</code></td></tr><tr><td>Public key:</td><td><pre>---- BEGIN SSH2 PUBLIC KEY ----
Comment: "Saved by Rebex SSH"
AAAAC3NzaC1lZDI1NTE5AAAAIOdXzF+Jx/wvEBun5fxi8FQK30miLZFND0rxkYwN
cYlE
---- END SSH2 PUBLIC KEY ----
</pre></td></tr></tbody></table>

#### ecdsa-sha2-nistp521

<table><colgroup><col> <col></colgroup><tbody><tr><td>Key size:</td><td>521bit</td></tr><tr><td>MD5 Fingerprint:</td><td><code>cf:35:14:2d:fd:50:81:16:18:f3:1e:a7:91:6e:1f:c6</code></td></tr><tr><td>SHA-256 Fingerprint:</td><td><code>oB7DiC3aKylQc0FzKsRNFcb2beTonLqWC54fIyZRHD0</code></td></tr><tr><td>Public key:</td><td><pre>---- BEGIN SSH2 PUBLIC KEY ----
Comment: "Saved by Rebex SSH"
AAAAE2VjZHNhLXNoYTItbmlzdHA1MjEAAAAIbmlzdHA1MjEAAACFBAHR9Z8D+m2X
TsRdBgN7cyyxLWzoOaahQ1H6W7ivEVhm/qmx098BYD0clQoZWufKTuSDc+5tjPpi
68jJpbta5eqgbAGPA8+Ydxln+gcFkEhbmjoiCR2/zNH1ThzlGtiZPkc8uZDU7+n/
6iH41mNdGUPfE2T70qhQbPG9Q/Y2cHT7Eu8rZA==
---- END SSH2 PUBLIC KEY ----
</pre></td></tr></tbody></table>

#### ecdsa-sha2-nistp384

<table><colgroup><col> <col></colgroup><tbody><tr><td>Key size:</td><td>384bit</td></tr><tr><td>MD5 Fingerprint:</td><td><code>39:6b:50:38:53:6d:02:71:61:17:39:63:f1:90:29:bb</code></td></tr><tr><td>SHA-256 Fingerprint:</td><td><code>LrUz4tiRPOEG6PAns8XAcSTSz/Of6W9gFECD2fc7Tgg</code></td></tr><tr><td>Public key:</td><td><pre>---- BEGIN SSH2 PUBLIC KEY ----
Comment: "Saved by Rebex SSH"
AAAAE2VjZHNhLXNoYTItbmlzdHAzODQAAAAIbmlzdHAzODQAAABhBCSvNmFAneBP
S/4KQt3HCzXDuX9c5DBgwM2OyQzvdIsD3EHOIS5XDdM8fQlar6+7AgcjNzjfE7xm
1gp+0CxKJZWZqkTacR7Ji8GJhfJBKxhIyV65OBYstU/yNMtPXwsQRQ==
---- END SSH2 PUBLIC KEY ----
</pre></td></tr></tbody></table>

#### ecdsa-sha2-nistp256

<table><colgroup><col> <col></colgroup><tbody><tr><td>Key size:</td><td>256bit</td></tr><tr><td>MD5 Fingerprint:</td><td><code>3d:f0:7e:e0:b5:cf:6f:60:94:66:79:96:d3:2e:81:a4</code></td></tr><tr><td>SHA-256 Fingerprint:</td><td><code>OzvpQxRUzSfV9F/ECMXbQ7B7zbK0aTngrhFCBUno65c</code></td></tr><tr><td>Public key:</td><td><pre>---- BEGIN SSH2 PUBLIC KEY ----
Comment: "Saved by Rebex SSH"
AAAAE2VjZHNhLXNoYTItbmlzdHAyNTYAAAAIbmlzdHAyNTYAAABBBLZcZopPvkxY
ERubWeSrWOSHpxJdR14WFVES/Q3hFguTn6L+0EANqYcbRXhGBUV6SjR7SaxZACXS
xOzgCtG4kwc=
---- END SSH2 PUBLIC KEY ----
</pre></td></tr></tbody></table>

#### rsa-sha2-512

<table><colgroup><col> <col></colgroup><tbody><tr><td>Key size:</td><td>2048bit</td></tr><tr><td>MD5 Fingerprint:</td><td><code>03:61:c4:98:f1:ff:7d:23:97:51:07:13:88:b8:c5:55</code></td></tr><tr><td>SHA-256 Fingerprint:</td><td><code>FFMFsBkaSJbqAeiMb+4c2OJI765czqp6ArYO0GznBJo</code></td></tr><tr><td>Public key:</td><td><pre>---- BEGIN SSH2 PUBLIC KEY ----
Comment: "Saved by Rebex SSH"
AAAAB3NzaC1yc2EAAAABJQAAAQEAkRM6RxDdi3uAGogR3nsQMpmt43X4WnwgMzs8
VkwUCqikewxqk4U7EyUSOUeT3CoUNOtywrkNbH83e6/yQgzc3M8i/eDzYtXaNGcK
yLfy3Ci6XOwiLLOx1z2AGvvTXln1RXtve+Tn1RTr1BhXVh2cUYbiuVtTWqbEgErT
20n4GWD4wv7FhkDbLXNi8DX07F9v7+jH67i0kyGm+E3rE+SaCMRo3zXE6VO+ijcm
9HdVxfltQwOYLfuPXM2t5aUSfa96KJcA0I4RCMzA/8Dl9hXGfbWdbD2hK1ZQ1pLv
vpNPPyKKjPZcMpOznprbg+jIlsZMWIHt7mq2OJXSdruhRrGzZw==
---- END SSH2 PUBLIC KEY ----
</pre></td></tr></tbody></table>

#### ssh-rsa-sha256@ssh.com

<table><colgroup><col> <col></colgroup><tbody><tr><td>Key size:</td><td>2048bit</td></tr><tr><td>MD5 Fingerprint:</td><td><code>03:61:c4:98:f1:ff:7d:23:97:51:07:13:88:b8:c5:55</code></td></tr><tr><td>SHA-256 Fingerprint:</td><td><code>FFMFsBkaSJbqAeiMb+4c2OJI765czqp6ArYO0GznBJo</code></td></tr><tr><td>Public key:</td><td><pre>---- BEGIN SSH2 PUBLIC KEY ----
Comment: "Saved by Rebex SSH"
AAAAB3NzaC1yc2EAAAABJQAAAQEAkRM6RxDdi3uAGogR3nsQMpmt43X4WnwgMzs8
VkwUCqikewxqk4U7EyUSOUeT3CoUNOtywrkNbH83e6/yQgzc3M8i/eDzYtXaNGcK
yLfy3Ci6XOwiLLOx1z2AGvvTXln1RXtve+Tn1RTr1BhXVh2cUYbiuVtTWqbEgErT
20n4GWD4wv7FhkDbLXNi8DX07F9v7+jH67i0kyGm+E3rE+SaCMRo3zXE6VO+ijcm
9HdVxfltQwOYLfuPXM2t5aUSfa96KJcA0I4RCMzA/8Dl9hXGfbWdbD2hK1ZQ1pLv
vpNPPyKKjPZcMpOznprbg+jIlsZMWIHt7mq2OJXSdruhRrGzZw==
---- END SSH2 PUBLIC KEY ----
</pre></td></tr></tbody></table>

#### rsa-sha2-256

<table><colgroup><col> <col></colgroup><tbody><tr><td>Key size:</td><td>2048bit</td></tr><tr><td>MD5 Fingerprint:</td><td><code>03:61:c4:98:f1:ff:7d:23:97:51:07:13:88:b8:c5:55</code></td></tr><tr><td>SHA-256 Fingerprint:</td><td><code>FFMFsBkaSJbqAeiMb+4c2OJI765czqp6ArYO0GznBJo</code></td></tr><tr><td>Public key:</td><td><pre>---- BEGIN SSH2 PUBLIC KEY ----
Comment: "Saved by Rebex SSH"
AAAAB3NzaC1yc2EAAAABJQAAAQEAkRM6RxDdi3uAGogR3nsQMpmt43X4WnwgMzs8
VkwUCqikewxqk4U7EyUSOUeT3CoUNOtywrkNbH83e6/yQgzc3M8i/eDzYtXaNGcK
yLfy3Ci6XOwiLLOx1z2AGvvTXln1RXtve+Tn1RTr1BhXVh2cUYbiuVtTWqbEgErT
20n4GWD4wv7FhkDbLXNi8DX07F9v7+jH67i0kyGm+E3rE+SaCMRo3zXE6VO+ijcm
9HdVxfltQwOYLfuPXM2t5aUSfa96KJcA0I4RCMzA/8Dl9hXGfbWdbD2hK1ZQ1pLv
vpNPPyKKjPZcMpOznprbg+jIlsZMWIHt7mq2OJXSdruhRrGzZw==
---- END SSH2 PUBLIC KEY ----
</pre></td></tr></tbody></table>

#### ssh-rsa

<table><colgroup><col> <col></colgroup><tbody><tr><td>Key size:</td><td>2048bit</td></tr><tr><td>MD5 Fingerprint:</td><td><code>03:61:c4:98:f1:ff:7d:23:97:51:07:13:88:b8:c5:55</code></td></tr><tr><td>SHA-256 Fingerprint:</td><td><code>FFMFsBkaSJbqAeiMb+4c2OJI765czqp6ArYO0GznBJo</code></td></tr><tr><td>Public key:</td><td><pre>---- BEGIN SSH2 PUBLIC KEY ----
Comment: "Saved by Rebex SSH"
AAAAB3NzaC1yc2EAAAABJQAAAQEAkRM6RxDdi3uAGogR3nsQMpmt43X4WnwgMzs8
VkwUCqikewxqk4U7EyUSOUeT3CoUNOtywrkNbH83e6/yQgzc3M8i/eDzYtXaNGcK
yLfy3Ci6XOwiLLOx1z2AGvvTXln1RXtve+Tn1RTr1BhXVh2cUYbiuVtTWqbEgErT
20n4GWD4wv7FhkDbLXNi8DX07F9v7+jH67i0kyGm+E3rE+SaCMRo3zXE6VO+ijcm
9HdVxfltQwOYLfuPXM2t5aUSfa96KJcA0I4RCMzA/8Dl9hXGfbWdbD2hK1ZQ1pLv
vpNPPyKKjPZcMpOznprbg+jIlsZMWIHt7mq2OJXSdruhRrGzZw==
---- END SSH2 PUBLIC KEY ----
</pre></td></tr></tbody></table>
