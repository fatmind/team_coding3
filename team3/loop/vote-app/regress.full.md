# 回归报告 — vote-app

- benchmark: full
- workspace: /tmp/t3-regress/vote-app
- 开始时间: 2026-08-30 21-22-38
- 结束时间: 2026-08-30 23-50-39

## 指标

- 回归是否通过：是
  - story 通过数 4/4
  - uat_report.md 是否生成: 是

- 总耗时: 63m 23s（仅 agent 执行，不含互等空转；从开始到完成经过时间 148m 1s）
  - arch：13m 17s
  - dev：42m 22s
  - uat：7m 44s

- token 估算: total 1947295（in 1864944 / out 82351）
  - arch: 315092（in 302891 / out 12201）· 6 个 session
  - dev: 1434636（in 1370559 / out 64077）· 5 个 session
  - uat: 197567（in 191494 / out 6073）· 2 个 session

- 总 llm 请求数：314
  - arch：87
  - dev：211
  - uat：16

- Arch 派发的返工：无
  - dev_fix 0 次
  - uat_fix 0 次

- UAT 自修轮次: 1 轮
  - script_issue 0
  - product_issue 1

- 总 action 数: 20
  - 按任务类型: to_arch=7, dev_do=4, note=3, to_human=2, to_dev=1, uat_design=1, to_uat=1, uat_check=1
  - 按谁发送的: arch=8, dev=5, uat=4, human=3

## 基线对比
- 无退化
