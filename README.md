# Hugo Theme Arch

Hugo Theme Arch is a single column theme for hugo based on [Bootstrap](http://getbootstrap.com/) and a css styling from [Bootstrap Enhancement](http://behigh.github.io/bootstrap_dropdowns_enhancement/).

It is a simple template containing a nice header menu bar and content area.

Ported from [archweb](https://github.com/archlinux/archweb).

- [Demo](https://syui.github.io/hugo-theme-arch)

![Hugo Arch Theme screenshot](https://raw.githubusercontent.com/syui/hugo-theme-arch/master/themes/hugo-theme-arch/images/screenshot.png)

## Get the source code

I assume you've Git installed. Inside the folder of your Hugo site run

```bash
$ git clone https://github.com/syui/hugo-theme-arch
$ cd hugo-theme-arch
```

## Nearly finished

In order to see your site in action, run Hugo's built-in local server.

```bash
# install hugo
$ sudo pacman -S go
$ export GOPATH=$HOME/go
$ go get -v github.com/spf13/hugo

# build
$ hugo

# preview
$ hugo server
------------------------
$ curl -sL localhost:1313
```

Now enter [`localhost:1313`](//localhost:1313) in the address bar of your browser.

> config.toml

```toml
- baseurl = "https://syui.github.io/hugo-theme-arch/"
+ baseurl = "/"
```

## Annotations

Thanks to [Steve Francia](//github.com/spf13) for creating Hugo and the awesome community around the project.

Thanks to [Digitalcraftsman](https://github.com/digitalcraftsman) for creating Hugo theme.

## Comment

Moritz : [talaria](https://github.com/m2w/talaria)

## Reference

[archweb](https://github.com/archlinux/archweb)

