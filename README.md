# Personal Website

This is my personal website. It's simple and fast.

## Deployment

The master branch of this project is served using [GitHub Pages](https://pages.github.com/). Commits to the master branch will automatically be published.

`dig` can be used to confirm DNS is properly configured:

```bash
dig tdstein.github.io +nostats +nocomments +nocmd
```

```bash
; <<>> DiG 9.10.6 <<>> tdstein.github.io +nostats +nocomments +nocmd
;; global options: +cmd
;tdstein.github.io.		IN	A
tdstein.github.io.	3599	IN	A	185.199.110.153
tdstein.github.io.	3599	IN	A	185.199.108.153
tdstein.github.io.	3599	IN	A	185.199.109.153
tdstein.github.io.	3599	IN	A	185.199.111.153
```

## Built With

* [HTML5](https://whatwg.org/) - HTML
* [GitHub Pages](https://pages.github.com/) - Hosting

## Authors

* **Taylor Steinberg** - *Initial work* - [GitHub](https://github.com/tdstein)

