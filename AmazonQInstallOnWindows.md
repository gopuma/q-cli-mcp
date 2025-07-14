## Windows에 Amazon Q Developer CLI 설치하기

1. 윈도우에 Amazon Q 설치하기
    1. Windows 기능 켜기/끄기
￼
3. Linux용 Windows 하위 시스템과 가상 머신 플랫폼 기능을 켠다.
    
     <img width="761" height="1822" alt="windows_feature_on_off" src="https://github.com/user-attachments/assets/681c53df-66dc-461c-ad73-8caf191e9152" />
    1. 재부팅(Restart)하여 설정 변경 적용한다.

3. CMD에서 wsl 업데이트 및 ubuntu 설치
      ```wsl —install -d ubuntu
      
    패스워드 설정하고 사용 가능
       
4. Ubuntu용 Amazon Q를 다운로드 한다.
   ```
    wget https://desktop-release.q.us-east-1.amazonaws.com/latest/amazon-q.deb 
    sudo apt-get install -f
    sudo dpkg -i amazon-q.deb
       
6. Amazon Q을 실행
    1. q login
     ￼<img width="1964" height="1024" alt="q_login" src="https://github.com/user-attachments/assets/2812cf04-3672-45db-bcd3-e20fb40f8c31" />

    2. Amazon Builder ID 생성 및 등록
     ￼<img width="1969" height="1031" alt="amazon_builder_id" src="https://github.com/user-attachments/assets/bb4fe735-2519-4d55-a8bd-b04d5f8874aa" />
     위 CMD의 URL로 이동하여 Amazon Builder ID를 생성한다.

    3. Amazon Q CLI 실행
     ￼<img width="2045" height="1824" alt="amazonq_builder_id_login" src="https://github.com/user-attachments/assets/d0a34e1c-7e59-4e4b-8246-2c39a8c9a99b" />

