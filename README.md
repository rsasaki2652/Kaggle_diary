# Kaggle_diary

2024.6.6
【機械学習】
	・データ分析の手順としてまずはEDA(Exploratory data analysis)を行う。
	・EDAの手順としては
		　①データの確認（カラム数や行数、データの意味など）
		　②欠損値の確認（NaNとか0とか""とか）
		　③外れ値の確認
		　④データのパターンを確認（時系列、季節性、相関など）
【Git】
	・使い方を復習した
	・まずはGithubでリポジトリを作成
	・リポジトリ内のCodeからSSHをコピー
	・git clone コピーしたSSH
	・cd リポジトリ名
	・git checkout -b branch名
	・subl README.md
	・Kaggle日記を書く

2024.6.7
【機械学習】
	・データの確認方法は下記を参考に
　		①df.info()
　		②df.describe()
　		③sns.pairplot(df)
【Git】
	・git add ファイル名 #ファイルを変更したらaddする
	・git commit -m "コメント" #コメントは簡単に記載
	・git log #ファイルの状態を確認できる（addされているか、commitされているかなど）
	・git pull origin main #まずはmainをpullして最新状態へ
	・git push origin branch名 #変更したブランチをpushする
	・Github上でPull requestをMergeする

2024.6.8
【機械学習】
	・kaggleではpd.get_dummies()をするとboolianで返される
	　pd.get_dummies(df, columns[], drop_first=True, dtype=int)で0,1に変換できる
【PC】
	・Ctrl + TabでGoogle Chromeのタブを右隣へ移動できる
	・Cmd + 9 でGoogle Chromeの一番右のタブへ移動できる

2024.6.18
・モデルはLightGBMが主流
・タイタニックチュートリアルを読み進める

2024.6.20
・日付情報はpd.to_datetime()で特徴量エンジニアリングできる
・多項式特徴量も二乗の項や交差作用項などの新しい特徴量をエンジニアリングしている
・binningは量的な特徴量を質的な特徴量に変換する（年齢を代に分けるなど）








