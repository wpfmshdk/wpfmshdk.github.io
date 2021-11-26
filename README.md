---
layout: page
title: 프로젝트를 만든 과정
permalink: /about/
---

### 10주차
> 강의를 듣고서 Github에서 wpfmshdk.github.io 이름의 repository를 생성했고 원격 저장소의 주소를 복사하여 로컬 저장소와 연동시켰다("git clone <repo_name> <path>" 로 clone). 연동시키고 나서, 로컬 저장소에서 예시 파일(index.html)을 작성해봤다. 예시 파일을 원격 저장소에 push하였고 Github Page 설정에 들어가서 거기에 있는 주소(wpfmshdk.github.io)로 접속하여 반영 내용(index.html)을 확인했다.

### 11주차
> 로컬 저장소에 blog에 해당하는 디렉토리에 Jekyll을 설치하였다. 그러고 나서 bundle exec jekyll serve를 실행 후, localhost:4000에 접속하여 기본 테마로 된 Jekyll 사이트를 생성시켰다. 
> _config.yml의 내용을 바꾼 후 bundle exec jekyll serve를 실행하여 사이트의 내용을 변경하는 실습을 진행했고 로컬 저장소에서 바꾼 내용을 원격 저장소에 푸쉬했다.
> _posts 폴더에서 2021-11-11-example.md의 새로운 문서를 생성하였고 markdown 형식을 통해 내용을 작성했다. 그리고 이를 로컬 저장소에 커밋으로 반영하였고 원격 저장소에 푸쉬하여 반영시켜줬다. 그러고 나서 사이트에서 바뀐 내용을 확인할 수 있었다.
 마지막으로, 테마 사이트에서 'monos'라는 테마를 git clone하여 로컬 저장소에 받아왔고 _posts를 제외하고 테마를 로컬 저장소에 모두 반영시켰다.

### _config.yml
> Code block will look like this.
```yml
highlighter-theme: monokai //you can change your syntax color scheme.
date_format: "%Y-%M-%D" //and date format.
```


