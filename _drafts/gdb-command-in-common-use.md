## gdb 命令语法

### 4. 命令选项

有些命令接受以减号开头的选项，例如 `print -pretty`。但是这些命令可能也会以原始输入作为参数，例如 `print` 可以

| 命令 | 说明 | 简写 | 参数/备注 | 示例 |
|-----|------|-----|----------|-----|
| RET | 重复上一个输入的命令 | “回车键” | 不能重复某些命令，如 `run` | |
| print <变量\数组名> | 打印指定的变量 | p | 打印数组时可通过 `elements` 参数指定打印个数 | `p -elements 5 -- arr` |
| 