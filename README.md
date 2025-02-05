# 特效TA 测试题
## 测试内容
使用测试工程内/Script/Engine.SkeletalMesh'/Game/Medhue_Squirrel/Mesh/Squirrel_Mesh.Squirrel_Mesh'，利用Niagara和蓝图，构建一个生动、高性能、可交互的松鼠集群。
![image](https://github.com/user-attachments/assets/aca83a29-0746-4b07-b7f4-da5bc4d174d1)


### 基础要求
1.可以控制Crowd的数量和分布范围
2.松鼠可以运动在高低不平的物体表面
3.Niagara需要是GPU Simulation
4.至少包括三种松鼠的运动状态 【待机状态 - 行走状态 - 奔跑状态】 
5.Niagara中，不能使用Skeletal Mesh与Skeletal Animation
6.与角色交互
a.使用官方第三人称Demo角色
b.当角色靠近时，松鼠躲避角色
![image](https://github.com/user-attachments/assets/a0d4937c-6912-4ded-89f7-c02e25a6002c)


### 进阶要求	
1.更多的松鼠运动状态，与合理的切换逻辑。如
a.松鼠运动到陡坡时，切换为【爬行状态】
b.根据运动速度，自动切换【行走 - 奔跑】
c.更丰富的待机状态
2.更丰富的交互
a.在靠近到一定区域后，玩家可以击杀松鼠
b.松鼠被击杀后，在原地播放一个特效，或掉落一个小物体




