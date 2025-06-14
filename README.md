<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>墨语智学 - 专业英语考试学习平台</title>
<script src="https://cdn.tailwindcss.com"></script>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
<!-- 引入Vue和导航栏 -->
<script src="https://unpkg.com/vue@3/dist/vue.global.js"></script>
<script src="nav-bar.js"></script>
<script>
tailwind.config = {
  theme: {
    extend: {
      colors: {
        primary: '#2962FF',
        secondary: '#1A237E'
      },
      borderRadius: {
        'none': '0px',
        'sm': '2px',
        DEFAULT: '4px',
        'md': '8px',
        'lg': '12px',
        'xl': '16px',
        '2xl': '20px',
        '3xl': '24px',
        'full': '9999px',
        'button': '4px'
      },
      fontFamily: {
        'sans': ['Poppins', 'sans-serif']
      }
    }
  }
}
</script>
<style>
  body {
    min-height: 1024px;
    font-family: 'Poppins', sans-serif;
  }
  .gradient-bg {
    background: linear-gradient(135deg, #F0F7FF 0%, #E3F2FF 100%);
  }
  .card-hover {
    transition: all 0.3s ease;
  }
  .card-hover:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(41, 98, 255, 0.1);
  }
  .full-width-container {
    width: 100%;
    max-width: 100%;
    padding-left: 0;
    padding-right: 0;
  }
</style>
</head>
<body class="gradient-bg">
<div id="nav-bar-container"></div>

<!-- Hero区域 - 修改为全宽 -->
<div class="relative min-h-[800px] flex items-center pt-16 full-width-container">
  <div class="absolute inset-0 overflow-hidden">
    <img src="https://ai-public.mastergo.com/ai/img_res/180994d6124d052a5f61d034a8ae86e4.jpg" class="w-full h-full object-cover opacity-90" alt="Hero Background">
  </div>
  <div class="relative z-10 max-w-4xl px-6 lg:px-12">
    <h1 class="text-5xl lg:text-7xl font-bold text-secondary mb-6 leading-tight">让英语学习<br/>更简单高效</h1>
    <p class="text-lg lg:text-xl text-gray-600 mb-8 lg:mb-12 max-w-2xl">墨语智学为你提供专业的英语四六级备考资源，智能学习规划，全程跟踪辅导，助你轻松通过考试。</p>
    <div class="flex flex-col sm:flex-row gap-4 lg:gap-6">
      <a href="墨语智学聊天.html" class="group flex items-center justify-center px-6 lg:px-8 py-3 lg:py-4 bg-primary text-white !rounded-button hover:bg-secondary transition-all duration-300">
        <span class="whitespace-nowrap font-medium text-sm lg:text-base">开始学习</span>
        <i class="fas fa-arrow-right ml-3 group-hover:translate-x-1 transition-transform"></i>
      </a>
      <a href="#" class="flex items-center justify-center px-6 lg:px-8 py-3 lg:py-4 bg-white/90 backdrop-blur-sm text-primary border-2 border-primary !rounded-button hover:bg-blue-50 transition-colors">
        <i class="fas fa-mobile-alt mr-3"></i>
        <span class="whitespace-nowrap font-medium text-sm lg:text-base">获取手机app</span>
      </a>
    </div>
    <div class="mt-12 lg:mt-16 flex flex-wrap gap-6 lg:gap-12">
      <div class="flex items-center gap-4">
        <div class="w-10 lg:w-12 h-10 lg:h-12 bg-blue-100 rounded-full flex items-center justify-center">
          <i class="fas fa-users text-primary text-lg lg:text-xl"></i>
        </div>
        <div>
          <p class="text-xl lg:text-2xl font-bold text-secondary">50万+</p>
          <p class="text-gray-600 text-sm lg:text-base">在学学员</p>
        </div>
      </div>
      <div class="flex items-center gap-4">
        <div class="w-10 lg:w-12 h-10 lg:h-12 bg-blue-100 rounded-full flex items-center justify-center">
          <i class="fas fa-graduation-cap text-primary text-lg lg:text-xl"></i>
        </div>
        <div>
          <p class="text-xl lg:text-2xl font-bold text-secondary">96%</p>
          <p class="text-gray-600 text-sm lg:text-base">通过率</p>
        </div>
      </div>
      <div class="flex items-center gap-4">
        <div class="w-10 lg:w-12 h-10 lg:h-12 bg-blue-100 rounded-full flex items-center justify-center">
          <i class="fas fa-book text-primary text-lg lg:text-xl"></i>
        </div>
        <div>
          <p class="text-xl lg:text-2xl font-bold text-secondary">2000+</p>
          <p class="text-gray-600 text-sm lg:text-base">精选课程</p>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- 特色功能 -->
<div class="px-6 lg:px-12 py-16 lg:py-24">
  <div class="text-center mb-12 lg:mb-16">
    <h2 class="text-2xl lg:text-3xl font-bold text-secondary mb-4">创新学习体验</h2>
    <p class="text-gray-600 max-w-2xl mx-auto text-sm lg:text-base">采用先进的人工智能技术，为每位学员提供个性化的学习方案，让学习更有针对性和效率。</p>
  </div>
  <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 lg:gap-8 max-w-6xl mx-auto">
    <div class="bg-white p-6 lg:p-8 rounded-xl card-hover">
      <div class="w-12 lg:w-14 h-12 lg:h-14 bg-blue-50 rounded-lg flex items-center justify-center mb-4 lg:mb-6">
        <i class="fas fa-brain text-xl lg:text-2xl text-primary"></i>
      </div>
      <h3 class="text-lg lg:text-xl font-semibold text-secondary mb-3 lg:mb-4">智能学习规划</h3>
      <p class="text-gray-600 mb-4 lg:mb-6 text-sm lg:text-base">基于AI算法，分析学习数据，为你制定个性化学习计划，精准定位知识盲点。</p>
      <a href="#" class="text-primary hover:text-secondary transition-colors flex items-center gap-2 text-sm lg:text-base">
        了解更多
        <i class="fas fa-arrow-right text-sm"></i>
      </a>
    </div>
    <div class="bg-white p-6 lg:p-8 rounded-xl card-hover">
      <div class="w-12 lg:w-14 h-12 lg:h-14 bg-blue-50 rounded-lg flex items-center justify-center mb-4 lg:mb-6">
        <i class="fas fa-headset text-xl lg:text-2xl text-primary"></i>
      </div>
      <h3 class="text-lg lg:text-xl font-semibold text-secondary mb-3 lg:mb-4">在线互动教学</h3>
      <p class="text-gray-600 mb-4 lg:mb-6 text-sm lg:text-base">资深教师实时在线答疑，小班课程互动教学，让学习更有趣更高效。</p>
      <a href="#" class="text-primary hover:text-secondary transition-colors flex items-center gap-2 text-sm lg:text-base">
        了解更多
        <i class="fas fa-arrow-right text-sm"></i>
      </a>
    </div>
    <div class="bg-white p-6 lg:p-8 rounded-xl card-hover">
      <div class="w-12 lg:w-14 h-12 lg:h-14 bg-blue-50 rounded-lg flex items-center justify-center mb-4 lg:mb-6">
        <i class="fas fa-chart-line text-xl lg:text-2xl text-primary"></i>
      </div>
      <h3 class="text-lg lg:text-xl font-semibold text-secondary mb-3 lg:mb-4">学习追踪分析</h3>
      <p class="text-gray-600 mb-4 lg:mb-6 text-sm lg:text-base">全方位记录学习数据，可视化展示学习进度，帮助你更好地把握学习节奏。</p>
      <a href="#" class="text-primary hover:text-secondary transition-colors flex items-center gap-2 text-sm lg:text-base">
        了解更多
        <i class="fas fa-arrow-right text-sm"></i>
      </a>
    </div>
  </div>
</div>

<!-- 课程体系 -->
<div class="px-6 lg:px-12 py-16 lg:py-24 bg-white">
  <div class="max-w-6xl mx-auto">
    <div class="text-center mb-12 lg:mb-16">
      <h2 class="text-2xl lg:text-3xl font-bold text-secondary mb-4">系统化课程体系</h2>
      <p class="text-gray-600 max-w-2xl mx-auto text-sm lg:text-base">科学规划的课程体系，从基础到进阶，全面提升你的英语能力。</p>
    </div>
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 lg:gap-8">
      <div class="bg-gradient-to-br from-blue-50 to-blue-100 p-5 lg:p-6 rounded-xl card-hover">
        <div class="flex justify-between items-start mb-4 lg:mb-6">
          <div class="w-10 lg:w-12 h-10 lg:h-12 bg-white rounded-lg flex items-center justify-center">
            <i class="fas fa-book text-lg lg:text-xl text-primary"></i>
          </div>
          <span class="text-primary font-medium px-2 lg:px-3 py-1 bg-white rounded-full text-xs lg:text-sm">基础课程</span>
        </div>
        <h3 class="text-base lg:text-lg font-semibold text-secondary mb-2 lg:mb-3">词汇强化</h3>
        <p class="text-gray-600 text-xs lg:text-sm mb-4 lg:mb-6">系统掌握四六级核心词汇，建立扎实的词汇基础。</p>
        <div class="flex justify-between items-center">
          <span class="text-gray-500 text-xs lg:text-sm">32 课时</span>
          <a href="#" class="w-7 lg:w-8 h-7 lg:h-8 bg-white rounded-full flex items-center justify-center text-primary hover:bg-primary hover:text-white transition-colors">
            <i class="fas fa-arrow-right text-xs lg:text-sm"></i>
          </a>
        </div>
      </div>
      <div class="bg-gradient-to-br from-blue-50 to-blue-100 p-5 lg:p-6 rounded-xl card-hover">
        <div class="flex justify-between items-start mb-4 lg:mb-6">
          <div class="w-10 lg:w-12 h-10 lg:h-12 bg-white rounded-lg flex items-center justify-center">
            <i class="fas fa-headphones text-lg lg:text-xl text-primary"></i>
          </div>
          <span class="text-primary font-medium px-2 lg:px-3 py-1 bg-white rounded-full text-xs lg:text-sm">进阶课程</span>
        </div>
        <h3 class="text-base lg:text-lg font-semibold text-secondary mb-2 lg:mb-3">听力突破</h3>
        <p class="text-gray-600 text-xs lg:text-sm mb-4 lg:mb-6">提升听力理解能力，掌握听力考试答题技巧。</p>
        <div class="flex justify-between items-center">
          <span class="text-gray-500 text-xs lg:text-sm">40 课时</span>
          <a href="#" class="w-7 lg:w-8 h-7 lg:h-8 bg-white rounded-full flex items-center justify-center text-primary hover:bg-primary hover:text-white transition-colors">
            <i class="fas fa-arrow-right text-xs lg:text-sm"></i>
          </a>
        </div>
      </div>
      <div class="bg-gradient-to-br from-blue-50 to-blue-100 p-5 lg:p-6 rounded-xl card-hover">
        <div class="flex justify-between items-start mb-4 lg:mb-6">
          <div class="w-10 lg:w-12 h-10 lg:h-12 bg-white rounded-lg flex items-center justify-center">
            <i class="fas fa-pen text-lg lg:text-xl text-primary"></i>
          </div>
          <span class="text-primary font-medium px-2 lg:px-3 py-1 bg-white rounded-full text-xs lg:text-sm">高阶课程</span>
        </div>
        <h3 class="text-base lg:text-lg font-semibold text-secondary mb-2 lg:mb-3">写作进阶</h3>
        <p class="text-gray-600 text-xs lg:text-sm mb-4 lg:mb-6">掌握写作框架与技巧，提升写作表达能力。</p>
        <div class="flex justify-between items-center">
          <span class="text-gray-500 text-xs lg:text-sm">36 课时</span>
          <a href="#" class="w-7 lg:w-8 h-7 lg:h-8 bg-white rounded-full flex items-center justify-center text-primary hover:bg-primary hover:text-white transition-colors">
            <i class="fas fa-arrow-right text-xs lg:text-sm"></i>
          </a>
        </div>
      </div>
      <div class="bg-gradient-to-br from-blue-50 to-blue-100 p-5 lg:p-6 rounded-xl card-hover">
        <div class="flex justify-between items-start mb-4 lg:mb-6">
          <div class="w-10 lg:w-12 h-10 lg:h-12 bg-white rounded-lg flex items-center justify-center">
            <i class="fas fa-file-alt text-lg lg:text-xl text-primary"></i>
          </div>
          <span class="text-primary font-medium px-2 lg:px-3 py-1 bg-white rounded-full text-xs lg:text-sm">实战课程</span>
        </div>
        <h3 class="text-base lg:text-lg font-semibold text-secondary mb-2 lg:mb-3">真题解析</h3>
        <p class="text-gray-600 text-xs lg:text-sm mb-4 lg:mb-6">详细讲解历年真题，掌握答题技巧与方法。</p>
        <div class="flex justify-between items-center">
          <span class="text-gray-500 text-xs lg:text-sm">48 课时</span>
          <a href="墨语智学真题.html" class="w-7 lg:w-8 h-7 lg:h-8 bg-white rounded-full flex items-center justify-center text-primary hover:bg-primary hover:text-white transition-colors">
            <i class="fas fa-arrow-right text-xs lg:text-sm"></i>
          </a>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- 学习效果 -->
<div class="px-6 lg:px-12 py-16 lg:py-24">
  <div class="max-w-6xl mx-auto">
    <div class="text-center mb-12 lg:mb-16">
      <h2 class="text-2xl lg:text-3xl font-bold text-secondary mb-4">学员成绩展示</h2>
      <p class="text-gray-600 max-w-2xl mx-auto text-sm lg:text-base">墨语智学学员在历次考试中均取得优异成绩，以下是部分学员的真实成绩数据。</p>
    </div>
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 lg:gap-12">
      <div class="bg-white p-6 lg:p-8 rounded-xl">
        <h3 class="text-base lg:text-lg font-semibold text-secondary mb-4 lg:mb-6">四级成绩分布</h3>
        <div id="cet4Chart" class="w-full h-[250px] lg:h-[300px]"></div>
      </div>
      <div class="bg-white p-6 lg:p-8 rounded-xl">
        <h3 class="text-base lg:text-lg font-semibold text-secondary mb-4 lg:mb-6">六级成绩分布</h3>
        <div id="cet6Chart" class="w-full h-[250px] lg:h-[300px]"></div>
      </div>
    </div>
  </div>
</div>

<!-- 学员反馈 -->
<div class="px-6 lg:px-12 py-16 lg:py-24 bg-white">
  <div class="max-w-6xl mx-auto">
    <div class="text-center mb-12 lg:mb-16">
      <h2 class="text-2xl lg:text-3xl font-bold text-secondary mb-4">学员心声</h2>
      <p class="text-gray-600 max-w-2xl mx-auto text-sm lg:text-base">来自各高校学员的真实学习体验与感受分享。</p>
    </div>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 lg:gap-8">
      <div class="bg-blue-50 p-6 lg:p-8 rounded-xl">
        <div class="flex items-center gap-3 lg:gap-4 mb-4 lg:mb-6">
          <img src="https://ai-public.mastergo.com/ai/img_res/efaf745a03925d2b26470b7edb7d3176.jpg" class="w-10 lg:w-12 h-10 lg:h-12 rounded-full" alt="Student">
          <div>
            <h4 class="font-semibold text-secondary text-sm lg:text-base">冯宝宝</h4>
            <p class="text-xs lg:text-sm text-gray-600">浙江大学 - 四级 625 分</p>
          </div>
        </div>
        <p class="text-gray-600 text-sm lg:text-base">"墨语智学的课程设计非常科学，老师讲解也很细致。通过系统学习，我的英语水平有了明显提升，最终顺利通过了四级考试。"</p>
      </div>
      <div class="bg-blue-50 p-6 lg:p-8 rounded-xl">
        <div class="flex items-center gap-3 lg:gap-4 mb-4 lg:mb-6">
          <img src="https://ai-public.mastergo.com/ai/img_res/21700f28ec7bce2baabb5bc5ca822ec9.jpg" class="w-10 lg:w-12 h-10 lg:h-12 rounded-full" alt="Student">
          <div>
            <h4 class="font-semibold text-secondary text-sm lg:text-base">张楚岚</h4>
            <p class="text-xs lg:text-sm text-gray-600">武汉大学 - 六级 598 分</p>
          </div>
        </div>
        <p class="text-gray-600 text-sm lg:text-base">"智能学习规划功能很棒，帮我找出了薄弱环节，针对性练习后成绩提升很快。感谢墨语智学，推荐给准备考试的同学们！"</p>
      </div>
      <div class="bg-blue-50 p-6 lg:p-8 rounded-xl">
        <div class="flex items-center gap-3 lg:gap-4 mb-4 lg:mb-6">
          <img src="https://ai-public.mastergo.com/ai/img_res/15e04b9aec65ba8fe1f0a6ab6b66e6cb.jpg" class="w-10 lg:w-12 h-10 lg:h-12 rounded-full" alt="Student">
          <div>
            <h4 class="font-semibold text-secondary text-sm lg:text-base">夏荷</h4>
            <p class="text-xs lg:text-sm text-gray-600">南京大学 - 六级 610 分</p>
          </div>
        </div>
        <p class="text-gray-600 text-sm lg:text-base">"在线互动课堂让学习变得很有趣，老师们都很负责任。通过墨语智学的学习，顺利通过了六级考试。"</p>
      </div>
    </div>
  </div>
</div>

<!-- 底部 -->
<footer class="bg-gray-50 px-6 lg:px-12 py-12 lg:py-16">
  <div class="max-w-6xl mx-auto">
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-5 gap-6 lg:gap-8">
      <div class="col-span-1 md:col-span-2">
        <a href="/" class="flex items-center gap-3 mb-4 lg:mb-6">
          <span class="text-primary text-xl lg:text-2xl font-bold">墨语智学</span>
        </a>
        <p class="text-gray-600 mb-4 lg:mb-6 max-w-sm text-sm lg:text-base">墨语智学致力于为大学生提供优质的英语四六级备考服务，帮助学员实现英语学习目标。</p>
        <div class="flex gap-3 lg:gap-4">
          <a href="#" class="w-8 lg:w-10 h-8 lg:h-10 bg-blue-50 rounded-full flex items-center justify-center text-primary hover:bg-primary hover:text-white transition-colors">
            <i class="fab fa-weixin text-lg lg:text-xl"></i>
          </a>
          <a href="#" class="w-8 lg:w-10 h-8 lg:h-10 bg-blue-50 rounded-full flex items-center justify-center text-primary hover:bg-primary hover:text-white transition-colors">
            <i class="fab fa-weibo text-lg lg:text-xl"></i>
          </a>
          <a href="#" class="w-8 lg:w-10 h-8 lg:h-10 bg-blue-50 rounded-full flex items-center justify-center text-primary hover:bg-primary hover:text-white transition-colors">
            <i class="fab fa-qq text-lg lg:text-xl"></i>
          </a>
        </div>
      </div>
      <div class="col-span-1">
        <h4 class="font-semibold text-secondary mb-3 lg:mb-4 text-sm lg:text-base">学习资源</h4>
        <ul class="space-y-2 lg:space-y-3">
          <li><a href="#" class="text-gray-600 hover:text-primary transition-colors text-sm lg:text-base">在线课程</a></li>
          <li><a href="墨语智学真题.html" class="text-gray-600 hover:text-primary transition-colors text-sm lg:text-base">真题解析</a></li>
          <li><a href="#" class="text-gray-600 hover:text-primary transition-colors text-sm lg:text-base">学习资料</a></li>
          <li><a href="#" class="text-gray-600 hover:text-primary transition-colors text-sm lg:text-base">备考攻略</a></li>
        </ul>
      </div>
      <div class="col-span-1">
        <h4 class="font-semibold text-secondary mb-3 lg:mb-4 text-sm lg:text-base">考试服务</h4>
        <ul class="space-y-2 lg:space-y-3">
          <li><a href="http://cet-bm.neea.edu.cn/" target="_blank" class="text-gray-600 hover:text-primary transition-colors text-sm lg:text-base">考试报名</a></li>
          <li><a href="http://cet.neea.edu.cn/cet/" target="_blank" class="text-gray-600 hover:text-primary transition-colors text-sm lg:text-base">成绩查询</a></li>
          <li><a href="#" class="text-gray-600 hover:text-primary transition-colors text-sm lg:text-base">证书办理</a></li>
          <li><a href="#" class="text-gray-600 hover:text-primary transition-colors text-sm lg:text-base">考试时间</a></li>
        </ul>
      </div>
      <div class="col-span-1">
        <h4 class="font-semibold text-secondary mb-3 lg:mb-4 text-sm lg:text-base">关于我们</h4>
        <ul class="space-y-2 lg:space-y-3">
          <li><a href="#" class="text-gray-600 hover:text-primary transition-colors text-sm lg:text-base">公司介绍</a></li>
          <li><a href="#" class="text-gray-600 hover:text-primary transition-colors text-sm lg:text-base">加入我们</a></li>
          <li><a href="#" class="text-gray-600 hover:text-primary transition-colors text-sm lg:text-base">联系方式</a></li>
          <li><a href="#" class="text-gray-600 hover:text-primary transition-colors text-sm lg:text-base">用户协议</a></li>
        </ul>
      </div>
    </div>
    <div class="mt-12 lg:mt-16 pt-6 lg:pt-8 border-t border-gray-200">
      <div class="flex flex-col md:flex-row justify-between items-center gap-4">
        <p class="text-gray-500 text-xs lg:text-sm text-center md:text-left">© 2025 墨语智学教育科技有限公司 版权所有</p>
        <div class="flex gap-4 lg:gap-8">
          <a href="#" class="text-gray-500 hover:text-primary transition-colors text-xs lg:text-sm">隐私政策</a>
          <a href="#" class="text-gray-500 hover:text-primary transition-colors text-xs lg:text-sm">服务条款</a>
          <a href="#" class="text-gray-500 hover:text-primary transition-colors text-xs lg:text-sm">免责声明</a>
        </div>
      </div>
    </div>
  </div>
</footer>

<script src="https://cdnjs.cloudflare.com/ajax/libs/echarts/5.5.0/echarts.min.js"></script>
<script>
// 四级成绩分布图表
const cet4Chart = echarts.init(document.getElementById('cet4Chart'));
cet4Chart.setOption({
  animation: false,
  color: ['#2962FF'],
  tooltip: {
    trigger: 'axis'
  },
  grid: {
    top: 10,
    right: 20,
    bottom: 30,
    left: 40,
    containLabel: true
  },
  xAxis: {
    type: 'category',
    data: ['425-450', '451-500', '501-550', '551-600', '601-625'],
    axisLine: {
      lineStyle: {
        color: '#E5E7EB'
      }
    }
  },
  yAxis: {
    type: 'value',
    name: '人数',
    axisLine: {
      show: false
    },
    splitLine: {
      lineStyle: {
        color: '#E5E7EB'
      }
    }
  },
  series: [{
    data: [120, 200, 350, 280, 150],
    type: 'bar',
    barWidth: '60%',
    itemStyle: {
      borderRadius: [4, 4, 0, 0]
    }
  }]
});

// 六级成绩分布图表
const cet6Chart = echarts.init(document.getElementById('cet6Chart'));
cet6Chart.setOption({
  animation: false,
  color: ['#1A237E'],
  tooltip: {
    trigger: 'axis'
  },
  grid: {
    top: 10,
    right: 20,
    bottom: 30,
    left: 40,
    containLabel: true
  },
  xAxis: {
    type: 'category',
    data: ['425-450', '451-500', '501-550', '551-600', '601-625'],
    axisLine: {
      lineStyle: {
        color: '#E5E7EB'
      }
    }
  },
  yAxis: {
    type: 'value',
    name: '人数',
    axisLine: {
      show: false
    },
    splitLine: {
      lineStyle: {
        color: '#E5E7EB'
      }
    }
  },
  series: [{
    data: [90, 180, 320, 250, 180],
    type: 'bar',
    barWidth: '60%',
    itemStyle: {
      borderRadius: [4, 4, 0, 0]
    }
  }]
});

// 响应式调整图表大小
window.addEventListener('resize', function() {
  cet4Chart.resize();
  cet6Chart.resize();
});
</script>
</body>
</html>
