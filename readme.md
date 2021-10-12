仮想環境：python3 -m venv \[newenvname\]  
切り替え：  
.\\[newenvname\]\Scripts\activate  
.\\[newenvname\]\Scripts\deactivate  
django_tutorial\mysite配下に「.env」ファイルを作成  
ジェネレーターで「SECRET_KEY」を作成し、「.env」に記載  
→from django.core.management.utils import get_random_secret_key  
※空白NG