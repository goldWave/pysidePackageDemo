# pysidePackageDemo
# 本文是pyside2 打包博客教程的对应demo

[Pyside2 学习系列一：创建包含ui文件的项目 （超详细的Pyside2 攻略）](https://blog.csdn.net/goldWave01/article/details/120157906) 

[Pyside2 学习系列二：PyInstaller打包项目exe （超详细的Pyside2 攻略）](https://blog.csdn.net/goldWave01/article/details/120454092)

[Pyside2 学习系列三：PyInstaller打包项目瘦身（超详细的Pyside2 攻略）](https://blog.csdn.net/goldWave01/article/details/120509125)


# 命令行步骤：

1. 创建虚拟环境： `python -m venv packenv`
2. 加载虚拟环境: `call packenv\scripts\activate.bat`
3. 添加自定义依赖： `pip3 install PySide2 PyInstaller`
4. 进行打包： `pyinstaller -w pymain.py`
