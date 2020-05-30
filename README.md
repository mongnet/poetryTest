# poetryTest
## poetry测试打包用

- 需要新建一个文件夹，文件夹名称与项目名一致，自己的代码需要放在这个新建文件夹下面

- 打包到pipy后,使用pip install 安装
>eg：pip install poetrytest

- 使用方法如下:
>from poetrytest import base<br>
if __name__ == '__main__':<br>
    print(base.generate_random_phone())