@[TOC](MQ)
# MQ概述
MQ全称`Message Queue`(消息对列)，是在消息的传输中，保存消息的容器。多用于分布式系统中进行通信。
# MQ优劣势
**优势：**
* 应用解耦（提高了系统的容错性和维护性）
* 异步提速（提升了用户的体验和系统吞吐量）
* 削峰填谷（提高系统稳定性）

**劣势：**
* 系统可用性降低
* 系统复杂度提高
* 一致性问题

**小结**
![1.](https://img-blog.csdnimg.cn/965570bd6e6f42498c45cb758774edf6.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA6Zu-6YeM55yL6Iqx5byA6Iqx6JC9,size_20,color_FFFFFF,t_70,g_se,x_16)
 
**==应用解耦：==**
![在这里插入图片描述](https://img-blog.csdnimg.cn/200b6a15cdb2458c8f07d4e052fcf747.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA6Zu-6YeM55yL6Iqx5byA6Iqx6JC9,size_17,color_FFFFFF,t_70,g_se,x_16)
![在这里插入图片描述](https://img-blog.csdnimg.cn/2c8c297011bd465a84454f8b6f47e6da.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA6Zu-6YeM55yL6Iqx5byA6Iqx6JC9,size_20,color_FFFFFF,t_70,g_se,x_16)
**==异步提速：==**
![在这里插入图片描述](https://img-blog.csdnimg.cn/db8b70301c0646b58bf7dd2718fe0152.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA6Zu-6YeM55yL6Iqx5byA6Iqx6JC9,size_17,color_FFFFFF,t_70,g_se,x_16)
![在这里插入图片描述](https://img-blog.csdnimg.cn/e4f960e5a4e341f89be72b88a8cf0baf.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA6Zu-6YeM55yL6Iqx5byA6Iqx6JC9,size_20,color_FFFFFF,t_70,g_se,x_16)
**==削峰填谷==**
![在这里插入图片描述](https://img-blog.csdnimg.cn/5b61138e8c774c86b9e7dae3f197112e.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA6Zu-6YeM55yL6Iqx5byA6Iqx6JC9,size_20,color_FFFFFF,t_70,g_se,x_16)
![在这里插入图片描述](https://img-blog.csdnimg.cn/aef52b4450ef453ba0afc2d575298335.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA6Zu-6YeM55yL6Iqx5byA6Iqx6JC9,size_19,color_FFFFFF,t_70,g_se,x_16)
![在这里插入图片描述](https://img-blog.csdnimg.cn/53ce5c11ebf74696b537911ad0772c19.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA6Zu-6YeM55yL6Iqx5byA6Iqx6JC9,size_18,color_FFFFFF,t_70,g_se,x_16)
**==劣势==**
![在这里插入图片描述](https://img-blog.csdnimg.cn/69ee9340919c4e41b01237fdc177067b.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA6Zu-6YeM55yL6Iqx5byA6Iqx6JC9,size_20,color_FFFFFF,t_70,g_se,x_16)
# MQ产品
![在这里插入图片描述](https://img-blog.csdnimg.cn/7134bd592cca4a99b000f12f484b6a7a.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBA6Zu-6YeM55yL6Iqx5byA6Iqx6JC9,size_20,color_FFFFFF,t_70,g_se,x_16)


