# Final task pool

This pool contains the 44 tasks marked `implemented` in the Task Tracker's Task Status Table after the latest developer-branch audit, dated 2026-11-09.

## Contents

- Each task is copied verbatim from its developer branch into `tasks/finalpool/<task-name>/`, retaining the task's original subdirectories.
- The example template is unchanged under `tasks/examples/`.
- Task owners are recorded in Notion and in the source-path mapping below.

## Selection and validation

The latest task-addition commits on the 14 developer branches introduced 31 named tasks requiring review. All 31 are recorded as `implementing`: each lacks `task_config.json`, whose `needed_mcp_servers` and `needed_local_tools` requirements are stated in `tasks/examples/example-task/readme.txt`; several also omit other files or have English-documentation violations.

For other task artifacts, the examples specify presence/non-emptiness and English-only documentation (the user-system prompt is optional). Apart from explicitly stated content requirements, only file existence is checked. Optional workspace directories and evaluation/preprocessing scripts are not universally required. No implementation files were repaired or invented for this pool.

The 44 pool tasks were selected by their existing Notion `implemented` status, not newly certified by a full historical re-audit. In particular, activity-logger and deal-manager were removed from the pool after this audit changed their statuses to `implementing`.

The requested `finalpool` branch is available in `spadardtubmanhc385593/BenchTasksCollv3` because the authenticated account could not write directly to `toolathlon/BenchTasksCollv3`. An upstream pull request could not be created: GitHub rejected the head reference with a validation error. The upstream comparison is available at https://github.com/toolathlon/BenchTasksCollv3/compare/main...spadardtubmanhc385593:BenchTasksCollv3:finalpool; it is not an already-open pull request.

## Source paths

The following original paths are mapped to `tasks/finalpool/<basename>` without changing file contents:

- `yuzhen/alert-system` (owner: yuzhen-dev)
- `yuxuan/asset-optimizer` (owner: yuxuan-dev)
- `xiaochen/backup-utility` (owner: xiaochen_dev)
- `gyy/blog-engine` (owner: gyy)
- `junteng/booking-system` (owner: junteng_dev)
- `wenshuo/image-processor` (owner: wenshuo-dev)
- `junteng/calendar-sync` (owner: junteng_dev)
- `ruige/canvas-automation` (owner: ruige)
- `yuzhen/invoice-generator` (owner: yuzhen-dev)
- `jl/canvas-grade-automation` (owner: jl_dev)
- `lv/chat-bot` (owner: lv)
- `zhaochen/load-balancer` (owner: zhaochen)
- `gyy/cms-builder` (owner: gyy)
- `junteng/contact-manager` (owner: junteng_dev)
- `xiaochen/monitoring-agent` (owner: xiaochen_dev)
- `yuxuan/content-manager` (owner: yuxuan-dev)
- `gyy/content-scheduler` (owner: gyy)
- `fan/coupon-manager` (owner: fan-dev)
- `lueyang/crm-system` (owner: lueyang-dev)
- `lv/voice-processor` (owner: lv)
- `ruige/data-analytics` (owner: ruige)
- `haoze/video-trimmer` (owner: haoze)
- `yuzhen/data-validator` (owner: yuzhen-dev)
- `junxian/translation-api` (owner: junxian_dev)
- `xiaochen/deployment-tool` (owner: xiaochen_dev)
- `lueyang/email-campaign` (owner: lueyang-dev)
- `zhaochen/template-engine` (owner: zhaochen)
- `jl/email-classification-system` (owner: jl_dev)
- `yuxuan/task-scheduler` (owner: yuxuan-dev)
- `xiaochen/error-tracker` (owner: xiaochen_dev)
- `haoze/subtitle-generator` (owner: haoze)
- `ruige/expense-tracker` (owner: ruige)
- `gyy/social-publisher` (owner: gyy)
- `lv/feedback-collector` (owner: lv)
- `ruige/file-manager` (owner: ruige)
- `junteng/shipment-tracker` (owner: junteng_dev)
- `lueyang/follow-up-reminder` (owner: lueyang-dev)
- `yuzhen/form-builder` (owner: yuzhen-dev)
- `lv/sentiment-analyzer` (owner: lv)
- `xiaochen/security-scanner` (owner: xiaochen_dev)
- `wenshuo/search-engine` (owner: wenshuo-dev)
- `lueyang/sales-pipeline` (owner: lueyang-dev)
- `junteng/reminder-service` (owner: junteng_dev)
- `junxian/qr-generator` (owner: junxian_dev)
