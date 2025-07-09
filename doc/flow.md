graph TD
```angular2html
A[代码推送/Pull Request] --> B[触发工作流]
B --> C[检出代码]
C --> D[设置JDK 21环境]
D --> E[Maven构建项目]
E --> F[验证JAR文件]
F --> G[运行JAR应用]
G --> H[流程结束]
```

