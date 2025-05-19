# VehicleDetection
这是一个基于yolov5的车辆和牌照检测与识别程序，功能为检测车辆类型，检测是否有牌照出现
项目链接：
将待检测图片放在 myData\images 文件夹中，运行指令：

检测车辆：python detect.py --source .\myData\images --weights .\runs\train\exp4\weights\best.pt --data .\vehicle.yalm
检测牌照：python detect.py --source .\myData\images --weights .\runs\train\exp5\weights\best.pt --data .\plate.yalm

结果存储在 runs\detect\exp* 文件夹中
程序运行需要配置相关环境，否则无法运行

todo：将车辆检测结果和拍照检测结果合并显示
	  实现牌照内容识别
          制作ui