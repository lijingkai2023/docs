## [torch 参数更多 ]torch.rad2deg

### [torch.rad2deg](https://pytorch.org/docs/1.13/generated/torch.rad2deg.html?highlight=torch+rad2deg#torch.rad2deg)

```python
torch.rad2deg(input, *, out=None)
```

### [paddle.rad2deg](https://www.paddlepaddle.org.cn/documentation/docs/zh/api/paddle/rad2deg_cn.html)

```python
paddle.rad2deg(x, name=None)
```

其中 Pytorch 相比 Paddle 支持更多其他参数，具体如下：
### 参数映射
| PyTorch       | PaddlePaddle | 备注                                                   |
| ------------- | ------------ | ------------------------------------------------------ |
| input  | x  | 表示输入的 Tensor ，仅参数名不一致。  |
| out  | -  | 表示输出的 Tensor ， Paddle 无此参数，需要进行转写。    |


### 转写示例
#### out：指定输出
```python
# Pytorch 写法
torch.rad2deg(x, out=y)

# Paddle 写法
paddle.assign(paddle.rad2deg(x), y)
```
