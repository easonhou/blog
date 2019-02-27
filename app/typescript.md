# TypeScript
## 资料
 * 官方手册：http://www.typescriptlang.org/docs/handbook/basic-types.html  
 * 中文版Handbook：https://zhongsp.gitbooks.io/typescript-handbook/content/

## 安装
首先，安装nodeJS: http://nodejs.cn/  
 然后用js自带的npm工具： 
 ```
 npm install -g typescript
 ```

 ## Hello World
 建立文件Hello.ts
 ```
 function sayHello(person: string) {
    return 'Hello, ' + person;
}

let user = 'Tom';
console.log(sayHello(user));
 ```

 跑：  
 ```
 tsc hello.ts
 ```