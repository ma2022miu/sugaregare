# sugaregare
<!DOCTYPE html>
<html lang="ja">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>須賀オンライン塾 レガーレ - 小・中・高・大学受験・英検対策</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&family=Noto+Sans+JP:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="icon" href="塾のアイコン.png">

    <style>
        body {
            font-family: 'Noto Sans JP', 'Inter', sans-serif;
        }
        .hero-bg {
            background-image: url("background.png");
            background-size: cover;
            background-position: bottom;
        }
        .header-background {
            background-image: url("background.png");
            background-size: cover;
            background-position: bottom;
        }
        .tab-active {
            color: #fbbf24; /* text-amber-400 */
            border-bottom: 2px solid #fbbf24;
            font-weight: 700;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <header class="header-background shadow-md sticky top-0 z-50">
        <div class="bg-amber-800 bg-opacity-75">
        <nav class="container mx-auto px-6 py-3 flex justify-between items-center">
                <a href="#" class="text-xl sm:text-2xl font-bold text-white">須賀オンライン塾 <span class="text-amber-400">レガーレ</span></a>
                <div id="main-nav" class="hidden md:flex space-x-8 items-center">
                    <a href="#" class="nav-link text-gray-200 pb-1 hover:text-white" data-tab="home">Home</a>
                    <a href="#" class="nav-link text-gray-200 pb-1 hover:text-white" data-tab="features">選ばれる理由</a>
                    <a href="#" class="nav-link text-gray-200 pb-1 hover:text-white" data-tab="courses">コース・料金</a>
                    <a href="#" class="nav-link text-gray-200 pb-1 hover:text-white" data-tab="flow">受講の流れ</a>
                    <a href="#" class="nav-link text-gray-200 pb-1 hover:text-white" data-tab="information">Information</a>
                    <a href="#" class="nav-link text-gray-200 pb-1 hover:text-white" data-tab="faq">よくある質問</a>
                </div>
                 <a href="javascript:void(0);" class="open-modal-button hidden md:block bg-amber-500 text-white font-bold py-2 px-4 rounded-lg hover:bg-amber-600 transition-colors">無料体験はこちら</a>
                <div class="md:hidden">
                    <button id="mobile-menu-button" class="text-white focus:outline-none">
                        <i class="fas fa-bars fa-lg"></i>
                    </button>
                </div>
            </nav>
            <div id="mobile-menu" class="hidden md:hidden bg-gray-800 bg-opacity-90 py-2">
                <a href="#" class="nav-link-mobile block px-6 py-2 text-gray-200 hover:bg-gray-700" data-tab="home">Home</a>
                <a href="#" class="nav-link-mobile block px-6 py-2 text-gray-200 hover:bg-gray-700" data-tab="features">選ばれる理由</a>
                <a href="#" class="nav-link-mobile block px-6 py-2 text-gray-200 hover:bg-gray-700" data-tab="courses">コース・料金</a>
                <a href="#" class="nav-link-mobile block px-6 py-2 text-gray-200 hover:bg-gray-700" data-tab="flow">受講の流れ</a>
                <a href="#" class="nav-link-mobile block px-6 py-2 text-gray-200 hover:bg-gray-700" data-tab="information">Information</a>
                <a href="#" class="nav-link-mobile block px-6 py-2 text-gray-200 hover:bg-gray-700" data-tab="faq">よくある質問</a>
                <a href="javascript:void(0);" class="open-modal-button block mx-4 my-2 text-center bg-amber-500 text-white font-bold py-2 px-4 rounded-lg hover:bg-amber-600 transition-colors">無料体験はこちら</a>
            </div>
        </div>
    </header>
    <main>
        <div id="tab-content-home" class="tab-content">
            <section class="hero-bg text-white">
                <div class="bg-black bg-opacity-50 min-h-[60vh] flex items-center">
                    <div class="container mx-auto px-6 text-center">
                        <h1 class="text-5xl md:text-6xl font-bold mb-4 tracking-wider">レガーレ</h1>
                        <p class="text-lg md:text-2xl mb-8">知識と未来をつなぐ。全国どこからでも、質の高い教育をあなたに。</p>
                        <a href="javascript:void(0);" class="open-modal-button bg-amber-500 text-white font-bold py-4 px-8 rounded-full text-lg hover:bg-amber-600 transition-transform transform hover:scale-105 inline-block">
                            <i class="fas fa-rocket mr-2"></i>まずは2週間の無料体験から
                        </a>
                    </div>
                </div>
            </section>
            <section id="director" class="py-16 bg-white">
                <div class="container mx-auto px-6">
                    <h2 class="text-3xl font-bold text-center mb-12">教室長紹介</h2>
                    <div class="bg-gray-50 rounded-lg shadow-xl p-8 flex flex-col md:flex-row items-center gap-8 md:gap-12">
                        <div class="md:w-1/3 text-center">
                            <img src="suga.jpg" alt="教室長 須賀 將太" class="rounded-full w-48 h-48 mx-auto shadow-lg object-cover">
                            <h3 class="text-xl font-bold mt-4">教室長 須賀 將太</h3>
                            <p class="text-cyan-600 font-semibold">Shota Suga</p>

                            <div class="mt-4 space-y-2">
                                <a href="https://www.instagram.com/sugajuku/" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center w-40 px-4 py-2 rounded-lg text-white bg-pink-600 hover:bg-pink-700 transition-colors shadow-sm">
                                    <i class="fab fa-instagram fa-lg mr-2"></i>
                                    <span>Instagram</span>
                                </a>

                                <a href="https://www.facebook.com/61578401284432/" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center w-40 px-4 py-2 rounded-lg text-white bg-blue-600 hover:bg-blue-700 transition-colors shadow-sm">
                                    <i class="fab fa-facebook fa-lg mr-2"></i>
                                    <span>Facebook</span>
                                </a>

                                    </div>

                        </div>
                        <div class="md:w-2/3">
                            <h4 class="text-xl font-bold text-cyan-700 mb-3">「わかる」喜びが、君を未来へ「つなぐ」。</h4>
                            <p class="text-gray-600 mb-4 text-base leading-relaxed">
                                はじめまして。教室長の須賀です。私自身、塾講師の経験を通し、教えることの難しさも、目標を達成した時の喜びも知っています。大学在学中に公認会計士試験に合格できたのは、物事を論理的に考え、効率的に学習する「型」を身につけられたからに他なりません。<br>
                                勉強は、決して暗記だけではありません。なぜそうなるのかを理解し、知識を繋げていくことで、世界は一気に面白くなります。私たちは、その「わかる」喜びを一人ひとりに届けたい。そして、その成功体験を通じて、自信を持って自分の未来を切り拓く力を育んでほしいと願っています。<br>
                                あなたの挑戦を、全力でサポートします。一緒に頑張りましょう。
                            </p>
                            <div class="mt-6 border-t pt-6">
                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                                    <div>
                                        <h5 class="font-bold text-lg mb-2">プロフィール</h5>
                                        <ul class="list-disc list-inside text-gray-700 space-y-1">
                                            <li>慶應義塾大学 卒業</li>
                                            <li>大学在学中に公認会計士試験合格</li>
                                        </ul>
                                    </div>
                                    <div>
                                        <h5 class="font-bold text-lg mb-2">当塾の主な合格実績</h5>
                                        <ul class="list-disc list-inside text-gray-700 space-y-1">
                                            <li>岡山大学、関西学院大学、日本大学、青山学院大学、近畿大学、大阪公立大学、高知工科大学 ほか多数</li>
                                            <li>英検準2級、2級合格実績あり</li>
                                            <li>簿記指導実績あり</li>
                                            <li>公立高校 100名以上</li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </div>

        <div id="tab-content-features" class="tab-content hidden">
            <section id="features" class="py-16">
                <div class="container mx-auto px-6">
                    <h2 class="text-3xl font-bold text-center mb-12">須賀オンライン塾が選ばれる<span class="text-cyan-600">3</span>つの理由</h2>
                    <div class="space-y-12">
                         <div class="flex flex-col md:flex-row items-center gap-8">
                            <div class="md:w-1/2">
                                <img src="juku.jpg" alt="全国に広がるネットワーク" class="rounded-lg shadow-lg">
                            </div>
                            <div class="md:w-1/2">
                                <span class="font-bold text-cyan-600">REASON 01</span>
                                <h3 class="text-2xl font-bold my-2">小・中・高一貫の全国対応オンライン指導</h3>
                                <p class="text-gray-600">中学受験、高校受験、大学受験、さらに英検対策まで。お住まいの地域に関わらず、難関校の入試を突破してきたプロ講師による一貫した質の高い指導が受けられます。各年代、各都道府県の入試制度に合わせた最適な対策を提供します。</p>
                            </div>
                        </div>
                        <div class="flex flex-col md:flex-row-reverse items-center gap-8">
                            <div class="md:w-1/2">
                                <img src="jugyo.png" alt="講師のイメージ" class="rounded-lg shadow-lg">
                            </div>
                            <div class="md:w-1/2">
                                <span class="font-bold text-cyan-600">REASON 02</span>
                                <h3 class="text-2xl font-bold my-2">完全1対1の個別指導</h3>
                                <p class="text-gray-600">経験豊富なプロ講師が、生徒一人のためだけに授業を行います。お子様の学力や性格を深く理解し、「なぜ間違えたのか」を根本から解決。質問しやすい環境で、苦手を自信に変えます。</p>
                            </div>
                        </div>
                        <div class="flex flex-col md:flex-row items-center gap-8">
                            <div class="md:w-1/2">
                                <img src="schedule.jpg" alt="学習計画のイメージ" class="rounded-lg shadow-lg">
                            </div>
                            <div class="md:w-1/2">
                                <span class="font-bold text-cyan-600">REASON 03</span>
                                <h3 class="text-2xl font-bold my-2">柔軟な学習プランと徹底サポート</h3>
                                <p class="text-gray-600">部活動や習い事に合わせて、受講曜日や時間を選択可能。毎回の授業後には保護者様へ指導報告書を送り、ご家庭との連携を密にします。進路相談もいつでも対応し、親子で受験を乗り越えるサポートをします。</p>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </div>

        <div id="tab-content-courses" class="tab-content hidden">
            <section id="courses" class="py-16">
                <div class="container mx-auto px-6">
                    <h2 class="text-3xl font-bold text-center mb-12">コース・料金</h2>
                    <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 max-w-7xl mx-auto">
                        <div class="bg-white border border-gray-200 rounded-lg p-8 shadow-lg flex flex-col h-full">
                            <h3 class="text-2xl font-bold text-center text-gray-700">「Zoom」オンライン自習室</h3>
                            <p class="text-center text-gray-600 mt-2 mb-6">学習習慣を確立するための集中環境</p>
                            <div class="flex-grow mb-6">
                                <ul class="space-y-3 text-gray-700">
                                    <li class="flex items-start">
                                        <i class="fas fa-check-circle text-green-500 mt-1 mr-3 flex-shrink-0"></i>
                                        <p><strong>学習習慣の確立:</strong> 「自宅だと集中できない」を解決し、決まった時間に机に向かうリズムを作ります。</p>
                                    </li>
                                    <li class="flex items-start">
                                        <i class="fas fa-check-circle text-green-500 mt-1 mr-3 flex-shrink-0"></i>
                                        <div>
                                            <p><strong>利用時間:</strong></p>
                                            <p class="pl-2">平日 17:30～22:30<br>土日祝日 10:00～15:30</p>
                                        </div>
                                    </li>
                                </ul>
                            </div>
                            <div class="text-center mt-auto">
                                <p class="text-lg">月額</p>
                                <p class="text-4xl font-bold text-gray-800">3,000<span class="text-xl">円</span><span class="text-base font-normal">(税込)</span></p>
                            </div>
                        </div>

                        <div class="bg-white border border-gray-200 rounded-lg p-8 shadow-lg flex flex-col h-full">
                            <h3 class="text-2xl font-bold text-center text-gray-700">少人数グループ指導</h3>
                            <p class="text-center text-gray-600 mt-2 mb-6">仲間と切磋琢磨できる、リーズナブルなプラン</p>
                            <div class="flex-grow mb-6">
                                <ul class="space-y-3 text-gray-700">
                                    <li class="flex items-start">
                                        <i class="fas fa-users text-green-500 mt-1 mr-3 flex-shrink-0"></i>
                                        <p><strong>対象:</strong> 2～4名の少人数グループで、友達と一緒の受講も可能です。</p>
                                    </li>
                                    <li class="flex items-start">
                                        <i class="fas fa-comments-dollar text-green-500 mt-1 mr-3 flex-shrink-0"></i>
                                        <p><strong>料金:</strong> 1対1指導より授業料を抑え、質の高い授業を提供します。</p>
                                    </li>
                                    <li class="flex items-start">
                                        <i class="fas fa-lightbulb text-green-500 mt-1 mr-3 flex-shrink-0"></i>
                                        <p><strong>相乗効果:</strong> 仲間の意見や質問が新たな気づきを生み、学習意欲を高めます。</p>
                                    </li>
                                </ul>
                            </div>
                            <div class="text-center mt-auto">
                                <p class="text-lg">月額 (週1回の場合)</p>
                                <p class="text-4xl font-bold text-gray-800">8,000<span class="text-xl">円</span><span class="text-base font-normal">(税込)</span></p>
                            </div>
                        </div>

                        <div class="bg-cyan-50 border-2 border-cyan-500 rounded-lg p-8 shadow-xl flex flex-col h-full">
                            <h3 class="text-2xl font-bold text-center text-cyan-700">1対1 完全個別指導</h3>
                            <p class="text-center text-gray-600 mt-2 mb-6">君だけのオーダーメイドプランで合格へ</p>
                            <div class="flex-grow mb-6">
                                <p class="text-center text-gray-600 mb-4 font-semibold">月額料金 (税込) - 高校受験コースの場合</p>
                                 <ul class="space-y-4 text-gray-700">
                                    <li class="flex justify-between items-baseline border-b pb-2">
                                        <span class="font-semibold">週1回コース</span>
                                        <span class="font-bold text-2xl text-cyan-600">18,000<span class="text-base font-normal">円</span></span>
                                    </li>
                                    <li class="flex justify-between items-baseline border-b pb-2">
                                        <span class="font-semibold">週2回コース</span>
                                        <span class="font-bold text-2xl text-cyan-600">34,000<span class="text-base font-normal">円</span></span>
                                    </li>
                                     <li class="flex justify-between items-baseline">
                                        <span class="font-semibold">週3回コース</span>
                                        <span class="font-bold text-2xl text-cyan-600">48,000<span class="text-base font-normal">円</span></span>
                                    </li>
                                </ul>
                            </div>
                            <div class="text-center mt-auto">
                                 <p class="text-sm text-gray-600">※1回80分の個別指導です。</p>
                            </div>
                            <div class="mt-6 border-t border-cyan-200 pt-4 text-center">
                                <div class="inline-flex items-center text-amber-600 bg-amber-100 rounded-full px-4 py-2">
                                    <i class="fas fa-star mr-2"></i>
                                    <p class="font-semibold">週2回以上のコースはオンライン自習室が無料！</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <p class="text-center text-sm text-gray-500 mt-8">
                        ※全コース別途、教材費が必要となる場合がございます。<br>
                        ※上記は高校受験コースの料金です。中学受験、大学受験、英検対策コースの料金はお問い合わせください。<br>
                        プランは、状況に応じ変更となる場合がございます。<br>
                        設備費として、別途2,000円/月かかります。
                    </p>
                    </div>
            </section>
        </div>

        <div id="tab-content-flow" class="tab-content hidden">
            <section id="flow" class="py-16 bg-white">
                <div class="container mx-auto px-6">
                    <h2 class="text-3xl font-bold text-center mb-12">受講までの流れ</h2>
                    <div class="relative">
                        <div class="hidden md:block absolute top-5 left-0 w-full h-0.5 bg-cyan-300"></div>
                        <div class="grid md:grid-cols-4 gap-8 relative">
                            <div class="text-center">
                                <div class="relative"><div class="w-12 h-12 mx-auto bg-cyan-500 text-white rounded-full flex items-center justify-center text-xl font-bold z-10 relative">1</div></div>
                                <h3 class="font-bold mt-4 mb-2">お問い合わせ</h3>
                                <p class="text-sm text-gray-600">まずは無料体験をお申し込みください。</p>
                            </div>
                            <div class="text-center">
                                <div class="relative"><div class="w-12 h-12 mx-auto bg-cyan-500 text-white rounded-full flex items-center justify-center text-xl font-bold z-10 relative">2</div></div>
                                <h3 class="font-bold mt-4 mb-2">学習カウンセリング</h3>
                                <p class="text-sm text-gray-600">現状の学力や目標を伺い、学習プランをご提案します。</p>
                            </div>
                            <div class="text-center">
                                <div class="relative"><div class="w-12 h-12 mx-auto bg-cyan-500 text-white rounded-full flex items-center justify-center text-xl font-bold z-10 relative">3</div></div>
                                <h3 class="font-bold mt-4 mb-2">無料体験授業</h3>
                                <p class="text-sm text-gray-600">週1回の個別指導を2週間体験。期間中、オンライン自習室も最低2回利用していただき、塾の学習スタイルを掴んでください。</p>
                            </div>
                            <div class="text-center">
                                <div class="relative"><div class="w-12 h-12 mx-auto bg-cyan-500 text-white rounded-full flex items-center justify-center text-xl font-bold z-10 relative">4</div></div>
                                <h3 class="font-bold mt-4 mb-2">ご入会・受講開始</h3>
                                <p class="text-sm text-gray-600">ご納得いただけましたら、正式に受講スタートです！</p>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </div>

        <div id="tab-content-information" class="tab-content hidden">
            <section id="information" class="py-16">
                <div class="container mx-auto px-6 max-w-4xl">
                    <h2 class="text-3xl font-bold text-center mb-12">お知らせ</h2>
                    <div class="space-y-8">
                        <div class="bg-white rounded-lg shadow-md p-6">
                            <p class="text-sm text-gray-500 mb-2">2025年7月20日</p>
                            <h3 class="text-xl font-bold mb-3">ホームページを開設しました</h3>
                            <p class="text-gray-600">
                                本日、須賀オンライン塾-レガーレ-の公式ホームページを公開いたしました。
                                このサイトを通じて、私たちの教育理念やコース内容、日々の出来事などを発信してまいります。
                                生徒一人ひとりの未来に「つなぐ」お手伝いができるよう、講師一同、精一杯サポートさせていただきます。
                                どうぞよろしくお願いいたします。
                            </p>
                        </div>
                        </div>
                </div>
            </section>
        </div>

        <div id="tab-content-faq" class="tab-content hidden">
            <section id="faq" class="py-16">
                <div class="container mx-auto px-6 max-w-4xl">
                    <h2 class="text-3xl font-bold text-center mb-12">よくあるご質問</h2>
                    <div class="space-y-4">
                        <div class="bg-gray-50 rounded-lg">
                            <button class="w-full flex justify-between items-center p-4 font-bold text-left focus:outline-none faq-toggle">
                                <span>パソコンは必要ですか？</span>
                                <i class="fas fa-chevron-down transition-transform"></i>
                            </button>
                            <div class="faq-content hidden p-4 pt-0 text-gray-600">
                                <p>カメラ・マイク付きのパソコンまたはタブレット、安定したインターネット環境をご用意ください。スマートフォンの場合は画面が小さく、教材が見えづらい可能性があるため推奨しておりません。</p>
                            </div>
                        </div>
                        <div class="bg-gray-50 rounded-lg">
                            <button class="w-full flex justify-between items-center p-4 font-bold text-left focus:outline-none faq-toggle">
                                <span>宿題は出ますか？</span>
                                <i class="fas fa-chevron-down transition-transform"></i>
                            </button>
                            <div class="faq-content hidden p-4 pt-0 text-gray-600">
                                <p>毎回の授業内容の定着を促すため、お子様の学力や学習状況に合わせた適切な量の宿題をお出しします。家庭学習の習慣づけもサポートします。</p>
                            </div>
                        </div>
                        <div class="bg-gray-50 rounded-lg">
                            <button class="w-full flex justify-between items-center p-4 font-bold text-left focus:outline-none faq-toggle">
                                <span>授業の振替は可能ですか？</span>
                                <i class="fas fa-chevron-down transition-transform"></i>
                            </button>
                            <div class="faq-content hidden p-4 pt-0 text-gray-600">
                                <p>急な体調不良や学校行事の場合、前日の22時までにご連絡いただければ、無料で振替授業を設定いたします。振替の日程は講師と相談の上、決定します。</p>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </div>

        <section id="trial-cta" class="py-20 bg-cyan-600 text-white">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-3xl font-bold mb-4">さあ、第一志望校合格への一歩を踏み出そう。</h2>
                <p class="text-lg mb-8">まずは2週間の無料体験で、レガーレの指導を実感してください。</p>
                <a href="javascript:void(0);" class="open-modal-button bg-amber-500 text-white font-bold py-4 px-8 rounded-full text-lg hover:bg-amber-600 transition-transform transform hover:scale-105 inline-block">
                    <i class="fas fa-user-check mr-2"></i>無料体験に申し込む
                </a>
            </div>
        </section>
    </main>

    <footer class="bg-gray-800 text-white">
        <div class="container mx-auto px-6 py-8">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-6 md:mb-0">
                    <h3 class="text-xl font-bold">須賀オンライン塾 レガーレ</h3>
                    <p class="text-sm text-gray-400">全国の小・中・高・大学受験をオンラインでサポート</p>
                </div>
                <div class="text-sm">
                    <a href="javascript:void(0);" class="open-modal-button text-gray-400 hover:text-white mx-2">お問い合わせ</a>
                </div>
            </div>
            <div class="mt-8 border-t border-gray-700 pt-4 text-center text-gray-500 text-xs">
                &copy; 2025 須賀オンライン塾 レガーレ. All Rights Reserved.
            </div>
        </div>
    </footer>

    <div id="contact-modal" class="hidden fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 p-4">
        <div class="bg-white rounded-lg shadow-2xl p-8 max-w-sm w-full relative">
            <button id="close-modal-button" class="absolute top-2 right-3 text-gray-500 hover:text-gray-800 text-3xl font-bold">&times;</button>
            <h3 class="text-2xl font-bold text-center mb-6">無料体験へのお申し込み</h3>
            <p class="text-center text-gray-600 mb-6">ご希望のお問い合わせ方法をお選びください。</p>
            <div class="space-y-4">
                <a href="mailto:sugashota1204@gmail.com" class="block w-full bg-cyan-600 text-white text-center font-bold py-3 px-4 rounded-lg hover:bg-cyan-700 transition-colors">
                    <i class="fas fa-envelope mr-2"></i>メールで問い合わせる
                </a>
                <a href="https://line.me/R/ti/p/@636jjftt" target="_blank" rel="noopener noreferrer" class="block w-full bg-green-500 text-white text-center font-bold py-3 px-4 rounded-lg hover:bg-green-600 transition-colors">
                    <i class="fab fa-line mr-2"></i>LINEで問い合わせる
                </a>
            </div>

        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', function () {
            // Tab switching logic
            const tabs = document.querySelectorAll('.nav-link');
            const mobileTabs = document.querySelectorAll('.nav-link-mobile');
            const contents = document.querySelectorAll('.tab-content');
            const mobileMenu = document.getElementById('mobile-menu');

            function showTab(tabName) {
                contents.forEach(content => content.classList.add('hidden'));
                tabs.forEach(tab => tab.classList.remove('tab-active')); // Remove old active styles
                mobileTabs.forEach(tab => tab.classList.remove('font-bold', 'bg-cyan-100'));

                document.getElementById(`tab-content-${tabName}`)?.classList.remove('hidden');

                // Apply active styles based on header background
                const activeDesktopTab = document.querySelector(`.nav-link[data-tab="${tabName}"]`);
                if (activeDesktopTab) {
                    activeDesktopTab.classList.add('tab-active');
                }
                const activeMobileTab = document.querySelector(`.nav-link-mobile[data-tab="${tabName}"]`);
                if (activeMobileTab) {
                    activeMobileTab.classList.add('font-bold', 'bg-gray-700'); // Active style for mobile
                }
            }

            tabs.forEach(tab => {
                tab.addEventListener('click', function (e) {
                    e.preventDefault();
                    showTab(this.dataset.tab);
                });
            });

            mobileTabs.forEach(tab => {
                tab.addEventListener('click', function (e) {
                    e.preventDefault();
                    showTab(this.dataset.tab);
                    mobileMenu.classList.add('hidden');
                });
            });

            showTab('home');

            // Mobile menu toggle
            const mobileMenuButton = document.getElementById('mobile-menu-button');
            mobileMenuButton.addEventListener('click', () => {
                mobileMenu.classList.toggle('hidden');
            });

            // FAQ toggle
            const faqToggles = document.querySelectorAll('.faq-toggle');
            faqToggles.forEach(toggle => {
                toggle.addEventListener('click', () => {
                    const content = toggle.nextElementSibling;
                    const icon = toggle.querySelector('i');
                    content.classList.toggle('hidden');
                    icon.classList.toggle('fa-chevron-down');
                    icon.classList.toggle('fa-chevron-up');
                });
            });

            // Modal logic
            const modal = document.getElementById('contact-modal');
            const openModalButtons = document.querySelectorAll('.open-modal-button');
            const closeModalButton = document.getElementById('close-modal-button');

            openModalButtons.forEach(button => {
                button.addEventListener('click', (e) => {
                    e.preventDefault();
                    modal.classList.remove('hidden');
                });
            });

            closeModalButton.addEventListener('click', () => {
                modal.classList.add('hidden');
            });

            // Close modal by clicking outside
            modal.addEventListener('click', (e) => {
                if (e.target === modal) {
                    modal.classList.add('hidden');
                }
            });
        });
    </script>
</body>
</html>
