# OSDEO_FOSS
공간정보아카데미

## 오픈소스에 대한 이해와 진실

## 오픈소스 소프트웨어

## 오픈소스 GIS

## 웹 브라우저에서 수정

## 오픈소스 활동에 참여하기

## GitHub을 이용하여 협업하기
1. 버전관리시스템
2. Git 개요
3. Git 설치
4. Github 소개
5. 저장소 만들기
6. 버전 만들기
7. 브랜치 생성, 병합
8. 충돌
9. 충돌 해결하기(confilct)
## 오픈소스 개발환경 구축하기
cd eclipse-workspace
git clone geoserver
cd geoserver
git branch
git checkout 2.22.x
cd src
mvn install -DsktipTests
mvn eclipse:eclipse


## 오픈소스 서비스환경



### 2일차
* 책의 144page

* GeoServer 활용법

### 작업 공간
 * 새로운 작업 공간 추가(http://localhost/worldmap) 
 * 저장소 클릭
 * 새로운 저장소 생성하기 클릭
 * 작업 공간은 사용할 저장소를 기준으로 생성
 * 활성화를 클릭 해제할 시 서비스 불가
 
### 레스터 데이터
 * 새로운 저장소 생성하기
 * tif 생성
 * 발행하기 클릭 후 설정
 * 좌표계 확인 후 발행에서 캐시 클릭
 
### 벡터 데이터
 * 새로운 저장소 생성하기
 * 사용할 좌표계 확인
 * 레이어 최소영역 설정
 * 발행하기
 * 캐시 설정
 
### 레이어 그룹
 * 새로운 레이어 그룹 생성
 * 이름 설정 (Worldmap_group) 
 * 레이어 추가하기 (차례대로 설정)
 * 저장
 * 레이어 미리보기에서 확인

```
작업공간과 저장소는 매핑이 되어있음

QGIS의 레이어 -> 새로운 레이어 생성에서 새 GeoPackage는 QGIS의 Polyline, Ploygon 등을 패키지로 만들어 GeoServer로 올릴 수 있음

PostGIS는 Postgresql 에서 사용 가능
PostGIS는 Database로 벡터 데이터 활용에서 가장 많이 사용함
```
