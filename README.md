# Django

regular expression:
url(r'^topivs/(?P<topic_id>\d+)/$',views.topics, name = 'topic') 
解释：
r-告诉Django将字符串作为 raw string 编译（原始字符串）
双斜线/  / 之间的内容matches and stores the integer value in topic_id 中
