# **Indigo4 Firmware**
<br>

## 프로젝트 주요 기능과 목적 
    - Safety A/D Board에 적용된 SocioNext社의 Indigo4 IC에 대한 Firmware 
## Firmware 개발 기간 
    2024년 9월 ~  
## 개발환경 
    1. Visual Studio Code 

    2. Developer Studio Next (SocioNext社)    

    3. git & GitHub 

    4. SourceTree
## 폴더&파일 구조
    1_code : *.par file 
    2_doc : 관련 문서 
    3_bin : *.bin file 

## 버전 이력 (각 Version 별 자세한 내용은 아래 Version을 클릭)
    V0.0.0. (2024.10.) 

## 참고 사항 
    - 개발의도 파악과 시인성, 가독성을 위해, Source Code를 볼 때는 Visual Studio Code를 추천한다. 
        - language는 Julia로 설정한다. 
        - doc 폴더에 있는 settings.json을 적용한다. 
        - 각 주석 의미는 "주석 template.par"을 참고한다. 

## 버전 별 상세내역 
<details>
<summary>V0.0.0. (2024.10.)</summary>  

>- 1차 릴리즈. 
>- Bottom up 위주로 기능 자체 구현에만 중점을 둠. 
>- bin은 없으며, 모든 Component, Unit에 대해 검증 되지 않음. 
>- Component, Unit 간의 정리되지 않음. 또한, 전달, 반환 형식에 대해 통일 되지 않음. 
>- 거의 대부분의 명령어 argu는 수정 필요. 
>- SEERIS IP를 이용하는 Component과 Unit에 대해 진행 되지 않음.
>- 예제 소스 등도 포함되어 있는 경우 있어서 정리 필요. 
>- 설계서와의 nametag 등 매칭 필요. 
</details>