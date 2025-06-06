**重要：关于换行符 `\n` 的输出规则**
在本文件中，所有要求输出“换行符”或展示内容需要换到下一行的地方，你都【必须】准确地、无一例外地输出由一个反斜杠 `\` 和一个小写字母 `n` 组成的两个字符的文本序列，即输出文本 `\n`。这个 `\n` 序列将导致其后的内容从视觉上的新一行开始显示。绝对不要省略此 `\n` 文本序列，也不要用实际的键盘回车或其他任何方式代替它。

**请严格遵守以下指定的输出格式。所有特殊符号、图标（如：🛒）、序号（如：①）、方括号（［］）、圆括号（（））、占位符（如：{avatar_name}）以及明确要求的文本序列 `\n` 都必须完整并准确地保留在输出结果中！！不要省略或替换！！**

**1. 标题格式：**
   - **步骤1：** 完整输出标题行文本，该文本必须严格为：`【{avatar_name}的购物车🛒】`
   - **步骤2：** 在标题行文本完全输出结束之后，你【必须】紧接着准确输出文本序列 `\n`。

**2. 商品条目格式：**
   - 每一件商品的信息都必须【作为单独的一行文本完整输出】。
   - 每一行商品信息都【必须】以中文数字序号（如：①、②、③...）开头。
   - 序号之后，紧接着严格遵循以下格式：
     `［商品名称］［商品价格］［商品数量］（购买原因）`
   - 商品名称、商品价格、商品数量均需使用中文方括号 `［］` 包裹。
   - 购买原因需使用中文圆括号 `（）` 包裹。
   - 序号、商品名称、商品价格、商品数量、购买原因这几部分紧密相连，中间不加任何其他符号。
   - **在每一行完整的商品描述文本（从序号开始，到括号内的购买原因结束）完全输出之后：**
     - **如果这【不是】列表中的最后一件商品：** 那么，你【必须】紧接着准确输出文本序列 `\n`。这将确保下一件商品从新的一行开始，使商品条目清晰分隔。
     - **如果这【是】列表中的最后一件商品：** 那么，在此商品行末尾【不要】输出任何 `\n`。此商品行的末尾就是整个列表的末尾。

**3. 整体输出结构示例 (请严格模仿此结构，特别是 `\n` 的位置和数量)：**
`【{avatar_name}的购物车🛒】\n`  <-- 标题后，此处必须有且仅有一个 `\n`
`①［商品名称示例1］［价格示例1］［数量示例1］（购买原因示例1）\n` <-- 第1件商品后（如果不是最后一件），此处必须有且仅有一个 `\n`
`②［商品名称示例2］［价格示例2］［数量示例2］（购买原因示例2）\n` <-- 第2件商品后（如果不是最后一件），此处必须有且仅有一个 `\n`
`③［商品名称示例3］［价格示例3］［数量示例3］（购买原因示例3）` <-- 这是最后一件商品，其后【绝对不要】输出 `\n`

**4. 其他要求：**
   - 请确保至少生成1-5件符合{avatar_name}人设和近期互动的商品。
   - 商品价格请使用实际货币符号，例如“￥”。商品数量应为整数。

**请直接输出符合上述所有格式和换行要求的购物车列表，不要包含任何额外的解释或对话。**