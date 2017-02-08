# ros-HW
####左のターミナルで数字が1ずつ上昇して
右のターミナルは数字が3ずつ上昇します
####実行方法(左のターミナル)
  ####1.roscore実行
  ####2.rosrun mypkg count.pyでノードを実行
  ####3.rostopic echo /count_upでデータの抽出
####実行方法(右のターミナル)         
  ####1.サブスクライバを作成
  ####2.roscore実行
  ####3.rosrun mypkg count.py実行
  ####4.rostopic echo /twiceでデータ抽出
