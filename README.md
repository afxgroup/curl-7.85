## Curl 7.85 for AmigaOS4 and clib4

Configure with:  

`./configure --host=ppc-amigaos --prefix=/usr/ppc-amigaos/SDK/local/clib4 CPPFLAGS="-mcrt=clib4 -D__USE_INLINE__" CFLAGS="-mcrt=clib4 -D__USE_INLINE__" LDFLAGS=-mcrt=clib4 LIBS="-lpthread -latomic -lauto" --with-openssl --disable-shared --disable-ntlm --disable-ipv6 --disable-manual --with-nghttp3 --with-ca-fallback --without-default-ssl-backend --enable-openssl-auto-load-config`
