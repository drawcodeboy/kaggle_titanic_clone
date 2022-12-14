# Titanic - Machine Learning from Disaster
<b>Kaggle</b>을 배우며 Kaggle에 필요한 공부가 무엇인지 <b>클론 코딩</b>을 통해 배웁니다.
 
### 각 사이트 링크
>* [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)
>* [이유한님 블로그](https://kaggle-kr.tistory.com/17?category=868316)
>* [이유한님 유튜브](https://www.youtube.com/watch?v=_iqz7tFhox0)

### File List
* titanic-clone-eda
    + 데이터 셋을 확인하고, 데이터 간의 관계를 파악하는 EDA를 수행합니다.
* titanic-clone-fe-n-modeling
    + EDA를 통한 인사이트를 가지고서 Feature Engineering을 수행하고, 적합한 모델을 찾아 만들어냅니다.

### Process
* Dataset Check
    + Null Data Check
    + Target Label 확인
* EDA
    + Pclass
    + Sex
    + Both Sex and Pclass
    + Age
    + Pclass, Sex, Age
    + Embarked
    + Family (SibSp + Parch)
    + Cabin
* Feature Engineering
    + Fill Null data
        + Fill Null in Age using title
        + Fill Null in Embarked
    + Change Age (Continous to categorical)
    + Change Initial, Embarked and Sex (string to numerical)
    + One-hot Encoding on Initial and Embarked
    + Drop Columns
* Building machine learning model and perdiction using the trained model
    + Preparation - Split dataset into train, vaild, and test set
    + Model generation and prediction
    + Feature importance
* Conclusion
