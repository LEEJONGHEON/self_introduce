# 주제 : GPT기반 자소서 생성과 KoBart,TextRank 기반 자소서 요약

# self_introduce
### 모델 : kykim/gpt3-kor-small_based_on_gpt2
### 토큰나이저 : BertTokenizerFast
### 데이터개수 : 39355개
![image](https://user-images.githubusercontent.com/54635552/171105297-21b5e02c-ef3f-41ef-ac9b-39e6ea701249.png)

# 모델 학습 parameter
### max_length = 2048
### batch_size = 1
### epochs = 6(3 epochs 씩 끊어서 진행)
### GPU 사양 : 
![image](https://user-images.githubusercontent.com/54635552/171107299-71f24b0b-0268-4267-8d37-82f3ccca1cc4.png)

# 모델 학습 결과
### 3 epochs
![image](https://user-images.githubusercontent.com/54635552/171107660-cede938a-9abc-4079-99fe-7e73521422ef.png)
### 6 epochs
![image](https://user-images.githubusercontent.com/54635552/171107686-890cd047-a8cb-4d6b-8247-da3dba739ce9.png)
### 학습시간
![image](https://user-images.githubusercontent.com/54635552/171107752-02e47338-598e-4f81-a944-36c95363ebbd.png)

# Summarization
### 모델 : Kobart ,digit82/kobart-summarization

### 모델 : TextRank



