# kernel-audit-system

# Linux内核安全审计系统

## 功能
- 实时监控Linux内核审计日志
- 检测特权升级、容器逃逸等安全事件
- 多级告警系统（CRITICAL/HIGH/MEDIUM/LOW）
- 自动生成安全报告

## 安装
```bash
# 安装系统依赖
sudo apt install auditd

# 安装Python依赖
pip install -r requirements.txt
