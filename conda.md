## 1. 가상환경 생성
`conda create -n 가상환경명 python=3.7`

환경 구성 후 확인 `conda info --envs`

활성화 `activate 가상환경명`

## 2. 가상환경에 jupyter notebook 설치
`pip install ipykernel`

jupyter notebook에 가상환경 커널 추가
 `python -m ipykernel install --user --name 가상환경명 --display-name "표시할이름"`

## 3. 가상환경&커널 제거
`conda env remove -n 가상환경명`  
`jupyter kernelspec list`에 kernel이 있으면 `jupyter kernelspec uninstall 커널명`으로 커널 제거

## 4. conda install
