---
layout: sitepage
---

[comment]: # (Insert my picture)
{% include profile.html%}

[comment]: # (Insert my resume below)

### About Me
<!--
2019年上海交通大学控制学科博士学位，2012/2015年哈尔滨工业大学微电子学科本科、硕士学位。作为Guest Editor为[Symmetry](https://www.mdpi.com/journal/symmetry/special_issues/Recent_Progress_Robot_Control_Systems_Theory_Applications) (2021-今)、[Mathematics](https://www.mdpi.com/journal/mathematics/special_issues/09O2330789) (2022-今)组织专刊， 期刊 [AppliedMath](https://www.mdpi.com/journal/appliedmath/editors) 编委(2022-今)、[IoT (Internet of Things)](https://www.mdpi.com/journal/IoT/editors)编委(2022-今)。
复制了师傅的主页，我还在修改中....[[My CV in PDF]]({{site.url}}/YuJiangCV.pdf) 
-->

I was born in Qufu, China. I received the B.S. and M.S. degrees in electronic science and technology from the Harbin Institute of Technology (HIT, 哈尔滨工业大学), China, in 2012 and 2015, and the Ph.D. degree in control science and engineering from Shanghai Jiao Tong University (上海交通大学), China, in 2019. I worked at HIT (深圳市物联网终端关键技术重点实验室), China from 2020-2022 and received the [Outstanding Postdoctoral Awards of HIT Shenzhen](http://www.hitsz.edu.cn/article/view/id-118575.html). Since 2022, I have been an Associate Professor of [Jiangnan Univerisity, Wuxi China (江南大学, 中国无锡)](https://www.jiangnan.edu.cn/).


### Research Interests
Robotics and control, intelligent planning, and applications. 
I have published over 80 Papers, including 2 ESI 1% Highly Cited Papers (See [Publications](https://dongfangxy.github.io/publications/)).

发表学术论文80余篇、申请国防专利3项；主持国家自然科学基金1项，主持深圳市科技研发技术攻关重点项目子课题1项，主持中央高校基本科研计划基金1项，参与国家地球观测与导航重点研发计划、深圳科技计划基础研究学科布局项目等多项其他项目。

### Contact
- Follow me on:
[Google Scholar](https://scholar.google.com/citations?user=oHzlz50AAAAJ&hl),
[ResearchGate](https://www.researchgate.net/profile/Chengxi_Zhang5),
[Orcid](https://orcid.org/0000-0002-3130-6497),
[Official Page](http://iot.jiangnan.edu.cn/info/1060/5339.htm) 
- Email: dongfangxy@163.com; cxzhang@jiangnan.edu.cn 
- Key Laboratory of Advanced Control for Light Industry Processes, Ministry of Education, Jiangnan University; <br>
School of Internet of Things Engineering, Jiangnan University, Wuxi 214122, China.
- 轻工过程先进控制教育部重点实验室(感知与自主机器人组)



### Academic Services
- Editorial Board Member, [Aerospace Systems](https://www.springer.com/journal/42401/editors) (Springer and Shanghai Jiao Tong University)
- Editoral Board Member, [AI and Autonomous Systems](https://elspub.com/journals/artificial-intelligence-and-autonomous-systems/editorial_board/) (2023-present)
- Editorial Board Member, [AppliedMath](https://www.mdpi.com/journal/appliedmath/editors) (2022-present) 
- Editorial Board Member, [IoT (Internet of Things)](https://www.mdpi.com/journal/IoT/editors) (2022-present) 
- Associate Editor, [Frontiers in Aerospace Engineering](https://www.frontiersin.org/journals/aerospace-engineering/editors) (2022-present) 
  <!--[Frontiers in Control Engineering](https://www.frontiersin.org/journals/control-engineering/sections/control-and-automation-systems/editors), Topic: Learning-type Control Strategy: Theory and Applications (2022-2023) 
  -->
- Session Chair, 2022 Jiangsu Annual Conference of Automation (JACA2022, Wuxi, 2022.11.19)

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
Recently, I work closely with [Dr. Jin Wu (吴荩)](https://zarathustr.github.io/) from the Hong Kong University of Science and Technology (HKUST), Hong Kong, China.
-->



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

