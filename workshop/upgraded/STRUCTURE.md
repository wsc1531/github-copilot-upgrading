# upgraded 폴더 파일 구조 설명

이 디렉터리는 레거시 프로젝트의 모든 파일과 폴더를 동일하게 복사한 업그레이드 작업 공간입니다.

## 주요 폴더 및 파일

- MANIFEST.in, README.rst, distribute-0.6.10.tar.gz, distribute_setup.py, setup.py: 레거시 Python 패키징 관련 파일
- docs/: 프로젝트 문서 및 Sphinx 빌드 결과물 포함
  - build/: Sphinx 빌드 산출물(html, doctrees 등)
  - source/: Sphinx 문서 원본(rst, conf.py 등)
- guachi/: 주요 Python 모듈 및 테스트 코드
  - __init__.py, config.py, database.py: 핵심 모듈
  - tests/: 단위 및 통합 테스트
- guachi.egg-info/: 패키징 메타데이터

## 활용 목적
- 레거시 코드를 최신 Python 환경으로 포팅 및 리팩토링
- 테스트 및 문서화, 패키징 구조 유지
- 업그레이드 작업의 기준점 역할

각 파일은 레거시 프로젝트의 원본을 그대로 복사한 것으로, 업그레이드 작업 시 파일별로 수정 및 개선이 이루어집니다.