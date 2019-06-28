#+options: toc:nil ^:nil tags:t f:t
#+author: Sanglae Kim
#+title: 00. 브레드보드 및 LED 회로 이해하기
#+subtitle: 아두이노 시작하기
#+description: 
#+beamer_theme: Berlin
#+beamer_font_theme: professionalfonts
#+setupfile:~/org-html-themes/setup/theme-bigblow.setup
#+HTML_HEAD_EXTRA: <style>pre {font-size:2em; font-family: 'consolas';}</style>

* 학습목표
   - 브래드보드 구성 이해
   - LED 기본 동작 이해
   - 아두이노의 DC전원을 사용하여 회로 구성하기
     
* 1. 기본 LED 회로
    
#+caption:  기본 LED 회로
#+attr_html: :alt neural network :title Neural network representation :align right
#+attr_html: :width 100% :height 100%
    [[./images/led01Direct.jpg]]
    
* 2. 공통 전원을 사용한 LED 회로 
  
** 1. 한개의 led 회로
#+caption: single led circuit
#+attr_html: :alt neural network :title Neural network representation :align right
#+attr_html: :width 100% :height 100%
    [[./images/singleLedDirectCommonPowerGround.jpg]]
    
** 2. 두개의 led 회로
#+caption: dual led circuit
#+attr_html: :alt neural network :title Neural network representation :align right
#+attr_html: :width 100% :height 100%
    [[./images/dualLedDirectCommonPowerGround.jpg]]

 
* How to remove a file on repo without deleting a local file
  
** use git rm
  
*** remove a file on both local and repo
https://stackoverflow.com/questions/2047465/how-can-i-delete-a-file-from-git-repo
 #+BEGIN_SRC shell
 git rm fileName.txt
 git commit -m 'remove fileName.txt
 #+END_SRC
    
    
*** remove a file just on repo
 #+BEGIN_SRC shell
 git rm --cached fileName.txt
 git commit -m 'remove fileName.txt
 #+END_SRC
 
** and to push changes to repo
#+BEGIN_SRC shell
git push 
#+END_SRC
    
    
   
  
   
    
   
   
     
   

   
  
   
    
   
   
     
   

