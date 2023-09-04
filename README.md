# WeChatKey
动态获取 windows 微信key。

依赖pymem库，支持x32 x64微信版本，目前成功率极高，暂时没发现失败过的情况。

找key方面，不要过度依赖pymem库，去搜索特征码，我发现它有问题。有能力的师傅，最好自己写一套特征码匹配算法，如sunday，kmp等。可大幅度加快搜索速度。

目前只能找key，没去适配获取微信号、微信id、手机号等信息。

在微信打开的前提下，无法判断是否已登录微信。所以找key失败，要么没登录微信，要么微信特征码已发生改变。
