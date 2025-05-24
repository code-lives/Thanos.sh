<!-- 

Fork and tell your story here, then PR. 
EXAMPLE:

## Title: 从删库到跑路

Author: example mail@example.com

…

-->
## I erased a big bank's account data

Author: hotvulcan hotvulcan@gmail.com

Many years ago, I got a project from a big unit (something like a company, but belonging to the state of China) in China. That included an interface to a big bank's front machine. It was early years, and information security was not as serious as it is today. So they put me in a small chamber and gave me access to that front. The project was not officially online but had some transactions already — some hundreds of thousands CNY a day.

It was the end of month, and I had to remove the test data so they could do the settlement. The SQL was something like `delete from journals where done_by = 'example';`.  I had worked 36+ hours, got very tired, and typoed it as `delete from journals ; where done_by 'example'`. And, the journals were gone. 

I was frozen, as I perceived it, for about ten years. Eventually, I started to ponder. Most information was available from other tables, but that day's journal data were helplessly lost. However, the project was still in debug mode, so I still had enough logs to re-calculate that data. I wrote a Perl script and the data was restored. Fortunately, I didn't have to go to jail or run for my life...

_P.S._ "Some hundreds of thousands CNY" could buy a big apartment in Beijing or 200~300 ounces of gold in that year. 

## 差点代码没有了

Author: code-lives 948870149@qq.com

当时入职一家公司，当时接手的项目，非常的nice，上线就是ftp直接覆盖～😂，刚接手没什么时间优化，有一次ssh连接测试和正式环境，需要去`rm`缓存日志，`rm -rf *`，嗯 没毛病～。继续输入`ls`，error..... 什么👻，啥命令也不对了。一看上面命令行，刺激啊，在根目录执行的😂。瞬间头皮发麻，完啦！要倒霉了！立即访问正式项目！咦，能访问。一看ssh操上面的连接是测试环境，立马舒了口气！马不停蹄的把测试环境初始化、安装环境、部署代码。

当时上面注册了几千个律师，投入了500W。。。。。。。



## PR your story here 
Fork and tell your story here, then PR. 
EXAMPLE:

 ## Title: 从删库到跑路

Author: example mail@example.com

…
