employee-onboarding-project/
├── employee-onboarding-backend/
├── employee-onboarding-frontend/
# 员工入职管理系统（前后端分离）
## 环境
后端：JDK17 + MySQL 8.0
前端：Node.js 18

## 后端 employee-backend
1. 在MySQL创建数据库 `employee_system`
2. 执行 sql/init.sql 建表并初始化数据
3. 修改 application.yml 中的数据库账号、密码
4. IDEA导入项目，启动主类
   后端地址：http://localhost:8080
   接口：
   POST /      创建员工
   POST /login 登录
   密码：MD5哈希加密存入数据库

## 前端 employee-frontend
1. 进入前端目录
2. npm install
3. npm run dev
   前端访问地址：http://localhost:5173

