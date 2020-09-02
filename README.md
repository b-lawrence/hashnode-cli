你好！
很冒昧用这样的方式来和你沟通，如有打扰请忽略我的提交哈。我是光年实验室（gnlab.com）的HR，在招Golang开发工程师，我们是一个技术型团队，技术氛围非常好。全职和兼职都可以，不过最好是全职，工作地点杭州。
我们公司是做流量增长的，Golang负责开发SAAS平台的应用，我们做的很多应用是全新的，工作非常有挑战也很有意思，是国内很多大厂的顾问。
如果有兴趣的话加我微信：13515810775  ，也可以访问 https://gnlab.com/，联系客服转发给HR。

# Hashnode CLI

Wanted to get [Hashnode](https://hashnode.com) on your terminal? Ahoy! now you can.

Here is a quick sample

```
hashnode --help
hashnode stories --hot
hashnode discussions --hot

(0) Download Monitoring: A Cross-Browser Story
    PreambleWhen you want to implement something in a cross-browser way, you are in for a ride down the bugtracker hole. After some ex
(1) How IDE is a blessing for beginners
    Quite recently I came across the post  IDE - The beginner's trap. It's a must a read, good article by YounesButI can't agree to it
(2) HTTP request with ES6 tagged templates
    ES6 template literals are one of my favorite features in es6. A few days ago I saw an open source project on github - htm, there a
(3) Benefits of Progressive Web Applications (PWAs) and How to Build One
    In this tutorial, we're going to build up the fundamentals on Progressive Web Applications (PWAs). I'll help you understand the pa
(4) The all-new Hashnode Chrome extension
    With the start of the new year, new team members, new features, and new product(s), we here at Hashnode are working hard to bring
(q) Quit
    Press to exit
```
## Installation
#### Linux
    curl -L https://github.com/Hashnode/hashnode-cli/releases/download/v0.1.7/hashnode-linux-amd64.tar.gz -o hashnode.tar.gz

```
tar xvf hashnode.tar.gz
chmod +x hashnode
sudo mv ./hashnode /usr/local/bin/hashnode
```
#### MacOS
`brew install hashnode/tap/hashnode`
    
#### Windows:

Download from [GitHub](https://github.com/Hashnode/hashnode-cli/releases) and add the binary to your PATH.

#### Go
Installing using go get pulls from the master branch with the latest development changes.

    go get -u github.com/hashnode/hashnode-cli
# Demo
[![asciicast](https://asciinema.org/a/221329.svg)](https://asciinema.org/a/221329)
