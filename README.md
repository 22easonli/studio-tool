# studio-tool | AI 工作室接单管家

给小工作室用的 AI 接单管家：管客户、管订单、管定金、管进度、管跟进。
A SaaS tool for small studios to manage clients, orders, deposits, progress and follow-ups, with AI assistance.

## 适合谁
毕设辅导、设计、摄影、培训、咨询等接单收定金、需要跟进度的小工作室。

## 主流程
注册登录 → 新建客户 → 建订单 → 收定金 → 推进进度 → 到期提醒跟进 → 交付收尾款 → 看板统计

## 功能
- 账号权限：注册登录、JWT token、角色权限（老板 / 员工 / 客户）
- 客户管理：增删改查、搜索、分页
- 订单管理：建单、改价、状态流转
- 定金账本：收款记录、已收 / 待收统计
- 进度跟进：进度时间线、跟进记录、到期提醒
- 文件资料：上传、列表、资料摘要
- 看板统计：待跟进、本月收入、订单状态分布
- AI 功能：跟进话术生成、客户资料摘要、知识库问答

## 技术栈
- 前端：Vue3 + Element-Plus + Vite + Vue Router + Pinia + Axios
- 后端：SpringBoot + MyBatis-Plus
- 数据库：MySQL，缓存：Redis
- 安全：JWT + 密码加密 + 接口拦截
- AI：大模型 API，Key 放环境变量，设成本上限，失败降级
- 部署：Docker + Nginx + HTTPS

## 开发路线
第 1 周：地基 + 登录权限
第 2-3 周：客户、订单、定金、进度
第 4 周：文件、提醒、看板
第 5-6 周：AI 三件套
第 7-8 周：打磨、演示、找 10 家工作室试用
