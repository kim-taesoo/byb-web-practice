# BYB Manager Tool Project
바이비를 이용하는 아파트의 관리자들이 사용하는 운영 S/W 프로젝트입니다. 사내에서는 '바이비 운영툴'이라 통칭합니다.

## About The Project
![image](https://user-images.githubusercontent.com/105332712/191900470-2106d635-a327-4adf-9c5d-96238654a8b0.png)

바이비 운영툴의 '매장 관리' 페이지입니다. 위와 같이 입주민과 관리자들의 편의를 제공하기 위해 바이비 운영툴은 여러 기능을 제공하고 있습니다.
더욱 자세한 사항은 하기 페이지에서 참고해주시기 바랍니다.

바이비 운영툴 탭 정의: https://htbeyond.atlassian.net/wiki/spaces/BMXBLUE/pages/439124614
 
### Built With
바이비 운영툴에서 사용되는 프레임워크, 라이브러리 목록입니다.

* ![React](https://img.shields.io/badge/react-444444?style=for-the-badge&logo=react)
* ![Typescript](https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=fff)
* ![Redux](https://img.shields.io/badge/redux-764ABC?style=for-the-badge&logo=redux)
* ![Amazon S3](https://img.shields.io/badge/amazons3-569A31?style=for-the-badge&logo=amazons3&logoColor=fff)
* ![Amazon AWS](https://img.shields.io/badge/amazonaws-232F3E?style=for-the-badge&logo=amazons3&logoColor=fff)
* ![Firebase](https://img.shields.io/badge/firebase-444444?style=for-the-badge&logo=firebase)
* ![Git](https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=fff)
* <img src="https://img.shields.io/badge/styled components-DB7093?&logo=styled-components&logoColor=white"/>

### Directory Structure
바이비 운영툴의 디렉토리 구조는 크게 복잡한 편은 아닙니다. 아래에 정리된 표와 같이 훑어보시길 권장드립니다.

바이비 운영툴 디렉토리 구조: https://htbeyond.atlassian.net/wiki/spaces/BMXBLUE/pages/340820049

## Getting Started
프로젝트를 로컬에서 돌려보도록 합시다. 아래의 단계를 천천히 따라오시면 됩니다.

### Version
* node : upper 16.0
* yarn : 1.22.5

### environment
#### env
1. `.env`
* 실제 환경용 환경변수가 있는 파일로 템플릿 안에 있습니다.
2. `.env.develop`
* 개발 환경용 환경변수가 있는 파일이며, 템플릿 안에 없습니다. 생성해야 합니다.
* `.env` 파일을 복사하여 `.env.develop`명으로 붙이고 `REACT_APP_PROFILE=DEV`을 넣어주면 됩니다.
3. `.env.dev-build`
* 로컬 빌드 스크립트, `REACT_APP_PROFILE=DEV`가 있으면 개발환경 없으면 실제환경으로 연결됩니다.


#### Profile
* `release`: 상용 환경
* `dev`: 개발 환경
* `local`: 로컬 환경
* `alpha`: 테스트 환경


### Installation
* 레포지토리 클론해오기
```
git clone https://github.com/htbeyond/blue-web-byb-admin.git
```
* Yarn, Npm Packages 설치하기
```
yarn install / npm install
```
