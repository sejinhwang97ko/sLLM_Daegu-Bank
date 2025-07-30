# Daegu-Bank

반갑습니다!

### 📁 llama3_runpod 폴더 설명(2407 업데이트)

1. **`법령용어_데이터.csv`**  
   → 법령용어 OpenAPI로 가져온 데이터  
   → 포함 컬럼: `법령용어명`, `법령용어내용`

2. **`법령용어_QA_데이터_제작.ipynb`**  
   → `법령용어_데이터.csv`의 각 항목을 기반으로 GPT-4o를 활용해 Q&A 형식의 데이터를 생성

3. **`fine_tuning.ipynb`**  
   → RunPod의 A100 SXM GPU 환경에서 실행  
   → LoRA 기반 파인튜닝 및 모델 테스트 수행

## -이전에 올린 파일들-
- **최종 코드 폴더** 

  - law_page1to50.json 는 국가 법령 정보 센터의 OpenAPI를 활용하여 법령용어 데이터를 XML 형태로 추출 후 JSON 형식으로 재가공한 파일

  - 데이터전처리.ipynb 는 Polyglot-ko 12.8B QLoRA 학습하기_ 법령.ipynb 에서 쓰이는 law_rere.json 파일을 만드는 과정을 나타낸 파일
(데이터전처리.ipynb 는 law_page1to50.json 을 활용)

  - law_rere.json
 
  - **Polyglot-ko 12.8B QLoRA 학습하기_ 법령.ipynb**
