# s649_weightModification
重荷状態の算出方法を変更して重量限界＝インベントリの各マスの重量限界とする。  
重荷状態は装備やホットバースロットを含めてインベントリの最も重いアイテムで決まる。  
コンテナ等のアイテムの重さはバニラと同じ。（コンテナ系統のアイテムが有利すぎる為）  
当面の間、影響の範囲はプレイヤーのみとする。（検証が大変すぎる為）  
上記の変更により、スタックして重量限界を超える重さになっても分割することで重量限界を超えない重さにして持ち運べるように。  

対策済み。→ ~~※重要※　超過状態の重荷ペナルティで受ける各種ダメージはインベントリの所持重量を参照してるらしく、バニラよりも被ダメージがかさむと思われるので注意！~~
 
上の機能だけだとただのチートMODになりかねないので付随して重量関係のルールを追加する（コンフィグ可）  
- 重量限界を種族サイズごとに補正。サイズに囚われない除外枠もあり 
	- SS・5％　S・10%　M・25%  L・50%  LL・100％ EX・200%(※暫定)
	- サイズリストの項目はコンフィグで編集可能。
	- 後天的な身長変動に対応するかどうかは今後の課題
- 重すぎるアイテムは持ち上げられない。重量限界の200％まで（デフォルト）  
  	- ※未設置のものはOK。持ち上げられるアイテムの重さは重量限界との比率で決まる。（デフォルトは200％※ﾊﾞﾆﾗでは所持重量（手持ち・装備含む）が限界重量の180％の辺りから重荷の段階が上がらなくなるため）    
	- ※共生中の相手が持ち上げをサポートしてくれる機能あり。  
- 重いものは遠くに投げられない（距離が2マス以内なら可）。重量限界の50％まで（デフォルト）。スタックされているアイテムは単体の重さを参照。  

備忘録的なもの  
- 重荷状態の時は浮遊にならないように（バニラはどうなのか）  
- SSのキャラが非浮遊状態でM以上のサイズのキャラと重なろうとすると・・・
- 競合対策・・・・・・
  
