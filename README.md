# nginx-rpms
Provides custom rpms for nginx.

Packages that can be downloaded from here have been built from official corresponding sources, and compilation options from the closest (in terms of version) src.rpm provided on nginx official website (http://nginx.org/download).
I may also add custom modules which will then be specified in the appropriate section below.

# 1.9.7-1.el6.ngx
OS Version: Redhat EL 6.5
Architecture: x86_64
Specific modules:
 - nginx-goodies-nginx-sticky-module-ng-c78b7dd79d0d (Adds a 'sticky' directive that allow the use of sticky cookies for loadbalancing under upstream section)

