# kyorobo
共ロボ用のプログラム  
mbed-OS-6.15.0  
  
<できるようになったこと>  
・ロボマスをぶん回す  
・ロボマスからの値取得(角度取得、速度取得), 角度制御, 速度制御、、？  
・ロータリーエンコーダーからの角度取得    

<今後のための注意点>  
･**電源と基盤には必ずヒューズをかませる！！！**  
･モタドラのアドレス指定は0x01から(配線時に数字の基数が分からなくなる)  
･配線時に言う数字は2進数で統一  
･機械班には回路ボックスに余裕を持たせるように指示を  
･PS3の同時押しは極力実装しない(どうしてもの時はif文のネストで、&&を使わない)  
