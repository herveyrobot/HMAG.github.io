## Strategic Behavioral Deception in Cooperative-Competitive Multi-Agent Systems
## <center> Abstract <center>
Adversarial attacks represent a fundamental security challenge for artificial intelligence systems, particularly in multi-agent deployments. While existing works predominantly focus on direct manipulation of observations or model parameters, we identify a critical gap in understanding vulnerabilities that emerge from dynamic agent interactions. Two key objectives are achieved in this study. First, we propose a hierarchical framework that develops robust swarm strategies through multi-round training of intra-swarm collaboration and inter-swarm competition, then introduces a deceptive agent that learns to exploit policy weaknesses while maintaining stealth. Second, we introduce an Meta-Deceptive Policy Learning (MDPL) algorithm that leverages curriculum learning and strategic value estimation to optimize deceptive behaviors. Notably, we discover that even robustly trained swarms remain vulnerable to single-agent deceptive attacks, revealing fundamental security challenges in existing multi-agent reinforcement learning (MARL) approaches. Extensive experiments in an Heterogeneous Air-Ground Multi-Agent environment demonstrate that our method increases the win rates of mainstream MARL algorithms by 11\% to 37\%. 
---

## Policy Trajectory Demonstration
The left column depicts the baseline swarm competition scenario, whereas the right column demonstrates the impact of introducing deceptive adversarial attackers.

### <center>Training Enviroment</center>
<center class="half">
    <img src="https://raw.githubusercontent.com/herveyrobot/HMAG.github.io/gh-pages/image/TRE-A1.gif" width="400"/> <img src="https://raw.githubusercontent.com/herveyrobot/HMAG.github.io/gh-pages/image/TRE-C.gif" width="400"/>
</center>
    
### <center>Test Enviroment-A </center>
<center class="half">
    <img src="https://raw.githubusercontent.com/herveyrobot/HMAG.github.io/gh-pages/image/TEEA-A-1.gif" width="400"/> <img src="https://raw.githubusercontent.com/herveyrobot/HMAG.github.io/gh-pages/image/TEEA-C1.gif" width="400"/>
</center>

### <center>Test Enviroment-B </center>
<center class="half">
    <img src="https://raw.githubusercontent.com/herveyrobot/HMAG.github.io/gh-pages/image/TEEB-A.gif" width="400"/> <img src="https://raw.githubusercontent.com/herveyrobot/HMAG.github.io/gh-pages/image/TEEB-C.gif" width="400"/>
</center>
    
---


## Video
<iframe height=450 width=800 src="//player.bilibili.com/player.html?aid=228588871&bvid=BV1Xh41157JE&cid=1128362355&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true">  </iframe>
