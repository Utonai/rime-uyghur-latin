# rime-uyghur-latin

基于拉丁维吾尔文输入传统维吾尔文的 [Rime](https://rime.im) 输入方案

## 用法

字母键位按照现行维吾尔文拉丁化方案安排  
其中对应拉丁维文二合字母和附标字母的字母键位为其首字母的大写  
（比如 'G' => 'gh' => 'غ'，'E' => 'ë' => 'ې'）  
元音字母的键位不包含 'ئ'，可用 'v' 输入 'ئ'  
可用 'L' 输入 'لا' 合字  
可用没有被占用的 'c' 代替 'C' 输入 'چ'

## 安装

### 手动安装

将项目中的 `uly_to_uey.schema.yaml` 文件直接放入[用户文件夹](https://github.com/rime/home/wiki/UserData)中即可

### 使用 [東風破](https://github.com/rime/plum) 安装

~~~bash
bash rime-install Utonai/rime-uyghur-latin
~~~

### [小狼毫](https://github.com/rime/weasel)安装

输入法设定 -> 获取更多输入方案… -> 输入 `Utonai/rime-uyghur-latin`
