ENU = ν ポアソン比
EMOD = E 縦弾性係数
EG = G 横弾性係数
ELAME = λ Lame の定数

STATEV
1-6:EELAS
7-12:EPLAS
13:EQPLAS
14:FEQSTRESS
15:GEQSTRESS
16-22:STRESS
28:V4
29:FK
30:BBB
31-36:AⅠ
37-42:AⅠⅠ
41-46:ETOTAL
50:FLDW
51:SMAX
52:SMIN
53:FLDF

読み込むのは
EELAS、EPLAS、ETOTAL、AⅠ、AⅠⅠ、EQPLAS

アップデートするもの
ひずみ増分

DSTRESS...トライアルストレスとステップ開始時のステップの差分
PSTRESS...トライアルストレス
PBSTRESS...背応力コミのトライアルストレス