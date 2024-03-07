%%% title = "Extending HTTP status codes to include developer errors" abbrev = "7xxhttpcodes" category = "info" docName = "draft-barton-7xxhttpcodes-00" updates = [7231] ipr= "trust200902" area = "Internet" workgroup = "" keyword = ["http", "errors"]  

date = 2020-04-01T00:00:00Z  

[[author]] initials="J. R." surname="Barton" fullname="J. R. Barton" organization = "Railscamp" [author.address] email = "jb@johnbarton.co" %%%  

.# 抽象  
我们强烈建议以下的状态码应该出现在7XX段的HTTP状态码中。  

{主要内容}  

# 介绍
一些词之类的玩意。在[@?RFC7231]的参考，将500系列作为未知的未知状况，并将700系列作为已知的未知状况。  

# 术语  
关键字MUST, MUST NOT, REQUIRED, SHALL, SHALL NOT, SHOULD, SHOULD NOT, RECOMMENDED, MAY, 和OPTIONAL, 当它们出现在本文档内时，应被以[@?RFC2119]解释。  

# 开发者错误
## 不可解释的
701 - 好好好  
702 - Emacs  
703 - 炸了  
704 - Goto失败  
705 - 我写了这个状态码但是因为过度思考忘了验证必要性 (见795)  
706 - 你删号罢。（神之宣告）  
707 - 无法退出vi  

##  新颖性实现
710 - PHP  
711 - 便利店  
712 - NoSQL  
718 - 我不是个茶壶  
719 - Haskell  

##  边缘情况
720 - 不可能  
721 - 已知的未知  
722 - 未知的未知  
723 - 难搞  
724 - 这行代码应该是不可达  
725 - 在我的机器上能跑  
726 - 这是个feature, 不是bug  
727 - 32位就够了  
728 - 在我的时区能跑  

##  傻逼
730 - 傻逼npm  
731 - 傻逼Rubygems  
732 - 傻逼Unic💩de  
733 - 傻逼死锁  
734 - 傻逼取消引用  
736 - 傻逼条件竞争  
735 - 傻逼IE  
737 - 傻线程逼  
738 - 傻逼一次性送达  
739 - 傻逼Windows  
738 - 傻逼一次性送达  
739 - 傻逼McAfee  

##  为一般性放你妈的屁保留
74x 摸了。有脑子相信这种情况。  

##  语法错误
750 - 我妹编译！  
753 - 语法错误！  
754 - 分号太多了  
755 - 分号太少了    
756 - 不够礼貌  
757 - 忒礼貌了  
759 - 此之二之句读，未所期也。  

##  大了的开发者
761 - 嗑药下头了    
762 - 嗑嗨了  
763 - 咖啡因不足  
764 - 咖啡因过量  
765 - Railscamp  
766 - 没喝高  
767 - 喝高了  
768 - 结业周把头痛药吃成安眠药  

##  可预测问题
771 - 缓存时间过长  
772 - 缓存时间不够长  
773 - 没缓存  
774 - 这东西为什么缓存了这玩意?  
775 - 没钱了  
776 - 错误错误  
777 - 巧合  
778 - 一(1), ①个错误  
779 - 错误太多懒得数了  

##  不是我的锅
780 - 乙方鸽了  
781 - 操作员的锅  
782 - QA的锅  
783 - yysy,是客户的要求  
784 - 管理的锅，很显然  
785 - 妹发测试文档  
786 - 现在试试  
787 - 需要更多经费  
788 - 设计师的最后设计不是这  
789 - 不是我的部门  

##  因特网崩溃
791 - 因特网被DMCA  
792 - 气候变更导致的灾难性天气事件  
793 - 丧尸末世  
794 - 有人把PHP正则放在REPL正则附近  
795 - # 心脏流血 （见705）  
796 - 我不好说，应该是傻逼DNS崩了  
797 - 这是因特网的最后一页，点击这里返回上一页。  
798 - 我检查了数据库备份cupboard,但是cupboard是空的  
799 - 世界末日  

{backmatter}  

# 提及  
Railscamp人员，github发布者，之类  
