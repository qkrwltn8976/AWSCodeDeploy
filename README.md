# AWSCodeDeploy : Code Pipeline을 활용한 배포 자동화
AWS deployment automation using pipeline
- https://docs.aws.amazon.com/ko_kr/codepipeline/latest/userguide/getting-started-codepipeline.html

## 1 IAM 사용자 생성
> Identity and Access Management (IAM)

> Access management 

> Users

> Add user
![](img/1.png)
* User name
* Select Access Type
  * AWS Management Console access
* Permission
  * Add user to group (생성된 그룹이 없을 시 Create group)
* Tag (생략)
* Review
* Access key & scret access key

## 2 IAM 관리형 정책을 사용해 IAM 사용자에게 CodePipeline 권한 할당
> Identity and Access Management (IAM)

> Access management 

> Policies 정책

> AWS Management 콘솔을 사용해 IAM 사용자에게 권한을 부여
* 정책 목록에서 AWSCodePipelineFullAcess 관리형 정책 선택
![](img/2.png)
* Policy action
* Attach : 정책을 부여할 유저 선택


## 3 AWS CLI 설치

## 4 CodePipeline 콘솔 열기


