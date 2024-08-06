# room1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>demo</title>
    <style>  
        .container {  
            position: relative;  
            width: 100vw; /* 设置容器的宽度 */  
            
        }  
        .image {  
            
            height: auto; /* 自适应高度 */  
            object-fit: cover;  
            width: 100vw;  
            height: 100vh;  
        
        }  
        
        .text {  
            position: absolute;  
            top: 50%; /* 垂直居中 */  
            left: 50%; /* 水平居中 */  
            transform: translate(-50%, -50%); /* 完全居中 */  
            color: white; /* 文字颜色 */  
            font-size: 20px; /* 文字大小 */  
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7); /* 文字阴影 */  
            max-width: 100%;
        }  
        a {  
            color: rgb(255, 255, 255); /* 普通状态下的颜色 */  
            text-decoration: none; /* 去掉下划线 */  
        }  

        a:hover {  
            color: red; /* 鼠标悬停时的颜色 */  
            text-decoration: underline;
        }  

        a:visited {  
            color: rgb(255, 255, 255); /* 已访问链接的颜色 */  
        }  

        a:active {  
            color: green; /* 点击链接时的颜色 */  
        }  
        h1 {
            color: rgb(255, 255, 255);
        }
        header {
            background-color: rgb(32, 32, 32);
            width: 100%;
            border: 5px rgb(33, 33, 33) solid;
            position: relative;
        }
        section{
            background-color: rgb(0, 62, 6);
            border: 5px rgb(73, 109, 0) solid;

        }
        footer{
            background-color: blueviolet;
            margin: 30px;
            border: 5px rgb(73, 109, 0) solid;
            padding: 30px 50px;
        }
        hr{
            border-width: 1px;
        }
        header ul{
            position: relative;
            right: 5vw;;
            top: 0;
            line-height: 80px;
        }
        header li{
            display: inline;
            margin-right: 4vw;
        }
        .news{
            background-color: rgb(255, 255, 255);
            color: rgb(171, 171, 171);
            height: 85vh;
            display: flex;
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
            width: 100%;
            
        }
        p{
            font-size: 15px;
            color: rgb(205, 205, 205);
        }
        
        * {  
    margin: 0;  
    padding: 0;  
    box-sizing: border-box;  
        }

html, body {  
    height: 100%;  
}  


blockquote{
    color: rgb(198, 198, 198);
}
.slogan{
    background-color: rgb(0, 51, 22);
    color: white;
    height: 150px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 40px;
    width: 100%;
}
.alpha{
    height: 100px;
    width: 100%;
}
footer{
    background-color: rgb(0, 0, 0);
    color: rgb(169, 169, 169);
    height: 5px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 14px;
    width: 100vw;
    
}
    </style>  
</head>
<body>
    <header> <h1><em>“逸涛社区书记么么茶：“逸起有你 涛心为民，1350”工作法，齐心聚力办实事”</em></h1><hr>
        <blockquote>党的二十大报告提出，要“完善协商民主体系，统筹推进政党协商、人大协商、政府协商、政协协商、人民团体协商、基层协商以及社会组织协商，健全各种制度化协商平台，推进协商民主广泛多层制度化发展”。近些年来，为提升基层治理水平，逸涛社区自2023年4月起开展“书记么么茶”议事协商平台，探索出“‘1350’工作法，齐心聚力办实事”的基层协商议事模式，在工作中总结形成“请茶-洗茶-泡茶-分茶-品茗”五步工作法，以议事协商深化居民自治，形成内外联动、全面统合的社区治理格局。
            项目背景</blockquote>
            
       </header>
    <nav></nav>

   
    <section class="news"> <div class="container">  
        <img src="image\微信图片_20240805205714.jpg" alt="Your Image" class="image"> <!-- 替换为你的图片路径 -->  
       
        <div class="text"><a href="http://127.0.0.1:5500/demo3.html"><strong>模 式 介 绍 : 一 壶 三 杯 茶 </strong></a><br>
           <p>“书记么么茶”议事协商平台坚持问题导向，回应居民需求，探索出“一壶三杯茶”议事协商工作新模式。“一壶”即是秉持“逸起有你 涛心为民”的服务理念，党组织书记以“一壶”流动茶深入群众中间，始终围绕党建引领为民服务的主线，“三杯茶”分别指“红茶”、“绿茶”、“清茶”三种议事类型，其中，“红茶”涉及政府管理事项和基本公共服务事项、重大基础设施建设和重大民生实事等涉及区、街化解的事项，可称为社区“公事”；“绿茶”涉及居民之间的共同事务、业委会、物业企业依法履职行为规范等社区居民共同事务，可称为社区“共事”；“清茶”涉及噪音污染、邻里矛盾、家长里短等居民之间冲突，可称为社区“家事”。</p><br>
            <ul><li><a href="http://127.0.0.1:5500/demo2.html" target="_self" text-decoration: none;>请茶：收集问题</a></li>
                <p>围绕基层治理及为民服务事项，党组织书记通过协商议事平台开展调研走访、座谈交流、网络沟通等方式，多渠道收集社区居民<strong>最关心、最直接、最现实</strong>的问题，充分听取各方面意见建议。</p>
                <br><li><a href="http://127.0.0.1:5500/demo2.html" target="_self" text-decoration: none;>洗茶：确定议题</a></li>
                <p>党组织书记通过协商议事平台对收集到的意见建议进行梳理筛选和分析研判，根据协商的内容性质、影响范围等不同情况，确定议题类型，集体研究确定后将需要协商的议题以《议题报告单》、《议题情况审查单》的形式报社区党委审查。</p>
                <br><li><a href="http://127.0.0.1:5500/demo2.html" target="_self" text-decoration: none;>泡茶：开展议事</a></li>
                <p>党组织书记以“一壶”茶深入议题所涉及小区，与当事人及相关利益方“喝茶话事”，在协商中探讨解决方式和落实流程。对于“红茶”议题，需有三分之二以上的固定成员和一定数量的非固定成员参加；对于“绿茶”议题，可视情况组织部分人员进行协商；对于“清茶”议题，需要相关方人员到场，摒弃分歧，需求利益共同点。根据议题需要，可邀请相关部门或专业人士参与指导，提高协商质量。</p>
                <br><li><a href="http://127.0.0.1:5500/demo2.html" target="_self" text-decoration: none;>分茶：协商落实</a></li>
                <p>党组织书记基于协商成果形成议事纪要，提交社区党委研究，由社区居委会成立议题工作专班，整合各方资源，联动多方力量参与，积极联动议题落实所需的人力、物力、财力、政策等资源，妥善推动议题及时处置和落实。</p>
                <br><li><a href="http://127.0.0.1:5500/demo2.html" target="_self" text-decoration: none;>品茗：情况公示</a></li>
                <p>社区居委会根据议题办理落实结果，及时向社区党委反馈，对于议定事项无争议且在社区“两委”职责范围内的，通过公开透明程序迅速办理落实；对于超出社区“两委”职责范围的，社区两委及时向街道党工委、办事处反映并请求支持。同时，议事协商成果落实情况须要及时向当事人反馈，通过社区公开栏、微信公众号等方式进行公示，接受监督。</p>
        </ul>
        </div>  
        
    </div> </section>
    <section class="alpha">
<h3>经验启示</h3>

    </section>
   
    <section class="news"> <div class="container">  
        <img src="image\微信图片_20240805205736.jpg" alt="Your Image" class="image"> <!-- 替换为你的图片路径 -->  
       
        <div class="text"><a href="http://127.0.0.1:5500/demo3.html"><strong>经 验 启 示 </strong></a><br>
           
            <ul><li><a href="http://127.0.0.1:5500/demo2.html" target="_self" text-decoration: none;>
                01建设协商平台，发动群众参与是基础</a></li>
                <p>按照社区搭台主办原则，由党组织书记进行牵头，广泛吸纳多元力量参与的协商队伍，在协商出办法、出共识、出感情、出团结。</p>
                <br><li><a href="http://127.0.0.1:5500/demo2.html" target="_self" text-decoration: none;>02完善协商机制，尊重群众意见是关键</a></li>
                <p>“书记么么茶”让居民群众事情有地方反馈、有渠道协商、有资源落实。议事前，能够对议题进行分类，充分了解政策规定、实际情况和意见建议；议事中，能够确保主体平等、充分表达，邀请居民代表、利益相关方等参加，多方听取意见、达成协商共识；议事后，能够及时向社会公示、接受群众监督，确保了议题真协商、成果真落实、群众真受益。</p>
                <br><li><a href="http://127.0.0.1:5500/demo2.html" target="_self" text-decoration: none;>03营造浓厚气氛，促进社会和谐是保障</a></li>
                <p>坚持群众诉求在哪里，“书记么么茶”就去哪里的解决机制，积极拓展协商在公事、共事、家事各个具体领域延伸，“一壶三杯茶”协商化解基层治理各项“麻烦事”，激发居民群众参与协商的“主人翁”精神，让基层社区协商议事蔚然成风。</p>
        </div>  
        
    </div> </section>


   <img src="image\微信图片_20240805205743.png" alt="图片" width="100%" height="auto">
   

</body>
</html>
