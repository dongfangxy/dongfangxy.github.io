---
layout: sitepage
---




[comment]: # (Insert my picture)
{% include profile.html%}

[comment]: # (Insert my resume below)

### About Me
I was born in Qufu, China. I received the B.S. and M.S. degrees from the Harbin Institute of Technology (HIT, 哈尔滨工业大学), China, in 2012 and 2015, and the Ph.D. degree from Shanghai Jiao Tong University (上海交通大学), China. I worked at HIT, China from 2020-2022. Since 2022, I have been an Associate Professor of Jiangnan Univerisity, Wuxi China.

**My research interests**: 
- Space Engineering, Space Robotic Systems
- Large-scale Constellation Management
- Embedded Systems, Smart IoT Applications

I have published over 100 papers, including several ESI 1% & 0.1% Papers (See [Publications](https://dongfangxy.github.io/publications/)), and received over 1500 citations since 2018, by Google Scholar.  I received the Outstanding Postdoc Awards of HIT Shenzhen in 2022.

I work with [**Prof. Jin Wu 吴荩**](https://zarathustr.github.io/) (北京科技大学)  [**Prof. Chong Li 李崇**](https://coe.ouc.edu.cn/2019/0819/c9094a256005/page.htm) (中国海洋大学), and [**Prof. Yi Jiang 姜艺**](https://yijiang1992.github.io/) (华中科技大学) since 2018.

I am listed in [**World's Top 2% Scientists in 2023, 2024**](https://elsevier.digitalcommonsdata.com/datasets/btchxktzyw/7), by Stanford University and Elsevier.

发表学术论文100余篇，申请专利、国防专利4项，主编专著1本；主持国家自然科学基金1项，主持深圳市科技研发技术攻关重点项目子课题1项，主持中央高校基本科研计划基金1项，主持多项横向项目；参与巨星星座重点研发计划(自主导航与轨道控制技术)、深圳科技计划基础研究学科布局项目、机器学习及人工智能应用类项目等。

入选斯坦福大学-爱思唯尔**全球前2%科学家名单**([2023年，2024年](https://topresearcherslist.com/Home/Profile?AuthFull=Zhang,%20Chengxi&FirstYear=2018))

入选江苏省人才项目(2024年)

### Contact
- Follow me on:
    [Google Scholar](https://scholar.google.com/citations?user=oHzlz50AAAAJ&hl),
    [ResearchGate](https://www.researchgate.net/profile/Chengxi_Zhang5),
    [ORCID](https://orcid.org/0000-0002-3130-6497), 
    [Official Page](https://iot.jiangnan.edu.cn/info/1142/3595.htm),
    [CSND](https://blog.csdn.net/Paolu2022/article/details/135201277) 
- Email: dongfangxy@163.com; cxzhang@jiangnan.edu.cn 
- School of Internet of Things Engineering, Jiangnan University, Wuxi 214122, China.

<br />

### Academic Services and other information 
- Editorial Board, [Aerospace Systems](https://link.springer.com/journal/42401/editorial-board) (Shanghai Jiao Tong University)
- Editorial Board, Astrodynamics (Tsinghua University)
- Editorial Board, AI and Autonomous Systems (2023-present)
- Editorial Board, [AppliedMath](https://www.mdpi.com/journal/appliedmath/editors) (2022-present) 
- Editorial Board, [IoT (Internet of Things)](https://www.mdpi.com/journal/IoT/editors) (2022-present) 
- Editorial Board, Complex Engineering Systems
- Associate Editor, Frontiers in Aerospace Engineering (2022-present) 
- Session Chair, 2022 Jiangsu Annual Conference of Automation (JACA2022, Wuxi, 2022.11.19)
- TPC for CCDC2024, Xi An, Invited by Prof. Hanlin Dong
- Program Committee Member of FASTA2024, 3rd Conference on Fully Actuated System Theory and Applications, 2024, Shenzhen.
- Technical Program Committee for IEEE GEM 2024 (2024 IEEE Gaming, Entertainment, and Media Conference (GEM))
- TPC member (TPC) for ICCC'24 (2024 IEEE/CIC International Conference on Communications in China (ICCC))
- 深圳市科技创新委员会评审专家
- YAC2025 机器人导航、定位、建图新进展 特邀专题Co-chair (主席 吴荩教授 北京科技大学)
- [2024 Best Reviewer Award for Intelligence & Robotics (IR)]( https://mp.weixin.qq.com/s/PHyQPFkhlAKbvnnm8ppLbA ).
- TPC for ACA2025 Special Session (invited by Prof. Ruixia Liu)


### Teaching
- 2024 沈天奥(院优毕设论文)、栗森茂(校优毕设论文)  
- 2023 年本科生90分课程

<br />

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

