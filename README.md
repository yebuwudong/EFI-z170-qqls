OpenCore-z170-qqls魔改（我的主板是微星z170a gaming m7）

如果使用的是sata固态请去掉NVRAM-7C436110-AB2A-4BBB-A880-FE41995C9F82里面的（#EnableTRIM）参数前面的#符号启用此参数以启用sata固态Trim，nvme固态不需要

机型建议使用iMac19.1机芯，我这里使用感觉表现最好，看跑分图还有待机功耗图,cpu关闭超线程超4.7g测试。

NVMeFix.kext驱动用不用随意，没问题可不用

驱动文件夹里面的IOKitPersonalitiesInjector.kext驱动是mac mini8.1 igpu电源管理优化，使用什么机型需要更改驱动里面的机型，默认的是19.1机型，用不用这个驱动随意。

九代630核显都可以用，有独显的自行更改加速id即可，usb定制,声卡id,网卡驱动,自行根据自己的硬件更改。

此EFI可能会不定时更新，也可以尝试下载以后通过OCAT升级。

此EFI支持更新到最新系统版本。

当前OpenCore版本：0.7.9

请自行添加三码 请自行添加三码 请自行添加三码 

系统预览：

<img width="622" alt="iShot2022-03-14 20 08 47" src="https://user-images.githubusercontent.com/37100815/158169546-bf74e013-e2aa-4269-87d3-59bdd5bd0680.png">

<img width="1012" alt="iShot2022-03-14 20 04 48" src="https://user-images.githubusercontent.com/37100815/158169838-a9b5d3bb-f921-438c-999d-281e9024d833.png">

<img width="1636" a<img width="1012" alt="iShot2022-03-14 20 16 03" src="https://user-images.githubusercontent.com/37100815/158170323-07126647-113a-4375-902b-967c4e62d12f.png">

<img width="939" alt="iShot2022-03-14 16 15 06" src="https://user-images.githubusercontent.com/37100815/158131813-e15d2673-4c11-4395-9b22-2de06496bacb.png">

<img width="939" alt="iShot2022-03-14 16 15 02" src="https://user-images.githubusercontent.com/37100815/158131823-b9cd20c2-c79a-4e20-abdf-7c7cece8e335.png">

<img width="843" alt="iShot2022-02-22 20 34 23" src="https://user-images.githubusercontent.com/37100815/155139792-02a43ad8-75be-45f7-9e37-0988b1c6c3f1.png">
