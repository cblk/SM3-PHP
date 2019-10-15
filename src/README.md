# SM3-PHP

PHP实现的SM3加密算法，
对外提供了 `\SM3\SM3` 类，可直接对此类传参调用。

#### 命名空间目录：

- `\SM3\handler`
    加密过程中的核心算法
- `\SM3\libs`
    *动态读写配置的逻辑* 和 *一些底层的基础操作（如：按位运算）*
- `\SM3\types`
    自定义的扩展类型
- `\SM3\config.php`
    配置文件
- `\SM3\SM3`
    入口类