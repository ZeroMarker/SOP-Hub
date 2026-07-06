# SOP-Hub

标准操作规程（SOP）统一管理仓库，涵盖医疗、软件等领域的标准化流程文档。

## 目录结构

```
sops/
├── medical/                  # 医疗类
│   ├── outpatient/           # 门诊
│   │   └── registration.md   # 门诊挂号操作规程
│   ├── inpatient/            # 住院
│   │   ├── admission.md      # 住院入院操作规程
│   │   └── discharge.md      # 住院出院操作规程
│   ├── emergency/            # 急诊
│   │   └── triage.md         # 急诊预检分诊操作规程
│   ├── laboratory/           # 检验
│   │   └── specimen-collection.md # 检验标本采集操作规程
│   ├── pharmacy/             # 药房
│   │   └── dispensing.md     # 处方调配操作规程
│   ├── surgery/              # 手术
│   │   └── preoperative-preparation.md # 术前准备操作规程
│   ├── imaging/              # 影像
│   │   └── examination.md    # 影像检查管理规范
│   └── infection-control/    # 院感
│       └── hand-hygiene.md   # 手卫生管理规范
├── software/                 # 软件类
│   ├── dev/                  # 开发
│   │   └── development.md    # 软件开发标准流程
│   ├── ops/                  # 运维
│   │   └── operations.md     # 运维管理规范
│   ├── qa/                   # 测试
│   │   └── testing.md        # 测试管理规范
│   ├── product/              # 产品
│   │   └── requirements.md   # 需求管理规范
│   ├── project/              # 项目
│   │   └── delivery.md       # 项目交付管理规范
│   ├── security/             # 安全
│   │   └── application-security.md # 应用安全管理规范
│   ├── data/                 # 数据
│   │   └── data-governance.md # 数据治理管理规范
│   └── support/              # 客服支持
│       └── customer-support.md # 客户支持管理规范
```

## SOP 清单

| 编号 | 名称 | 分类 | 版本 | 状态 |
|------|------|------|------|------|
| SOP-MED-OP-REG-001 | 门诊挂号 | 医疗-门诊 | v1.0 | 生效中 |
| SOP-MED-IP-ADM-001 | 住院入院 | 医疗-住院 | v1.0 | 生效中 |
| SOP-MED-IP-DSG-001 | 住院出院 | 医疗-住院 | v1.0 | 生效中 |
| SOP-MED-ER-TRI-001 | 急诊预检分诊 | 医疗-急诊 | v1.0 | 生效中 |
| SOP-MED-LAB-SPC-001 | 检验标本采集 | 医疗-检验 | v1.0 | 生效中 |
| SOP-MED-PHA-DSP-001 | 处方调配 | 医疗-药房 | v1.0 | 生效中 |
| SOP-MED-SUR-PRE-001 | 术前准备 | 医疗-手术 | v1.0 | 生效中 |
| SOP-MED-IMG-EXM-001 | 影像检查管理 | 医疗-影像 | v1.0 | 生效中 |
| SOP-MED-IC-HH-001 | 手卫生管理 | 医疗-院感 | v1.0 | 生效中 |
| SOP-SW-DEV-STD-001 | 软件开发标准流程 | 软件开发 | v1.0 | 生效中 |
| SOP-SW-OPS-MGT-001 | 运维管理规范 | 软件运维 | v1.0 | 生效中 |
| SOP-SW-QA-TST-001 | 测试管理规范 | 软件测试 | v1.0 | 生效中 |
| SOP-SW-PRD-REQ-001 | 需求管理规范 | 软件产品 | v1.0 | 生效中 |
| SOP-SW-PM-DLV-001 | 项目交付管理规范 | 软件项目 | v1.0 | 生效中 |
| SOP-SW-SEC-APP-001 | 应用安全管理规范 | 软件安全 | v1.0 | 生效中 |
| SOP-SW-DATA-GOV-001 | 数据治理管理规范 | 软件数据 | v1.0 | 生效中 |
| SOP-SW-SUP-CS-001 | 客户支持管理规范 | 软件客服 | v1.0 | 生效中 |

## 文档规范

- 文件格式：Markdown
- 命名规则：`sops/{分类}/{子分类}/{文档名}.md`
- 编号规则：`SOP-{分类缩写}-{子分类缩写}-{业务缩写}-{序号}`

## 使用方式

1. 按目录结构定位所需 SOP
2. 文档内含流程图、职责分工、质量标准等完整内容
3. 附件模板可直接下载使用

## License

MIT
