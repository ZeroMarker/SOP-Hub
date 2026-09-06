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
├── fashion/                  # 服装设计类
    ├── planning/             # 企划
    │   └── season-plan.md    # 季度商品企划
    ├── design/               # 设计
    │   └── design-development.md # 款式设计开发
    ├── material/             # 面辅料
    │   └── fabric-sourcing.md # 面辅料开发与采购
    ├── pattern/              # 制版
    │   └── pattern-making.md # 制版与工艺规范
    ├── sample/               # 样衣
    │   └── sampling-review.md # 样衣制作与评审
    ├── production/           # 生产
    │   └── bulk-production.md # 大货生产跟单
    ├── quality/              # 质检
    │   └── quality-inspection.md # 成衣质检与入库
    └── tools/                # 工具
        └── software-tools.md # 设计生产软件工具管理规范
└── hardware/                 # 硬件设计类
    ├── planning/             # 立项
    │   └── requirement-approval.md # 需求与立项评审
    ├── design/               # 设计
    │   ├── schematic-design.md # 原理图设计
    │   └── pcb-layout.md     # PCB设计
    ├── prototype/            # 样机
    │   └── prototype-smt.md  # 打样与贴片
    ├── testing/              # 测试
    │   └── hardware-testing.md # 硬件测试与调试
    ├── production/           # 生产
    │   └── npi-mass.md       # 试产与量产导入
    └── certification/        # 认证
        └── compliance.md     # 认证合规
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
| SOP-HW-PLN-REQ-001 | 需求与立项评审 | 硬件-立项 | v1.0 | 生效中 |
| SOP-HW-DES-SCH-001 | 原理图设计 | 硬件-设计 | v1.0 | 生效中 |
| SOP-HW-DES-PCB-001 | PCB设计 | 硬件-设计 | v1.0 | 生效中 |
| SOP-HW-PTO-SMT-001 | 打样与贴片 | 硬件-样机 | v1.0 | 生效中 |
| SOP-HW-TST-HWT-001 | 硬件测试与调试 | 硬件-测试 | v1.0 | 生效中 |
| SOP-HW-PRD-NPI-001 | 试产与量产导入 | 硬件-生产 | v1.0 | 生效中 |
| SOP-HW-CER-COM-001 | 认证合规 | 硬件-认证 | v1.0 | 生效中 |
| SOP-SW-OPS-MGT-001 | 运维管理规范 | 软件运维 | v1.0 | 生效中 |
| SOP-SW-QA-TST-001 | 测试管理规范 | 软件测试 | v1.0 | 生效中 |
| SOP-SW-PRD-REQ-001 | 需求管理规范 | 软件产品 | v1.0 | 生效中 |
| SOP-SW-PM-DLV-001 | 项目交付管理规范 | 软件项目 | v1.0 | 生效中 |
| SOP-SW-SEC-APP-001 | 应用安全管理规范 | 软件安全 | v1.0 | 生效中 |
| SOP-SW-SUP-CS-001 | 客户支持管理规范 | 软件客服 | v1.0 | 生效中 |
| SOP-FAS-PLN-SEA-001 | 季度商品企划 | 服装-企划 | v1.0 | 生效中 |
| SOP-FAS-DES-DDV-001 | 款式设计开发 | 服装-设计 | v1.0 | 生效中 |
| SOP-FAS-MAT-FAB-001 | 面辅料开发与采购 | 服装-面辅料 | v1.0 | 生效中 |
| SOP-FAS-PAT-MKG-001 | 制版与工艺规范 | 服装-制版 | v1.0 | 生效中 |
| SOP-FAS-SMP-REV-001 | 样衣制作与评审 | 服装-样衣 | v1.0 | 生效中 |
| SOP-FAS-PRD-BLK-001 | 大货生产跟单 | 服装-生产 | v1.0 | 生效中 |
| SOP-FAS-QC-INS-001 | 成衣质检与入库 | 服装-质检 | v1.0 | 生效中 |
| SOP-FAS-TOL-SFW-001 | 设计生产软件工具管理规范 | 服装-工具 | v1.0 | 生效中 |

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
