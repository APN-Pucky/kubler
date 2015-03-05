### gentoobb/log-collector:20150108
Built: Sun Jan 11 23:16:48 CET 2015

Image Size: 179.5 MB
#### Installed
Package | USE Flags
--------|----------
*gem install*: fluentd | --no-ri --no-rdoc
*gem install*: fluent-plugin-elasticsearch | --no-ri --no-rdoc
*manual install*: docker-gen-0.3.2 | http://github.com/jwilder/docker-gen/
#### Inherited
Package | USE Flags
--------|----------
**FROM gentoobb/ruby-gcc** |
app-admin/eselect-ruby-20141227 | ``
dev-lang/ruby-2.2.0 | `berkdb rdoc readline sse2 ssl -debug -doc -examples -gdbm -ipv6 -jemalloc -ncurses -rubytests -socks5 -xemacs`
dev-libs/libffi-3.0.13-r1 | `pax`
dev-libs/libyaml-0.1.6 | `-doc -examples -static-libs {-test}`
dev-ruby/json-1.8.2 | `-doc {-test}`
dev-ruby/rake-10.4.2 | `-doc {-test}`
dev-ruby/rdoc-4.1.2 | `-doc {-test}`
dev-ruby/rubygems-2.4.5 | `-server {-test}`
sys-libs/db-4.8.30-r2 | `cxx -doc -examples -java -tcl {-test}`
**FROM gentoobb/gcc** |
dev-libs/gmp-5.1.3-r1 | `cxx -doc -pgo -static-libs`
dev-libs/mpc-1.0.1 | `-static-libs`
dev-libs/mpfr-3.1.2-r1 | `-static-libs`
sys-devel/binutils-2.24-r3 | `cxx nls zlib (-multislot) -multitarget -static-libs {-test} -vanilla`
sys-devel/binutils-config-3-r3 | ``
sys-devel/gcc-4.8.3 | `cxx hardened nls nptl openmp (-altivec) -awt -doc (-fixed-point) -fortran -gcj -go -graphite (-libssp) -mudflap (-multilib) (-multislot) -nopie -nossp -objc -objc`
sys-devel/gcc-config-1.7.3 | ``
sys-devel/make-4.0-r1 | `nls -guile -static`
sys-kernel/linux-headers-3.16 | ``
**FROM gentoobb/bash** |
app-admin/eselect-1.4.3 | `-doc -emacs -vim-syntax`
app-shells/bash-4.2_p53 | `net nls (readline) -afs -bashlogger -examples -mem-scramble -plugins -vanilla`
net-misc/curl-7.39.0 | `ssl threads -adns -idn -ipv6 -kerberos -ldap -metalink -rtmp -ssh -static-libs {-test}`
sys-apps/file-5.21 | `zlib -python -static-libs`
sys-apps/sed-4.2.1-r1 | `acl nls (-selinux) -static`
sys-libs/ncurses-5.9-r3 | `cxx unicode -ada -debug -doc -gpm -minimal -profile -static-libs -tinfo -trace`
sys-libs/readline-6.2_p5-r1 | `-static-libs`
**FROM gentoobb/openssl** |
app-misc/ca-certificates-20130906-r1 | ``
dev-libs/openssl-1.0.1k | `bindist (sse2) tls-heartbeat zlib -gmp -kerberos -rfc3779 -static-libs {-test} -vanilla`
sys-apps/acl-2.2.52-r1 | `nls -static-libs`
sys-apps/attr-2.4.47-r1 | `nls -static-libs`
sys-apps/coreutils-8.21 | `acl nls (xattr) -caps -gmp (-selinux) -static -vanilla`
sys-apps/debianutils-4.4 | `-static`
sys-libs/zlib-1.2.8-r1 | `-minizip -static-libs`
**FROM gentoobb/s6** |
dev-lang/execline-1.3.1.1 | `-static-libs`
dev-libs/skalibs-1.6.0.0 | `-doc -static-libs`
sys-apps/s6-1.1.3.2 | ``
*manual install*: entr-2.9 | http://entrproject.org/
**FROM gentoobb/glibc** |
sys-libs/glibc-2.19-r1 | `hardened -debug -gd (-multilib) -nscd -profile (-selinux) -suid -systemtap -vanilla`
sys-libs/timezone-data-2014i-r1 | `nls -right`
#### Purged
- [ ] Headers
- [x] Static Libs

#### Included
- [x] Headers from gentoobb/bash