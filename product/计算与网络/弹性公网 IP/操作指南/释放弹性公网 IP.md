若您不再需要使用公网 IP（EIP），可在控制台将其释放，释放后将不再收取 EIP 的IP 资源费用。

## 操作场景
- **非带宽上移账户**
  对处于“未绑定，扣费中”状态中的 EIP 进行释放，停止收取 IP 资源费。
- **带宽上移账户**
 - 对处于“未绑定，扣费中”状态中的按流量计费 EIP 进行释放，停止收取 IP 资源费。
 - 对处于“未绑定”状态中的按小时带宽计费 EIP 进行释放，停止收取公网网络费用。

## 操作步骤

1. 登录 [EIP 控制台](https://console.cloud.tencent.com/cvm/eip)。
2. 在 EIP 管理页面，选择需要被释放的 EIP 的地域，并在对应 EIP 所在行的操作栏下，选择【更多】>【释放】。
3. 在弹出的“确定释放所选弹性公网IP”窗口中，勾选【确定释放以上IP】，单击【释放】。
   ![](https://main.qcloudimg.com/raw/628d18674ff0344f22ef96e28d0bc260.png)

## 后续步骤

- [找回公网 IP 地址](https://cloud.tencent.com/document/product/1199/41708)

