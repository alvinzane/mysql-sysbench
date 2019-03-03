# mysql-sysbench

## 使用说明

```

git clone https://github.com/alvinzane/mysql-sysbench.git

cd mysql-sysbench/scripts

# 修改配置文件
vim sysbench_mysql.conf.sh

# 100个表，100个进程 100万数据
./sysbench_mysql_prepare.sh 100 100 1000000

# 开始压测
./sysbench_oltp.sh

```