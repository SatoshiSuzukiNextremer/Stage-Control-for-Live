# Stage Control for Live  
  
Stage Control for Live (SC4L) is an open source framework for controlling stage equipment from live.  
If you use Ableton Live as master sequencer, this framework will make the connection stronger between sound, video and light team.  
For professional use, this framework make it possible to construct safety network for backup,  
to check the network automatically, and to switch to the safety automatically when the main is not woking.
  
First, check out "Setup Example.als" in examples folder.  
  
舞台やホールでAbleton Liveを使う方へ向けたMax for Live デバイスです。  
OSCを用いて、照明と映像との同期・連携を強化します。  
  
・OSC Setting.amxd OSCネットワークの構築（メイン・セーフティの2系統）、ネットワークの監視、セーフティネットワークへの自動切り替え  
・EnvGenerator.amxd 照明や映像の輝度とオーディオの出力の同期  
・Time Adjustment 同期の際のレイテンシー補正  
・OSC-route.maxpat CNMATのものと違い、Abstractionなのでより幅広い環境で動作します。  
・Speaker_Test.maxpat スピーカーの確認・調整用。  
  
examplesフォルダの"Setup Example.als"をご確認ください。  