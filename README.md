# sodre90.com

My personal site: who I am, Mirador and my other projects. Plain HTML and CSS.

It is served from home, by the nginx proxy add-on of Home Assistant on the Raspberry Pi, out of a clone of this repo in `/share/sodre90-site`, with the `*.sodre90.com` certificate. GitHub Pages serves a copy at sodre90.github.io. To publish a change after pushing it:

```sh
ssh hassio@192.168.1.165 'sudo git -C /share/sodre90-site pull'
```

The Inter font is under the SIL Open Font License (`assets/inter-LICENSE.txt`).
