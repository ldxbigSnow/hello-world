# hello-world<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<style>
    .progress {
        width: 1000px;
        border-radius: 4px;
        background: #f2feff;
        padding: 50px 15px;
        width: 950px;
        margin: 0 auto;
    }

    .progress  > ul {
        width: 100%;
        position: relative;
    }

    .progress > ul:before{
        position: absolute;
        top: -23px;
        content: "";
        width: 2px;
        height: 100%;
        background: #0068b7;
        left: 50%;
    }

    .progress  ul li {
        position: relative;
        width: 100%;
        padding-bottom: 4%;
        list-style: none;
    }

    .messageTime > span {
        position: absolute;
        top: 3px;
        background: #f2feff;
        display: block;
        line-height: 40px;
        left: 43%;
    }

    .discripationContent {
        background:#f9f2f0;
        color: #8d7a7d;
        width: 300px;
        padding: 15px;
        margin-left:19%;
        word-wrap: break-word;
        font-family: 宋体;
        border-radius: 5%;
    }

    .discripationPosition {
        position: relative;
    }

    .discripationPosition:before {
        content: '';
        position: absolute;
        top: -1px;
        width: 20px;
        height: 20px;
        background:#f9f2f0;
        -webkit-transform: rotate(45deg);
        -moz-transform: rotate(45deg);
        transform: rotate(45deg);
    }

    .static {
        position: absolute;
        width: 73px;
        top: 6px;
        font-size: 12px;
    }

    .static p {
        margin: 0;
        color:#333;
    }

    .static > span {
        color: #bcb1b3;
    }
    .rightList .discripationContent {
        margin-left: 58%;
    }

    .rightList .discripationPosition:before {
        left: -9%;
    }

    .rightList .static {
        text-align: left;
        right:9%;
    }

    .leftMeassages .static {
        left: 10%;
        text-align: right;
    }

    .leftMeassages .discripationPosition:before {
        right: -23px;
    }

    .leftMeassages .messageTime > span {
        color: #a07530;
        z-index: 20;
    }

    .leftMeassages .discripationContent,
    .leftMeassages .discripationPosition:before {
        color: #fff;
        background: #18cb46;
        margin-left: 3%;
    }

    .leftMeassages .discripationPosition:before {
        box-shadow: none;
    }
</style>
<body>
<div class="progress">
    <ul>
        <li class="rightList">
            <div class="messageTime">
                <span>2011年11月30日</span>
                <div class="discripationContent">
                    <div class="discripationPosition">
                        基地成立啦
                    </div>
                </div>
            </div>
        </li>
        <li class="leftMeassages">
            <div class="messageTime">
                <span>2011年赛绩</span>
                <div class="discripationContent">
                    <div class="discripationPosition">
                        微软（MS）机器人舞台擂台赛仿真项目中获 亚军
                        <br>机器人武术擂台赛规定动作技术挑战项目获二等奖
                    </div>
                </div>
            </div>
        </li>
        <li class="rightList">
            <div class="messageTime">
                <span>2013年赛绩</span>
                <div class="discripationContent">
                    <div class="discripationPosition">
                        仿人机器人竞速比赛标准组项目获二等奖<br>
                        机器人武术擂台赛规定动作技术挑战项目获二等奖<br>
                        第八届全国信息技术应用水平大赛机械装备制造综合技能团体赛获二等奖
                    </div>
                </div>
            </div>
        </li>
        <li class="leftMeassages">
            <div class="messageTime">
                <span>2018年赛绩</span>
                <div class="discripationContent">
                    <div class="discripationPosition">
                        “天行者队“在武术擂台赛-轻量组项目获一等奖<br>
                        “快乐风男“在武术擂台赛-无差别1vs1项目获一等奖<br>
                        “怪兽队“在武术擂台赛-无差别1vs1项目获一等奖<br>
                        “志存高远队“在武术擂台赛-轻量组项目获二等奖
                    </div>
                </div>
            </div>
        </li>
    </ul>
</div>
</body>
</html>

