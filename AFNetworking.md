![](https://intranetproxy.alipay.com/skylark/lark/0/2024/jpeg/110956639/1709025470914-eef6d18b-9f6c-4474-950e-06ced1ab6d8f.jpeg)
![](https://intranetproxy.alipay.com/skylark/lark/__puml/5b3e74f19e83fb8d4d1bf3949e052ca4.svg#lake_card_v2=eyJ0eXBlIjoicHVtbCIsImNvZGUiOiJAc3RhcnR1bWxcblxuQUZVUkxTZXNzaW9uTWFuYWdlciAgKi11cC0gTlNVUkxTZXNzaW9uXG5cbkFGVVJMU2Vzc2lvbk1hbmFnZXIgKi1sZWZ0LSBkZWxlZ2F0ZXNcbmRlbGVnYXRlcyBcIjFcIiAtbGVmdC0-IFwibWFueVwiIEFGVVJMU2Vzc2lvbk1hbmFnZXJUYXNrRGVsZWdhdGVcblxuQUZVUkxTZXNzaW9uTWFuYWdlciAqLWRvd24tIFwiZGF0YVRhc2tzL3VwbG9hZFRhc2tzL2Rvd25sb2FkVGFza3NcIlxuXCJkYXRhVGFza3MvdXBsb2FkVGFza3MvZG93bmxvYWRUYXNrc1wiIFwiM1wiICotdXAtIFwibWFueVwiIE5TVVJMU2Vzc2lvblRhc2tcblxuQUZVUkxTZXNzaW9uTWFuYWdlclRhc2tEZWxlZ2F0ZSAqLWxlZnQtPiBOU1VSTFNlc3Npb25UYXNrOiDlpITnkIZkZWxlZ2F0ZeWbnuiwg1xuXG5BRlVSTFNlc3Npb25NYW5hZ2VyICotZG93bi0gQUZTZWN1cml0eVBvbGljeVxuQUZVUkxTZXNzaW9uTWFuYWdlciAqLWRvd24tIEFGTmV0d29ya1JlYWNoYWJpbGl0eU1hbmFnZXJcblxuXG5BRlVSTFNlc3Npb25NYW5hZ2VyICotdXAtIEFGSlNPTlJlc3BvbnNlU2VyaWFsaXplclxuY2xhc3MgQUZKU09OUmVzcG9uc2VTZXJpYWxpemVyIGV4dGVuZHMgQUZIVFRQUmVzcG9uc2VTZXJpYWxpemVyXG5jbGFzcyBBRkhUVFBSZXNwb25zZVNlcmlhbGl6ZXIgaW1wbGVtZW50cyBBRlVSTFJlc3BvbnNlU2VyaWFsaXphdGlvblxuXG5cbkFGVVJMU2Vzc2lvbk1hbmFnZXIgPHwtcmlnaHQtIEFGSFRUUFNlc3Npb25NYW5hZ2VyOiDnu6fmib9cbkFGSFRUUFNlc3Npb25NYW5hZ2VyICotcmlnaHQtIEFGSFRUUFJlcXVlc3RTZXJpYWxpemVyXG5jbGFzcyBBRkhUVFBSZXF1ZXN0U2VyaWFsaXplciBpbXBsZW1lbnRzIEFGVVJMUmVxdWVzdFNlcmlhbGl6YXRpb25cblxuY2xhc3MgQUZVUkxTZXNzaW9uTWFuYWdlclRhc2tEZWxlZ2F0ZSBpbXBsZW1lbnRzIE5TVVJMU2Vzc2lvblRhc2tEZWxlZ2F0ZVxuY2xhc3MgQUZVUkxTZXNzaW9uTWFuYWdlclRhc2tEZWxlZ2F0ZSBpbXBsZW1lbnRzIE5TVVJMU2Vzc2lvbkRhdGFEZWxlZ2F0ZVxuY2xhc3MgQUZVUkxTZXNzaW9uTWFuYWdlclRhc2tEZWxlZ2F0ZSBpbXBsZW1lbnRzIE5TVVJMU2Vzc2lvbkRvd25sb2FkRGVsZWdhdGVcblxuY2xhc3MgQUZVUkxTZXNzaW9uTWFuYWdlciBpbXBsZW1lbnRzIE5TVVJMU2Vzc2lvblRhc2tEZWxlZ2F0ZVxuY2xhc3MgQUZVUkxTZXNzaW9uTWFuYWdlciBpbXBsZW1lbnRzIE5TVVJMU2Vzc2lvbkRhdGFEZWxlZ2F0ZVxuY2xhc3MgQUZVUkxTZXNzaW9uTWFuYWdlciBpbXBsZW1lbnRzIE5TVVJMU2Vzc2lvbkRvd25sb2FkRGVsZWdhdGVcblxuQGVuZHVtbCIsInVybCI6Imh0dHBzOi8vaW50cmFuZXRwcm94eS5hbGlwYXkuY29tL3NreWxhcmsvbGFyay9fX3B1bWwvNWIzZTc0ZjE5ZTgzZmI4ZDRkMWJmMzk0OWUwNTJjYTQuc3ZnIiwiaWQiOiJwSFRkOSIsIm1hcmdpbiI6eyJ0b3AiOnRydWUsImJvdHRvbSI6dHJ1ZX0sImNhcmQiOiJkaWFncmFtIn0=)

## delegate处理
根据URLSessionTask的delegate属性的注释
> /* Sets a task-specific delegate. Methods not implemented on this delegate will
> * still be forwarded to the session delegate.
> *
> * Cannot be modified after task resumes. Not supported on background session.
> *
> * Delegate is strongly referenced until the task completes, after which it is
> * reset to `nil`.
> */

URLSessionTask的delegate回调会优先找自身的delegate，如果不存在，就会去调用URLSession的delegate

因此，框架中所有task的回调都会先在sessionManager层的delegate触发，再由sessionManager层从mutableTaskDelegatesKeyedByTaskIdentifier 找到 task 对应的 taskDelegate，然后触发 taskDelegate 的回调方法。
![image.png](https://intranetproxy.alipay.com/skylark/lark/0/2024/png/110956639/1709033103428-3460833d-e5cd-4877-8438-428a38705242.png#clientId=u1ec21b90-53d8-4&from=paste&height=324&id=u4d6bda12&originHeight=1064&originWidth=1808&originalType=binary&ratio=1.7999999523162842&rotation=0&showTitle=false&size=193336&status=done&style=none&taskId=ua674f5d2-c277-4cbe-aac4-110d2e050f9&title=&width=550.8837280273438)
## task进度管理
delegate => update NSProgress => block call
### 进度关联
taskDelegate 维护了两个 NSProgress，用来管理下载和上传的进度
![image.png](https://intranetproxy.alipay.com/skylark/lark/0/2024/png/110956639/1709032661053-a3ccd9e1-f194-474e-9cba-61104a53bf8d.png#clientId=u161e6aaf-65ae-4&from=paste&height=476&id=u5a7d99d6&originHeight=1724&originWidth=1948&originalType=binary&ratio=1.7999999523162842&rotation=0&showTitle=false&size=280830&status=done&style=none&taskId=uf29afded-961b-4933-9395-c171963e90d&title=&width=537.8784790039062)
### 进度更新
在各个delegate回调方法中更新NSProgress进度，例如
![image.png](https://intranetproxy.alipay.com/skylark/lark/0/2024/png/110956639/1709032760926-70f40263-00e8-4da9-b1ba-4909ab0d066d.png#clientId=u161e6aaf-65ae-4&from=paste&height=346&id=u18957197&originHeight=1250&originWidth=1942&originalType=binary&ratio=1.7999999523162842&rotation=0&showTitle=false&size=287840&status=done&style=none&taskId=uf4be62de-d151-45db-ab33-9a341bf6dce&title=&width=537.8837280273438)
### KVO监听
并且通过KVO监听NSProgress的进度更新，从而触发调用对应block![image.png](https://intranetproxy.alipay.com/skylark/lark/0/2024/png/110956639/1709032881523-ab13093a-aebb-411f-be87-0128749becfd.png#clientId=u161e6aaf-65ae-4&from=paste&height=245&id=evyp7&originHeight=940&originWidth=2728&originalType=binary&ratio=1.7999999523162842&rotation=0&showTitle=false&size=193057&status=done&style=none&taskId=ubca449ab-3cfa-40eb-9882-551583bc039&title=&width=710.8646240234375)


## 其他
### 多读单写
![image.png](https://intranetproxy.alipay.com/skylark/lark/0/2024/png/110956639/1709033248034-29d85bb6-689c-4f78-bfd3-514564e6fc1e.png#clientId=u9d0c6fbc-e6a5-4&from=paste&height=393&id=u1d13131b&originHeight=1118&originWidth=2028&originalType=binary&ratio=1.7999999523162842&rotation=0&showTitle=false&size=238120&status=done&style=none&taskId=ue443e09c-eaac-493f-a39d-da56ea3f66e&title=&width=712.8837280273438)
