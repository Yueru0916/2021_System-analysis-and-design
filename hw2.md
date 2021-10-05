```graphviz
digraph{
node[shape=record];
	rankdir="LR";
  no1 [label = "研擬計畫 | 開始:第1天 | 結束:第1天 | 需時:1天"]
  no2 [label = "任務分配 | 開始:第2天 | 結束:第5天 | 需時:4天"]
  no3 [label = "取得硬體 | 開始:第2天 | 結束:第18天 | 需時:17天"]
  {rank=same;no2 no3}
  no1->no2
  no1->no3
  no4 [label = "程式開發 | 開始:第6天 | 結束:第75天 | 需時:70天"]
  no2->no4
  no5 [label = "安裝硬體 | 開始:第19天 | 結束:第28天 | 需時:10天"]
  no3->no5
  
}
'''
