# Python 安全

基础漏洞
---

#### Code Execution 

- [从Django的SECTET_KEY到代码执行](http://xxlegend.com/2015/04/01/%E4%BB%8EDjango%E7%9A%84SECTET_KEY%E5%88%B0%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C/)

#### Command Execution 
- [Command Injection in Python: Examples and Prevention](https://www.stackhawk.com/blog/command-injection-python/)
- [Python RCE vulnerability in Celery](https://snyk.io/blog/python-rce-vulnerability/)
#### CSRF
- [CSRF Protection and Sessions](https://codefellows.github.io/sea-python-401d4/lectures/pyramid_day6_csrf.html)


#### Deserialization 

- [掌阅iReader某站Python漏洞挖掘](https://www.leavesongs.com/PENETRATION/zhangyue-python-web-code-execute.html)
- [Python Pickle的任意代码执行漏洞实践和Payload构造](http://code2sec.com/python-picklede-ren-yi-dai-ma-zhi-xing-lou-dong-shi-jian-he-payloadgou-zao.html)
- [浅析python unpickle反序列化漏洞](https://m3lon.github.io/2018/04/12/%E6%B5%85%E6%9E%90python-unpickle%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E6%BC%8F%E6%B4%9E/)

#### XSS

- [富文本XSS过滤器](https://www.leavesongs.com/PYTHON/python-xss-filter.html)
- [Flask Debugger页面上的通用XSS漏洞分析和挖掘过程记录](http://blog.neargle.com/2016/09/21/flask-src-review-get-a-xss-from-debuger/)

#### Open Redirection

- [python http.server open redirect vulnerability](https://www.leavesongs.com/PENETRATION/python-http-server-open-redirect-vulnerability.html)

#### File Operation 

- [python和django的目录遍历漏洞(任意文件读取)](http://www.lijiejie.com/python-django-directory-traversal/)
- [ARBITRARY FILE READ IN MUSICLOUD](https://www.shawarkhan.com/2019/02/cve-2019-8389-arbitrary-file-read-in.html)
#### SSRF

- [谈一谈如何在Python开发中拒绝SSRF漏洞](https://www.leavesongs.com/PYTHON/defend-ssrf-vulnerable-in-python.html)
- [Python安全 - 从SSRF到命令执行惨案](https://www.leavesongs.com/PENETRATION/getshell-via-ssrf-and-redis.html)

#### SSTI
- [Flask/Jinja2 SSTI && python 沙箱逃逸](https://www.kingkk.com/2018/06/Flask-Jinja2-SSTI-python-%E6%B2%99%E7%AE%B1%E9%80%83%E9%80%B8/)
- [关于python ssti的思考](https://lexsd6.github.io/2020/03/27/python%20%E5%85%B3%E4%BA%8E%E6%B2%99%E7%9B%92%E9%80%83%E9%80%B8%E7%9A%84%E6%80%9D%E8%80%83/)

#### Zip Slip
- [Zip Slip in NLTK (CVE-2019-14751)](https://salvatoresecurity.com/zip-slip-in-nltk-cve-2019-14751/)
- [247CTF "Slippery Upload" Write-Up](https://www.secjuice.com/247ctf-slippery-upload-write-up/)
- [Exploiting insecure file extraction in Python for code execution](https://ajinabraham.com/blog/exploiting-insecure-file-extraction-in-python-for-code-execution)
