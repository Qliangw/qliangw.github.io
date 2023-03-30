---
sort: 1
---

# notion_sync_data

{% include list.liquid all=true %}

source: `{{ page.path }}`

将豆瓣书单标记记录（看过/想看/在看）爬取下来，爬取内容包括条目标题、ISBN、、作者国家、作者/译者、原书名、书封面、出版社、出版年份、标记时间、标记状态、短评、评分、豆瓣链接，备份至数据库。

通过该数据库整理notion的个人书单。