<template>
    <div class="portfolio_banner container-fluid bg-gray-100">
        <div class="container d-f fd-c ai-c text-center">
            <div class="portfolio_slogan d-f fd-c ai-c text-center mt-40">
                <svg class="quote" width="65" height="64" viewBox="0 0 65 64" fill="none"
                    xmlns="http://www.w3.org/2000/svg">
                    <path
                        d="M30.3454 42.0188C30.3454 39.6722 29.732 37.7042 28.5054 36.1068C27.636 35.0082 26.4574 34.2855 24.9667 33.9415C23.5 33.6002 22.1134 33.5762 20.86 33.8668C20.4334 31.3335 21.1267 28.6508 22.8867 25.8082C24.6467 22.9682 26.9267 20.8295 29.708 19.4002L25.492 13.3335C23.3587 14.3895 21.332 15.7282 19.4654 17.3468C17.572 18.9655 15.892 20.8268 14.3987 22.9308C12.9054 25.0348 11.7854 27.4108 11.0654 30.1042C10.3454 32.7975 10.1454 35.5442 10.4894 38.3708C10.9374 42.1042 12.1427 45.0908 14.1054 47.3042C16.0654 49.5468 18.5107 50.6668 21.4334 50.6668C24.0067 50.6668 26.1427 49.8935 27.8334 48.3255C29.508 46.7895 30.34 44.6855 30.34 42.0108L30.3454 42.0188ZM54.676 42.0188C54.676 39.6722 54.0627 37.7042 52.836 36.1068C51.9667 34.9868 50.7827 34.2615 49.2974 33.9282C47.804 33.5975 46.436 33.5815 45.1907 33.8695C44.764 31.3628 45.4307 28.6695 47.196 25.8162C48.956 22.9895 51.2307 20.8562 54.012 19.4162L49.8067 13.3335C47.6734 14.3895 45.66 15.7282 43.78 17.3468C41.8694 18.9895 40.1726 20.8655 38.7294 22.9308C37.2467 25.0375 36.1427 27.4108 35.4227 30.1042C34.6942 32.7959 34.4976 35.6039 34.844 38.3708C35.2867 42.1042 36.4867 45.0908 38.444 47.3042C40.3987 49.5282 42.836 50.6428 45.7587 50.6428C48.3374 50.6428 50.4734 49.8695 52.164 48.3042C53.836 46.7682 54.676 44.6642 54.676 41.9895V42.0188Z"
                        fill="#E9E9E9" />
                </svg>
                <svg class="quote_big_left" width="72" height="72" viewBox="0 0 72 72" fill="none"
                    xmlns="http://www.w3.org/2000/svg">
                    <path
                        d="M33.5761 47.271C33.5761 44.631 32.8861 42.417 31.5061 40.62C30.5281 39.384 29.2021 38.571 27.5251 38.184C25.8751 37.8 24.3151 37.773 22.9051 38.1C22.4251 35.25 23.2051 32.232 25.1851 29.034C27.1651 25.839 29.7301 23.433 32.8591 21.825L28.1161 15C25.7161 16.188 23.4361 17.694 21.3361 19.515C19.2061 21.336 17.3161 23.43 15.6361 25.797C13.9561 28.164 12.6961 30.837 11.8861 33.867C11.0761 36.897 10.8511 39.987 11.2381 43.167C11.7421 47.367 13.0981 50.727 15.3061 53.217C17.5111 55.74 20.2621 57 23.5501 57C26.4451 57 28.8481 56.13 30.7501 54.366C32.6341 52.638 33.5701 50.271 33.5701 47.262L33.5761 47.271ZM60.9481 47.271C60.9481 44.631 60.2581 42.417 58.8781 40.62C57.9001 39.36 56.5681 38.544 54.8971 38.169C53.2171 37.797 51.6781 37.779 50.2771 38.103C49.7971 35.283 50.5471 32.253 52.5331 29.043C54.5131 25.863 57.0721 23.463 60.2011 21.843L55.4701 15C53.0701 16.188 50.8051 17.694 48.6901 19.515C46.5407 21.363 44.6318 23.4735 43.0081 25.797C41.3401 28.167 40.0981 30.837 39.2881 33.867C38.4685 36.8952 38.2474 40.0542 38.6371 43.167C39.1351 47.367 40.4851 50.727 42.6871 53.217C44.8861 55.719 47.6281 56.973 50.9161 56.973C53.8171 56.973 56.2201 56.103 58.1221 54.342C60.0031 52.614 60.9481 50.247 60.9481 47.238V47.271Z"
                        fill="#E9E9E9" />
                </svg>
                <svg class="quote_big_right" width="72" height="72" viewBox="0 0 72 72" fill="none"
                    xmlns="http://www.w3.org/2000/svg">
                    <path
                        d="M38.4239 24.729C38.4239 27.369 39.1139 29.583 40.4939 31.38C41.4719 32.616 42.7979 33.429 44.4749 33.816C46.1249 34.2 47.6849 34.227 49.0949 33.9C49.5749 36.75 48.7949 39.768 46.8149 42.966C44.8349 46.161 42.2699 48.567 39.1409 50.175L43.8839 57C46.2839 55.812 48.5639 54.306 50.6639 52.485C52.7939 50.664 54.6839 48.57 56.3639 46.203C58.0439 43.836 59.3039 41.163 60.1139 38.133C60.9239 35.103 61.1489 32.013 60.7619 28.833C60.2579 24.633 58.9019 21.273 56.6939 18.783C54.4889 16.26 51.7379 15 48.4499 15C45.5549 15 43.1519 15.87 41.2499 17.634C39.3659 19.362 38.4299 21.729 38.4299 24.738L38.4239 24.729ZM11.0519 24.729C11.0519 27.369 11.7419 29.583 13.1219 31.38C14.0999 32.64 15.4319 33.456 17.1029 33.831C18.7829 34.203 20.3219 34.221 21.7229 33.897C22.2029 36.717 21.4529 39.747 19.4669 42.957C17.4869 46.137 14.9279 48.537 11.7989 50.157L16.5299 57C18.9299 55.812 21.1949 54.306 23.3099 52.485C25.4593 50.637 27.3682 48.5265 28.9919 46.203C30.6599 43.833 31.9019 41.163 32.7119 38.133C33.5315 35.1048 33.7526 31.9458 33.3629 28.833C32.8649 24.633 31.5149 21.273 29.3129 18.783C27.1139 16.281 24.3719 15.027 21.0839 15.027C18.1829 15.027 15.7799 15.897 13.8779 17.658C11.9969 19.386 11.0519 21.753 11.0519 24.762L11.0519 24.729Z"
                        fill="#E9E9E9" />
                </svg>

                <div class="portfolio_slogan_item d-f fd-c ai-c">
                    <h2 class="portfolio_title fz-20 fw-bold mb-8">讓使用者在觀賞與使用的旅程中，發現設計的價值
                        <svg class="mark" width="108" height="6" viewBox="0 0 108 6" fill="none" xmlns="">
                            <path fill-rule="evenodd" clip-rule="evenodd"
                                d="M107.958 1.90825C107.517 1.20093 103.73 0.903094 92.3502 0.654909C81.7315 0.419133 69.3697 -0.263363 47.7716 0.108914C31.2625 0.394327 10.7063 1.53599 10.7063 2.16886C10.7063 2.628 11.5078 2.64041 19.1612 2.23091C26.2337 1.85863 29.8601 1.77177 34.2879 1.67249C16.5366 2.64041 12.7499 3.27326 3.29323 3.88131C-2.63722 4.266 0.828888 5.37043 2.9927 5.25875C3.01274 5.25875 30.6014 3.8689 33.206 3.94336C33.4464 3.95577 30.8218 4.17913 27.3557 4.43973C17.6786 5.18428 19.5419 6.4252 26.7947 5.85437C51.1977 3.93094 74.1581 3.33528 91.8493 4.1667C97.4392 4.4273 98.0603 4.4273 98.0603 4.10465C98.0603 3.53383 96.5376 3.09953 94.1534 3.01267C90.4268 2.86375 76.0816 2.44183 69.5901 2.31774C69.0892 2.30533 69.3296 2.06959 69.7704 2.04477C72.4151 1.88345 93.4121 2.00749 101.667 2.18122C107.737 2.30531 108.178 2.29294 107.958 1.90825Z"
                                fill="#F7AF5A" />
                        </svg>
                        <svg class="mark-big" width="148" height="8" viewBox="0 0 148 8" fill="none"
                            xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd"
                                d="M147.942 2.54434C147.338 1.60124 142.149 1.20413 126.554 0.873212C112.002 0.558844 95.0622 -0.351151 65.4648 0.145219C42.8412 0.525769 14.6716 2.04799 14.6716 2.89182C14.6716 3.504 15.7699 3.52055 26.258 2.97454C35.9499 2.47817 40.9194 2.36235 46.9871 2.22999C22.6613 3.52055 17.4721 4.36435 4.51295 5.17508C-3.61397 5.688 1.13588 7.16058 4.10111 7.01167C4.12857 7.01167 41.9352 5.15854 45.5045 5.25781C45.8339 5.27436 42.2372 5.57218 37.4874 5.91964C24.2262 6.91238 26.7796 8.56693 36.7186 7.80583C70.1598 5.24125 101.624 4.44704 125.868 5.5556C133.528 5.90306 134.379 5.90306 134.379 5.47287C134.379 4.71177 132.292 4.13271 129.025 4.01689C123.918 3.81834 104.26 3.25577 95.3642 3.09031C94.6778 3.07377 95.0073 2.75945 95.6113 2.72636C99.2355 2.51126 128.009 2.67666 139.321 2.9083C147.64 3.07375 148.244 3.05726 147.942 2.54434Z"
                                fill="#F7AF5A" />
                        </svg>
                    </h2>
                    <h2 class="portfolio_title_two fz-20 fw-bold mb-40">而我在設計與開發的過程中，看見自己的價值
                        <svg class="markTwo" width="108" height="6" viewBox="0 0 108 6" fill="none" xmlns="">
                            <path fill-rule="evenodd" clip-rule="evenodd"
                                d="M107.958 1.90825C107.517 1.20093 103.73 0.903094 92.3502 0.654909C81.7315 0.419133 69.3697 -0.263363 47.7716 0.108914C31.2625 0.394327 10.7063 1.53599 10.7063 2.16886C10.7063 2.628 11.5078 2.64041 19.1612 2.23091C26.2337 1.85863 29.8601 1.77177 34.2879 1.67249C16.5366 2.64041 12.7499 3.27326 3.29323 3.88131C-2.63722 4.266 0.828888 5.37043 2.9927 5.25875C3.01274 5.25875 30.6014 3.8689 33.206 3.94336C33.4464 3.95577 30.8218 4.17913 27.3557 4.43973C17.6786 5.18428 19.5419 6.4252 26.7947 5.85437C51.1977 3.93094 74.1581 3.33528 91.8493 4.1667C97.4392 4.4273 98.0603 4.4273 98.0603 4.10465C98.0603 3.53383 96.5376 3.09953 94.1534 3.01267C90.4268 2.86375 76.0816 2.44183 69.5901 2.31774C69.0892 2.30533 69.3296 2.06959 69.7704 2.04477C72.4151 1.88345 93.4121 2.00749 101.667 2.18122C107.737 2.30531 108.178 2.29294 107.958 1.90825Z"
                                fill="#F7AF5A" />
                        </svg>
                        <svg class="mark-bigTwo" width="148" height="8" viewBox="0 0 148 8" fill="none"
                            xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd"
                                d="M147.942 2.54434C147.338 1.60124 142.149 1.20413 126.554 0.873212C112.002 0.558844 95.0622 -0.351151 65.4648 0.145219C42.8412 0.525769 14.6716 2.04799 14.6716 2.89182C14.6716 3.504 15.7699 3.52055 26.258 2.97454C35.9499 2.47817 40.9194 2.36235 46.9871 2.22999C22.6613 3.52055 17.4721 4.36435 4.51295 5.17508C-3.61397 5.688 1.13588 7.16058 4.10111 7.01167C4.12857 7.01167 41.9352 5.15854 45.5045 5.25781C45.8339 5.27436 42.2372 5.57218 37.4874 5.91964C24.2262 6.91238 26.7796 8.56693 36.7186 7.80583C70.1598 5.24125 101.624 4.44704 125.868 5.5556C133.528 5.90306 134.379 5.90306 134.379 5.47287C134.379 4.71177 132.292 4.13271 129.025 4.01689C123.918 3.81834 104.26 3.25577 95.3642 3.09031C94.6778 3.07377 95.0073 2.75945 95.6113 2.72636C99.2355 2.51126 128.009 2.67666 139.321 2.9083C147.64 3.07375 148.244 3.05726 147.942 2.54434Z"
                                fill="#F7AF5A" />
                        </svg>
                    </h2>
                </div>
            </div>
            <div class="portfolio_content d-f fd-c ai-c mb-60">
                <div class="portfolio_content_item d-f fd-c ai-c">
                    <h3 class="portfolio_title">2B經驗</h3>
                    <div class="line bg-gray-200 mb-8"></div>
                    <p class="portfolio_text mb-20">內部監控系統、庫存系統、採購系統、行銷整合系統</p>
                </div>
                <div class="portfolio_content_item_two d-f fd-c ai-c">
                    <h3 class="portfolio_title">2C經驗</h3>
                    <div class="line bg-gray-200 mb-8"></div>
                    <p class="portfolio_text mb-20">跨國美妝保養電商、個人品牌網站、醫美網站、電子商務</p>
                </div>
            </div>
        </div>
    </div>
    <div class="portfolio_work container">
        <ul class="portfolio_work_list d-f fd-c jc-sb ai-c flex-wrap mt-80">
            <li class="portfolio_work_item col-12 col-md-6 mb-48" @click="openModal">
                <img class="portfolio_work_img border-1 border-radius-8 border-gray mb-16"
                    src="https://github.com/hexschool/2022-web-layout-training/blob/main/2024%20web-camp/work-image1.png?raw=true"
                    alt="圖片">
                <h2 class="portfolio_work_item_title fz-20 fw-bold mb-8">星際旅行訂票平台</h2>
                <p class="portfolio_work_item_text text-gray-dark mb-16">悠遊宇宙的夢想，從這裡開始實現</p>
                <ul class="portfolio_work_item_tags d-f">
                    <li class="portfolio_work_item_tags_item bg-gray border-radius-16 mr-8 px-12 py-4">網頁設計</li>
                    <li class="portfolio_work_item_tags_item bg-gray border-radius-16 mr-8 px-12 py-4">響應式設計</li>
                    <li class="portfolio_work_item_tags_item bg-gray border-radius-16 px-12 py-4">Bootstrap</li>
                </ul>
            </li>
            <li class="portfolio_work_item col-12 col-md-6 mb-48">
                <img class="portfolio_work_img border-1 border-radius-8 border-gray mb-16"
                    src="https://github.com/hexschool/2022-web-layout-training/blob/main/2024%20web-camp/work-image2.png?raw=true"
                    alt="圖片">
                <h2 class="portfolio_work_item_title fz-20 fw-bold mb-8">理財App</h2>
                <p class="portfolio_work_item_text text-gray-dark mb-16">連動帳戶與行動支付，讓 AI 提供您最好的理財建議</p>
                <ul class="portfolio_work_item_tags d-f">
                    <li class="portfolio_work_item_tags_item bg-gray border-radius-16 mr-8 px-12 py-4">APP設計</li>
                    <li class="portfolio_work_item_tags_item bg-gray border-radius-16 mr-8 px-12 py-4">iOS</li>
                    <li class="portfolio_work_item_tags_item bg-gray border-radius-16 px-12 py-4">React</li>
                </ul>
            </li>
            <li class="portfolio_work_item col-12 col-md-6 mb-48">
                <img class="portfolio_work_img border-1 border-radius-8 border-gray mb-16"
                    src="https://github.com/hexschool/2022-web-layout-training/blob/main/2024%20web-camp/work-image3.png?raw=true"
                    alt="圖片">
                <h2 class="portfolio_work_item_title fz-20 fw-bold mb-8">醫美診所官網</h2>
                <p class="portfolio_work_item_text text-gray-dark mb-16">永保青春的秘密，從粹究開始</p>
                <ul class="portfolio_work_item_tags d-f">
                    <li class="portfolio_work_item_tags_item bg-gray border-radius-16 mr-8 px-12 py-4">網頁設計</li>
                    <li class="portfolio_work_item_tags_item bg-gray border-radius-16 mr-8 px-12 py-4">響應式設計</li>
                    <li class="portfolio_work_item_tags_item bg-gray border-radius-16 px-12 py-4">WordPress</li>
                </ul>
            </li>
            <li class="portfolio_work_item col-12 col-md-6 mb-48">
                <img class="portfolio_work_img border-1 border-radius-8 border-gray mb-16"
                    src="https://github.com/hexschool/2022-web-layout-training/blob/main/2024%20web-camp/work-image4.png?raw=true"
                    alt="圖片">
                <h2 class="portfolio_work_item_title fz-20 fw-bold mb-8">美美美早餐店 POS 機 UI Design</h2>
                <p class="portfolio_work_item_text text-gray-dark mb-16">訂單送單一目瞭然，自動報表分析好輕鬆</p>
                <ul class="portfolio_work_item_tags d-f">
                    <li class="portfolio_work_item_tags_item bg-gray border-radius-16 mr-8 px-12 py-4">UI 設計</li>
                    <li class="portfolio_work_item_tags_item bg-gray border-radius-16 mr-8 px-12 py-4">前端開發</li>
                    <li class="portfolio_work_item_tags_item bg-gray border-radius-16 px-12 py-4">Wix</li>
                </ul>
            </li>
            <li class="portfolio_work_item col-12 col-md-6 mb-48">
                <img class="portfolio_work_img border-1 border-radius-8 border-gray mb-16"
                    src="https://github.com/hexschool/2022-web-layout-training/blob/main/2024%20web-camp/work-image5.png?raw=true"
                    alt="圖片">
                <h2 class="portfolio_work_item_title fz-20 fw-bold mb-8">電影院訂票系統</h2>
                <p class="portfolio_work_item_text text-gray-dark mb-16">三步驟完成訂票，電腦手機都支援</p>
                <ul class="portfolio_work_item_tags d-f">
                    <li class="portfolio_work_item_tags_item bg-gray border-radius-16 mr-8 px-12 py-4">前端開發</li>
                    <li class="portfolio_work_item_tags_item bg-gray border-radius-16 mr-8 px-12 py-4">後端支援</li>
                    <li class="portfolio_work_item_tags_item bg-gray border-radius-16 px-12 py-4">Vue</li>
                </ul>
            </li>
            <li class="portfolio_work_item col-12 col-md-6 mb-48">
                <img class="portfolio_work_img border-1 border-radius-8 border-gray mb-16"
                    src="https://github.com/hexschool/2022-web-layout-training/blob/main/2024%20web-camp/work-image6.png?raw=true"
                    alt="圖片">
                <h2 class="portfolio_work_item_title fz-20 fw-bold mb-8">巧克巧克形象官網設計</h2>
                <p class="portfolio_work_item_text text-gray-dark mb-16">三步驟完成訂票，電腦手機都支援</p>
                <ul class="portfolio_work_item_tags d-f">
                    <li class="portfolio_work_item_tags_item bg-gray border-radius-16 mr-8 px-12 py-4">UI設計</li>
                    <li class="portfolio_work_item_tags_item bg-gray border-radius-16 mr-8 px-12 py-4">設計系統</li>
                    <li class="portfolio_work_item_tags_item bg-gray border-radius-16 px-12 py-4">網路電商</li>
                </ul>
            </li>
        </ul>
        <div class="portfolio_work_pagination d-f jc-c mb-80">
            <div class="portfolio_work_pagination_list">
                <a href="#"
                    class="portfolio_work_pagination_item bg-dark text-light fz-24 mr-16 border-radius-4 text-center">1</a>
                <a href="#" class="portfolio_work_pagination_item fz-24 mr-16 border-radius-4 text-center">2</a>
                <a href="#" class="portfolio_work_pagination_item fz-24 mr-16 border-radius-4 text-center">3</a>
            </div>
        </div>
    </div>

    <div class="modal">
        <div class="modal_content pt-88 text-center border-radius-16">
            <button type="button" class="modal_close_btn" @click="closeModal">
                <span class="material-symbols-outlined">close</span>
            </button>
            <h2 class="modal_content_title mb-8 fz-28 fw-bold">星際旅行訂票平台</h2>
            <p class="modal_content_text text-gray-dark mb-24">悠遊宇宙的夢想，從這裡開始實現</p>
            <div class="modal_content_text_wrap">
                <div>
                    <p class="modal_content_text_two text-gray-900 text-start fw-bold">STAR TRAVEL 為 KK 公司宇宙旅行的購票網站。</p>
                    <p class="modal_content_text_two text-gray-900 text-start fw-bold">
                        主要從地球出發，目的地包含月球、火星、水星、木星；未來太空轉運站建置完畢，將再擴增目的地土星和金星。
                    </p>
                </div>
                <div class="description mt-24 py-24 text-gray-300 border-top-1 border-gray-200">
                    <div class="mobile">
                        <p class="fw-bold">設計原則</p>
                        <p class="fw-bold mb-24">宇宙旅行、深色背景、強烈視覺效果</p>
                        <p class="fw-bold">開發方式</p>
                        <p class="fw-bold">Bootstrap、Javascript、RWD</p>
                    </div>
                    <div class="pc my-8 pl-24 border-left-1 border-gray-200">
                        <p class="fw-bold mb-8">設計原則：<span>宇宙旅行、深色背景、強烈視覺效果</span></p>
                        <p class="fw-bold">開發方式：<span>Bootstrap、Javascript、RWD</span></p>
                    </div>
                </div>
            </div>
            <div class="card bg-gray-400 py-40 px-16">
                <ul class="card-list">
                    <li class="card-item pb-56">
                        <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2024%20web-camp/modal-image1.png?raw=true"
                            alt="" class="card_img border-radius-8">
                        <h3 class="card_title fz-20 fw-bold text-gray-900 mt-16 mb-8">主視覺</h3>
                        <p class="text-gray-300 text-start">可直接設定日期、起迄星球、張數，快速查詢可購買的票券。</p>
                    </li>
                    <li class="card-item">
                        <img src="https://github.com/hexschool/2022-web-layout-training/blob/main/2024%20web-camp/modal-image2.png?raw=true"
                            alt="" class="card_img border-radius-8">
                        <h3 class="card_title fz-20 fw-bold text-gray-900 mt-16 mb-8">推薦查詢</h3>
                        <p class="text-gray-300 text-start">給予最快起飛，以及最熱門的景點推薦，協助使用者進行選擇。</p>
                    </li>
                </ul>
            </div>
        </div>
    </div>
    <div class="maskEffect"></div>


</template>

<script setup>
const openModal = () => {
    const modal = document.querySelector('.modal')
    modal.classList.toggle('openModal')
    const maskEffect = document.querySelector('.maskEffect')
    maskEffect.classList.toggle('mask')
    window.scrollTo(0, 0)
}

const closeModal = () => {
    const modal = document.querySelector('.modal')
    modal.classList.toggle('openModal')
    const maskEffect = document.querySelector('.maskEffect')
    maskEffect.classList.toggle('mask')
}
</script>

<style lang="scss">
/*modal*/
.modal {
    position: absolute;
    top: 68px;
    width: 100%;
    z-index: 100;
    display: flex;
    justify-content: center;
    align-items: center;
    opacity: 0;
    pointer-events: none;
}


.modal.openModal {
    opacity: 1;
    pointer-events: auto;
    transition: .4s ease;
}

.modal_content {
    background-color: #fff;
    width: 90%;
    transform: scale(0);
}

.modal.openModal .modal_content {
    transform: scale(1);
    transition: .4s ease;
    transition-delay: .25s;
}

.modal_close_btn {
    position: absolute;
    top: 32px;
    right: 32px;
    border: none;
    background-color: transparent;
    cursor: pointer;
    padding: 0;
    height: 32px;

    .material-symbols-outlined {
        font-size: 32px;
    }
}

/*遮罩效果*/
.mask {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.7);
    z-index: 10;
}

.card {
    width: 100%;
    border-radius: 0 0 16px 16px;
}

.line {
    width: 24px;
    height: 2px;
}

.mark-big,
.mark-bigTwo,
.quote_big_left,
.quote_big_right {
    display: none;
}


.portfolio_work_item {
    cursor: pointer;
}

.portfolio_work_pagination_item {
    width: 40px;
    height: 40px;
}

.pc {
    display: none;
}


@media (max-width: 768px) {
    .portfolio_banner {
        height: 540px;
    }

    h2.portfolio_title {
        width: 300px;
        position: relative;
    }

    h2.portfolio_title_two {
        width: 260px;
        position: relative;
    }

    p.portfolio_text {
        width: 235px;
    }

    .mark {
        position: absolute;
        bottom: 0;
        right: 75px;
    }

    .markTwo {
        position: absolute;
        bottom: 0;
        right: 50px;
    }

    .modal_content_text_two {
        width: 287px;
        margin: 0 auto;
    }

    .description .mobile {
        width: 287px;
        margin: auto;
    }

    .card-item {
        width: 319px;
        margin: auto;
    }
}

@media screen and (min-width: 767px) {
    .modal {
        position: absolute;
        top: 631px;
    }

    .portfolio_banner {
        height: 460px;
    }

    .portfolio_content {
        flex-direction: row;
        justify-content: space-between;
        width: 636px;

        .portfolio_content_item,
        .portfolio_content_item_two {
            width: 298px;
        }
    }

    h2.portfolio_title,
    h2.portfolio_title_two {
        position: relative;
        font-size: 24px;
        width: 580px;
    }

    h2.portfolio_title_two {
        margin-bottom: 0;
    }

    .mark,
    .markTwo,
    .quote {
        display: none;
    }

    .mark-big {
        display: block;
        position: absolute;
        bottom: 0;
        right: 0;
    }

    .mark-bigTwo {
        display: block;
        position: absolute;
        bottom: 0;
        right: 30px;
    }

    .portfolio_slogan {
        width: 670px;
        height: 192px;
        position: relative;
        justify-content: center;
        margin-top: 80px;
    }

    .quote_big_left {
        display: block;
        position: absolute;
        top: 0;
        left: 0;
    }

    .quote_big_right {
        display: block;
        position: absolute;
        bottom: 0;
        right: 0;
    }

    .portfolio_work.container {
        padding: 0;
    }

    .portfolio_work_list {
        flex-direction: row;
        margin-top: 120px;
        margin-bottom: 72px;
    }

    .portfolio_work_item_tags_item {
        margin-right: 16px;
    }

    .portfolio_work_pagination {
        margin-bottom: 120px;
    }

    .modal_content {
        padding-top: 104px;
    }

    .modal_close_btn {
        top: 40px;
    }

    .modal_content_text_wrap {
        display: flex;
        justify-content: space-around;
    }

    .modal_content_text_wrap>div:first-child {
        display: flex;
        flex-direction: column;
        justify-content: center;
        width: 532px
    }

    .description {
        margin-block: 40px;
        border-top: none;
    }

    .mobile {
        display: none;
    }

    .pc {
        display: block;
    }

    .card {
        padding-block: 80px;

        .card-item {
            h3 {
                font-size: 24px;
                margin: 24px 0 16px 0;
            }

            p {
                text-align: center;
            }
        }
    }
}
</style>
