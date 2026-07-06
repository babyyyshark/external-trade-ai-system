# Customer Development AI System（客户开发系统）

## 1. 系统目标

用于自动化/半自动化完成外贸客户开发流程，包括：

- 客户搜索
- 客户筛选
- 客户分类
- 邮箱获取
- 开发信生成
- 跟进建议

---

## 2. 输入（Input）

用户提供：

- 产品类型（如：水果 / 海鲜）
- 目标国家（如：Canada / USA / UAE）
- 客户类型（Importers / Wholesalers / Retailers）

---

## 3. 输出（Output）

标准输出结构：

### ① 客户列表
- 公司名
- 国家
- 网站
- 邮箱（如可获取）
- 类型判断

### ② 客户评分（0-10）
- 是否进口水果
- 是否活跃进口商
- 是否匹配产品
- 是否有官网

### ③ 开发信（英文）

结构：
- Greeting
- Company intro
- Product intro
- Advantage
- Call to action

---

## 4. 工作流程（Workflow）

Step 1：确定目标市场  
Step 2：搜索潜在客户  
Step 3：筛选进口商  
Step 4：提取联系方式  
Step 5：评分  
Step 6：生成开发信  

---

## 5. AI执行规则

- 必须结构化输出
- 不允许只给“建议”
- 必须给可执行结果
- 不确定信息必须标注

---

## 6. 后续扩展

未来可接入：

- Email automation
- CRM系统
- WhatsApp跟进
- RAG知识库
