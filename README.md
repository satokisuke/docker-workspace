# 1.ディレクトリ移動
```
cd 任意のディレクトリ/docker-workspace
```
<br><br>
# 2.Docker起動
```
docker-compose up -d
```
<br><br>
# 2.Dockerプロセス確認
```
docker-compose ps
```
StatusがUpとなっていること
<br><br>
# 3,コンテナに接続
```
docker-compose exec python bash
```
<br><br>
# 4.起動
```
cd main
python main.py
```
<br><br>
# 5.プラグインインストール　※必要な場合のみ
```
（例）
python -m pip install numpy
python -m pip install pandas
python -m pip install matplotlib
python -m pip install networkx
python -m pip install pyyaml
python -m pip install xlsxwriter
python -m pip install tornado
```
<br><br>

# 5.プラグインの確認
```
python -m pip list
```
<br><br>