interface IParking {
    // 打印输出结果
    public void print();
    // 检查是否有 carType 对应的停车位
    // 如果没有空车位，请返回 false ，否则将该车停入车位并返回 true
    public boolean addCar(int carType);
    // 解析命令行输入的参数（格式），如文档描述
public static IParams parse() throws Exception{
 	...
 };
}
