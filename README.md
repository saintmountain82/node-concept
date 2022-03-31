# Node JS 핵심 개념

## require
- node standard library에 존재하는 모듈은 절대경로를 지정해 가져온다.
- module.paths 내에 존재하는 모듈 역시 경로를 지칭하지 않아도 가져올 수 있다.
- module.paths의 경로들을 순서대로 검사하여 해당 모듈이 있으면 가장 첫 번째 것을 가져온다.
- 프로젝트 내의 다른 파일은 상대경로를 지칭해 가져온다.