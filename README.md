# finalspeed_autorestart

在无人使用时自动重启finalspeed 也许可以一定程度上减少断流情况 

min_time 和 max_time 指定重启的最小和最大间隔

使用时 下载脚本到本地 并添加cron任务

echo "*/20 * * * * root /path/to/fs_restart.sh" >> /etc/crontab
