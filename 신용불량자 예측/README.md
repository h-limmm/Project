신용불량자 예측

3/13: dataset 분석, modeling, searching for other cases??
3/14: 오전- 각자 모델, 아이디어 브리핑/오후- 선정후 hyperparameter
3/15: preparing presentation,
Google drive: https://drive.google.com/drive/folders/1MtVJeJDuhlqY7XovxRg3yxkXaIs7r0I8
- excel: dataset
   cf. origianl dataset: https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients
	- 오래된 데이터 셋이므로, 캐글에서 찾기만해도 400개 정도는 나옴.
	- 원래의 데이터 셋으로는 어떻게해도 좋은 결과를 내기 힘듦으로, 유의미한 변수를 만드는 것이 중요할 수도 있음.
	  이 경우, 유의미한 변수를 코드로 구현하지 못할 것 같으면 아이디어만 가지고 와도 됨.
	- 잘 만들어진 모델을 가지고 와서, 설명을 하는 것도 가능...
- ipynb: 오전 강의파일. 잘해서 보여주는 것은 아닌듯.
- class 1의 재현율: default를 선언할 사람을 찾아내는 것이 가장 중요.
- 데이터가 skewed 되어있음을 유념.
- class 0과 1의 비율이 3:1 -> upsampling 고려(smote oversampling 참조)
* 그래서 두분이 내일까지 해올일: data set의 이해, 유의미할것이라 예상되는 feature 생각해오기. 생각해본 모델이 있으면 돌려오기, 혹은 괜찮다고 생각한 코드 가져오기.

PPT
https://docs.google.com/presentation/d/1GeDcSWbTIVTeIFe1g9JnBMGlW5Mbpgxp/edit#slide=id.p6
