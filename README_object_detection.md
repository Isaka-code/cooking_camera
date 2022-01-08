# 基本的な物体検出
参考１： https://www.alpha.co.jp/blog/202108_02 
・基本的にはサイト通りでOK。
./venv-yolov5/Scripts/activate　でエラーが出た。Set-ExecutionPolicy RemoteSigned -Scope Process　で解決。
・pip install -r requirements.txt　でpip のバージョンが古くてエラー。python -m pip install --upgrade pip　し、解決。
・python detect.py でエラー。C:\Users\tsuyo\CODE\cooking_camera\yolov5\data\coco128.yaml のコメントに文字コードエラー。コメント部分すべて削除して解決。


# 物体検出＋α
参考２：　https://www.youtube.com/watch?v=O9bkqVsa_cs　　https://www.youtube.com/watch?v=Xxba-pd8Eh8