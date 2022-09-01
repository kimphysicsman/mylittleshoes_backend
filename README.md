# 👟 MyLittleShoes

나만의 신발 스타일 만들기

<br />

# 📃 프로젝트 정보

### 1. 제작기간

> 2022.06.28 ~ 07.06

### 2. 참여 인원

> |                    Name                    |  Position   |
> | :----------------------------------------: | :---------: |
> | [김동우](https://github.com/kimphysicsman) |    Back     |
> |   [김진수](https://github.com/creamone)    |    Back     |
> |     [박진우](https://github.com/J1NU2)     |    Back     |
> |    [최민기](https://github.com/mankic)     |    Back     |

### 3. 역할 분담

> - 김동우 : 회원가입 / 로그인 기능 / Generative model 사용
> - 김진수 : 추천 스타일 페이지
> - 박진우 : 이미지 업로드 + 결과 페이지 (결과 페이지에서 저장을 누르면 히스토리에 저장됨)
> - 최민기 : 히스토리(게시판) 페이지 / 좋아요 / 댓글 / 즐겨찾기 기능

<br />

# 📚 기술 스택

### Back-end

> python3  
> Django  
> Django-rest-framwork

<br />

# 📊 ERD

<details>
<summary>ERD</summary>
<div markdown="1" style="padding-left: 15px;">
<img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/a1b9badd-e923-4a82-abc8-6a72480a1f77/mylittleshoes_%281%29.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220823%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220823T071050Z&X-Amz-Expires=86400&X-Amz-Signature=7023202f6ba7b54d834bb0d2cca9a9dfd7ce20d41727db6a98a07a62a8d4bfdc&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22mylittleshoes%2520%281%29.png%22&x-id=GetObject" width="800px"/>
</div>
</details>

<br />

# 🔑 구현 내용

### 1. Serializer를 통한 회원가입 / 로그인 기능 구현

> Sirailizer의 cumstom validate, create, update 사용  
> [코드보러가기](https://github.com/kimphysicsman/mylittleshoes_backend/blob/1f7ca0fd899f14b9aedada4f46f716d207480da0/user/serializers.py#L9)


<br />

### 2. Generative model 이용한 새로운 신발 스타일링 기능 구현

> 이미지 두장 받아서 새로운 스타일의 이미지 만들어서 반환  
> [코드보러가기](https://github.com/kimphysicsman/mylittleshoes_backend/blob/master/upload/views.py#L35)




<br />

# 📕 기타 자료

### 1. 기획문서

> [MyLittleShoes - Notion](https://www.notion.so/kimphysicsman/MLS-My-Little-Shoes-2d7eafdb6a514ae7a569f11cc04411e1)

### 2. Generative model

> [style-transfer-pytorch - Github](https://github.com/crowsonkb/style-transfer-pytorch)

### 3. 발표영상

<table>
  <tbody>
    <tr>
      <td>
        <p align="center"> 22.07.06 발표 </p>
        <a href="https://www.youtube.com/watch?v=-UBy-KnmZs4" title="MyLittleShoes 발표">
          <img align="center" src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/d3d05756-264f-4f13-bf98-8d823f012d02/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220823%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220823T073555Z&X-Amz-Expires=86400&X-Amz-Signature=ca1ce99ba02ee89c5986be87c819a9bb4f1d218329b5ee3da6dc81a6bfe7d1cf&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject" width="300" >
        </a>
      </td>
    </tr>
  </tbody>
</table>
