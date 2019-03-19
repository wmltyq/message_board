# 运行项目
进入项目根目录，运行以下命令
```
# 安装依赖
pip install -r requirements.txt

# 运行Web
python guestbook.py
```

# 添加留言
1. 通过工程的根目录进入Python Shell
```
import datetime
from guestbook import save_data
from guestbook import load_data
save_data('测试用户', '测试留言', datetime.datetime(2019, 3, 19, 17, 18, 0))
load_data()
```

2. 通过网页添加留言数据

# 文件说明
guestbook.bak、guestbook.dat和guestbook.dir三个文件是存储留言数据用的，可以删除。使用以上添加留言的方式可以自动生成。
