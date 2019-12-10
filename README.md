# TestDBServer

테스트 서버 

# 서버 사용방법

## 회원가입
신규 유저의 등록
### 요청
> {POST} /users/signup/

전달값
<pre>
{
 'username':'hongildong',
 'password':'hong1234',
 'nickname':'hong'
}
</pre>

### 결과
#### 성공
<pre>
{
 '_id':'1234567890',
 'username':'hongildong',
 'nickname':'hong'
}
</pre>
#### 실패
{
 'message':'400 Bad Request'
}

## 로그인
### 요청

### 결과
