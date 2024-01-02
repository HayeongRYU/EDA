# Easy Data Augmentation Techniques
## 1) **Easy Data Augmentation** Techniques for Boodting performance on Text Classification Tasks
 : 자연어 처리에서의 데이터 증강 기법 
 [Paper](https://arxiv.org/pdf/1901.11196.pdf)

1. 유의어로 교체(Synonym Replacement, **SR**)

2. 랜덤 삽입(Random Insertion, **RI**)

3. 랜덤 교체(Random Swap, **RS**)

4. 랜덤 삭제(Random Deletion, **RD**)

</br></br>


## 2) 실행
- PyCharm 이용하여 작동
- example.txt에 원본 text데이터를 넣으면 eda_example.txt에 데이터를 증강한 결과가 저장된다.
</br>

- **실행방법**
`augment.py`파일의 터미널 창에서 
```
python augment.py --input=example.txt
```
을 실행시켜준다.

</br></br></br></br>

### 출처
[EDA-영어.ver code](https://github.com/jasonwei20/eda_nlp/blob/master/README.md)
 : augment.py 사용
 
[EDA-한국어.ver code](https://github.com/catSirup/KorEDA/blob/master/eda.py)
 : eda.py 사용
