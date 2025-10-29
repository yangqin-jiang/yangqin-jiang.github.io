<style>
.box {
  display: inline-block;
  background-color: lightgray;
}
.blue-text {
  color: blue;
}
.paper-box {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    border: 1px solid #e0e0e0;
    border-radius: 12px;
    padding: 20px;
    margin-bottom: 20px;
    background-color: #fafafa;
    transition: all 0.3s ease;
    box-shadow: 0 2px 4px rgba(0,0,0,0.05);
}

.paper-box:hover {
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    transform: translateY(-2px);
}
.paper-box-image {
    flex: 0 0 200px;
    text-align: left;
    margin-right: 20px;
}

.paper-box-image img {
    width: 200px;
    height: 200px;
    object-fit: contain;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    background-color: white;
    padding: 10px;
}

.paper-box-text {
    flex: 1;
    padding: 0;
    line-height: 1.6;
    text-align: left;
}

.paper-box-text a {
    color: #0066cc;
    text-decoration: none;
    font-weight: 500;
}

.paper-box-text a:hover {
    text-decoration: underline;
}

/* 响应式设计 */
@media (max-width: 768px) {
    .paper-box {
        flex-direction: column;
        text-align: left;
        align-items: flex-start;
    }
    
    .paper-box-image {
        flex: none;
        margin-right: 0;
        margin-bottom: 15px;
    }
    
    .paper-box-image img {
        width: 150px;
        height: 150px;
    }
    
    .paper-box-text {
        flex: none;
    }
}

@media (max-width: 480px) {
    .paper-box {
        padding: 15px;
    }
    
    .paper-box-image img {
        width: 120px;
        height: 120px;
    }
}
</style>

## 🛠️ Ongoing Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Open Source Project</div><img src='images/ai-trader.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
[AI-Trader: Can AI Beat the Market?](https://hkuds.github.io/AI-Trader/)\\ 

🌟 <a href="https://github.com/HKUDS/AI-Trader">Open Source Code</a> 🌟

</div>
</div>

# 📝 Selected Publications 

( <sup>#</sup> indicates the corresponding authorship.) 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/lightagent.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
[LightAgent: Mobile Agentic Foundation Models](https://arxiv.org/abs/2510.22009)\\
<b>Yangqin Jiang</b>, Chao Huang<sup>#</sup>.   

🌟 <a href="https://github.com/HKUDS/LightAgent">Open Source Code</a> 🌟

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025 Main</div><img src='images/recgpt.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
[RecGPT: A Foundation Model for Sequential Recommendation](https://arxiv.org/abs/2506.06270)\\
<b>Yangqin Jiang</b>, Xubin Ren, Lianghao Xia, Da Luo, Kangyi Lin, Chao Huang<sup>#</sup>.   

🌟 <a href="https://github.com/HKUDS/RecGPT">Open Source Code</a> 🌟

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025 Main</div><img src='images/reclm.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
[RecLM: Recommendation Instruction Tuning](https://arxiv.org/abs/2412.19302)\\
<b>Yangqin Jiang</b>, Yuhao Yang, Lianghao Xia, Da Luo, Kangyi Lin, Chao Huang<sup>#</sup>.   

🌟 <a href="https://github.com/HKUDS/RecLM">Open Source Code</a> 🌟

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024 Oral</div><img src='images/diffmm.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
[DiffMM: Multi-Modal Diffusion Model for Recommendation](https://arxiv.org/abs/2406.11781)\\
<b>Yangqin Jiang</b>, Lianghao Xia, Wei Wei, Da Luo, Kangyi Lin,  Chao Huang<sup>#</sup>. 
🌟 <a href="https://github.com/HKUDS/DiffMM">Open Source Code</a> 🌟

🏆 <font color="red">Best Paper Honourable Mention Award (7/1149)</font>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WSDM 2024 Oral</div><img src='images/diffkg.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
[DiffKG: Knowledge Graph Diffusion Model for Recommendation](https://arxiv.org/abs/2312.16890)\\
<b>Yangqin Jiang</b>, Yuhao Yang, Lianghao Xia, Chao Huang<sup>#</sup>.  
🌟 <a href="https://github.com/HKUDS/DiffKG">Open Source Code</a> 🌟

🏆 <font color="red">Top-11 Most Cited Paper, 11<sup>st</sup>/112</font>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGKDD 2023</div><img src='images/adagcl.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
[Adaptive Graph Contrastive Learning for Recommendation](https://arxiv.org/abs/2305.10837)\\
<b>Yangqin Jiang</b>, Chao Huang<sup>#</sup>, Lianghao Xia.  
🌟 <a href="https://github.com/HKUDS/AdaGCL">Open Source Code</a> 🌟

🏆 <font color="red">Most Influential Paper, 10<sup>th</sup>/497</font>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">VLDB 2022</div><img src='images/cssh.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
[Effective Community Search over Large Star-Schema Heterogeneous Information Networks](https://www.vldb.org/pvldb/vol15/p2307-jiang.pdf)\\
<b>Yangqin Jiang</b>, Yixiang Fang<sup>#</sup>, Chenhao Ma, Xin Cao, Chunshan Li.   
🌟 <a href="https://github.com/yangqin-jiang/CS-StarSchemaHIN">Open Source Code</a> 🌟
</div>
</div>

- <span style="color: blue; background-color: lightgray; "> SIGIR 2025 </span>[Ask and Retrieve Knowledge: Towards Proactive Asking with Imperfect Information in Medical Multi-turn Dialogues](https://dl.acm.org/doi/pdf/10.1145/3726302.3729898), Bolin Zhang, Shengwei Wang, **Yangqin Jiang**, Dianbo Sui, Zhiying Tu, Dianhui Chu. 
- <span style="color: blue; background-color: lightgray; "> WWW 2024 </span>&nbsp;[PromptMM: Multi-Modal Knowledge Distillation for Recommendation with Prompt-Tuning](https://arxiv.org/abs/2402.17188), Wei Wei, Jiabin Tang, Lianghao Xia,  **Yangqin Jiang**, Chao Huang<sup>#</sup>. 🌟 <a href="https://github.com/HKUDS/PromptMM">Open Source Code</a> 🌟
- <span style="color: blue; background-color: lightgray; "> ICWS 2021 </span>&nbsp;DGPF: A Dialogue Goal Planning Framework for Cognitive Service Conversational Bot, Bolin Zhang, Zhiying Tu, **Yangqin Jiang**, Shufan He, Guoqing Chao, Dianhui Chu, Xiaofei Xu. 

