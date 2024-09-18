---
layout: sitepage
---




[comment]: # (Insert my picture)
{% include profile.html%}

[comment]: # (Insert my resume below)

### About Me
I was born in Qufu, China. I received the B.S. and M.S. degrees in electronic science and technology from the Harbin Institute of Technology (HIT, 哈尔滨工业大学), China, in 2012 and 2015, and the Ph.D. degree in control science and engineering from Shanghai Jiao Tong University (上海交通大学), China, in 2019. I worked at HIT (深圳市物联网终端关键技术重点实验室), China from 2020-2022 and received the Outstanding Postdoc Awards of HIT Shenzhen. Since 2022, I have been an Associate Professor of Jiangnan Univerisity, Wuxi China (江南大学, 轻工过程先进控制教育部重点实验室, 中国无锡).

**My research interests**: Space engineering, Robotic systems, and Smart IoT applications. 

I have published over 100 papers, including 2 ESI 1% Highly Cited Papers (See [Publications](https://dongfangxy.github.io/publications/)), and received over 1000 citations since 2018, summarized by Google Scholar. 

I work with [Prof. Jin Wu 吴荩](https://zarathustr.github.io/) (香港科技大学HKUST)  [Prof. Chong Li 李崇](https://coe.ouc.edu.cn/2019/0819/c9094a256005/page.htm) (中国海洋大学OUC), and [Prof. Yi Jiang 姜艺](https://yijiang1992.github.io/) (东北大学) since 2018.

I am listed in **[World’s Top 2% Scientists in 2022](https://elsevier.digitalcommonsdata.com/datasets/btchxktzyw/6)**, by Stanford University and Elsevier in 2023 (**[Rank 173th in mainland China in Aerospace](https://mp.weixin.qq.com/s/rkxaO_kFjHpIWuZNl1ezEw)**).

发表学术论文100余篇，申请专利、国防专利4项，主编专著1本；主持国家自然科学基金1项，主持深圳市科技研发技术攻关重点项目子课题1项，主持中央高校基本科研计划基金1项，主持多项横向项目；参与巨星星座重点研发计划(自主导航与轨道控制技术)、深圳科技计划基础研究学科布局项目等多项其他项目。

入选斯坦福大学-爱思唯尔**全球前2%科学家名单**(2023，2024, 更新)

入选江苏省人才项目(2024年)

### Contact
- Follow me on:
    [Google Scholar](https://scholar.google.com/citations?user=oHzlz50AAAAJ&hl),
    [ResearchGate](https://www.researchgate.net/profile/Chengxi_Zhang5),
    [ORCID](https://orcid.org/0000-0002-3130-6497), 
    [Official Page](https://iot.jiangnan.edu.cn/info/1142/3595.htm),
    [CSND](https://blog.csdn.net/Paolu2022/article/details/135201277) 
- Email: dongfangxy@163.com; cxzhang@jiangnan.edu.cn 
- Key Laboratory of Advanced Control for Light Industry Processes, Ministry of Education, Jiangnan University; <br>
    School of Internet of Things Engineering, Jiangnan University, Wuxi 214122, China.
- (感知与自主机器人组)

### Academic Services
- Editorial Board, [Aerospace Systems](https://www.springer.com/journal/42401/editors) (Shanghai Jiao Tong University)
- Editorial Board, Astrodynamics (Tsinghua University)
- Editorial Board, AI and Autonomous Systems (2023-present)
- Editorial Board, [AppliedMath](https://www.mdpi.com/journal/appliedmath/editors) (2022-present) 
- Editorial Board, [IoT (Internet of Things)](https://www.mdpi.com/journal/IoT/editors) (2022-present) 
- Editorial Board, Complex Engineering Systems
- Associate Editor, Frontiers in Aerospace Engineering (2022-present) 
- Session Chair, 2022 Jiangsu Annual Conference of Automation (JACA2022, Wuxi, 2022.11.19)
- Invited Session Chair, 36th Chinese Control and Decision Conference (CCDC2024, Xi An, Invited by Prof. Hanlin Dong)
- Program Committee Member of FASTA2024, 3rd Conference on Fully Actuated System Theory and Applications, 2024, Shenzhen.
- Technical Program Committee for IEEE GEM 2024 (2024 IEEE Gaming, Entertainment, and Media Conference (GEM))
- TPC member (TPC) for ICCC'24 (2024 IEEE/CIC International Conference on Communications in China (ICCC))
- 深圳市科技创新委员会评审专家


### Honoured students
- 2024 沈天奥(院优毕设论文)、栗森茂(校优毕设论文)  


### Publications
<ul>
{% for papers in site.posts limit:10%}
{% if papers.category == "paper"%}
<li>
  {{papers.date | date: '%D'}} <a href="{{site.baseurl}}{{ papers.url }}">{{ papers.title }}</a>
  <p>{{papers.content}}</p>
</li>
{% endif %}
{% endfor %}
</ul>





<!--
<a href="mailto:dongfangxy@163.com"><span style="line-height:2;">dongfangxy@163.com</span>;  <a href="mailto:cxzhang@jiangnan.edu.cn"><span style="line-height:2;">cxzhang@jiangnan.edu.cn</span>
# Experiences
* New Position, <a href="https://dongfangxy.github.io/">New Affiliation</a>, Location, 2021-
* Post-doc Position,  <a href="https://dongfangxy.github.io/">Harbin Institute of Technology</a>, School of Electronics and Information, Shenzhen, Dec 2019 - 2021.
-->

<!--
# Education
* Ph.D., Control Science and Engineering, <a href="https://dongfangxy.github.io/">Shanghai Jiao Tong University</a>, Shanghai, Mar. 2015 - Dec. 2019. 
* M.S.,  Microelectronics and Solid State Electronics, <a href="https://dongfangxy.github.io/">Harbin Institute of Technology</a>, Shenzhen, Sep. 2012 - Jan. 2015. 
* B.S.,  Electronics Science and Technology, <a href="https://dongfangxy.github.io/">Harbin Institute of Technology</a>, Weihai, Sep. 2008 - Jun. 2012.
-->

<!--
# Other information
* Service: 
国家自然科学基金信息学部函评专家 (Correspondence Review Expert of the National Natural Science Foundation of China, from 2020), Reviewer for more than 20 journals and conferences.
* Awards：
上海交大 2019 届研究生校友班级理事(2019-2024)，哈工大深圳优秀博士后(2021)。
-->

