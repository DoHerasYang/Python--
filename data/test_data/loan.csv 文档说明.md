# loan.csv 文档说明



投资者（贷方）为借款人提供贷款，以换取利息偿还的承诺。 这意味着如果借款人偿还贷款，贷方只会赚取利润（利息）。 但是，如果他/她没有偿还贷款，那么贷款人会失去金钱。

我们将使用 LendingClub.com 使用公开的数据。 数据涵盖了2007年5月至2010年5月之间的平台资助的9,578贷款。为每位借款人提供利率。

下面是对数据集中每个特征的简短描述：

+ credit_policy：如果客户符合LendingClub.com的信用承保标准，则为1，否则为0
+ purpose：贷款的目的，如：credit_card、debt_consolidation等
+ int_rate：贷款的利率（比例
+ installment：如果贷款有资金，借款人所欠的每月分期付款 ($)。
+ log_annual_inc：借款人年收入的自然对数。
+ dti：借款人的债务收入比。
+ fico：借款人的 FICO 信用评分。
+ days_with_cr_line：借款人拥有信用额度的天数。
+ revol_bal：借款人的循环余额。
+ revol_util：借款人的循环线利用率。
+ inq_last_6mths：借款人最近6个月的债权人查询次数。
+ delinq_2yrs：借款人在过去 2 年内逾期 30 天以上的付款次数。
+ pub_rec：借款人的贬义公共记录数量。
+ not_fully_paid：表示贷款是否未全额偿还（借款人违约或借款人被认为不太可能偿还）