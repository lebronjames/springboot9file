包括
1. 单个文件上传
http://localhost:8080/file/upload
2. 多个文件上传
http://localhost:8080/file/upload/batch


使用SpringBoot进行文件上传的方法和SpringMVC差不多，本文单独新建一个最简单的DEMO来说明一下。 
主要步骤包括： 
1、创建一个springboot项目工程，本例名称（demo-uploadfile）。 
2、配置 pom.xml 依赖。 
3、创建和编写文件上传的 Controller（包含单文件上传和多文件上传）。 
4、创建和编写文件上传的 HTML 测试页面。 
5、文件上传相关限制的配置（可选）。 
6、运行测试。