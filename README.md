# MystudyPython

맥에서 우선 설치되어있어야 하는 프로그램

brew install imagemagick    --> 이미지매직은 그래픽 이미지를 새로 만들거나, 고치는 데 사용되는 자유-오픈 소스 소프트웨어

brew install tesseract      --> 이미지에서 문자 및 숫자 인식하는 오픈소스

brew install tesseract-lang --> tesseract 언어 팩(한글도 인식 어느정도됨)


tesseract --list-lang --> 설치된 언어팩 리스트 확인


기본 테스트
convert input.png -resize 400% -type Grayscale input.tif --> 이미지를 400퍼 증가 및 이미지를 gray로 변환

tesseract -l kor input.tif output 이미지를 읽어 
