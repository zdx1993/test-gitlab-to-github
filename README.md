# test-gitlab-to-github

测试,将上传至gitlab的项目自动上传到github

测试自动推送功能!

## 具体步骤

1. 打开gitlab项目，在左侧菜单栏选择`Settings->Repository`
2. 选择Push to a remote repository，打开之后可以看到相关的配置信息。
3. 勾选Remote mirror repository
4. 填写Git repository URL：这个URL地址就是你在码云或者github上面创建的项目的ssh地址，不过需要在地址里加上你的码云或者github的账号密码。 
   比如： 
   我在码云的账号：userName 
   密码：password 
5. 那么这个地址应该相应的改成这样： 
   `https://userName:password@gitee.com/FutaoSmile/SpringCloud-ServiceRegisterCenter.git` 
   密码和地址之间有一个`@`符号。
6. 测试：提交一次push到gitlab之后，gitlab会帮我们自动push代码到我们所配置的远程仓库。