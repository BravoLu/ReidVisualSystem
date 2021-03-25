# reid visual system

## 使用方法
1. 参考[https://github.com/BravoLu/open-VehicleReID/blob/master/evaluators/base.py](https://github.com/BravoLu/open-VehicleReID/blob/master/evaluators/base.py)#74~99行生成对应的.pkl文件。

2. 运行脚本，并指定数据集的位置
```shell
python visualize.py -data ${data_path}
```

3. 输入生成的.pkl文件，不带后缀，然后点击load键。
![pic](imgs/system_input.jpg)
![pic](imgs/system_load.jpg)


4. 可视化结果展示
![pic](imgs/example1.jpg)
![pic](imgs/example2.jpg)
![pic](imgs/example3.jpg)
![pic](imgs/example4.jpg)