1. 能力所限，难免在脚本中有一些符号没有匹配到，暂时写在 missing.html 文件中．
2. Unicode 中有一些上标和下标可以使用，这样子会使得 LaTeX 更加易读．相邻的上标或者下标会自动组合在一起，也可以认为是 A¹⁺² 等价于 A^{1+2}，但是 f'¹ 这样子的输入会被认为是有误的，也许可以给开发者报告 bug．这些上标和下标符号还比较少，并且 unicode-math-table.tex 中并没有对应的宏命令，所以我只能尽量找出来，可能有误，还请修正．这部分对应的码表写在 subscripts-and-superscripts.html 中．目前 unicode-math 宏包支持的上标有：A⁰¹²³⁴⁵⁶⁷⁸⁹⁺⁻⁼⁽⁾ⁱⁿZ，其中 A 和 Z 只是个分界符，方便你看到输出结果；它支持的下标有：A₀₁₂₃₄₅₆₇₈₉₊₋₌₍₎ₐₑᵢₒᵣᵤᵥₓᵦᵧᵨᵩᵪZ．也许 unicode-math 宏包更新之后会添加其他的上下标，到时候再添加．

