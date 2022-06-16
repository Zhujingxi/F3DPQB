# FFF 3D Printer Qulity Banchmark

## Purpose

This project is use to justify the printing quilty of your 3D printer including slicer software & printing material.

## Statement

All of the Banchmark are base on my own experience, If you have any suggestion send an issus.

## Description

This banchmark is use to help you justify the printing quilty and help you to increase your printing qulity.

## Tool you need

 1. vernier caliper
 2. flash light
 3. new printing material
 4. new 4mm nozzel
 5. new throat (optional)

# List

1. Sruface
    1. 层纹
        * 打印件“A”一号面与二号面的纹理最接近图几
    2. 震纹
        * 打印件“A”一号面与二号面的纹理最接近图几
    3. 弧线
        * 打印件“A”三号面的纹理最接近图几
    4. 疙瘩
        * 打印件“A”一号二号三号面上总共有多少个疙瘩
    5. 微小部件
        1. 小面积封顶
            1. 单个小面积封顶
                * 打印件“A”的顶部可用层数为多少
            2. 多个小面积封顶
                * 打印件“B”的顶部一共有多少层可用（从第一个损坏的之后排出）
            2. 尖顶
                1. 单个尖顶
                    * 打印件“A”的尖顶最接近图几
                2. 多个尖顶
                    * 打印件“C”中的尖顶接近图片的各有多少个
2. 精度
    1. X轴精度
        1. 外精度
            * 使用游标卡尺测量打印件”A“的X轴尺寸
        2. 内精度
            * 使用游标卡尺测量打印件”A“的X轴尺寸
    2. Y轴精度
        1. 外精度
            * 使用游标卡尺测量打印件”A“的Y轴尺寸
        2. 内精度
            * 使用游标卡尺测量打印件”A“的Y轴尺寸
    3. Z轴精度
        1. 外精度
            * 使用游标卡尺测量打印件”A“的Z轴尺寸
        2. 内精度
            * 使用游标卡尺测量打印件”A“的Z轴尺寸
    4. 大象脚
        1. x轴大象脚
            * 底部与实际值的偏差是多少（只能测试大象脚不能测试内凹（应该调整为刚好不突出））
        2. y轴大象脚
            * 底部与实际值的偏差是多少
    5. 自小分离间隙
        * 打印件可以分离的为多少
3. 搭桥
    1. 悬空表面
        * 悬空表面是否有疙瘩
    2. 下垂幅度
        * 在悬空表面中的至厚处与至薄处与标准值的差距（补偿掉Z轴的误差）
4. Support
    1. 支撑表面
        * 支撑表面剥离后的平滑度
    2. 支撑的承受面
        * 承受面剥离后的平滑度
    3. 支撑
        * 支撑的重量

## Q&A

1. Why testing 3D pirnter & Slicer software together
    * The print quality of a 3d printer is so closely related to the slicing software algorithm and settings as well as the consumables that it is difficult to test the two separately. For example, there are various scenarios that can lead to pulling, such as insufficient extruder pullback acceleration, too many slicing software paths crossing boundaries, insufficient pullback length, higher nozzle temperature than consumables, etc. Therefore, this test does not evaluate the 3d printer and slicing software separately from the consumables. 
2. Is this test still worthwhile after I replace the consumables?
    * It has some reference value. Even though there are some differences between the material produced by different manufacturers, in general, there is no great difference in print quality as long as the material type is the same (the temperature can be adjusted appropriately). Unless the poor quality, expired materials lead to plugging and bubbling, etc., there will be a significant reduction in print quality.
3. Why there isn't infill test?
    * Internal filling for 3d printing molding quality basically no substantial impact, generally only in the case of very low filling rate filling shape will have a substantial impact on the strength of the finished product, and various software for filling rate calculation is not the same, so for the time being is not set up this test.

  

## Recommended Usage

We recommend that you complete the premise of good print quality step by step to improve the print speed rather than set the print speed to improve the quality, the former can better help you understand your machine's performance ceiling, while the latter is prone to expectations exceed the limits of the machine waste a lot of time on meaningless adjustments.

## How to use test file

All files in this test are step, the files are real cruve, and will also provide high reslution stl files, but limited by the principle of stl, if you use the slicing software supports step files please try to use step for testing.
