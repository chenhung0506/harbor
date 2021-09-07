.
├── data         #由install.sh 產生，存放資料與憑證
│   ├── ca_download
│   ├── database
│   ├── job_logs
│   ├── redis
│   ├── registry
│   └── secret   #憑證在這邊
├── harbor
│   ├── common
│   ├── common.sh
│   ├── data
│   ├── docker-compose-nginx.yml  #由docker-compose.yml 手動改寫而來，用途為指定network
│   ├── docker-compose.yml
│   ├── harbor.v2.1.1.tar.gz
│   ├── harbor.yml   #設定網站domain root 密碼，自己申請憑證位置
│   ├── install.sh   #第一次安裝需執行此腳本
│   ├── LICENSE
│   └── prepare
├── harbor-offline-installer-v2.1.1.tgz   # harbor 安裝程式
└── README.md
