# tpho.dk-caddy-fs-template

caddy file server template for tpho.dk

use like this:

```Caddyfile
tpho.dk {
    root * <PROJECT>/tpho.dk/index
    import <PROJECT>/fs.Caddyfile
}
```

or inline:

```Caddyfile
tpho.dk {
    root * <PROJECT>/tpho.dk/index
    file_server /caddy-fs.css {
        root <PROJECT>/tpho.dk/
    }
    file_server {
        browse <PROJECT>/tpho.dk/caddy-fs.tmpl
    }
}
```

ascii icons created by me
