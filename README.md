# Prot0tt
> tikoly prototype

## background
...TBD

## goal
> all Cloudflare free source can usage base tt CLI

- [] re-build proj.
- [] cobra as CLI
- [] TOML as cfg.
    - [] multi. cfg
    - [] echo cfg.s
    - [] pick cfg.
    - [] update cfg.
    - [] del. cfg.
- [] ...

## logging

### 240614 sgh
pull into new host

- 官方下载页面 https://go.dev/doc/install
- tar -C /opt/go/local -xzf go1.22.4.linux-amd64.tar.gz
- ~/.bashrc
```
export GOROOT=/opt/go
export PATH=$GOPATH/bin:/opt/go/local/go/bin:$PATH
```
- go version
    + go version go1.22.4 linux/amd64


### 240515 --orphan
> make orphan branch for new proj.

```bash
$ git co --orphan prot0tt
# deleted all not need
$ git new
# commit up
$ cd ../
# jump into as: /opt/go/src/github.com/tiktagus
$ git clone --single-branch -b prot0tt git@github.com:tiktagus/tiktag.git prot0tt
$ git br
* prot0tt
#only can see self , anti-commit-into-other-branch
```

## Licensing

[The 3-Clause BSD License](https://opensource.org/licenses/BSD-3-Clause)
