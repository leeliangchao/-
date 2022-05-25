# Some-curious-things-when-writing-paper
## subplots绘图
<link>https://blog.csdn.net/m0_38125087/article/details/106593500</link>
<link>https://wenku.baidu.com/view/9e2cd176f31dc281e53a580216fc700aba68524d.html</link>

```python
    fig = plt.figure(dpi=300, figsize=(10, 6))
    ax = fig.subplots(5,1)
    fig.supylabel("$Z /nT$", fontsize='11')
    fig.supxlabel("持续数据$t/s$", fontsize='11')
    x = np.arange(data.shape[0])
    ax[0].plot(x, data)
    ax[0].set_title("原始干扰数据", fontsize='11')
    ax[0].set_ylabel("$Z /nT$", fontsize='11')
```
