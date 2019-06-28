#+options: toc:nil ^:nil tags:t f:t
#+author: Sanglae Kim
#+title: 01. 아두이노 시작하기
#+subtitle: 아두이노 시작하기
#+description: 
#+beamer_theme: Berlin
#+beamer_font_theme: professionalfonts
#+setupfile:~/org-html-themes/setup/theme-bigblow.setup
#+HTML_HEAD_EXTRA: <style>pre {font-size:2em; font-family: 'consolas';}</style>

* 학습목표
   - 아두이노 및 통합 개발 환경 이해하기
   - 아두이노 개발 과정 숙지
   - 아두이노 개발보드의 구성 이해하기
   - 아두이노 구조 이해하기
   - 아두이노의 응용분야 이해하기
     
* 아두이노 및 아두이노 실습보드 둘러보기
  
** 아두이노란?
   - 마이크로 컨트롤러보드로 2005년 이탈리아 이브레아(Ivrea)에서 비전공자를 위해  제작
   - 마이크로 컨트롤러 보드와 통합개발환경(IDE)으로 구성
   - Atmel의 마이크로컨트롤러를 사용
   - 사용된 마이크로컨트롤러에 따라 다양한 아두이노 보드존재
     
** 다양한 아두이노
*** Entry Level
    
#+caption: Entry Level Arduino Boards
#+attr_html: :alt neural network :title Neural network representation :align right
#+attr_html: :width 100% :height 100%
    [[./images/entry_level.jpg]]
    
*** Enhanced Features
#+caption: Advanced Level Arduino Boards
#+attr_html: :alt neural network :title Neural network representation :align right
#+attr_html: :width 100% :height 100%
    [[./images/enhanced_features.jpg]]
    
*** Arduino Products
#+caption: Level Arduino Boards
#+attr_html: :alt neural network :title Neural network representation :align right
#+attr_html: :width 100% :height 100%
    [[./images/arduino_products.jpg]]
    
    
** 아두이노 메가 이해 
#+caption: Arduino Mega2560
#+attr_html: :alt neural network :title Neural network representation :align right
#+attr_html: :width 100% :height 100%
   [[./images/arduino_mega_2560.jpg]]
** Technical specs
   #+CAPTION: Technical specs
   #+ATTR_HTML: :align center:width 800 :hight 600
   [[./images/technical_specs.jpg]]
   
   
** 아두이노 Frizing
   #+CAPTION: Training Kit
   #+ATTR_HTML: :alt cat/spider image :title Action! :align center :width 800 :hight 1200
   [[./images/arduino_fritzing.jpg]]
   
** 실습보드 둘러보기
   #+CAPTION: Training Kit
#+attr_html: :alt neural network :title Neural network representation :align right
#+attr_html: :width 100% :height 100%
   [[./images/training_kit.jpg]]
   
* 아두이노 통합개발환경(IDE)
  
** 아두이노 통합개발환경(IDE) 설치하기
   #+CAPTION: Technical specs
#+attr_html: :alt neural network :title Neural network representation :align right
#+attr_html: :width 100% :height 100%
   [[./images/arduino_cite.jpg]]
   
** 아두이노 환경 설정
   
*** 설정내용
   - 환경설정
     + 줄번호 표시
     + 코드폴딩사용
   - 글자폰트 바꾸기
     + consolas
       
*** 환경설정창
   #+CAPTION: Tool Setting Dialog01 
#+attr_html: :alt neural network :title Neural network representation :align right
#+attr_html: :width 100% :height 100%
    [[./images/arduinoSetting.jpg]]
    

   #+CAPTION: Tool Setting Dialog02 
#+attr_html: :alt neural network :title Neural network representation :align right
#+attr_html: :width 100% :height 100%
    [[./images/arduino_env01.jpg]]
    
    
*** 윈도우 탐색기
    - 주의: preferences 파일을 수정하기전 반드시 아두이노를 종료해야 한다.
   #+CAPTION: File Browser
#+attr_html: :alt neural network :title Neural network representation :align right
#+attr_html: :width 100% :height 100%
    [[./images/preferences.jpg]]
    
*** 폰트설정
   #+CAPTION: Font Setting
#+attr_html: :alt neural network :title Neural network representation :align right
#+attr_html: :width 100% :height 100%
    [[./images/font.jpg]]
    
** 아두이노 GUI 이해하기
   #+CAPTION: Arduino Interface
#+attr_html: :alt neural network :title Neural network representation :align right
#+attr_html: :width 100% :height 100%
   [[./images/arduino_ide.jpg]]
   
** 시리얼 모니터
   #+CAPTION: Serial Monitor
#+attr_html: :alt neural network :title Neural network representation :align right
#+attr_html: :width 100% :height 100%
   [[./images/serial_monitor1.jpg]]
   
** 아두이노 단축키 
   - Ctrl - r : 컴파일하기
   - Ctrl - u : 업로드 및 실행하기
   - Ctrl - Shift - m : 시리얼모니터 실행 
   - Ctrl - t : 스케치 전체 자동 들여쓰기
   - Ctrl - k : 스케치 폴더 열기
   - Ctrl - / : 주석달기
   - Ctrl - n : 새 스케치 열기
   - Ctrl - q : 스케치 닫기
     
* Hands On
  
** 작업디렉토리 생성
   - d:\ss_work - 성수
   - d:\kw_work - 광운
   - d:\ys_work - 용산
   - d:\se_work - 서울전자
   - d:\sm_work - 세명
     
** 실행순서
   
*** 스케치 생성 및 저장
   - 아두이노 프로그램 실행
   - 파일 -> 새파일
   - 파일 -> 다른이름으로 저장
   - 작업폴더 선택(d:\xx_work)
   - 스케치이름(*led*)저장
   - 스케치 및 폴더 생성 확인
     
*** 코딩 및 보드 연결
   - 코딩
   - 컴파일(Ctrl-R)
   - 보드 연결
   - 보드설정(Mega2560)
   #+CAPTION: Board Selection
#+attr_html: :alt neural network :title Neural network representation :align right
#+attr_html: :width 100% :height 100%
   [[./images/board_selection.jpg]]
   - 포트설정(COM12~) - 컴퓨터마다 다름
   #+CAPTION: Port Selection
#+attr_html: :alt neural network :title Neural network representation :align right
#+attr_html: :width 100% :height 100%
   [[./images/port_selection.jpg]]
   
*** 실행 및 확인 
   - 업로드(Ctrl-U)및 확인
   - https://youtu.be/zThoWUI5DEE
   
** blink LED 
   #+name: blinkLed.ino
   #+begin_src c++ -n 
void setup() {
  pinMode(13, OUTPUT);
}
void loop() {
  digitalWrite(13, HIGH);
  delay(1000);
  digitalWrite(13, LOW);
  delay(1000);
}
   #+end_src
   
* youtube 동영상
  - https://www.youtube.com/watch?v=5zf82lLVMrw
  - https://www.youtube.com/watch?v=FawoBxDKVbI 

* arduino main.c
  - [[C:\Program%20Files%20(x86)\Arduino\hardware\arduino\avr\cores\arduino\main.cpp][C:\Program Files (x86)\Arduino\hardware\arduino\avr\cores\arduino\main.cpp]]
    
  #+BEGIN_SRC c++ -n
// 일부 생략
    int main(void) {
      init();
      initVariant();
    #if defined(USBCON)
      USBDevice.attach();
    #endif
      setup();
      for (;;) {
        loop();
        if (serialEventRun) serialEventRun();
      }
      return 0;
    }
#+END_SRC
