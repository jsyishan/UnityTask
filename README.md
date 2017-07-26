#### Instruction
* WASD/方向键 控制人物移动
* Space键 控制人物攻击
* Ctrl键 使用技能

#### Tasks
* 尝试阅读并理解`Assets/Scripts`目录下的五个游戏脚本的功能（部分代码结构故意写的很乱，请理顺思路后尝试重构）
* 理解`Assets/Config`目录下的`config.json`文件的结构
    * 合理修改各项参数
    * 合理安排每批次出兵数量以及顺序
* 模仿上述json文件的格式，使用JSONObject库或Unity自带的JsonUtility将各个enemy的参数(HP，damage等)与逻辑代码分离
    * 合理修改各enemy数值
* 要求同上，把玩家人物的各项参数属性以json形式与逻辑代码分离
    * 合理修改各数值
* 修改一切可能影响游戏平衡的东西
    * 伤害碰撞(Trigger2D)检测区域的位置/大小的合理设置
    * 攻击动画帧数(即实际开始进行伤害判定帧）的合理设置
    * 使用技能时的无敌与否
    * enemy的移动方式
    * ......
* 思考游戏AI的设计
    * enemy的AI (用UML图表示)
        * 规避
        * 聚集
        * 跟随
        * ...
    * player的AI (如AUTO模式下的行为， 用UML图表示)
        * 索敌范围
        * 攻击目标的取舍
        * ...
