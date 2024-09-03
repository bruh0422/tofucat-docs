# 數數字

用法 `=count`\
\
每天半夜會在[支援伺服器](https://discord.gg/X4QCqNkGWA)公布獲勝伺服器。\
\
起始數字為 `1`。\
每天半夜會結算伺服器當前的數字，以伺服器為單位給出一個排名，將依照排名來給予遊玩的玩家相等於貢獻值 (contribution) 比例的金錢，第一名到第十名的伺服器內的玩家分別共可以拿到 `10000` `9000` `8000` ... `1000` 元。\
\
相關公式如下：

$$
contribution = \frac{self\_count\_times}{current\_number}
$$

$$
earn = server\_rank\_money*contribution
$$

{% tabs %}
{% tab title="創建數數字頻道" %}
用法 `=count set`

{% hint style="info" %}
你必須有 <mark style="color:green;">管理伺服器</mark> 的權限才可執行此指令。
{% endhint %}
{% endtab %}

{% tab title="刪除數數字頻道" %}
用法 `=count delete/del`

{% hint style="info" %}
你必須有 <mark style="color:green;">管理伺服器</mark> 的權限才可執行此指令。
{% endhint %}
{% endtab %}
{% endtabs %}

