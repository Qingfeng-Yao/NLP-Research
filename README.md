## 中文预处理
- jieba分词、去停用词
- bert分字: 张量表示文本时会截取前512


## 问题
- 类别不均衡 | 指标 | 前两项不平衡，后两项平衡
    - lr/jieba:prec:0.9342546002924704 ; reacll:0.9467812577472936 ; f1:0.9307093833263903 ; acc:0.9467812577472936 ; auc:0.574323614632152
    - lr/bert:prec:0.9229454747425921 ; reacll:0.9415750764399636 ; f1:0.9269167210555449 ; acc:0.9415750764399636 ; auc:0.5702162151567715
    - lr/jieba:prec:0.7321850975753992 ; reacll:0.7320916905444126 ; f1:0.7320647432542002 ; acc:0.7320916905444126 ; auc:0.7320916905444126
    - lr/bert:prec:0.7009442653155228 ; reacll:0.7005730659025788 ; f1:0.7004347210043964 ; acc:0.7005730659025788 ; auc:0.7005730659025787
- 深度学习模型文本截断512
- 深度学习运行速度：gpu
- 短文本