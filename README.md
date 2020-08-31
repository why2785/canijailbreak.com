我是光年实验室高级招聘经理。
我在github上访问了你的开源项目，你的代码超赞。你最近有没有在看工作机会，我们在招软件开发工程师，拉钩和BOSS等招聘网站也发布了相关岗位，有公司和职位的详细信息。
我们公司在杭州，业务主要做流量增长，是很多大型互联网公司的流量顾问。公司弹性工作制，福利齐全，发展潜力大，良好的办公环境和学习氛围。
公司官网是http://www.gnlab.com,公司地址是杭州市西湖区古墩路紫金广场B座，若你感兴趣，欢迎与我联系，
电话是0571-88839161，手机号：18668131388，微信号：echo 'bGhsaGxoMTEyNAo='|base64 -D ,静待佳音。如有打扰，还请见谅，祝生活愉快工作顺利。

<h1 align="center">
  <img src="https://ipsw.me/assets/images/brand/racer.png"><br>
  canijailbreak.com
</h1>

<p align="center">
  <a href="https://travis-ci.org/cj123/canijailbreak.com"><img src="https://travis-ci.org/cj123/canijailbreak.com.svg?branch=master" alt="Build Status"></a>
</p>

a website which tells you whether you can jailbreak your iPhone, iPad, iPod touch or Apple TV.

## Contributing

We welcome contributions to the code/design/data of the site! Currently, it's fairly basic.

A few guidelines for contributing:

1. **No beta jailbreaks**
2. **No beta iOS versions**
3. **Use one pull request per jailbreak addition** - this will allow us to easily approve/reject new additions on a one-by-one basis.
4. Commit tags for new jailbreaks, in the form of `[jailbreak] <name> <version> for <ios versions>` are recommended :)
5. Try to find the _simplest_ route to jailbreak, such as one click GUIs, that support _as many devices/ios versions as possible_.


## installation

```bash

$ go get github.com/cj123/canijailbreak.com
$ cd $GOPATH/src/github.com/cj123/canijailbreak.com
$ go build .
```

## running it

```bash
$ ./canijailbreak.com --help
```

This will generate output, by default into `./static`. 

## adding jailbreaks

look in the file `./jailbreaks.json` for a layout

then run the `./canijailbreak.com` util again
