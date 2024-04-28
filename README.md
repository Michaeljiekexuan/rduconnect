有别于一般的用户画像系统，项目采用深度学习、知识图谱等前沿技术，挖掘学生数据，在保障数据质量和数据安全的同时，精准构建学生画像。

1.学生图书数据
    book_standard.csv的属性有
    class图书类型A->Z
    columns对应的类型中文名称

    borrow_train.csv的属性有
    id借阅该书的学生id
    time借阅该书的时间
    book借阅该书的信息
    ss该书的类型

2.学生外出数据
    dorm_train.csv的属性有
    1学生id
    2时间
    3外出还是回来，0代表回来，1代表外出

3.学生兴趣
    responses.csv的属性有
    历史:不感兴趣1-2-3-4-5非常感兴趣(整数)
    心理学:不感兴趣1-2-3-4-5非常感兴趣(整数)
    政治:不感兴趣1-2-3-4-5非常感兴趣(整数)
    数学:不感兴趣1-2-3-4-5非常感兴趣(整数)
    物理:不感兴趣1-2-3-4-5非常感兴趣(整数)
    互联网:不感兴趣1-2-3-4-5非常感兴趣(整数)
    PC软件，硬件:不感兴趣1-2-3-4-5非常感兴趣(整数)
    经济、管理:不感兴趣1-2-3-4-5非常感兴趣(整数)
    生物学:不感兴趣1-2-3-4-5非常感兴趣(整数)
    化学:不感兴趣1-2-3-4-5非常感兴趣(整数)
    诗歌阅读:不感兴趣1-2-3-4-5非常感兴趣(整数)
    地理:不感兴趣1-2-3-4-5非常感兴趣(整数)
    外语:不感兴趣1-2-3-4-5非常感兴趣(整数)
    医学:不感兴趣1-2-3-4-5非常感兴趣(整数)
    法则:不感兴趣1-2-3-4-5非常感兴趣(整数)
    美术:不感兴趣1-2-3-4-5非常感兴趣(整数)
    宗教:不感兴趣1-2-3-4-5非常感兴趣(整数)
    户外活动:不感兴趣1-2-3-4-5非常感兴趣(整数)
    舞蹈:不感兴趣1-2-3-4-5非常感兴趣(整数)
    演奏乐器:不感兴趣1-2-3-4-5非常感兴趣(整数)
    诗歌写作:不感兴趣1-2-3-4-5非常感兴趣(整数)
    体育休闲活动:不感兴趣1-2-3-4-5非常感兴趣(整数)
    竞技级体育:不感兴趣1-2-3-4-5非常感兴趣(整数)
    园艺:不感兴趣1-2-3-4-5非常感兴趣(整数)
    名人生活方式:不感兴趣1-2-3-4-5非常感兴趣(整数)
    购物:不感兴趣1-2-3-4-5非常感兴趣(整数)
    科技:不感兴趣1-2-3-4-5非常感兴趣(整数)
    戏剧:不感兴趣1-2-3-4-5非常感兴趣(整数)
    社交:不感兴趣1-2-3-4-5非常感兴趣(整数)
    肾上腺素运动:不感兴趣1-2-3-4-5非常感兴趣(整数)
    宠物:不感兴趣1-2-3-4-5非常感兴趣(整数)


    History: Not interested 1-2-3-4-5 Very interested (integer)
    Psychology: Not interested 1-2-3-4-5 Very interested (integer)
    Politics: Not interested 1-2-3-4-5 Very interested (integer)
    Mathematics: Not interested 1-2-3-4-5 Very interested (integer)
    Physics: Not interested 1-2-3-4-5 Very interested (integer)
    Internet: Not interested 1-2-3-4-5 Very interested (integer)
    PC Software, Hardware: Not interested 1-2-3-4-5 Very interested (integer)
    Economy, Management: Not interested 1-2-3-4-5 Very interested (integer)
    Biology: Not interested 1-2-3-4-5 Very interested (integer)
    Chemistry: Not interested 1-2-3-4-5 Very interested (integer)
    Poetry reading: Not interested 1-2-3-4-5 Very interested (integer)
    Geography: Not interested 1-2-3-4-5 Very interested (integer)
    Foreign languages: Not interested 1-2-3-4-5 Very interested (integer)
    Medicine: Not interested 1-2-3-4-5 Very interested (integer)
    Law: Not interested 1-2-3-4-5 Very interested (integer)
    Art: Not interested 1-2-3-4-5 Very interested (integer)
    Religion: Not interested 1-2-3-4-5 Very interested (integer)
    Outdoor activities: Not interested 1-2-3-4-5 Very interested (integer)
    Dancing: Not interested 1-2-3-4-5 Very interested (integer)
    Playing musical instruments: Not interested 1-2-3-4-5 Very interested (integer)
    Poetry writing: Not interested 1-2-3-4-5 Very interested (integer)
    Sport and leisure activities: Not interested 1-2-3-4-5 Very interested (integer)
    Sport at competitive level: Not interested 1-2-3-4-5 Very interested (integer)
    Gardening: Not interested 1-2-3-4-5 Very interested (integer)
    Celebrity lifestyle: Not interested 1-2-3-4-5 Very interested (integer)
    Shopping: Not interested 1-2-3-4-5 Very interested (integer)
    Science and technology: Not interested 1-2-3-4-5 Very interested (integer)
    Theatre: Not interested 1-2-3-4-5 Very interested (integer)
    Socializing: Not interested 1-2-3-4-5 Very interested (integer)
    Adrenaline sports: Not interested 1-2-3-4-5 Very interested (integer)
    Pets: Not interested 1-2-3-4-5 Very interested (integer)

3.学生想法
    responses.csv的属性有
    Daily events	我注意到我周围发生的事情： 非常不同意 1-2-3-4-5 非常同意（整数）
    Prioritising workload		我尽量尽快完成任务，直到最后一刻才离开。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Writing notes	我总是列出一个清单，这样我就不会忘记任何事情。 非常不同意 1-2-3-4-5 非常同意（整数）
    Workaholism	即使在业余时间，我也经常学习或工作。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Thinking ahead	在我继续之前，我会从各个不同的角度看待事物。 非常不同意 1-2-3-4-5 非常同意（整数）
    Final judgement	我相信坏人总有一天会受苦，好人会得到回报。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Reliability		我在工作中很可靠，总是完成交给我的所有任务。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Keeping promises	我总是信守诺言： 非常不同意 1-2-3-4-5 非常同意（整数）
    Loss of interest	我很快就会爱上某人，然后完全失去兴趣。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Friends versus money	我宁愿有很多朋友，也不愿有很多钱。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Funniness	Fake	我总是努力成为最有趣的一个。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Criminal damage	我过去生气时损坏了东西。 非常不同意 1-2-3-4-5 非常同意（整数）
    Decision making	我花时间做决定： 非常不同意 1-2-3-4-5 非常同意（整数）
    Elections		我总是尝试在选举中投票。 非常不同意 1-2-3-4-5 非常同意（整数）
    Self-criticism	我经常思考并后悔我所做的决定。 非常不同意 1-2-3-4-5 非常同意（整数）
    Judgment calls	当我和他们说话时，我可以判断他们是否听我说话。 非常不同意 1-2-3-4-5 非常同意（整数）
    Hypochondria	我是疑病症患者： 非常不同意 1-2-3-4-5 非常同意（整数）
    Empathy	我是有同情心的人.： 强烈不同意 1-2-3-4-5 非常同意（整数）
    Eating to survive	我吃东西是因为我必须吃。我不喜欢吃东西，吃得越快越好： 强烈不同意 1-2-3-4-5 非常同意（整数）
    Giving	我试着在圣诞节尽可能多地给别人。 非常不同意 1-2-3-4-5 非常同意（整数）
    Compassion to animals	我不喜欢看到动物受苦。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Borrowed stuff	我照顾我从别人那里借来的东西。 非常不同意 1-2-3-4-5 非常同意（整数）
    Loneliness		我在生活中感到孤独： 强烈不同意 1-2-3-4-5 非常同意（整数）
    Cheating in school	我曾经在学校作弊： 非常不同意 1-2-3-4-5 非常同意（整数）
    Health	我担心我的健康。 非常不同意 1-2-3-4-5 非常同意（整数）
    Changing the past	我希望我能因为我所做的事情而改变过去。 强烈不同意 1-2-3-4-5 非常同意（整数）
    God	I believe in God.： 强烈不同意 1-2-3-4-5 非常同意（整数）
    Dreams	我总是有好梦： 强烈不同意 1-2-3-4-5 非常同意（整数）
    Charity	我总是捐给慈善机构： 非常不同意 1-2-3-4-5 非常同意（整数）
    Number of friends		我有很多朋友： 非常不同意 1-2-3-4-5 非常同意（整数）
    Waiting	我非常有耐心。 非常不同意 1-2-3-4-5 非常同意（整数）
    New environment	我可以快速适应新环境。 非常不同意 1-2-3-4-5 非常同意（整数）
    Mood swings	我的情绪变化很快： 非常不同意 1-2-3-4-5 非常同意（整数）
    Appearence and gestures	我彬彬有礼，我照顾我的外表。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Socializing	我喜欢结识新朋友。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Achievements	我总是让别人知道我的成就。 非常不同意 1-2-3-4-5 非常同意（整数）
    Responding to a serious letter		在回答任何重要信件之前，我会仔细考虑： 非常不同意 1-2-3-4-5 非常同意（整数）
    Children	我喜欢儿童的陪伴。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Assertiveness	如果我对某事有强烈的感觉，我不怕发表我的意见。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Getting angry	我很容易生气。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Knowing the right people	我总是确保我与合适的人建立联系。 非常不同意 1-2-3-4-5 非常同意（整数）
    Public speaking	我必须在公开演讲前做好充分的准备。 非常不同意 1-2-3-4-5 非常同意（整数）
    Unpopularity	如果人们不喜欢我，我会在自己身上找到缺点。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Life struggles	当我情绪低落或事情不顺利时，我会哭泣。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Happiness in life	我对我的生活 100% 满意。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Energy levels	我总是充满活力和活力。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Small - big dogs	我更喜欢大型危险狗而不是更小、更冷静的狗。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Personality	我相信我所有的性格特征都是积极的。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Finding lost valuables	如果我发现不属于我的东西，我会把它交出来。 非常不同意 1-2-3-4-5 非常同意（整数）
    Getting up	我发现早上起床很困难： 非常不同意 1-2-3-4-5 非常同意（整数）
    Interests or hobbies	我有许多不同的爱好和兴趣。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Parents' advice	我总是听父母的建议： 非常不同意 1-2-3-4-5 非常同意（整数）
    Questionnaires or polls	我喜欢参加调查。 非常不同意 1-2-3-4-5 非常同意（整数）
    Internet usage	你花多少时间上网？： 根本没有时间 - 每天不到一个小时 - 每天几个小时 - 一天中的大部分时间（分类）
    Finances	我尽我所能存钱： 非常不同意 1-2-3-4-5 非常同意（整数）
    Shopping centres	我喜欢去大型购物中心。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Branded clothing	我更喜欢品牌服装而不是非品牌服装。 非常不同意 1-2-3-4-5 非常同意（整数）
    Entertainment spending	我在聚会和社交上花了很多钱。 非常不同意 1-2-3-4-5 非常同意（整数）
    Spending on looks	我花了很多钱在我的外表上。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Spending on gadgets	我在小工具上花了很多钱。 强烈不同意 1-2-3-4-5 非常同意（整数）
    Spending on healthy eating    我很乐意为优质、优质或健康的食物支付更多的钱。 强烈不同意 1-2-3-4-5 非常同意（整数）



    Daily events	I take notice of what goes on around me.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Prioritising workload		I try to do tasks as soon as possible and not leave them until last minute.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Writing notes	I always make a list so I don't forget anything.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Workaholism	I often study or work even in my spare time.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Thinking ahead	I look at things from all different angles before I go ahead.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Final judgement	I believe that bad people will suffer one day and good people will be rewarded.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Reliability		I am reliable at work and always complete all tasks given to me.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Keeping promises	I always keep my promises.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Loss of interest	I can fall for someone very quickly and then completely lose interest.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Friends versus money	I would rather have lots of friends than lots of money.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Funniness	Fake	I always try to be the funniest one.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Criminal damage	I damaged things in the past when angry.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Decision making	I take my time to make decisions.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Elections		I always try to vote in elections.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Self-criticism	I often think about and regret the decisions I make.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Judgment calls	I can tell if people listen to me or not when I talk to them.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Hypochondria	I am a hypochondriac.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Empathy	I am emphatetic person.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Eating to survive	I eat because I have to. I don't enjoy food and eat as fast as I can.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Giving	I try to give as much as I can to other people at Christmas.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Compassion to animals	I don't like seeing animals suffering.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Borrowed stuff	I look after things I have borrowed from others.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Loneliness		I feel lonely in life.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Cheating in school	I used to cheat at school.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Health	I worry about my health.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Changing the past	I wish I could change the past because of the things I have done.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    God	I believe in God.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Dreams	I always have good dreams.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Charity	I always give to charity.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Number of friends	I have lots of friends.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Waiting	I am very patient.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    New environment	I can quickly adapt to a new environment.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Mood swings	My moods change quickly.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Appearence and gestures	I am well mannered and I look after my appearance.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Socializing	I enjoy meeting new people.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Achievements	I always let other people know about my achievements.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Responding to a serious letter		I think carefully before answering any important letters.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Children	I enjoy childrens' company.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Assertiveness	I am not afraid to give my opinion if I feel strongly about something.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Getting angry	I can get angry very easily.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Knowing the right people	I always make sure I connect with the right people.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Public speaking	I have to be well prepared before public speaking.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Unpopularity	I will find a fault in myself if people don't like me.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Life struggles	I cry when I feel down or things don't go the right way.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Happiness in life	I am 100% happy with my life.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Energy levels	I am always full of life and energy.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Small - big dogs	 I prefer big dangerous dogs to smaller, calmer dogs.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Personality	I believe all my personality traits are positive.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Finding lost valuables	If I find something the doesn't belong to me I will hand it in.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Getting up	I find it very difficult to get up in the morning.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Interests or hobbies		I have many different hobbies and interests.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Parents' advice	I always listen to my parents' advice.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Questionnaires or polls	I enjoy taking part in surveys.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Internet usage	How much time do you spend online?: No time at all - Less than an hour a day - Few hours a day - Most of the day (categorical)
    Finances	I save all the money I can.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Shopping centres	I enjoy going to large shopping centres.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Branded clothing	I prefer branded clothing to non branded.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Entertainment spending	I spend a lot of money on partying and socializing.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Spending on looks	I spend a lot of money on my appearance.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Spending on gadgets	I spend a lot of money on gadgets.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)
    Spending on healthy eating	I will hapilly pay more money for good, quality or healthy food.: Strongly disagree 1-2-3-4-5 Strongly agree (integer)

5.学生在校表现
    competetion_name.csv
    name比赛名称
    introduce比赛介绍

    student_compete.csv
    id学生id
    time学生在校时期（一学期为单位）
    compete学生在校的比赛所获得奖
    score_exam考试得分
    score_actives操行分
    core_compete职业技能分

    student-perfrom.csv
    2 sex - student's sex (binary: "F" - female or "M" - male)
    3 age - student's age (numeric: from 15 to 22)
    4 address - student's home address type (binary: "U" - urban or "R" - rural)
    5 famsize - family size (binary: "LE3" - less or equal to 3 or "GT3" - greater than 3)
    6 Pstatus - parent's cohabitation status (binary: "T" - living together or "A" - apart)
    7 Medu - mother's education (numeric: 0 - none,  1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)
    8 Fedu - father's education (numeric: 0 - none,  1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)
    9 Mjob - mother's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other")
    10 Fjob - father's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other")
    11 reason - reason to choose this school (nominal: close to "home", school "reputation", "course" preference or "other")
    12 guardian - student's guardian (nominal: "mother", "father" or "other")
    13 traveltime - home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)
    14 studytime - weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)
    15 failures - number of past class failures (numeric: n if 1<=n<3, else 4)
    16 schoolsup - extra educational support (binary: yes or no)
    17 famsup - family educational support (binary: yes or no)
    18 paid - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)
    19 activities - extra-curricular activities (binary: yes or no)
    20 nursery - attended nursery school (binary: yes or no)
    21 higher - wants to take higher education (binary: yes or no)
    22 internet - Internet access at home (binary: yes or no)
    23 romantic - with a romantic relationship (binary: yes or no)
    24 famrel - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
    25 freetime - free time after school (numeric: from 1 - very low to 5 - very high)
    26 goout - going out with friends (numeric: from 1 - very low to 5 - very high)
    27 Dalc - workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
    28 Walc - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
    29 health - current health status (numeric: from 1 - very bad to 5 - very good)
    30 absences - number of school absences (numeric: from 0 to 93)


    sex -学生的性别(二进制:“F”-女性或“M”-男性)
    年龄-学生年龄(数字:15至22岁)
    4 .地址-学生家庭住址类型(二进制:“U”-城市或“R”-农村)
    5 famsize -家庭规模(二进制:"LE3" -小于或等于3或"GT3" -大于3)
    Pstatus -父母的同居状态(二进制:“T”-同居或“A”-分开)
    7 Medu -母亲的教育(数字:0 -没有，1 -初等教育(小学)，2 -初中，3 -中等教育或4 -高等教育)
    8 Fedu—父亲的教育(数字:0—无，1—初等教育(小学)，2—初中，3—中等教育或4—高等教育)
    9 Mjob -母亲的工作(名义上:"教师"、"工人"相关、公务员"服务"(如行政或警察)、"在家"或"其他")
    10 Fjob——父亲的工作(名义上:"教师"、"工人"相关、公务员"服务"(如行政或警察)、"在家"或"其他")
    11理由-选择这所学校的理由(名义上:接近“家”，学校“声誉”，“课程”偏好或“其他”)
    监护人-学生的监护人(名义上:“母亲”、“父亲”或“其他”)
    13旅行时间-从家到学校的旅行时间(数字:1 - <15分钟，2 - 15至30分钟，3 - 30分钟至1小时，或4 - >1小时)
    14学习时间-每周学习时间(数字:1 - <2小时，2 - 2至5小时，3 - 5至10小时，或4 - >10小时)
    15次挂科-过去挂科的次数(数字:如果1<=n<3，则为n，否则为4)
    学校支持-额外的教育支持(二进制:是或否)
    famsup—家庭教育支持(二元:是或否)
    18个付费-课程科目内的额外付费课程(二进制:是或否)
    19项活动-课外活动(二元:是或否)
    20所托儿所-就读于托儿所(二进制:是或否)
    教育——想接受更好的教育(二元:是或不是)
    22 internet -在家上网(二进制:是或否)
    浪漫——有一段浪漫的关系(二元:是或不是)
    家庭关系的质量(数字:从1 -非常差到5 -非常好)
    25 freetime -放学后的自由时间(数字:从1 -非常低到5 -非常高)
    good -和朋友出去玩(数字:从1 -非常低到5 -非常高)
    27 Dalc -工作日饮酒量(数字:从1 -非常低到5 -非常高)
    Walc -周末饮酒量(数字:从1 -非常低到5 -非常高)
    29 health -当前健康状况(数字:从1 -非常差到5 -非常好)
    30缺勤-缺勤次数(数字:从0到93)


6.学生最终信息
    all_stu_data.csv
    id    默认学号
    politics and history   喜欢政治与历史的程度
    nature	喜欢大自然和生活的程度
    arts and culture  喜欢艺术与文化的程度
    socializing	   喜欢社交的程度
    technology and computer    喜欢电子与科技的程度
    sports	喜欢运动的程度
    h_f1      最喜欢的  0：arts and culture      1：nature      2：politics and history       3：socializing       4：sports            5：technology and computer
    h_f2      齐次喜欢的  0：arts and culture      1：nature      2：politics and history       3：socializing       4：sports            5：technology and computer
    h_m1    不喜欢的  0：arts and culture      1：nature      2：politics and history       3：socializing       4：sports            5：technology and computer
    Behavioral self-control    自我行为管理程度
    Emotional self-control    自我情绪管理程度	
    religion	信仰宗教程度	
    figure	对外观的重视程度  0(差)--->(好)
    Attitude towards life	 对待生活的态度 0(差)--->(好)
    In good shape   对身体健康的重视程度  0(差)--->(好)  
    t_f1	最重视的  0：Attitude towards life          1：Behavioral self-control          2：Emotional self-control          3：In good shape         4：figure        5：religion
    t_f2	次要重视的     0：Attitude towards life          1：Behavioral self-control          2：Emotional self-control          3：In good shape         4：figure        5：religion
    t_m1	不重视的       0：Attitude towards life          1：Behavioral self-control          2：Emotional self-control          3：In good shape         4：figure        5：religion
    zi_zhu	学校资助的钱
    xuan_yuan   所在学院	
    pai_ming	综测排名
    sex	性别
    age	年龄
    address	生活的地区 （二进制：“1”-城市或“0”-农村）
    famsize	家庭成员 （二进制：“1” - 小于或等于 3 或“0” - 大于 3）
    Pstatus	父母的同居状态(二进制:“1”-同居或“0”-分开)
    Medu	母亲的教育(数字:0 -没有，1 -初等教育(小学)，2 -初中，3 -中等教育或4 -高等教育)
    Fedu	父亲的教育(数字:0—无，1—初等教育(小学)，2—初中，3—中等教育或4—高等教育)
    Mjob	母亲的工作(名义上:"教师"、"工人"(相关)、公务员"服务"(如行政或警察)、"在家"或"其他")
    Fjob	父亲的工作(名义上:"教师"、"工人"(相关)、公务员"服务"(如行政或警察)、"在家"或"其他")
    reason	选择这所学校的理由(名义上:接近“家”，学校“声誉”，“课程”偏好或“其他”)
    guardian	学生的监护人(名义上:“母亲”、“父亲”或“其他”)
    traveltime	  在外游玩时间时间(数字:1 - <15分钟，2 - 15至30分钟，3 - 30分钟至1小时，或4 - >1小时)
    studytime	每周学习时间(数字:1 - <2小时，2 - 2至5小时，3 - 5至10小时，或4 - >10小时)
    failures	过去挂科的次数(数字:如果1<=n<3，则为n，否则为4)
    schoolsup	额外的教育支持(二进制:0：是或1：否)
    famsup	家庭教育支持(二进制:1：是或0：否)
    paid	课程科目内的额外付费课程(二进制:1：是或0：否)
    activities	课外活动(二进制:1：是或0：否)
    nursery	就读过托儿所(二进制:1：是或0：否)
    higher	想接受更好的教育(二元:0：是或1：否)
    internet	经常上网(二进制:1：是或0：否)
    romantic	谈过恋爱(二进制:1：是或0：否)
    famrel	家庭关系的质量(数字:从1 -非常差到5 -非常好)
    freetime	自由时间(数字:从1 -非常低到5 -非常高)
    goout	和朋友出去玩(数字:从1 -非常低到5 -非常高)
    Dalc	饮酒量(数字:从1 -非常低到5 -非常高)
    Walc	周末饮酒量(数字:从1 -非常低到5 -非常高)
    health	当前健康状况(数字:从1 -非常差到5 -非常好)
    absences	缺勤次数(数字:从0到93)
    perdict	预测成绩的走向(1：提升或0：下降)
    score	在线教育考试统合得分
    total_study_time	全部的在线教育学习时间(一学期)
    study_frequency	在线教育每日学习频率
    joinedClassroomNum    在线教育加入的教室数量
    joinedCourseNum	在线教育学习的科目数量数量
    finishedTaskNum	在线教育完成的作业数量
    book_class  喜欢看的图书类型  
    counts	图书的借阅次数
    all_outing_counts	外出总次数(一学期)
    all_outing_time	外出总时长(一学期)
    操行分(10%）	
    课程学习综合分（60%）	
    体艺综合分（10%）	
    职业技能综合分（20%）	
    Stress Level   个人压力判断  0(好)---->3(差)


将以上所有的文件放入python根目录下的data文件夹中







安装环境要求

•操作系统：Windows 7/8/10。

•数据库：MySQL 5.7。

•开发工具：IDEA、PyCharm、Navicat Premium 16、Vscode。

•框架：Spring Boot 2.1.5、Vue 2.6。

 

安装过程

1.安装软件 python3.9、JDK1.7、Node.js v20.12、MySQL 5.7、maven

2.数据载入（将所需的数据csv文件放入指定的文件位置，在python项目中README.md中有详细介绍）

3.数据处理

3.1安装依赖库 pip install -r requirements.txt

3.2设置数据库信息

3.3运行main.py，得到模型和处理好的数据（可能时间比较长，大概5-10分钟）

4.启动后端

4.1使用maven下载依赖

4.2修改数据库配置

4.3启动Spring Boot，端口为8080

5.启动前端

5.1打开前端Vue项目，下载依赖npm install

5.2启动项目npm run serve 端口为8081