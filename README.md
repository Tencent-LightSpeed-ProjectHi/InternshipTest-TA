# 特效TA 测试题
## 测试内容
使用UE5.5打开工程
使用测试工程内Content/Medhue_Squirrel/Mesh/Squirrel_Mesh，利用Niagara和蓝图，构建一个生动、高性能、可交互的松鼠集群。
![image](https://github.com/user-attachments/assets/aca83a29-0746-4b07-b7f4-da5bc4d174d1)

### 注意事项
鼓励各种形式的搜索、research，但需要在理解的基础上复用，禁止抄袭公开代码或相互抄袭。

### 基础要求
1. 可以控制Crowd的数量和分布范围
2. 松鼠可以运动在高低不平的物体表面
3. Niagara需要是GPU Simulation
4. 至少包括三种松鼠的运动状态 【待机状态 - 行走状态 - 奔跑状态】 
5. Niagara中，不能使用Skeletal Mesh与Skeletal Animation
6. 与角色交互
- 使用官方第三人称Demo角色
- 当角色靠近时，松鼠躲避角色

![image](https://github.com/user-attachments/assets/a0d4937c-6912-4ded-89f7-c02e25a6002c)


### 进阶要求	
1. 参数控制
  - 体型大小、速度快慢、交互范围
  - 动画播放速率与运动速度快慢结合
2. 更多的松鼠运动状态，与合理的切换逻辑。如
- 松鼠运动到陡坡时，切换为【爬行状态】
- 根据运动速度，自动切换【行走 - 奔跑】
- 更丰富的待机状态，松鼠可以播放不同的待机动作
3. 更丰富的交互
- 在靠近到一定区域后，玩家可以击杀松鼠
- 松鼠被击杀后，在原地播放一个特效，或掉落一个小物体


## 提交方式
- 将Content打包成zip或上传到github并设置项目为public，发送到branqian@tencent.com
- 并附上个人简历
