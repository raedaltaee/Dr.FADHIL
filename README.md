<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>خارطة طريق لتطوير ديوان الوقف الشيعي</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Tajawal', sans-serif;
            background-color: #f0f4f8;
        }
        .chart-container {
            position: relative;
            margin: auto;
            height: 300px;
            max-height: 350px;
            width: 100%;
            max-width: 500px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 350px;
                max-height: 400px;
            }
        }
        .flowchart-step {
            border: 2px solid #66C7E4;
            background-color: #ffffff;
            color: #0d47a1;
        }
        .flowchart-arrow {
            color: #00A1E4;
            font-size: 2rem;
            line-height: 1;
        }
        .kpi-card {
            background-color: #ffffff;
            border-right: 5px solid #00A1E4;
        }
    </style>
</head>
<body class="bg-gray-50">

    <div class="container mx-auto p-4 md:p-8">

        <header class="text-center mb-12">
            <h1 class="text-4xl md:text-5xl font-black text-[#00A1E4] mb-2">خارطة طريق لتطوير ديوان الوقف الشيعي</h1>
            <p class="text-xl text-gray-600">نحو استدامة مالية وحوكمة رشيدة</p>
        </header>

        <main class="space-y-12">

            <section id="pillar1">
                <div class="text-center mb-8">
                    <h2 class="text-3xl font-bold text-gray-800">المحور الأول: تعزيز الإيرادات وتعظيم قيمة الأوقاف</h2>
                    <p class="text-gray-500 mt-2 max-w-3xl mx-auto">الانتقال من الإدارة التقليدية إلى نهج استثماري حديث يهدف إلى تنويع مصادر الدخل ورفع الكفاءة الاستثمارية للأصول الوقفية.</p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    
                    <div class="bg-white rounded-lg shadow-lg p-6 text-center transform hover:scale-105 transition-transform duration-300">
                        <div class="text-5xl mb-4">💰</div>
                        <h3 class="text-xl font-bold text-[#00A1E4] mb-2">تأسيس صندوق استثماري</h3>
                        <p class="text-gray-600">إطلاق صندوق استثماري وقفي يعمل بأدوات حديثة (صكوك، محافظ عقارية) لتعظيم العوائد وتنويع المخاطر.</p>
                    </div>

                    <div class="bg-white rounded-lg shadow-lg p-6 text-center transform hover:scale-105 transition-transform duration-300">
                        <div class="text-5xl mb-4">💻</div>
                        <h3 class="text-xl font-bold text-[#00A1E4] mb-2">التحول الرقمي للأصول</h3>
                        <p class="text-gray-600">إنشاء قاعدة بيانات جغرافية (GIS) لتوثيق جميع الأملاك إلكترونياً وتحديد الفرص الاستثمارية الكامنة.</p>
                    </div>

                    <div class="bg-white rounded-lg shadow-lg p-6 text-center transform hover:scale-105 transition-transform duration-300">
                        <div class="text-5xl mb-4">🕌</div>
                        <h3 class="text-xl font-bold text-[#00A1E4] mb-2">تطوير السياحة الدينية</h3>
                        <p class="text-gray-600">إقامة مشاريع خدمية وثقافية في العتبات المقدسة لتوفير مصادر تمويل ذاتي مستدامة وإبراز الإرث الحضاري.</p>
                    </div>
                </div>
                
                <div class="mt-10 bg-white rounded-lg shadow-lg p-6 md:p-8">
                    <h3 class="text-2xl font-bold text-center text-gray-800 mb-2">التأثير المتوقع على تنويع الإيرادات</h3>
                    <p class="text-center text-gray-500 mb-6">يهدف المقترح إلى تقليل الاعتماد على الإيجارات التقليدية وخلق مزيج إيرادات أكثر توازناً واستدامة.</p>
                    <div class="chart-container">
                        <canvas id="revenueChart"></canvas>
                    </div>
                </div>
            </section>

            <section id="pillar2">
                <div class="text-center mb-8">
                    <h2 class="text-3xl font-bold text-gray-800">المحور الثاني: الحفاظ على الممتلكات وحوكمة الإجراءات</h2>
                    <p class="text-gray-500 mt-2 max-w-3xl mx-auto">تعزيز الإطار القانوني والتنظيمي لحماية الأصول الوقفية من التجاوز والضياع، ورفع مستوى الشفافية والمساءلة.</p>
                </div>
                
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <div class="bg-white rounded-lg shadow-lg p-6 text-center transform hover:scale-105 transition-transform duration-300">
                        <div class="text-5xl mb-4">🛡️</div>
                        <h3 class="text-xl font-bold text-[#33B4E4] mb-2">حماية قانونية استباقية</h3>
                        <p class="text-gray-600">إنشاء وحدة متخصصة لمتابعة وتسجيل الأملاك وإزالة التجاوزات بشكل وقائي قبل تفاقم النزاعات.</p>
                    </div>
                    
                    <div class="bg-white rounded-lg shadow-lg p-6 text-center transform hover:scale-105 transition-transform duration-300">
                        <div class="text-5xl mb-4">⚖️</div>
                        <h3 class="text-xl font-bold text-[#33B4E4] mb-2">إطار تنظيمي للمتولين</h3>
                        <p class="text-gray-600">إصدار لائحة تحدد معايير اختيار المتولين وآليات الرقابة عليهم لضمان حسن الإدارة والمساءلة.</p>
                    </div>

                    <div class="bg-white rounded-lg shadow-lg p-6 text-center transform hover:scale-105 transition-transform duration-300">
                        <div class="text-5xl mb-4">📄</div>
                        <h3 class="text-xl font-bold text-[#33B4E4] mb-2">تقرير الشفافية السنوي</h3>
                        <p class="text-gray-600">إصدار تقرير سنوي مفصل ومتاح للجمهور يوضح الإيرادات والمصروفات وأداء الاستثمارات لتعزيز الثقة.</p>
                    </div>
                </div>
                
                <div class="mt-10 bg-white rounded-lg shadow-lg p-6 md:p-8">
                    <h3 class="text-2xl font-bold text-center text-gray-800 mb-2">منهجية حماية الأصول المقترحة</h3>
                    <p class="text-center text-gray-500 mb-6">تمثل هذه الخريطة الإجرائية دورة العمل الاستباقية التي تضمن حماية الممتلكات الوقفية وتحويلها إلى أصول منتجة ومستدامة.</p>
                    <div class="flex flex-col items-center space-y-2">
                        <div class="flowchart-step rounded-lg p-4 w-full md:w-2/3 lg:w-1/2 text-center font-bold">تحديد وحصر الأصول</div>
                        <div class="flowchart-arrow">↓</div>
                        <div class="flowchart-step rounded-lg p-4 w-full md:w-2/3 lg:w-1/2 text-center font-bold">توثيق رقمي (GIS)</div>
                        <div class="flowchart-arrow">↓</div>
                        <div class="flowchart-step rounded-lg p-4 w-full md:w-2/3 lg:w-1/2 text-center font-bold">تحليل قانوني استباقي</div>
                        <div class="flowchart-arrow">↓</div>
                        <div class="flowchart-step rounded-lg p-4 w-full md:w-2/3 lg:w-1/2 text-center font-bold">إزالة التجاوزات والتسوية</div>
                        <div class="flowchart-arrow">↓</div>
                        <div class="bg-green-100 border-green-500 text-green-700 border-2 rounded-lg p-4 w-full md:w-2/3 lg:w-1/2 text-center font-bold">أصل محمي ومُستثمر</div>
                    </div>
                </div>
            </section>
            
            <section id="pillar3">
                <div class="text-center mb-8">
                    <h2 class="text-3xl font-bold text-gray-800">المحور الثالث: النهوض بالديوان وتطوير الأداء المؤسسي</h2>
                    <p class="text-gray-500 mt-2 max-w-3xl mx-auto">الاستثمار في العنصر البشري وتطوير الهياكل الإدارية والاستشارية لرفع كفاءة وجودة الأداء العام للمؤسسة.</p>
                </div>
                
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="bg-white rounded-lg shadow-lg p-6 text-center transform hover:scale-105 transition-transform duration-300">
                        <div class="text-5xl mb-4">🎓</div>
                        <h3 class="text-xl font-bold text-[#66C7E4] mb-2">بناء القدرات والتأهيل</h3>
                        <p class="text-gray-600">تنفيذ برامج تدريبية متخصصة في الإدارة المالية، الاستثمار، وتقنية المعلومات لرفع كفاءة الكوادر العاملة.</p>
                    </div>
                    
                    <div class="bg-white rounded-lg shadow-lg p-6 text-center transform hover:scale-105 transition-transform duration-300">
                        <div class="text-5xl mb-4">🧠</div>
                        <h3 class="text-xl font-bold text-[#66C7E4] mb-2">تفعيل المجلس الاستشاري</h3>
                        <p class="text-gray-600">الاستعانة بخبراء مستقلين في الاقتصاد والقانون والاستثمار لتقديم توصيات غير ملزمة ودعم اتخاذ القرار الاستراتيجي.</p>
                    </div>
                </div>

                <div class="mt-10 bg-white rounded-lg shadow-lg p-6 md:p-8">
                    <h3 class="text-2xl font-bold text-center text-gray-800 mb-2">مؤشرات تطوير القدرات المؤسسية</h3>
                    <p class="text-center text-gray-500 mb-6">مقارنة بين مستوى المهارات الحالي والمستهدف بعد تنفيذ برامج التأهيل والتطوير المقترحة.</p>
                    <div class="chart-container mx-auto" style="max-width: 700px;">
                        <canvas id="skillsChart"></canvas>
                    </div>
                </div>
            </section>
            
            <section id="impact">
                <div class="text-center mb-8">
                    <h2 class="text-3xl font-bold text-gray-800">الأثر الاستراتيجي المتوقع</h2>
                    <p class="text-gray-500 mt-2 max-w-3xl mx-auto">تتجسد نتائج تطبيق هذه الخارطة في تحقيق قفزات نوعية على المستويات المالية والإدارية والمؤسسية.</p>
                </div>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
                    <div class="kpi-card rounded-lg p-6 shadow-md text-center">
                        <p class="text-5xl font-black text-[#00A1E4]">+40%</p>
                        <p class="text-gray-700 font-bold mt-2">نمو متوقع في الإيرادات</p>
                    </div>
                    <div class="kpi-card rounded-lg p-6 shadow-md text-center">
                        <p class="text-5xl font-black text-[#00A1E4]">100%</p>
                        <p class="text-gray-700 font-bold mt-2">توثيق رقمي للأصول</p>
                    </div>
                     <div class="kpi-card rounded-lg p-6 shadow-md text-center">
                        <p class="text-5xl font-black text-[#00A1E4]">+60%</p>
                        <p class="text-gray-700 font-bold mt-2">كفاءة في إدارة الممتلكات</p>
                    </div>
                    <div class="kpi-card rounded-lg p-6 shadow-md text-center">
                        <p class="text-5xl font-black text-[#00A1E4]">+75%</p>
                        <p class="text-gray-700 font-bold mt-2">مستوى الشفافية والثقة</p>
                    </div>
                </div>
            </section>

        </main>
        
        <footer class="text-center mt-16 pt-8 border-t border-gray-200">
            <p class="text-gray-500 mb-4">تم إعداد هذه الوثيقة كجزء من رؤية استراتيجية لتطوير ديوان الوقف الشيعي وتحقيق أهدافه السامية.</p>
            <div class="text-sm text-gray-600">
                <p><strong>إعداد:</strong> رئيس مهندسين: رائد ابراهيم خليل ابراهيم / ماجستير هندسة اتصالات / ديوان الوقف الشيعي / دائرة أوقاف المحافظات / قسم المحافظات الجنوبية</p>
                <p><strong>إشراف:</strong> فاضل محمد رضا الشرع / دكتوراه / مدير عام دائرة أوقاف المحافظات</p>
            </div>
        </footer>

    </div>

    <script>
        function wrapLabel(label) {
            const maxLength = 16;
            if (typeof label !== 'string' || label.length <= maxLength) {
                return label;
            }
            const words = label.split(' ');
            const lines = [];
            let currentLine = '';
            for (const word of words) {
                if ((currentLine + ' ' + word).length > maxLength && currentLine.length > 0) {
                    lines.push(currentLine);
                    currentLine = word;
                } else {
                    currentLine += (currentLine.length === 0 ? '' : ' ') + word;
                }
            }
            if (currentLine.length > 0) {
                lines.push(currentLine);
            }
            return lines;
        }

        const sharedTooltipCallback = {
            plugins: {
                tooltip: {
                    callbacks: {
                        title: function(tooltipItems) {
                            const item = tooltipItems[0];
                            let label = item.chart.data.labels[item.dataIndex];
                            return Array.isArray(label) ? label.join(' ') : label;
                        }
                    }
                },
                legend: {
                    position: 'bottom',
                    labels: {
                        font: {
                            family: 'Tajawal',
                            size: 14
                        }
                    }
                }
            }
        };

        const revenueCtx = document.getElementById('revenueChart').getContext('2d');
        const revenueChart = new Chart(revenueCtx, {
            type: 'doughnut',
            data: {
                labels: ['إيجارات تقليدية', 'صندوق استثماري', 'سياحة دينية'],
                datasets: [{
                    label: 'توزيع الإيرادات',
                    data: [40, 40, 20],
                    backgroundColor: ['#99DAE4', '#33B4E4', '#00A1E4'],
                    borderColor: '#ffffff',
                    borderWidth: 3
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                ...sharedTooltipCallback
            }
        });
        
        const skillsCtx = document.getElementById('skillsChart').getContext('2d');
        const skillsChart = new Chart(skillsCtx, {
            type: 'bar',
            data: {
                labels: ['الإدارة المالية', 'الاستثمار العقاري', ['تقنية', 'المعلومات'], ['إدارة', 'المشاريع']].map(wrapLabel),
                datasets: [
                    {
                        label: 'المستوى الحالي',
                        data: [45, 50, 30, 40],
                        backgroundColor: '#99DAE4',
                        borderRadius: 5
                    },
                    {
                        label: 'المستوى المستهدف',
                        data: [90, 85, 80, 85],
                        backgroundColor: '#00A1E4',
                        borderRadius: 5
                    }
                ]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                scales: {
                    y: {
                        beginAtZero: true,
                        max: 100,
                        ticks: {
                           font: { family: 'Tajawal' }
                        }
                    },
                    x: {
                       ticks: {
                           font: { family: 'Tajawal', size: 12 }
                        }
                    }
                },
                ...sharedTooltipCallback
            }
        });
    </script>
</body>
</html>
# Dr.FADHIL
